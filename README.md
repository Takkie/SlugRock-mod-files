Quake3Arena modification for the ioq3 engine.


========================================================================================================================

title: SlugRock
file: ioq3SlugRock.pk3
author: UglyFoot / Takkie           
email address: jas.mail.mob@gmail.com 
URL: http://slugsandrockets.tumblr.com

Team SlugRock:	UglyFoot (coding, ideas, testing)
		Takkie	 (ideas, testing)	

========================================================================================================================

start-up information

SlugRock (short for slugs and rockets) is a Quake3arena mod build upon the ioq3 source-code.
You need to install the ioq3 engine before you can play this mod.
The ioq3 engine is available from the ioquake3 website (http://ioquake3.org/)
This engine contains many bugfixes and additional features.

You can start the ioq3SlugRock mod from the mods menu or you can use the .bat file.
Or create your own .bat file with these settings:
..
...

========================================================================================================================

play information

All items, powerups and weapons are removed from the map,
except for the flags in CTF.
Every time you (re)spawn in the arena you'll get the railgun
or the rocketlauncher (depending on your cvar setting).
Because there is no health available there also the option
'healthRegen', with this option on a player will recieve
5 health points every second until the maxium health of 125
points is reached. 

========================================================================================================================

List of new CVAR's

set by server:
g_healthRegen (default = 1)
	0 = off
	1 = on

g_forceWeaponMode (default = no)
	no = weaponmode is set by each player individual
		(with this set cg_WeaponMode and bot_WeaponMode are enabled
		otherwise they are disabled)

	alternate = railgun and rocketlauncher alternate at each respawn
	random = railgun and rocketlauncher are are given at random at respawn
	both = railgun and rocketlauncher are both given at respawn
	rg = railgun only
	rl = rocketlauncher only
	select = player selects weapon at match start (tdm / ctf only)

set by player:
(works only if g_forceWeaponMode is set to no)
cg_WeaponMode (default = alternate)
	aalternate = railgun and rocketlauncher alternate at each respawn
	random = railgun and rocketlauncher are are given at random at respawn
	both = railgun and rocketlauncher are both given at respawn
	rg = railgun only
	rl = rocketlauncher only

set by player for bots:
bot_WeaponMode (default = alternate)
	alternate = railgun and rocketlauncher alternate at each respawn
	random = railgun and rocketlauncher are are given at random at respawn
	both = railgun and rocketlauncher are both given at respawn
	rg = railgun only
	rl = rocketlauncher only

========================================================================================================================

background information:
After releasing SlugRock_4.21 i received some feedback on the quake3world forum.
I decided to recreate the mod from scratch because i lost the source-code.
Fortunally UglyFoot came to assist me.
By public demand we decided to use the ioquake3 source-code as a base.
We forked the  ioq3 code on GitHub (https://github.com/Takkie/SlugRock).

========================================================================================================================

Distribution / Copyright / Permissions 

Copyright (c) 
All rights reserved.

Quake III Arena is a registered trademark of id Software, Inc.

This mod may be electronically distributed only at NO
CHARGE to the recipient in its current state, MUST include
this .txt file, and may NOT be modified IN ANY WAY. UNDER NO
CIRCUMSTANCES IS THIS LEVEL TO BE DISTRIBUTED ON CD-ROM
WITHOUT PRIOR WRITTEN PERMISSION.

========================================================================================================================
