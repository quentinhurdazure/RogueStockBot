# RogueItemTracker
### Why?
Johnnie was a college student who recently graduated.  As a college grad and powerlifter he was frustrated 
that he was unable to access the gym. As a result, in his free time Johnnie worked quickly to create a home gym and to do
that he needed some gym equipment. 

However, many sites were out of stock, especially out of 
ROGUE products, his favorite fitness company. 

As a result, Johnie decided to create this bot
to update himself whenever an equipment is back 
in stock. 

He encountered a community on reddit r/homegym
 where other users faced the same problem and 
he decided this would be a great tool to help 
others just like him.
Please use Johnny main branch to donate.  

This is a special branch for testing only.


![result](/views/images/home-demo.png)

### Updates

v 2.1
* Added new items
* All CA Links are now supported

v 2.0
* Added new items including Ironmaster
* Updated /current-items to be easier to navigate
* Included Youtube video tutorial on website
* Added spell check suggestions

v 1.9
* Added new items
* Included last time in stock feature in 'status'

v 1.8
* Added new items
* Merged CA links to US links
* Added number of users searching to /current-items
* Can now stop single items with "stop item" ex. "stop plate echo color"

v 1.7
* Added new items
* Upgraded from AWS EC2 t2.small to t2.medium

v 1.6
* Updated bot guide to be more helpful
* Fixed grab bag barbells
* Included loadable dumbbells and other items

v 1.5
* Fixed cerakote options and customizable items such as Monster Utility Bench 2.0
* Added new items including Australian links

v 1.4
* Upgraded EC2 instance from t2.micro to t2.small increasing performance
* Added new items including some Canada links

v 1.3
* Included a new “non-cached” link with a random 6 letter string appended to the URL
    * This link redirects you to the page when a restock occurs and clears the cache so the items should show up instantly
    * Kept the original link as a back up
* Included the following items
    * SAML-24 Monster Lite Safety Spotter Arms (Pair)
    * Monster Safety Spotter Arms 2.0
    * Rogue Infinity Safety Spotter Arms
    * Rogue Landmines
    * Rogue Thompson Fatbells
* Removed customizable buggy items for now such as OPB cerakote, OPB ss
    * Unable to add custom items for now such as loadable dumbbells, monster utility bench 2.0

v 1.2
* Fixed bug where some pages did not correctly indicate they were in stock

v 1.1
* Included boneyard and misc used barbells.
    * Right now this feature only checks if the boneyard page is up
    * Thus, have the search enabled, and it will msg you when the boneyard page shows up
* Fixed bug where ‘stop’ would prevent user from searching again until next reset


### Commands
| Name | Purpose |
|:-:|:-:|
| help | Returns all commands of items to search |
| status | Checks current items and how long they have been searching for |
| stop | Stops checking all items |

### How to use
Refer to `roguestockbot.com/bot-guide` for tutorial of all the commands
