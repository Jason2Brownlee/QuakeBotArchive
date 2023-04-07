# BGBot

The BG Bot or BGBot was created by Robert DeFilppo aka "Punisher" extends the DMBot and the TMBot.

It was specifically designed to be an opponent for deathmatch games and may be one of the first dedicated QuakeC deathmatch bots.

I was able to track down eight versions of the BGBot that were publicly released between the end of August and the end of September 1996.

A total of six out of the eight releases were found on a CD titled "Power Tools for Quake (Europe)" located on the internet archive. Timestamps on the CD suggest that it was created March 1997 and perhaps distributed soon after.

1 Mar  1997 BGBOT1
1 Mar  1997 BGBOT11
1 Mar  1997 BGBOT12
1 Mar  1997 BGBOT125
1 Mar  1997 BGBOT13
1 Mar  1997 BGBOT15

The final two releases were widely distributed.

All of these releases appear to have been announced on Usenet and uploaded to cdrom.com. Only announcements for the eight known releases were discovered on Usenet, which suggests that no additional public releases of the bot were made.

The BGBot is an important bot as it founded a vast number of bots that build upon it. It has quite a legacy, perhaps the largest among the earliest Quake bots.





## BGBot v1.0

The first release of the bot was made with the filename bgbot1.zip.

The archive contained the compiled game code (progs.dat), a readme file (bgbot1.txt) and a zip containing the game source code (src.zip).

 112787 29 Aug  1996 SRC.ZIP
 435148 28 Aug  1996 PROGS.DAT
   2193 28 Aug  1996 BGBOT1.TXT

The readme file lists the release date as August 26th 1996 and explicitly gives credit to the TMBot and DMBot authors. This suggests that it is an extension of the DMBot release.

	Title    : BG Bot
	Filename : bgbot1.zip
	Version  : 1.00
	Date     : 96/8/26
	Author   : Punisher
	Email    : punisher@trojan.neta.com
	Credits  : Micheal Polucha (co-designer of Original TM bot)
	           Tim Polucha (co-designer of Original TM bot)
	           Nathaniel Gorham (Original DM bot)

The files in the archive are dated the 28th and 29th of August 1996.

The release was also announced on Usenet in the group rec.games.computer.quake.editing with the title "BG_Bot v1.0" and the author "BiG HuRT" on August 29th. This is taken as the public release date.

"BG" in the game of the bot likely refers to "BiG" in the authors Usenet handle and email handles used elsewhere such as "Mr Bg Hurt" and "bghurt".

The BGBot is a deathmatch bot fro the beginning.

	VERSION 1:
	        TM, DM Bot basis.
	        Ability to pick up things:
	                Weapons
	                Ammo
	                Health
	                Armor
	        Chooses weapon from ones it has.
	        Hunts all players (including creator)
	        Hunts other bots
	        Multiple Bots at once. (memory limiting)
	        Telefrags

-- bgbot1.txt

The readme makes it clear that the bot is an extension of the DMBot for deathmatch play, adding features such as the ability for the bot to pick-up and use weapons, armor and health, the ability to choose weapons and the ability to run multiple bots at once.

	Basically a TM and DM bot slightly modded. This bot can pick up Health, Armor, Weapons, and Ammo. Also chooses which weapons is better of the weapons it has picked up. Also shoots all players and other bots. You can create as many bots as you like, memory allowing.

-- bgbot1.txt

The readme file suggests that the release was distributed both on cdrom.com and the authors personal webpage.

	This modification is available from the following places:

	FTP   : ftp.cdrom.com
	WWW   : http://www.neta.com/~punisher/quakec.htm

Sadly, the authors homepage was not archived.




## BGBot v1.10

The next release was made with the filename bgbot11.zip.

The archive contained the same collection of files, namely the compiled game code (progs.dat), a readme file (bgbot11.txt) and a zip containing the game source code (src.zip).

   2851 26 Oct  1996 BGBOT11.TXT
 438312 26 Oct  1996 PROGS.DAT
 113453 26 Oct  1996 SRC.ZIP

The readme lists the release date as August 31st 1996 and the oldest modified date of the source code confirms this date.

	Title    : BG Bot
	Filename : bgbot1.zip
	Version  : 1.10
	Date     : 96/8/31

-- bgbot11.txt

Timestamps of the game code and readme appear to have been scrambled, listing October 26th. The release was announced on Usenet with the title "BG Bot v1.10" on September 1st and is likely the public release date.

The release adds further improvements to the bot AI, with some handling of doors and spawn points in deathmatch and coop play. The bot will also hunt for health when needed and no enemies are present.

	VERSION 1.1:
	        Added more bot recognition throughout game.
	                (ie doors, more recognition by monsters)
	        Better Spawning:
	                In ONE player spawns in players starting position.
	                In COOP and DM spawns in random player position.
	        Hunts Items if no enemys close enough.
	                Gets health if it needs it.
	        Other minor fixes.

-- bgbot11.txt

No doubt the public announcements on Usenet and availability on cdrom.com resulted in a lot of interest and feedback to Robert about the bot.




## BGBot v1.20

A followup release was made the same day as the previous release, this time with the filename bgbot12.zip.

The archived contained the same array of files and were timestamped as September 1st 1996 matching the date in the readme and the date of the Usenet post titled "BG Bot v1.20".

   3741  1 Sep  1996 BGBOT12.TXT
 114432  1 Sep  1996 SRC.ZIP
 438288  1 Sep  1996 PROGS.DAT

This release appears to be a quick fix for cooperate and team deathmatch play, seemingly based on direct feedback from the community:

	By Popular Demand: Now in COOP or one player, bots only attack monsters. In DM attacks everything. In teamplay, is on team of creator.

-- bgbot12.txt

Cooperative play (COOP) was also mentioned in the previous release and it's great to see that this style of multiplayer game with bots was supported so early on, likely prompted by the large and growing user base for the mod.

Also in this release, George Leithner aka "Detour", the author of the BGADMBot is called out in the credits. The v1.01 release of the BGADMBot based on the BGBot was released the day before on August 31 1996. No doubt Robert saw this release and perhaps even had email contact with George.

	det...@chrysalis.org (we had the same ideas and mods going about the same time. Just giving credit where credit is due.)

-- bgbot12.txt





## BGBot v1.25

Another release was made about two days later with the filename bgbot125.zip.

The archive contains the same assortment of files which are timestamped September 3rd 1996 matching the release date in the readme and the date of the Usenet post titled "BG Bot v1.25 released".

 114571  3 Sep  1996 SRC.ZIP
   4079  3 Sep  1996 BGBOT125.TXT
 437960  3 Sep  1996 PROGS.DAT

The smaller 0.5 increment in the version number suggests a change with a smaller scope. This is confirmed in the readme that suggests the changes were focused on better AI for picking up weapon ammunition and dropped backpacks.

	VERSION 1.25:
	Doesnt look for ammo if he has max ammo already.
	Doesnt look for items if they are hidden or behind a wall.
	Hunts backpacks now.
	Getting closer to displaying bots kills.
	I know what it needs. but quake wont let me do it.
	Need to find a way around it.

-- bgbot125.txt

A list of desired changes has been maintained and grown over the last three versions with a focus on better AI.

The release notes for this version also comment on progress perhaps being made along these lines.

	STILL NEEDS:
	Better roaming AI.
	(still walks same patterns)(Anyone willing to help?)
	Ability to walk into water, swim, jump, and walk over cracks
	in floor.
	Trying to get the bots score to come up on changelevel or when
	player dies. Cant seem to figure it out.(brainfried.)
	If anyone can lend some insight, lemme know.
	In Teamplay, Coop, and one player he is pretty useless on any
	level that has cracked floor, stairs, water, etc.

-- bgbot125.txt





## BGBot v1.30

This is another fast release, shared on the same day as the previous release with the filename bgbot13.zip.

The date of the Usenet announcement, file timestamps and release date in the readme agree on September 3rd.

   4275  3 Sep  1996 BGBOT13.TXT
 114071  3 Sep  1996 SRC.ZIP
 431872  3 Sep  1996 PROGS.DAT

The focus of the release seems to be changing the bot player model from the Enforcer to the same player used by human players in deathmatch.

	VRESION 1.30:
	Model is now the player model. He has the same colors as you.
	Fixed minor sound bug. (ie no sound when he fires.)
	Slightly improved roaming ai.

-- bgbot13.txt

The readme file is also must truncated, removing the changelog for previous versions and elaborating the "STILL NEEDS" section, highlighting goals for the ongoing AI development.

	STILL NEEDS:
	#1------Trying to get the bots score to come up on changelevel or when
	player dies. Cant seem to figure it out.(ie brain fried.)
	If anyone can lend some insight, lemme know.
	#2------Ability to walk into water, swim, jump, and walk over cracks
	in floor.
	#3------Better roaming AI.
	#4------Need to figure out how to change his colors. Random or

	otherwise.
	#5------In Teamplay, Coop, and one player he is pretty useless on any
	level that has cracked floor, stairs, water, etc.

-- bgbot13.txt





## BGBot v1.50

The next version was released as bgbot15.zip.

 114283  6 Sep  1996 SRC.ZIP
 433092  6 Sep  1996 PROGS.DAT
   4640  6 Sep  1996 BGBOT15.TXT

Version numbers jump from 1.3 in the previous release to 1.5 in this release.

There is a comment in the readme that version 1.4 was created but was not release publicly.

	VERSION 1.40:
	        Not publicly released due to major beta problems.

-- bgbot15.txt

The fuller changelog appears in the file again, having been truncated in the previous release.

The files in the archive are timestamped at September 6th 1996, matching the release date in the readme and the date of the Usenet post titled "BG Bot v1.50 Released".

The bots now support different names with automatic respawning and support for being gibbed like normal players.

	VERSION 1.50:
	        In Deathmatch 4 bots with diferent names are created. If they die they will respawn in starting positions again.
	        In single player or COOP, only one bot is created but is not respawned.
	        Bots can now be gibbed, with pieces flying everywhere.

-- bgbot15.txt







## BGBot v1.60

The next and penultimate version was released as bgbot16.zip.

The archive contains the same mixture of files, timestamped September 13th 1996. This matches the date in the readme file and the date of the Usenet post titled "BG Bot v1.60 [Jump and fixes]".

   5565 13 Sep  1996 BGBOT16.TXT
 114636 13 Sep  1996 SRC.ZIP
 434568 13 Sep  1996 PROGS.DAT

A key change in this release is the ability for bots to jump, made with help from a contributor.

	Bot now jumps thanks to a very helpfull David Wiedenmann!!!

-- bgbot16.txt

The changelog for this release summarizes a number of other minor features and bug fixes.

Among the other changes listed in the readme is the bots not losing their weapons when they die and being invisible to the bots when you have the ring of shadows.

	Fixed major bug where bots didnt loose their weapons when they respawned. Caused infinate ammo and weapons on level.

-- bgbot16.txt

Many bots were based on the BGBot, specifically this version. The reason is because the next is the final version and was released without source code.

This version remains on cdrom.com/pub/idgames2/quakec/bots/, although with a much later date, the 29th of September instead of the 13th.. It was likely added back to the directory given it was the last release that included source code.

	bgbot16.txt            29-Sep-96 11:04     5k
	bgbot16.zip            29-Sep-96 11:04   240k





## BGBot v2.00a

This is the final version of the bot released as bgbot20a.zip.

It looks like a test version (e.g. for limited testing by friends) that was publicly released, perhaps due to time constraints.

	 This is the ALPHA version. I know there
	are many, many bugs. If you find any it
	is ok to mail me about it. Just don't go
	overboard.

-- bgbot20a.txt

Interestingly, the archive includes a different mix of files than all previous releases. It contains a readme (bgbot20a.txt) and a pak file (pak0.pak) that contains the player models and compiled game code. Surprisingly, the game source code was not released for this version.

   4126 29 Sep  1996 BGBOT20A.TXT
 879862 29 Sep  1996 PAK0.PAK

Inspecting the contents of the PAK file shows the compiled game code (progs.dat) and custom model files for the bot.

	progs.dat
	progs/bghurt.mdl
	progs/biafra.mdl
	progs/h_bot.mdl
	quake.rc

These custom model files are called out in the changelog.

	There are now 3 custom MDL's. 2 bodies and 1 head!!! heh. (please do not use the mdl's in anything unless you have express written consent from Phillipe Doyon see above credit, and copywrite areas.)

-- bgbot20a.txt

The files in the archive are timestamped September 29th 1996, about one month after the first release.

These dates match the release date in the readme and the date of the Usenet post announcing the release titled "BGBot 2.00alpha RELEASED".

	Title    : BG Bot
	Filename : bgbot20a.zip
	Version  : 2.00a
	Date     : 96/9/29
	Author   : Punisher

The four bots in the mod have different personalities, managed by slightly different code and different player models that are distributed with the mod.

	Tad bit smarter. (I know not enough though!)
	Bot's are now use 4 different code bases. They all have their own brain per-say. I know that as of now it is minimal in the diferences, but soon it will be grand.

-- bgbot20a.txt

It is clear that subsequent versions were planned and perhaps underway.

The readme lists a number of features expected in the next version, such as dedicated servers support and the ability for bots to dodge.

There is also a comment that the author expected to release the source code.

	... .DAT: Do what you like. But consider this: Probably be smarter to wait till I release the source no?

-- bgbot20a.txt

A comment by Jon Platt on the rec.games.computer.quake.editing Usenet group a day before the release made some minor complaints about the bot, including the fact that bots don't die in water or lava.

	But they're all campers! :) Actually, the main problems are that they don't die in lava or water, they don't work in teamplay (no bot uprising style games :() You can crash the server if everyone has there own 4 bots, they keep the colour of the creator even if he changes, so that you can't be disguindesed...

-- [Jon Platt](https://groups.google.com/g/rec.games.computer.quake.editing/c/N0e6ZwIvZS4/m/IhH-XO1Pfz8J), rec.games.computer.quake.editing, 28 Sept 1996

Perhaps this comment triggered the premature release the next day.

Robert as " BiG HuRT"replied that this issue of bots not dying in lava and water, as well as other issues were fixed in the latest 2.00 alpha release.

	In version 2.00alpha the lava and nailgun probs have been fixed as
	well as the bots using their own mdls. Soon i will be releasing a
	dedicated server version also which should take care of the crashing
	for it wont create them for each player...only the server etc.

	pun......

	Water still seems to be a problem though....trying to get that now...

-- [BiG HuRT](https://groups.google.com/g/rec.games.computer.quake.editing/c/N0e6ZwIvZS4/m/m_8akzYHUsgJ), rec.games.computer.quake.editing, 29 Sept 1996.

He mentions an upcoming dedicated server version of the bot, that appears to have never been released publicly.

This was the last release of the bot by Robert. He had release a mod prior to the BGBot in early August 1996 called "Publishment", a weapons mod made in collaboration with other developers.

No doubt, this mod paved the way for the bot, including skill with QuakeC, distribution on cdrom.com and announcement on Usenet.

The BGBot was a big deal and is still fun to play today. It's sad that the source for the final version was never made public.

I did manage to reach out to Robert once in 2011 and then again in 2021 to see if he had old versions of the bot or code on a backup. He was unable to locate anything.

I'm not sure if he knows the legacy his bot has had, given the vast number of other bots that were developed off the back of his work. I'm sure he received a good many emails of positive feedback and feature requests in late 1996.

It was regarded fondly at the time.

	Well, I'm fond of Bgbot16, the bots are intelligent, they jump, go in water
	ect. If your playing Deathmatch it automatically spawns 4 bots. It can be
	optained at all the major sites (Stomper, ftp\cdrom, ect.). Check it out
	it's a great bot patch.
	Nakedman

-- [Best BOT](https://groups.google.com/g/rec.games.computer.quake.misc/c/7Me9KczEMsg/m/bSUKEts6be4J), The Nakedman, 2 Oct 1996.



Relevant Timeline

* BGBot v1.0, bgbot1.zip, August 29 1996.
* BGBot v1.1, bgbot1.zip, September 01 1996.
* BGBot v1.2, bgbot12.zip, September 01 1996.
* BGBot v1.25, bgbot125.zip, September 03 1996.
* BGBot v1.3, bgbot13.zip, September 03 1996.
* BGBot v1.5, bgbot15.zip, September 06 1996.
* BGBot v1.6, bgbot16.zip, September 13 1996.
* BGBot v1.20a, bgbot20a.zip, September 29 1996.


References

* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (internet archive)
* [BG_Bot v1.0](https://groups.google.com/g/rec.games.computer.quake.editing/c/iJPu8uLFORg/m/DjXlnveUx0cJ), rec.games.computer.quake.editing, 29 Aug 1996.
* [BG Bot v1.10](https://groups.google.com/g/rec.games.computer.quake.editing/c/PUccZoFC1hw/m/C9AkYuG7b94J), rec.games.computer.quake.editing, 1 Sept 1996.
* [BG Bot v1.20](https://groups.google.com/g/rec.games.computer.quake.editing/c/15zNrTZTUME/m/UiN939o81fYJ), rec.games.computer.quake.editing, 1 Sept 1996.
* [BG Bot v1.25 released](https://groups.google.com/g/rec.games.computer.quake.editing/c/ETxv6qoxbiw/m/y6PCdnlKM7gJ), rec.games.computer.quake.editing, 3 Sept 1996.
* [BG Bot v1.30 [AI and Model Update]](https://groups.google.com/g/rec.games.computer.quake.editing/c/NvDO3K0XQ5Y/m/bU_o4wmYVJgJ), rec.games.computer.quake.editing, 3 Sept 1996.
* [BG Bot v1.50 Released](https://groups.google.com/g/rec.games.computer.quake.editing/c/rPXwpZexhC8/m/8LowmffNKkkJ), rec.games.computer.quake.editing, 6 Sept 1996.
* [BG Bot v1.60 [Jump and fixes]](https://groups.google.com/g/rec.games.computer.quake.editing/c/N0e6ZwIvZS4/m/IhH-XO1Pfz8J), rec.games.computer.quake.editing, 13 Sept 1996.
* [BGBot 2.00alpha RELEASED](https://groups.google.com/g/rec.games.computer.quake.editing/c/yS_9nRaqvyY/m/8_7cfHDdw9kJ), rec.games.computer.quake.editing, 29 Sept 1996.




