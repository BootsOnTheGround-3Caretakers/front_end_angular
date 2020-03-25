# front_end_angular
The Boots on the Ground project

This repo contains Angular code for the front end of the Boots on the Ground project.

###
![Screenshot with code on buttons (for debugging)](https://i.imgur.com/rvNIYJr.png)


### DemoGoals Script
#### Short version.

* User makes account. Sees a bunch of people with needs and caretaker roles. Gets Excited!
* They enter in zip and sees local people. Filters by their need (i.e. Custom1 field in babyAPI).
* Gets matched to a cluster. They then see the emails of everyone in their cluster. 
* Then disbands the cluster. And makes another cluster. Showing off that they nearly instantaneously (with a refresh) update on the screen.


#### Long version
Wishlist of demo:

Login to screen, see 444 already matched. 100 looking for match.

User enters zip code and info and if they are Need or Caretaker.

Go to screen showing all the people they could match with. (it can be the admin panel, but without delete access). Emails hidden.

They make a "shopping cart of themselves (already checked) and checking off 3 other people". Then they can click "make a match.

Match made. The person gets a modal of their match and their emails. Warm greeting saying "You made a match. Contact these 4 people and (not on this platform) make a group chat of communication link. Read this Safety link (fake link or tinyurl.com/coronavirusAnxiety) Here are the 4 people's emails ...."

There is a "your cluster" on the page somewhere (maybe the bottom). There is an X mark. If they click on this, this does a dialog (are you sure you want to disband the cluster? You and the others will be put back in the LookingFor queues. If you disband too many clusters, we will lock you out of the system for a few days.

They click okay, and they see their name at the top of the queue. (sort the queue as newest/latest entries first, this just makes the demo easy since we automagically get recent records at the top)


Great: code it
Excellent: code it an record a video demo.

Note: BabyAPI is not firebase, so it won't do instant sync across devices.
