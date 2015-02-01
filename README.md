# X Universe Fleet Fest - XFF

The X Universe Fleet Fest (XFF) is originally a competition based on the game [X3: Terran Conflict](http://www.egosoft.com/games/x3tc/info_en.php) made by [Egosoft](http://www.egosoft.com) where fleets of ships created by the fans fight each other in a tournament. Since the game does not have a multiplayer function, the battles are record by one player and then posted on the internet so everyone can see them.

### First edition

The first edition of this competition was [organized](http://forum.egosoft.com/viewtopic.php?t=274071) by the English community on the Egosoft forum the 27.03.2010. Quoting the organization post:

> The idea behind the XFF (X-verse Fleet Fest) is basically an inter-player knockout tournament in which competitors have 250 million credits for which they use to put together a fleet to fight other players. 

### Second edition

The second edition, instead, was [organized](http://forum.egosoft.com/viewtopic.php?t=326365) by the Italian community of the Egosoft forum. The main differences with the previous edition were two: the tournament was based on the game [X3: Albion Prelude](http://www.egosoft.com/games/x3ap/info_en.php) and all the battles were presented and commented with [Twitch](http://www.twitch.tv/) during a period of one month.

Since this was a test, the streaming was made in Italian.

All the video of the second edition can be found in [this YouTube playlist](https://www.youtube.com/playlist?list=PL21F3C4A15D9F59D4).

## The script

The script works with the *Mission Director* engine and uses an initialization script created with the *Script Editor*.

In the folder "*script*" there are the two other folders:

* **original** - this is the spawner script of the first edition, unmodified, used with X3TC.
* **addon** - instead this is the spawner script of the second edition, used with X3AP.

Both works at the same way: execute the script *director/xff.director.fightmaker.xml*. In order to spawn different fleets, edit or replace this file.

### The maps

In the folder "*maps*" there are all the maps of the first and second edition. These maps go to the following folders:

* **X3TC:** X:\...\X3 Terran Conflict\maps
* **X3AP:** X:\...\X3 Terran Conflict\addon\maps

All the maps that starts with "*deatmatch_*" are available for both games. The others works only in X3AP since they use special object of this expansion.

### The second edition fleets

Since we don't have the scripts for the first edition, in the folder "*editions*" you will find only the second one.

In order to play again this tournament, it is necessary to have the base script.

The results of the single battles could be different from the results in the tournament.
