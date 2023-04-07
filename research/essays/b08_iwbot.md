# IronWulvt's Deathmatch Bot

IronWulvt's Deathmatch Bot or IWBot by Ben Garrod aka "IRONWULVT) is an extension of the BG bot for deathmatch.


## IWBot v0.1

The first version of the IWBot was released as the file "iwbot1.zip".

The archive contained the compiled game code (progs.dat) a readme file (iwbot1.txt) a code patch file (iwbot1.pat) a zip of the source code (iwbotsrc.zip) and a sprite used by the mod (null.spr).

   4405  1 Sep  1996 IWBOT1.TXT
 111605  1 Sep  1996 IWBOT1.PAT
 119209  1 Sep  1996 IWBOTSRC.ZIP
 468820  1 Sep  1996 PROGS.DAT
     57 22 Aug  1996 NULL.SPR

The release date in the readme is listed as the 1st of September 1996 and the timestamps of the files in the archive match.

	Title    : IronWulvt's Deathmatch Bot
	Filename : IWBOT1.zip
	Version  : 0.1
	Date     : 96/9/1
	Author   : Ben Garrod (IRONWULVT)

-- iwbot1.txt

The release was not announced on Usenet, although was noted by the author of the TM bot a few days later as one of the first dedicated deathmatch bots.

	I's not sure where to get it off the net but Ironwulvt (spelling?) has modified our code so a dm bot spawns on a deathmatch level...he respawns automatically (File name is IWBOT1.ZIP).

-- [TM Bot 1 - Quake C AI](https://groups.google.com/g/rec.games.computer.quake.editing/c/CCoT-6kWaeM/m/VNj0E7-eTdcJ), rec.games.computer.quake.editing, 5 Sept 1996

The readme credits first the authors of the TMBot and the author of the BGBot, suggesting that the bot is an extension of the BGBot, or perhaps an extension of the TMBot that incorporated aspects of the BGBot after it was released.

The readme confirms this second case directly.

	 Well, this is my deathmatch bot I have been working on. Using the original TMBOT as the base, I began work. Within a few days their was most of the original TMBOT code had been revamped, changed or taken out. Then BGBOT was released. I found it had success with a few things I wanted to do, but was having trouble with or was too busy with other things to implement. So I put in stuff from BGBOT.

-- iwbot1.txt

Given the date of release it is mostly likely an extension of the BGBot v1.0 released on August 29th or v1.1 released August 31st 1996.

The bot is designed for deathmatch play and will pickup items and use almost all weapons.

	This will create a deathmatch opponent. This opponent will be able to use all weapons except Lightning gun. He will pick up objects including powerups. He dodges and hunts his killer after respawning.

-- iwbot1.txt

The author is ambitious, listing may areas he'd like to improve and many desired future changes in the readme.

	Well, since this is version 0.1 you can expect there to be updates.
	This version is still really rusty.
	I am having trouble with the following things:

	Getting the bot to search for items without trying to walk through walls
	Getting the bot to walk off ledges
	Getting the bot to pick up health
	Getting the bot to face the opponent better
	Getting the bot to think through another entity(see source code for beginning of my work)
	Getting the bot to activate all buttons and triggers
	getting the bot to sidestrafe and continually change its facing and thus
	        the direction of the sidestrafe(for circle strafes)
	getting the bot not to flip out when dodging nails.
	Name of bots and frag counts on score lists

	Things I want to do, but haven't tried:

	Add Lightning Gun to bot's weaponry
	Add Axe to bot's weaponry
	get bot to jump intelligently
	get the bot to avoid lightning better(gets nailed by lightning every time!)
	get bot to learn(perform better based on number of frags)
	get bot to have skill rankings (Have the bot not appear on Start.bsp, but
	        all others. This way you can select a skill level for your bot to
	        play against.)
	ability to add bots to the fray(one spawns when you initially spawn,
	        and it keeps respawning)
	Random quotes for the bot
	Random names for the bot
	New skin for the bot
	Bot teamplay(maybe have a 2 players compete against 2 bots, or 1 player
	        and a bot versus another player and a bot.)
	More careful about up close firing of rocket launcher and grenade launcher
	Aiming in front of opponent to lead them.

	(wow, quite a list)

-- iwbot1.txt

A copy of this release was discovered on the "Power Tools for Quake" CD discovered on the internet archive.





## IWBot v0.16

The next public release that can be located was version 0.16 released as iwbot16.zip.

There may have been intermediate releases between v0.1 and v0.16, the version numbers suggest there were, but no public evidence can be found.

This release has more files that the previous release, also including a quake startup script (quake.rc) that adds as startup message for the mod, recorded demos of presumably the author playing the bot at deathmatch (9wbot.dem and iwbot2.dem), and batch files for starting the mod on windows (iwot16.bat and iwbot16l.bot).

 121093  6 Nov  1996 IWBOTSRC.ZIP
     37  1 Oct  1996 FILE_ID.DIZ
 359024 11 Sep  1996 IWBOT2.DEM
 492780 11 Sep  1996 PROGS.DAT
 143290 11 Sep  1996 IWBOT16.PAT
    375 11 Sep  1996 IWBOT16I.BAT
     19 11 Sep  1996 IWBOT16.BAT
    942 11 Sep  1996 QUAKE.RC
   6811 11 Sep  1996 IWBOT16.TXT
 600946 10 Sep  1996 IWBOT.DEM
     57 22 Aug  1996 NULL.SPR

A version of the [iwbot16.zip](http://cd.textfiles.com/swextrav8/swextrav8-2/gamapog1/iwbot16.zip) release was located on "[Shareware Extravaganza 8 (Disk 8)](http://cd.textfiles.com/swextrav8/)", containing 17,000 Files from PC-Ohio and released in 1997 across 8 CD ROMs. The file was on Disk 2 of the set.

The archive contains a "FILE_ID.DIZ" file dated 2 months after the release, suggesting that this version was probably distributed via a BBS before appearing on the CD.

The readme file list the release date as September 11th 1996 and the timestamps of files in the readme match this.

	Title    : IronWulvt's Deathmatch Bot
	Filename : IWBOT16.zip
	Version  : 0.16
	Date     : 96/11/9
	Author   : Ben Garrod (IRONWULVT)

-- iwbot16.txt

This release was also announced on Usenet by the author under the name "Bill Garrod" (perhaps a father, brother, or alternate name) with the title "IWBOT V0.16".

The announcement lists the features of the bot, which are impressive for the time including capabilities such as "Dodges when it is shot." and "Uses most of the items properly (becomes invisible, gains quad damage, uses health packs, etc...)".

	Hello, I placed on Ftp.cdrom.com the latest version of my bot. The bot is called IWBOT16. It has the
	following capabilities:
	Searches for items (all items including powerups)
	Uses all the weapons it can find (from Axe to Lightning Gun)
	Dodges when it is shot.
	Dodges randomly while running.
	Dodges incoming grenades, rockets, and nails.
	Respawns after death, remembering its killer as self.enemy.
	Uses most of the items properly (becomes invisible, gains quad damage, uses health packs, etc...)
	(However, until I get it to walk willingly into water and move around)
	(in it intelligently, it doesn't use the biosuit effectively)
	Attacks whoever attacks it, remembering the entity who it was fighting before.
	Can play against as many bots as you want. They do not appear on the start level, or in single player
	play, unless you use the key to add an additional bot. To select the number to fight against,
	select a difficulty level, and you will play against that many plus one as the base number.
	You can add more if you want.
	Uses deathmatch spawn points.
	Can run out of ammo.
	Each bot (except extra bots added) has a different name.
	Runs close to the same speed as the player can.
	When fighting a player, will tell the player its name and its frag count(this is in until I
	find a way to get the bots to appear on the score screen)
	More features, but thats a good enough list.

	There will be more updates in the future. I plan on releasing a version 0.2 by Monday September 16, 1996.

	The base code used was TMBOT1 by Tim and Micheal Polucha with additional code used from Punisher's BGBOT.

-- [IWBOT V0.16](https://groups.google.com/g/rec.games.computer.quake.editing/c/-H4WaO-axj4/m/OrSqDVJfZhQJ), rec.games.computer.quake.editing, bill garrod, 11 Sept 1996.

He also suggest a subsequent release of a version 0.2 will be made within days. No evidence that a public release of v0.20 can be found.

The readme suggests that v0.16 offers a small fix over version 0.15.

	Fixed crashing when from the bot_pain routine. This is pretty much the only thing changed from version .15. This will allow people to play against more than one bot now, without it crashing.

-- iwbot16.txt

This suggests that a version 0.15 was probably released publicly, although no evidence of the public release can be found.

In a discussion on "quake bot ideas/suggestions", Ben chims in a day after the release of IWBot 0.16 highlighting that his bot is able to use all weapons.

	I am the author of IWBOT16 which is a deathmatch opponent bot patch. First off, I wanted to say that
	the new version 0.16 has the ability to use all of the weapons including the axe. Also with the nailguns,
	it fires them very rapidly, resulting in acting like the player firing one of the nailguns. I am still
	trying to perfect the repitition of firing to match that of the player, but it is pretty close right now.
	It explores ok, but not how I really want it to. And on buttons and stuff, I've worked on it, and set things
	such that I would think they could push them, but they just don't. Hopefully I will figure this out by
	monday, which is when I hope to release a new version.
	the patch is available at ftp.cdrom.com/quake/newstuff

-- [quake bot ideas/suggestions](https://groups.google.com/g/rec.games.computer.quake.editing/c/USJ8q-MlrC0/m/donI5VdHDGsJ), rec.games.computer.quake.editing, bill garrod, 12 Sept 1996.




## IWBot v0.21

The next and final version of the bot was released as iwbot21.zip.

The archive contains the compiled game code (progs.dat), a readme file (iwbot2.txt), a Quake startup script (quake.rc) that lists the version as v0.20, a sprite file (null.spr) and windows batch files for installing and running the game (iwbot2.bat and iwbot2I.bat).

 387312  1 Oct  1996 PROGS.DAT
    580  1 Oct  1996 IWBOT2I.BAT
    993  1 Oct  1996 QUAKE.RC
   9701  1 Oct  1996 IWBOT2.TXT
     19 11 Sep  1996 IWBOT2.BAT
     57 22 Aug  1996 NULL.SPR

Interestingly, this version does not include source code, although a note that following versions will was provided in the readme file.

	(NOTE: This should be the only release without a patch and source included. I am still working out the bugs and will release the code next release which should be within a week)

-- iwbot21.txt

The readme lists the archive filename as "iwbot16.zip" (the prior public release), and the version as 0.20. The Quake startup script lists the version as v0.20. This may suggest that a v0.20 was publicly released and that this v0.21 release was made quickly to fix a bug.

	Title    : IronWulvt's Deathmatch Bot
	Filename : IWBOT16.zip
	Version  : 0.20
	Date     : 96/30/9
	Author   : Ben Garrod (IRONWULVT)

-- iwbot21.txt

The readme lists the release date as September 30th, and the timestamp of most the files in the archive is October 1st. The FTP timestamp is also October 1st and is taken as the release date, although the small difference in date-times may be due to differing timezones.

	iwbot21.txt            30-Sep-96 15:09     9k
	iwbot21.zip            30-Sep-96 15:10   127k

-- [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived December 25 1996)

In addition to the TMBot and BGBot, the readme file also gives credit to the author of the Eliminator bot (Cameron Newham), suggesting that the IMBot may incorporate waypoints in this or a planned future versions.

	Author of C-BOT Engine Eliminator bot. He proved to me with his bot that waypoint/pathways are a necessary thing and they have since become top priority on the IWBOT.

-- iwbot21.txt

The list of changes since the 0.16 release is long, suggesting much development over the nearly three weeks since the previous release.

This was the last public release of the bot and was preserved in the Quake Archive on cdrom.com. It also appeared on the "Toolkit For Quake (2nd edition)" CD released in 1997.

Ben did not author and release any more public quake bots or mods more generally.



## Release Timeline

* IWBot v0.1, iwbot1.zip, September 01 1996.
* IWBot v0.16, iwbot16.zip, September 11 1996.
* IWBot v0.21, iwbot21.zip, October 01 1996.



## References

* [Power Tools for Quake](https://archive.org/download/redump_pc_P/Power%20Tools%20for%20Quake%20%28Europe%29.7z), CD ISO, Internet Archive.
* [TM Bot 1 - Quake C AI](https://groups.google.com/g/rec.games.computer.quake.editing/c/CCoT-6kWaeM/m/VNj0E7-eTdcJ), rec.games.computer.quake.editing, 5 Sept 1996.
* [IWBOT V0.16](https://groups.google.com/g/rec.games.computer.quake.editing/c/-H4WaO-axj4/m/OrSqDVJfZhQJ), rec.games.computer.quake.editing, bill garrod, 11 Sept 1996.
* [quake bot ideas/suggestions](https://groups.google.com/g/rec.games.computer.quake.editing/c/USJ8q-MlrC0/m/donI5VdHDGsJ), rec.games.computer.quake.editing, bill garrod, 12 Sept 1996.
* [Shareware Extravaganza 8 (Disk 8)](https://archive.org/details/Shareware_Extravaganza_8_Most_Significant_Bits)
* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived December 25 1996).


