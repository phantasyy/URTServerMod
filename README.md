# URTServerMod for UrbanTerror
**The server mod that has everything you need for a complete UrT server; infinite stamina, no fall damage, colours names, infinite wall jumps, hide chat cmds and funstuff replacement**

## Cvar/Usage
It contains all the original cvars and 5 more for control the mods added. All mods are enabled by default you can use the following commands for disable it (for enable just replace '0' with '1'):

 > set sv_infiniteStamina 0

 > set sv_infiniteWallJumps 0

 > set sv_nofallDamage 0

 > set sv_colourNames 0
 
 > set sv_hideChatCmd 0
 
 
 Every message executed with a ! @ & and / will be hidden.


## Installation
You can download directly the binaries from https://github.com/phantasyy/UrTServerMod/releases .
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
