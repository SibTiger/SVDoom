# SVDoom
![Thy Flesh Consumed Intermission Screen](https://github.com/SibTiger/SVDoom/blob/main/GitHub%20Services/ReadMe/SVDoom.png)

This [PWAD](http://doomwiki.org/wiki/PWAD) allows the players to continuously play through all of the [Ultimate Doom](https://store.steampowered.com/app/2280) [episodes](https://doomwiki.org/wiki/The_Ultimate_Doom#Episodes) without needing to start a new game or to restart the same episode again within a multiplayer environment.  _SVDoom_ is ideal for both Multiplayer environments as well as Single Player games.

# Requirements

* **Recommended Doom Engine Port**
  * [ZDoom](https://zdoom.org/index) 1.22 or later

* **Game Requirement**
  * [Ultimate Doom](http://www.idsoftware.com/)
    * You can also buy it on [Steam](https://store.steampowered.com/app/2280/)
  * [Freedoom](http://freedoom.github.io/index.html)
    * An alternative if it is not possible to retrieve _Ultimate Doom_.


# ReadMe
```
===========================================================================
Advanced engine needed  : ZDoom 1.22 or later
Primary purpose         : No levels included
===========================================================================
Title                   : Server Doom
Filename                : SVDoom.wad
Release date            : 30 November. 2012
Author                  : Nicholas "Tiger" Gautier
Email Address           : SibTiger_and_Life@Hotmail.com

Description             : This allows any specific supported engine to
                          continuously run all maps from E1 to E4.
                          This file ignores (End Episode), and well reroute
                          to the next episode when the current is
                          finished.
                          Perfect for multiplayer proposes!
                          
                          Thanks to Kyle "Skunkrocker" Guthrie for the
                          episode 4 intermission screen, that SVDoom
                          utilizes and retrieved permission for.
                          
                          Version 1.00: 25 April. 2008
                               Original Release
                          
                          Version 1.01: 20 November. 2008
                               Fixed a possible HOM issue that sometimes occur
                                 in SkullTag.
                          
                          Version 2.00: 30 November. 2012
                               * Expunged CISVD.txt; superfluous ASCII file...
                               * Added a new lump 'ZMAPINFO' for engines that support it
                               * Applied level number capability; useful for ACS scripts.
                               * Enforced 'No Jumping' and 'No Crouching'; changable
                               * Enforce 'Smooth Lighting' variable to true.
                               * Enforce 'Normal Infighting'
                               * Ports that use MAPINFO should render intermission screens
                                   almost adjacent to those that use ZMAPINFO.
===========================================================================
* What is included *

Sounds                  : No
Music                   : No
Graphics                : No
Dehacked/BEX Patch      : No
Demos                   : No
Other                   : No
Other files required    : None


* Play Information *

Game                    : Doom
Single Player           : No
Cooperative 2-4 Player  : No
Deathmatch 2-4 Player   : No
Other game styles       : None
Difficulty Settings     : Not implemented


* Construction *

Base                    : Modified
Build Time              : Several hours
Editor(s) used          : Notepad++
May Not Run With...     : Any non-ZDoom based engine


* Copyright / Permissions *

Authors MAY use the contents of this file as a base for modification or
reuse.  Permissions have been obtained from original authors for any of
their resources modified or included in this file.

You MAY distribute this file, provided you include this text file, with no
modifications.  You may distribute this file in any electronic format (BBS,
Diskette, CD, etc) as long as you include this file intact.  I have
received permission from the original authors of any modified or included
content in this file to allow further distribution.

* Where to get the file that this text file describes *

The Usual: ftp://archives.3dgamers.com/pub/idgames/ and mirrors
```
