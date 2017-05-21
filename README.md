# URTServerMod for UrbanTerror
**The server mod that has everything you need for a complete UrT server; infinite stamina, no fall damage, colours names, infinite wall jumps, hide chat cmds and funstuff replacement**

## Cvar/Usage
It contains all the original cvars and 10 more for control the mods added. All mods are enabled by default you can use the following commands for disable it (to enable just replace '0' with '1'):

 > set sv_infiniteStamina 0

 > set sv_infiniteWallJumps 0

 > set sv_nofallDamage 0

 > set sv_colourNames 0
 
 > set sv_hideChatCmd 0
 
 > set sv_noKnife 0
 
 > set sv_forceGear ""
 
 > set sv_specChatGlobal "0"
 
 > set sv_block1337 "0"
 
 > set disableDefaultMaps "0"

If you wish to add more than just the default maps you can modify it in sv_client.c

Every message executed with a ! @ & and / will be hidden.

To use forceGear take the weapons&Gears you want then type /gear in console and put that gear code into the sv_forceGear command.

If you wish to add or edit the funstuff replacement go to code/server/sv_client.c and starting at line 1346 you will see how the function works and you can add more funstuff if you wish. It is of course also possible to change the replacement to another funstuff than "shit".

For users with access to command I also brought to you a few more features.

 > forcecvar
You can use forcecvar to change a name on a player and much more.
Usage: forcecvar "player name" "cvar" "cvar value". Can also use allbots.

> sendclientcommand 
Send a reliable command to a specific client. 
Usage: sendclientcommand "playername" "command". Can also use all or allbots.

> teleport
Simply Teleport "player1" to "player2". Works whether or not allowgoto is off for the player. Also works in all modes.


## Installation
You can download directly the binaries from https://github.com/phantasyy/URTServerMod/tree/master/binaries .
### Windows
If you want the **dedicated server** download the file named 'Quake3-UrT-Ded.exe' and replaced it in the UrbanTerror folder, execute it as normal.

For **client version** download 'Quake3-UrT.exe' and replaced it on the UrbanTerror folder, execute it as normal.

### Linux
If you want the **dedicated server** download the file named 'Quake3-UrT-Ded.i386/x86_64'¹ and replaced it on the UrbanTerror folder, execute it as normal.

For **client version** download 'Quake3-UrT.i386/x86_64'¹ and replaced it on the UrbanTerror folder, execute it as normal.

 ¹ *i386 is for 32bits and x86_64 for 64bits*

## Build
First of all download dependences: For **Ubuntu**
```
sudo apt-get install make gcc libsdl-dev
```
And compile it
```
make
```
Binary files are placed on the build folder.



###### ------------------------------ Credits ----------------------------------

Maintainers
  Aaron Gyes <floam at sh dot nu>,
  Ludwig Nussel <ludwig.nussel@suse.de>,
  Thilo Schulz <arny@ats.s.bawue.de>,
  Tim Angus <tim@ngus.net>,
  Tony J. White <tjw@tjw.org>,
  Zachary J. Slater <zakk@timedoctor.org>

Significant contributions from
  Ryan C. Gordon <icculus@icculus.org>,
  Andreas Kohn <andreas@syndrom23.de>,
  Joerg Dietrich <Dietrich_Joerg@t-online.de>,
  Stuart Dalton <badcdev@gmail.com>,
  Vincent S. Cojot <vincent at cojot dot name>,
  optical <alex@rigbo.se>
# URTServerMod
