# Eliminator Bot


The Eliminator Bot or CBot was developed by Cameron Newham over a three week period in September 1996.

It was perhaps one of the first advanced Quake bots and the first to use a waypoint system for bots to navigate levels.

Cameron was not new to modding, having developed and released maps for doom in 1994 and a "Simple Quake Examples and Methods" mod (sqeam.zip) for Quake in August 1996, shortly after the QuakeC source was released



## Eliminator v1.0

The first version of the Eliminator bot was released as elim10.zip.

This release was announced by Cameron on usenet in the rec.games.computer.quake.misc and rec.games.computer.quake.announce groups.

	Title : Eliminator CBot Engine
	Filename : elim10.zip
	Version : 1.00
	Date : 96/09/12
	Author : Cameron Newham

-- [[ANNOUNCE] Eliminator Bot V1.00 Released](https://groups.google.com/g/rec.games.computer.quake.misc/c/J3ZyRbtXits/m/DUm_nOMF3kQJ), rec.games.computer.quake.misc, Cameron Newham, 12 Sept 1996.

A copy of this release cannot be located, nor can the readme file, although we can get some ideas about the release from the Usenet announcement.

The release was made public on ftp.cdrom.com and the authors personal homepage.

	This modification is available from the following places:

	FTP : (eventually) ftp.cdrom.com in the Quake C area
	WWW : http://www.iinet.com.au/~cam/quakec.html
	http://www.iinet.com.au/~cam/elim10.zip

-- [[ANNOUNCE] Eliminator Bot V1.00 Released](https://groups.google.com/g/rec.games.computer.quake.misc/c/J3ZyRbtXits/m/DUm_nOMF3kQJ), rec.games.computer.quake.misc, Cameron Newham, 12 Sept 1996.

The announcement was made on September 12, 1996, which is taken as the release date.

Cameron's homepage was not captured by archive.org until 1999, long after development of the bot was done.

A message on the site captured at that time, dated April 1998 suggests downloading the bot from FTP mirrors.

	Last updated: 98/04/16 16:00 UT

	Many of the files not available here are now available through links in my Home Page

	Well, after nearly 20 months I'm STILL getting accesses to this page! Unfortunately I no longer have the space to store any Quake C stuff on here, and besides, Eliminator is very old. The files have been deleted. Please see the links on my home page or go to one of the many Quake FTP sites to find the Eliminator files.

	Thank you.

-- [http://www.iinet.com.au/~cam/quakec.html](https://web.archive.org/web/19990117033644/http://www.iinet.com.au/~cam/quakec.html) (archived January 17 1999)

Although the release was placed on ftp.cdrom.com, no evidence remains as captures of the site by archive.com were not made until December 1996, showing only later versions of the mod.

From the beginning, the bot is described as a deathmatch opponent, and even marketed as an alternative to having to setup or access an expensive local area network in order to play the multiplayer version of the game.

	The Eliminator Bot package provides you with some decent adversaries
	to play Quake against. Don't have a network connection? Maybe you
	have a $100,000 LAN at home but no friends... Well, here is the
	answer to your Deathmatch dreams. These automated deathmatch opponents
	are by no means friendly and they'd just love to kick your sorry
	behind all over the place. What's more, they aren't stupid like
	most of the other bots out there. These know how to fight and know
	their way around.

-- [[ANNOUNCE] Eliminator Bot V1.00 Released](https://groups.google.com/g/rec.games.computer.quake.misc/c/J3ZyRbtXits/m/DUm_nOMF3kQJ), rec.games.computer.quake.misc, Cameron Newham, 12 Sept 1996.




## Eliminator v1.1

The next version of the Eliminator bot was released as elim11.zip.

Like the first version, it was announced on Usenet, in this case on the rec.games.computer.quake.misc group.


	Title : Eliminator CBot Engine
	Filename : elim11.zip
	Version : 1.1
	Date : 96/09/15
	Author : Cameron Newham

-- [[ANNOUNCE] Eliminator Bot Version 1.1 Released](https://groups.google.com/g/rec.games.computer.quake.misc/c/WGLj8bcRaWY/m/EdQcKhrsdegJ), rec.games.computer.quake.misc, Cameron Newham, 15 Sept 1996.

A copy of the release was located on the "Nightowl 23" CDROM of BBS software released in 1997, archived on retroarchive.org.

The contents list two readme files, the compiled game code and two .map files. This version of the release also has a "FILE_ID.DIZ" file, added later for describing the file on BBSs.

     78 29 Sep  1996 FILE_ID.DIZ
   2126 15 Sep  1996 ELIM10.TXT
 457232 15 Sep  1996 PROGS.DAT
  36242 15 Sep  1996 START.MAP
  57188 15 Sep  1996 E1M5.MAP
   9204 15 Sep  1996 README.TXT

Source code for the release was not distributed.

Also interestingly, the "ELIM10.TXT" is included from the previous release, although the contents have been updated. This suggests the filename was not changed and released as-is accidentally.

The readme lists the release date as September 15th, 3 days after the first release. This is confirmed by the timestamps of files in the zip file and the date of the announcement on Usenet.

The readme also lists the name of the bot as "Eliminator Bot", but also the mod as the "CBOT-Engine". This may suggest the ambition of both the development of an infrastructure for running bots, e.g. waypoints in levels and usage in-game, and an instance of a bot that uses the infrastructure.

	Eliminator Bot for id Software's Quake
	--------------------------------------

	Archive Version 1.1  (Public Release)
	CBOT-Engine Version 1.1

-- README.TXT

The bot is claimed to be a the most sophisticated QuakeC bot at the time.

	Currently, this is the most sophisticated Quake C Bot available.

-- ELIM10.TXT

This probably a fair comment, if it played better than other simpler bots at the time, like the BGBot version 1.6.

The updated readme lists the bot as a deathmatch only player, and explicitly not a helper bot for singleplayer like many of the bots at this time provided.

	Please note that this is a Deathmatch patch. The Bots are designed
	specifically for playing against other deathmatch players - not
	monsters.  These Bots are *not* "helper" bots.  Indeed, the only help
	you'll get from them is a a rocket in your face.

-- README.TXT

Critically, the bot ships with support for only two maps, the "start" map and "e1m5" map.

Map support is must be explicitly prepared by creating a map file that contains the coordinates for the placement of waypoints throughput the map. These must then be compiled into the BSP map files distributed with the game.

	  * Bots have knowledge of Quake levels (currently only "start" and
	    "e1m5" (Gloom Keep)).

-- README.TXT

The mod does not distribute the maps ready to play, instead requiring the user to modify the maps themselves. Detailed instructions are provided in the "readme.txt" file on how to prepare the BSP files for game play with the bot.

I suspect this proved too challenging for almost all most the technical quake mod players at the time.

The changelog for the release lists many bug fixes.

	Version 1.0 -> 1.1

	* Observer Mode is fixed; Observers are now invisible to other players
	* cbots now fight even when they are stuck
	* cbots are much more willing to initiate an engagement if they only
	  have a shotgun
	* START and E1M5 have some small changes/fixes
	* Added a startup definition for the number of cbots to generate
	  on starting a level (useful for servers)
	* fixed priority waypoint detection so it's limited by pitch
	* fixed MODE determination for engage and disengage attack
	* tweaked targetting
	* tweaked a few other parameters
	* cleaned up some of the code

-- README.TXT

Credits are given to beta testers for the bot, although not to other bot release at the time like the TMBot, DMBot or BGBot.

	The following people kindly helped me Beta Test the patch:

	Roger Bolton
	Rowan Crawford ("Sumaleth" on IRC)
	Ben Schaffer

	Thanks also to

	Thane Sherrington - idea of auto-generation of cbots on startup

	Thanks to everyone for helpful comments and suggestions!

-- README.TXT

The use of beta testers is good practice. It perhaps suggests a higher level of quality in the mod. It may also suggest beta versions of the bot distributed for testing prior to public release.

This suggest that Cameron developed the bot himself from scratch, which is very impressive. Especially given the capabilities of the bot described in the readme.

	Features include:

	  * Bots have knowledge of Quake levels (currently only "start" and
	    "e1m5" (Gloom Keep)).
	  * Bots are able to pick up all items (health, armour, weapons,
	    ammo, specials).
	  * Bots start off with a shotgun and aquire equipment just like a
	    player.
	  * Bots know how to swim and can navigate over "broken ground".
	  * Bots don't just blindly fire - bots will only attack if they are
	    in a position to do so.
	  * Bots are able to camp (if they want to).
	  * Bots are able to activate all of the triggers on a level (eg:
	    buttons, doors, etc).
	  * A maximum of 10 bots can be created - each with its own name.
	  * You can specify the number of bots to start with in a config file.
	  * Bots regenerate at a new Deathmatch location after being killed.
	  * Based on the Enforcer model for easy identification.
	  * An Observer Mode is included - watch the bots fight it out
	    without getting in the way!
	  * Display the bot gib scores.
	  * Runs on the Quake server allowing it to be used in network games.
	  * Ability to use the engine for your own maps (requires technical
	    knowledge - I'll be posting up a document on this *soon*).

-- README.TXT




## Eliminator Construction Set

The next release related to the bot was elimtst1.zip.

This release contained the system required to prepare map data required for bots to play levels in Quake.

This release was announced on Usenet in the rec.games.computer.quake.editing group as the documentation and debug version of the bot needed to create waypoints for the bots to play ad hoc levels.

	Here is a copy of the document for creating waypoints for use with
	my Eliminator Bot Patch.

	There is also an Eliminator Construction Set available for testing
	and debugging your levels. It's available from:

	http://www.iinet.com.au/~cam/quakec.html

-- [[ANNOUNCE] Eliminator Bot Waypoint Document](https://groups.google.com/g/rec.games.computer.quake.editing/c/l2IOPgWG8rE/m/BMA_E2oWaG0J), rec.games.computer.quake.editing, Cameron Newham, 15 Sept 1996.

The elimtst1.zip, readme (elimtst1.txt), and waypoint readme (elimwpt.txt) were placed in the bots/eliminator/ subdirectory on ftp.cdrom.com with a timestamp of September 19th. Here the files remained, even in modern mirrors of the directory

	elimtst1.txt	1996-Sep-19 00:00:00	1.9K	text/plain
	elimtst1.zip	1996-Sep-19 00:00:00	152.1K	application/zip
	elimwpt.txt		1996-Sep-19 00:00:00	14.8K	text/plain

-- [https://www.quaddicted.com/files/idgames2/quakec/bots/eliminator/](https://www.quaddicted.com/files/idgames2/quakec/bots/eliminator/)

A copy of the release was located on the "Shareware Extravaganza 8 (Disk 8)" collection on CD 2.

It contains a readme file describing the release (readme.txt), a high-level summary readme that was also shared on Usenet (elimtst1.txt), waypoint documentation (elimwpt.txt), and example map file containing waypoints for the start map (examp.map), and a compiled version of the bot intended for debugging waypoints for maps (progs.dat)


   5069 15 Sep  1996 readme.txt
  15137 15 Sep  1996 elimwpt.txt
   1946 15 Sep  1996 elimtst1.txt
  31040 15 Sep  1996 examp.map
 457256 15 Sep  1996 progs.dat

The readme lists the release date as September 16th, one day after the version 1.1. release of the bot. The Usenet post and file stamps list the 15th of September, the same day as the previous release. The difference may be due to the differences in local timezone (Australia) compared to the Usenet and server timestamps in the United States.

	Title    : Eliminator CBot Engine - Level Construction Set
	Filename : elimtst1.zip
	Version  : 1.1
	Date     : 96/09/16
	Author   : Cameron Newham
	Email    : cam@iinet.com.au
	Credits  : see the readme.txt

-- elimtst1.txt

The release is described as a "Level Construction Set" for the "Eliminator CBot Engine".

	This is a construction set for creating levels for use with the
	Eliminator Bot Patch and the CBot Engine.

	It contains a compiled version of the Engine in Test Mode,
	a copy of the Eliminator Waypoint Guide, plus an example level
	(entities MAP for Start.BSP).

	For further details see the README.TXT file in the archive.

	For the Eliminator Bot Patch itself, get elim??.zip from
	your favourite archive site.

-- elimtst1.txt

The details of the waypoint system is quite elaborate in the elimwpt.txt.

It provides instruction on how to prepare waypoints in a map file for use by the bot, and how the waypoints will be used in game by a bot to navigate the level.


	The Eliminator Patch for Quake has at its heart a "waypoint" system
	for cbot navigation.  The basic idea is that a cbot (powered by
	a program written in Quake C - the CBot Engine) looks for the nearest
	waypoint in a level and then heads towards it.  Waypoints are
	daisychained together, so that once the cbot has aquired the waypoint
	(by standing within a short distance of it) it reads the information
	on the location of the next waypoint in the daisychain and heads
	towards that.

	Waypoints exist as entities in a level - that means that they can be
	added to a Quake MAP file, compiled into a BSP and will be available
	every time the level is loaded.

-- elimwpt.txt

This was probably the first waypoint-based bot for Quake, a technique that became popular with other games, and later versions of Quake, such as Quake 2. Nevertheless, the approach did not really take off with QuakeC bots, in favor of bots that are able to navigate any level on their own.

Cameron appeared to anticipate a hard limit on how long he could work on the bot, mentioning that he will be able to do anything after September 21st 1996.

	All other questions will be replied to as best I can.  Please note
	that I will not be available after the 21st of September 1996.

-- elimwpt.txt

He also states that he does not want to release the source code and that he's getting many requests.

This is not surprising given the high-level capabilities of the bots and the sophistication of the navigation system developed. Perhaps he was hoping to hold it back as a commercial product later.

	Please DO NOT MAIL ME ASKING FOR THE SOURCE CODE.  The answer is NO.
	I will not reply to mail of this type.

	(you can guess that this is currently the majority of mail I get - some
	of it is very persistant :)

-- elimwpt.txt




## Eliminator v1.2

The next version was released as elim12.zip.

The release was announced on Usenet in the rec.games.computer.quake.announce and rec.games.computer.quake.misc groups.

	Title : Eliminator CBot Engine
	Filename : elim12.zip
	Version : 1.2
	Date : 96/09/16
	Author : Cameron Newham

-- [[ANNOUNCE] Eliminator Bot Version 1.2 Released](https://groups.google.com/g/rec.games.computer.quake.announce/c/k69VBfLHkkU/m/hvkGUDzJZSMJ), rec.games.computer.quake.announce, Cameron Newham, 16 Sept 1996.

This was only one day after the the previous release, and perhaps very shortly after releasing the construction kit.

A copy of the release can be found on the "Nightowl 23" CDROM, archived by retroarchive.org, and on the "Shareware Extravaganza 8" CDROM on CD 2 archived by archive.org and textfiles.com.

The release contains the same two readme files, waypoins for two levels and the compiled game code. The version of the release I acquired also had the added "FILE_ID.DIZ" for describing the file on BBSs.

     34 28 Oct  1996 FILE_ID.DIZ
 460492 16 Sep  1996 PROGS.DAT
  10373 16 Sep  1996 README.TXT
   2880 16 Sep  1996 ELIM12.TXT
  36242 15 Sep  1996 START.MAP
  57188 15 Sep  1996 E1M5.MAP

The release date in the file is the 16th of September, matching the post on Usenet and the timestamps of files in the zip file.

	Title    : Eliminator CBot Engine
	Filename : elim12.zip
	Version  : 1.2
	Date     : 96/09/16
	Author   : Cameron Newham
	Email    : cam@iinet.com.au
	Credits  : see the readme.txt

-- ELIM12.TXT

The readme file contains a compact list of features of the, highlighting the advanced capabilities compared to BGBots and other bots of the era.

	Features Include:

	* Sophisticated AI Engine
	* True deathmatching on a whole level - just like human players
	* Up to 10 bots on a level
	* Bots know how to use all the of weapons
	* Ability to give the bots knowledge of any level
	* Server capability - deathmatch bots vs humans!
	  No other files needed by the clients.
	* Observer Mode - watch the bots battle it out!
	* Auto startup - define how many you want to start when you run Quake
	* Skins - give the bots their own identities!

-- ELIM12.TXT

The focus of this release appeared to be support for multiple player skins (multiskins), a popular mod for multiplayer at around this time.


	Updates 1.1 -> 1.2

	* Now uses "skins". If you have the player.mdl from the skins
	patch you can DM Duke Nukem and his friends (well... he ain't got
	any, I know :)

-- ELIM12.TXT

The fuller changelog in the readme file lists further tweaks to the custom bot scoreboard, like adding the players's score, as well as tweak to the bot AI.

Version 1.1 -> 1.2

	* Changed to using the player model
	* Added skins capability (one line change! :)
	* Increased the running speed of the cbots
	* Added players (clients) to the Gib Score printout
	* Gib Score printout is now local (not broadcast to everyone)
	* Added better weapons handling AI - cbots now know not to use
	  R/L or G/L up close (unless they have very good health), and
	  limits use of the G/L over large distances. SNG and LG are
	  only used for short/medium range
	* Tweaked some parameters
	* Fixed a bug in id's code w.r.t attenuated death sounds (cbots ONLY -
	  I didn't fix this for players... perhaps I should have)
	* Removed an old id debug use for "temp1"

-- README.TXT

It is surprising that the "construction set" was not included in the release, allowing a simplification into a single distribution, instead of potentially two distribution files.




## Eliminator v1.3

The next version of the bot was probably released as elim13.zip.

No copy of the release or readme file can be located.

We know of this release because it is mentioned in the changelog for the next released, version 1.4.

	Updates 1.2 -> 1.3

	* Bug fix for cl > cl.maxclients problem.

-- ELIM14.TXT

It was not announced on Usenet and no record exists on ftp.cdrom.com or BBS CDROMs.

It is possible that the release was minor and limited to beta testers, e.g. not made public.




## Eliminator v1.4

The next and last release of the bot was distributed as elim14.zip.

Like the 1.3 release, it was not announced on Usenet. This may be because of the authors tight time constraints for the project, as mentioned on the release of the construction set.

A copy of the release is available on the "Toolkit For Quake (QTool_0197)" CDROM. It is also on the "Shareware Extravaganza 8" CDROM on CD 2 archived by archive.org and textfiles.com. A copy can also be located on the "CD Zone Issue #48" magazine CDROM released in as late as March 1997, archived on archive.org.

As the last release, it remained present for some time. It appears on the "ls-laR.gz" file on ftp.cdrom.com captured just before Christmas in 1996. It lists the file in the /quakec/bots/eliminator subdirectory.

	./quakec/bots/eliminator:
	-rw-rw-r--  1 jschuur  ftp-id     3146 Sep 19 19:04 elim14.txt
	-rw-rw-r--  1 jschuur  ftp-id   163146 Sep 19 19:05 elim14.zip

-- [http://www.cdrom.com/pub/idgames2/ls-laR.gz](https://web.archive.org/web/19961221100334/http://www.cdrom.com/pub/idgames2/ls-laR.gz) (archived December 21 1996)

The readme file for the release also appears in the "00alltxt.tar.gz" on ftp.cdrom.com, recorded at the same time.

The release contains the same assortment of readme, map files and the compiled game code.

No source code is included in this final release, nor is the construction set included in the release.

 461796 19 Sep  1996 progs.dat
  11398 19 Sep  1996 readme.txt
   3146 19 Sep  1996 elim14.txt
  36242 15 Sep  1996 start.map
  57188 15 Sep  1996 e1m5.map

The release date in the readme file is listed as the 19th of September 1996. This matches the timestamps of files in the zip and the recovered FTP timestamps.

	Title    : Eliminator CBot Engine
	Filename : elim14.zip
	Version  : 1.4
	Date     : 96/09/19
	Author   : Cameron Newham

-- elim14.txt


A summary of the release suggests the release includes bug fixes as well as other minor changes.

The release may have been made in a hurry.

	Updates 1.3 -> 1.4

	* Fixed some bugs
	* Added support for low gravity and proper handling of specials
	* Added server lock - locks # of cbots at startup
	* Added some circle straf and missile avoidance

-- ELIM14.TXT




## Eliminator Maps

After the release of the level construction set, authors stared releasing map files containing waypoints for the bot was well as compiled BSP files.

The managers of ftp.cdrom.com created a bots/eliminator/ subdirectory for the bot, including the playable release, construction set release, as well as map files for the bot.

This directory is reported as being created on the 20th of September, one day after the 1.4 release.


	Major changes made to the directory structure of
	ftp://ftp.cdrom.com/pub/idgames2:
	...
    09/20/96 'quakec/bots/eliminator' directory created.

-- [http://cdrom.com/pub/idgames2/CHANGES](https://web.archive.org/web/19961221100153/http://cdrom.com/pub/idgames2/CHANGES) (archived December 25 1996)

More tan 40 map files were released and placed in the eliminator/ subdirectory, where they remained, even in modern mirrors of the directory.

For example:


	Name↓	Last Modified:	Size:	Type:
	../	 	-  	Directory
	cbot1.txt	1996-Oct-29 00:00:00	2.9K	text/plain
	cbot1.zip	1996-Oct-29 00:00:00	241.5K	application/zip
	e_qhenge.txt	1996-Oct-01 00:00:00	2.5K	text/plain
	e_qhenge.zip	1996-Oct-01 00:00:00	77.1K	application/zip
	el_dotd.txt	1996-Oct-12 00:00:00	2.0K	text/plain
	el_dotd.zip	1996-Oct-12 00:00:00	263.6K	application/zip
	el_e1m8.txt	1996-Oct-13 00:00:00	1.1K	text/plain
	el_e1m8.zip	1996-Oct-13 00:00:00	5.9K	application/zip
	el_e2m7.txt	1996-Oct-13 00:00:00	1.8K	text/plain
	el_e2m7.zip	1996-Oct-13 00:00:00	8.4K	application/zip
	el_kyse3.txt	1996-Oct-04 00:00:00	2.0K	text/plain
	el_kyse3.zip	1996-Oct-04 00:00:00	482.9K	application/zip
	elb_dm3.txt	1996-Oct-07 00:00:00	1.8K	text/plain
	elb_dm3.zip	1996-Oct-07 00:00:00	4.6K	application/zip
	elim-vx1.txt	1996-Sep-20 00:00:00	2.2K	text/plain
	elim-vx1.zip	1996-Sep-20 00:00:00	11.6K	application/zip
	elim141.txt	1997-Apr-26 00:00:00	3.7K	text/plain
	elim141.zip	1997-Apr-26 00:00:00	298.1K	application/zip
	elim14pk.txt	1996-Sep-20 00:00:00	1.0K	text/plain
	elim14pk.zip	1996-Sep-20 00:00:00	1.8M	application/zip
	elimd2m7.txt	1996-Sep-30 00:00:00	3.9K	text/plain
	elimd2m7.zip	1996-Sep-30 00:00:00	3.2K	application/zip
	elimdeso.txt	1996-Sep-28 00:00:00	2.4K	text/plain
	elimdeso.zip	1996-Sep-28 00:00:00	376.8K	application/zip
	elimdm4.txt	1996-Sep-27 00:00:00	2.3K	text/plain
	elimdm4.zip	1996-Sep-27 00:00:00	158.6K	application/zip
	elimtst1.txt	1996-Sep-19 00:00:00	1.9K	text/plain
	elimtst1.zip	1996-Sep-19 00:00:00	152.1K	application/zip
	elimwpt.txt	1996-Sep-19 00:00:00	14.8K	text/plain
	nr_dm6.txt	1996-Sep-26 00:00:00	2.8K	text/plain
	nr_dm6.zip	1996-Sep-26 00:00:00	6.3K	application/zip
	nr_e1m1.txt	1996-Sep-23 00:00:00	2.9K	text/plain
	nr_e1m1.zip	1996-Sep-23 00:00:00	602.2K	application/zip
	th_e2m7.txt	1997-Feb-21 00:00:00	2.9K	text/plain
	th_e2m7.zip	1997-Feb-21 00:00:00	8.3K	application/zip
	th12_dm5.txt	1997-Feb-22 00:00:00	3.3K	text/plain
	th12_dm5.zip	1997-Feb-22 00:00:00	4.8K	application/zip
	thetadm5.txt	1997-Feb-10 00:00:00	1.6K	text/plain
	thetadm5.zip	1997-Feb-10 00:00:00	4.0K	application/zip
	vx-e1m2a.txt	1996-Sep-27 00:00:00	2.0K	text/plain
	vx-e1m2a.zip	1996-Sep-27 00:00:00	9.4K	application/zip
	vx-e1m7.txt	1996-Sep-21 00:00:00	1.9K	text/plain
	vx-e1m7.zip	1996-Sep-21 00:00:00	3.9K	application/zip
	vx-e4m3.txt	1996-Sep-27 00:00:00	2.4K	text/plain
	vx-e4m3.zip	1996-Sep-27 00:00:00	9.4K	application/zip

-- <https://www.quaddicted.com/files/idgames2/quakec/bots/eliminator/>

A re-packaged version of the release was made and released as "elim14pk.zip" by "Moraca".

	        This is the latest version of ELIM 1.4.  I have placed this is a pak
	file for those who are having trouble and for convience.  I have also included
	Multiskin Pro with head gibs.  To install this, do the following:

-- elim14pk.txt

It helpfully added the waypoint data from the map files into the BSP files and distributed the ready-to-use BSP files, compiled game code, and player model in a PAK file.

	maps/e1m5.bsp
	maps/start.bsp
	progs.dat
	progs/h_player.mdl
	progs/player.mdl

-- PAK0.PAK




## Eliminator Source Code

Although claiming no plans to release the source code, Cameron did release the source code for the Eliminator Bot before the end of 1996.

The release was made as elimsrc.zip.

It was not announced on Usenet and may not have been uploaded to ftp.cdrom.com as no record of it can be found.

This released was shared on the authors personal homepage and the release was picked up and shared on bluesnews on December 27th.
	December 27, 1996

	Cameron Newham has released his source code for the Eliminator Bot (124 KB) on his homepage.

-- [Blues News Archive](https://www.bluesnews.com/archives/dec96-3.html), December 1996.

Bluesnews hosted a local copy of the file, which was captured by archive.org.

The release also appears on the "CD Zone Issue #48" magazine CD released on March 1997 and archived on archive.org.

The release contains simply a readme file (README.NOW) and the QuakeC source code files.


   960 25 Dec  1996 README.NOW
  2598 19 Sep  1996 progdefs.h
 12408 19 Sep  1996 world.qc
 48696 19 Sep  1996 cbotai.qc
 27158 19 Sep  1996 weapons.qc
 21510 18 Sep  1996 cbot.qc
 35745 18 Sep  1996 client.qc
  2303 18 Sep  1996 cbnmods.qc
  1602 17 Sep  1996 cbnmods.h
 20221 16 Sep  1996 player.qc
  7264 14 Sep  1996 combat.qc
 16254 12 Sep  1996 ai.qc
  3197 11 Sep  1996 buttons.qc
 15481 11 Sep  1996 triggers.qc
  8235 11 Sep  1996 plats.qc
   560  7 Sep  1996 progs.src
 31015  4 Sep  1996 items.qc
 18349  3 Sep  1996 doors.qc
 15760 31 Aug  1996 misc.qc
  6378 31 Aug  1996 subs.qc
 13659 31 Aug  1996 enforcer.qc
  7945 25 Jul  1996 fish.qc
 18750 25 Jul  1996 hknight.qc
   237 25 Jul  1996 jctest.qc
  9966 25 Jul  1996 knight.qc
 10373 25 Jul  1996 models.qc
  5034 25 Jul  1996 monsters.qc
 15129 25 Jul  1996 ogre.qc
  9675 25 Jul  1996 oldone.qc
  8131 25 Jul  1996 shalrath.qc
 13104 25 Jul  1996 shambler.qc
 10121 25 Jul  1996 soldier.qc
   512 25 Jul  1996 sprites.qc
  7350 25 Jul  1996 tarbaby.qc
 11085 25 Jul  1996 wizard.qc
 20635 25 Jul  1996 zombie.qc
  1776 25 Jul  1996 amtest.qc
 12808 25 Jul  1996 boss.qc
 18116 25 Jul  1996 defs.qc
 10279 25 Jul  1996 demon.qc
  9917 25 Jul  1996 dog.qc
  7617 25 Jul  1996 fight.qc


The timestamps of the file suggest that this version of the code that was released was not touched since the version 1.4 release.

The timestamp of the readme is listed as Christmas day 1996, matching the release date in the readme file itself and was probably the release date of the zip file.

	Eliminator Cbot Source for Quake - December 25th 1996
	By Cameron Newham (cam@iinet.com.au)

-- README.NOW

The release is described as a snapshot of the code from the last release as suspected.

The author comments that the code is completely unsupported and that he will not answer questions. The finality suggests that he does not expect to work on it any further.


	This is the snapshot of the most recent version of Eliminator.

	It's been some time since I worked on this so please don't
	send me mail asking how it works or how to compile or install it.  For
	the sake of argument 'I don't know'.  This is totally unsupported,
	and I have no intention of spending the next 6 months fielding quakec questions :)

-- README.NOW





## Extensions

The release of the bot did see extensions to it in the new year, firstly "elim141.zip" by Jonathan Down aka "Perged" in April 1997 that fixed a number of bugs.

	Version 1.4 -> 1.41
	-------------------

	* Author changed for Cameron B. Newham to Jonathan DOwn
	* Fixed the lava bug
	* The axe is now a usable bot weapon
	* Added axe frames
	* Added axe death frames
	* Added the rest of the player sounds
	* Improved the observer mode
	* Tweaked the AI
	* Removed the sliding corpse bug
	* Fixed small telefrag bug

-- elim141.txt

This version appears in the bots/eliminator/ subdirectory and modern mirrors.

This was followed by version 2.0 beta releases elim20b6.zip in June 1997 and elim20b7.zip release in September 1997 by Jonathan Down aka "Perged" and P. T. Craig aka "FuzzKatT". Copies of these releases were donated to the QuakeBotArchive.

Among additional features the authors describe the ability of the bot to dynamically map the environment, likely borrowing ideas from the reaper bot.


	Features      : -Uses the same frames as players
	                -Fires Weapons the same as players
	                -Jumps off ledges
	                -Variable Skill levels
	                -Skill affects Aiming, pain, shooting rate, etc.
	                -Dynamic Level Mapping
	                -Talks to player (Whines, taunts, comments).
	                -Appears on rankings screen
	                -53 different names
	                -Chooses a different color for each bot
	                -Leads targets
	                -Picks up items
	                -Drowns, dies in lava, and slime
	                -Can use triggers
	                -Prioritizes items
	                -Ycam (Harvey Lee, Wes Morrison)
					-Changes skill based on scores
	                -Will chase enemies
	                -They Do not Cheat

-- elim20b7.txt

THe releases were hosted on the author's personal homepages, which was not captured by archive.org. They also acquired hosting on planetquake under http://www.planetquake.com/eliminator/

References to further releases by these authors could not be located. It appears the authors lost interested and started to focus on the development of other mods, and an Eliminator bot for Quake 2.




## Addendum

Years later, the quake community was rediscovering old bot mods and writing wiki pages.

One example was the QuakeWiki that added a page to list quake bots and hosted a copy of the then defunct "BotArea 51" webpage.

Cameron left a comment on this page, highlighting the early capabilities of the Eliminator bot compared to the much famed Reaper bot.


	I see you have the archive of BotArea 51 and my bot Eliminator. Very useful as it gives the date when it was released – 19 Sept 1996 – which means it was the first level-aware bot to be created and beat Steve Polge’s “Reaper Bot” by several weeks. Indeed, mine was also the first to use map waypoints for bot navigation and the first bot which presented a real challenge to human players. Sadly I only got three weeks to work on it before moving to another country and having no time to improve it, so it’s almost forgotten about now. However it’s nice to see it has been archived after all these years!

-- [Quake 1 Bots](https://www.quakewiki.net/quake-1-bots/), QuakeWiki.




## Release Timeline

* Eliminator v1.0, elim10.zip, September 12 1996.
* Eliminator v1.1, elim11.zip, September 15 1996.
* Eliminator Construction Set v1.0, elimtst1.zip, September 15 1996.
* Eliminator v1.2, elim12.zip, September 16 1996.
* Eliminator v1.3, elim13.zip, ???
* Eliminator v1.4, elim14.zip, September 19 1996.
* Eliminator Source Code, elimsrc.zip, December 25 1996.



## References

* [[ANNOUNCE] Eliminator Bot V1.00 Released](https://groups.google.com/g/rec.games.computer.quake.misc/c/J3ZyRbtXits/m/DUm_nOMF3kQJ), rec.games.computer.quake.misc, Cameron Newham, 12 Sept 1996.
* [[ANNOUNCE] Eliminator Bot V1.00 Released](https://groups.google.com/g/rec.games.computer.quake.announce/c/hG7w_xClUM4/m/i7WbdHf-iaUJ), rec.games.computer.quake.announce, Cameron Newham, 12 Sept 1996.
* [[ANNOUNCE] Eliminator Bot Version 1.1 Released](https://groups.google.com/g/rec.games.computer.quake.misc/c/WGLj8bcRaWY/m/EdQcKhrsdegJ), rec.games.computer.quake.misc, Cameron Newham, 15 Sept 1996.
* [Nightowl 23, Shareware & Public Domain software for IBM PCs & Compatibles](http://annex.retroarchive.org/cdrom/nightowl-023/index.html)
* [[ANNOUNCE] Eliminator Bot Waypoint Document](https://groups.google.com/g/rec.games.computer.quake.editing/c/l2IOPgWG8rE/m/BMA_E2oWaG0J), rec.games.computer.quake.editing, Cameron Newham, 15 Sept 1996.
* [[ANNOUNCE] Eliminator Bot Version 1.2 Released](https://groups.google.com/g/rec.games.computer.quake.announce/c/k69VBfLHkkU/m/hvkGUDzJZSMJ), rec.games.computer.quake.announce, Cameron Newham, 16 Sept 1996.
* [[ANNOUNCE] Eliminator Bot Version 1.2 Released](https://groups.google.com/g/rec.games.computer.quake.misc/c/zyLMwBdZYP0/m/iXORMeZkER0J), rec.games.computer.quake.misc, Cameron Newham, 16 Sept 1996.
* [http://www.cdrom.com/pub/idgames2/ls-laR.gz](https://web.archive.org/web/19961221100334/http://www.cdrom.com/pub/idgames2/ls-laR.gz) (archived December 21 1996)
* [http://www.cdrom.com/pub/idgames2/00alltxt.tar.gz](https://web.archive.org/web/19961221100133/http://www.cdrom.com/pub/idgames2/00alltxt.tar.gz) (archived December 21 1996)

