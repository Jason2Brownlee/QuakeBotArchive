# Frogbot

The Frogbot was developed by Robert Field aka "Frog" over about one year in 1998.

This was late in quake bot development as Quake II had been released at the end of 1997 and many players and mod developers had moved over to it.

At the time that Robert was developing the Frogbot, he was a university student studying a graduate diploma in IT in Australia.

	This is my first publicly distributed quakeC patch.
	...
	I will be doing a Graduate Diploma in Information Technology at QUT (Brisbane, Australia) this year. I am 25 years old. I don't have my own web site because I've been too slack, and busy with other things.

-- frogphys00.zip/readme.txt

His specific focus was on player emulation. He wanted the bot to look and feel like a real player in the way it moved and operated in the level. This was a limitation of other bots at the time.

	The Frogbot is basically an exact client emulation bot.

-- [http://prime.telefragged.com/metro/frogbot_intro.shtml](https://web.archive.org/web/20030908211402/prime.telefragged.com/metro/frogbot_intro.shtml) (archived September 08 2003)

As such it remains an important bot, even for modern players that deeply care about the verisimilitude of the bots, such as QuakeWorld players.

Robert went on to work in the game industry at Infinity Ward and worked on Medal of Honor and Call of Duty.

	Robert Field has been a programmer at Infinity Ward since February 2002. Previously he was a programmer on Medal of Honor: Allied Assault, and the AI programmer for Laser Arena. He is the author of the Frogbot bot for Quake.

-- <https://callofduty.fandom.com/wiki/Robert_Field>




## Frogbot Physics v0.00

Before the bot was released, Robert released an example of the client emulation code which he called "Frogbot Physics" or "FrogPhys.

The first release of Frogbot Physics was v0.00 which was distributed as frogphys00.zip.

The release was announced on Terry Hendrix "Bot Shop" website.

	January 7, 1998

	Frog Bot released

	Yes the bot that promises the best player like movement in a QuakeC bot yet, has been released including source code here at Bot Shop. DL it here and at the Workshop page with details.

-- [http://www.planetquake.com/botshop/news/1998-01.html](https://web.archive.org/web/19991018233525fw/http://www.planetquake.com/botshop/news/1998-01.html) (archived October 18 1999)

This release, and the next, were mirrored on the Bot Shop. Copies of this file can still be found in modern mirrors of the bot shop file section, such as on [quaddicted](https://www.quaddicted.com/files/mirrors/ftp.planetquake.com/botshop/).

The release contains source code for the client emulation(.qc), a PAK file (Pak0.pak), readme file (frogphys00.txt), and configuration file (config.cfg).

   8175  7 Jan  1998 frogphys00.txt
   3363  7 Jan  1998 config.cfg
 194913  7 Jan  1998 Pak0.pak
   1235  7 Jan  1998 lists.qc
   3785  7 Jan  1998 botimp.qc
  17228  7 Jan  1998 defs.qc
  26131  7 Jan  1998 client.qc
   1920  7 Jan  1998 botthink.qc
   2424  7 Jan  1998 mathutil.qc
  12058  7 Jan  1998 world.qc
  12322  7 Jan  1998 triggers.qc
   5393  7 Jan  1998 combat.qc
   2914  7 Jan  1998 buttons.qc
  23182  7 Jan  1998 weapons.qc
   7888  7 Jan  1998 plats.qc
  15564  7 Jan  1998 doors.qc
  25924  7 Jan  1998 items.qc
    502  7 Jan  1998 frogphys.qcp
   2165  7 Jan  1998 server.qc
   4735  7 Jan  1998 subs.qc
   8951  5 Jan  1998 botphys.qc
  17554 26 Sep  1996 player.qc
  15088 26 Sep  1996 misc.qc

The PAK file contains compiled game code and some sound files.

	progs.dat
	quake.rc
	sound/demon/dland2.wav
	sound/misc/h2ohit1.wav

The readme file lists the release date as January 07 1997. This matches the timestamps of files in the readme fi.e.


	Title    : Frogbot physics
	Filename : frogphys00.zip
	Version  : Beta 0.0
	Date     : 7 Jan 1998
	Author   : Robert Field

-- frogphys00.txt

The release is described as a subset of the frogbot at the time that shows how a bot can emulate a player's movements exactly, rather than using a rough approximation as is implemented in other bots.

	The code of this mod is a subset of the Frogbot mod I am currently developing. Essentially I have made MOVETYPE_WALK (ie. player physics model) out of MOVETYPE_STEP (ie. monster physics model). This mod provides a player physics model for people who wish to develop a bot for Quake [...]. The Frogbot is controlled by arrow keys and jump and fire buttons just like a player uses. To my knowledge the Frogbot virtually behaves exactly like a player ...

-- frogphys00.txt

Robert provides some details on how he developed the client emulation, stating that he reversed engineered the movement of the player with print statement and reconstructed the movement using code.

 So how can I be sure that the physics in this mod replicate those of a player? I painstakingly reverse-engineered the Quake MOVETYPE_WALK physics model using bprint statements of things like self.origin, self.velocity, self.flags, self.waterlevel, self.watertype, self.v_angle, self.angles, self.teleport_time.

-- frogphys00.txt




## Frogbot Physics v0.01

An updated of the Frogbot Physics was released as frogphys001.zip.

The release contains the same files, with updates to the PAK file, one code file, and the config file. The compiled game code is also included as a separate release.

No announcement can be found of this release. I suspect much of the public announcements by Robert were made on message boards hosted on telefragged.com, most of which have been lost.

   3363  9 Jan  1998 config.cfg
 193552  9 Jan  1998 progs.dat
   8966  9 Jan  1998 botphys.qc
   1261  8 Jan  1998 Pak0.pak
   8175  7 Jan  1998 frogphys00.txt
   1235  7 Jan  1998 lists.qc
   3785  7 Jan  1998 botimp.qc
  17228  7 Jan  1998 defs.qc
  26131  7 Jan  1998 client.qc
   1920  7 Jan  1998 botthink.qc
   2424  7 Jan  1998 mathutil.qc
  12058  7 Jan  1998 world.qc
  12322  7 Jan  1998 triggers.qc
   5393  7 Jan  1998 combat.qc
   2914  7 Jan  1998 buttons.qc
  23182  7 Jan  1998 weapons.qc
   7888  7 Jan  1998 plats.qc
  15564  7 Jan  1998 doors.qc
  25924  7 Jan  1998 items.qc
    502  7 Jan  1998 frogphys.qcp
   2165  7 Jan  1998 server.qc
   4735  7 Jan  1998 subs.qc
  17554 26 Sep  1996 player.qc
  15088 26 Sep  1996 misc.qc


Reviewing a diff of this version to the previous version shows a one line change in the "botphys.qc" file related perhaps to the bot stepping out of water.



## Pre-Release

There was some murmurings about the frogbot before the official release.

A demo of the frogbot in action was released and announced on inside3d in February 1998.

Record of this announcement seems lost, although we know about it by a second-hand post on Blues News.

	FrogBot [Feb 19, 1998, 11:00 am ET]

	There's a demo on Inside 3D of a beta of the FrogBot, a new client bot in the works for Quake that they seem to feel could be the most formidable Quake bot ever encountered when it's released.

-- <https://www.bluesnews.com/s/231003/frogbot>

Timm Stokke aka "Mr?" interviewed Robert about the Frogbot in late February 1998.

The interview was announced on Blues News.

	Saturday, February 28, 1998

	Frog

	There is also an interview with Robert 'frog' Field, the author of the FrogBot on Metropolis, where there is also a demo of man a versus machine deathmatch showing the FrogBot for Quake in action.

-- <https://www.bluesnews.com/archives/feb98-4.html>

In the interview, Robert comments that he had been working on the bot since November 1997.

	Timm: how long time have you, and are you planing to use on it?

	Robert:
	First thing I did was the Frogbot physics mod (the code may still be at the botshop). This is a manual control bot. It is the only bot to my knowledge that basically emulates player physics exactly. I started this physics patch last November and basically finished it in January. At the time of was also testing out various waypoint approaches.

	When I released the Frogbot physics code (the Frogbot was taking too long so I wanted to release something) I decided to start afresh on the Frogbot. I scrapped all the dynamic waypoint stuff I was doing because I couldn't get a desirable framerate with it and it was generally far more unworkable than using static waypoints (which is all that the Frogbot supports).

-- [http://www.telefragged.com/metro/interview_frog.html](https://web.archive.org/web/19981206021000/http://www.telefragged.com/metro/interview_frog.html) (archived December 06 1998)

He also comments his goal of figuring out the hard problem of making the bot move like a player using QuakeC code alone.

	Timm: in which areas will the frogbot be ground-breaking?

	Robert:
	Hey this is the time for me to make big ego boosting comments. :)

	Currently the bots have the same physics model as a player, which would seem easy except id has deliberately or by accident obstructed that (it would take minor changes to quake.exe to allow this, but I have been forced to do the changes in QuakeC).

	I'm pretty proud of the mouse movement of the bots (you can become a bot). It hopefully is getting very playerlike.

	The bots are quite good at hogging stuff on the level and generally move around fluently (though the omicron is quite fluent - I've seen it navigate well on dm6).

	Generally all that stuff you hear that they can now do with Quake2 because it uses C (which of course is better to use) I know can be done with little old QuakeC. (of course without configuring from .ini files, etc - ed)

	Hopefully the Frogbot will appear to be a thoughtful (at least on higher skill levels) and realistic opponent.

	Well I can see at least a couple more months yet on the Frogbot, if I can squeeze in the time.

-- [http://www.telefragged.com/metro/interview_frog.html](https://web.archive.org/web/19981206021000/http://www.telefragged.com/metro/interview_frog.html) (archived December 06 1998)

This helped to fuel the anticipation of the bot among the community.






## Frogbot v0.00

The first version of the Frogbot was released as frogbot000.zip.

The release was announced on Blues News as a 25% complete alpha release.

	Sunday, March 8, 1998

	FrogBot
	The first public release of the FrogBot for Quake has been released over at Metropolis. Described as a 25% complete alpha or early beta, this version only supports play on DM6 (DM2, DM3, and DM4 support are promised soon), but the early report is that this is one of the more impressive showings on the AI scene.

-- <https://www.bluesnews.com/archives/march98-1.html>

The release was also announced on inside3D.

Both sites refer to the "Metropolis" website as the proxy home for the bot. This was a Quake news website created by Timm Stokke, formally a contributor to inside3d.

Metropolis became and remained the home for the bot and is mentioned in the readme file as the place to download the bot.

Nevertheless, not all new related to the bot broke on the site as my guess is that forum messages remained Roberts main way of announcing releases.

	Latest News March 8th

	Ribbit - Seconds ago, according to Timm, the Frog Bot was released! This is an excellent new bot for Quake1, find more information at Timm's newest page, Metropolis.

-- [http://www.inside3d.com/mar08-mar09.html](https://web.archive.org/web/19980614161728/http://www.inside3d.com/mar08-mar09.html) (archived June 14 1998)

A copy of this release was donated to the Quake Bot Archive.

The release contains a readme file (readme.txt) and a PAK file.

   2130  9 Mar  1998 readme.txt
 370389  9 Mar  1998 pak0.pak

The PAK file contains the compiled game code (progs.dat) a config file (quake.rc) and sound files, the same general composition as the Frogbot Physics release.

	progs.dat
	quake.rc
	sound/demon/dland2.wav
	sound/misc/h2ohit1.wav

The readme lists the release date as March 09 1998. This is one day after the announcements on Inside3D and Blues News. I suspect the release was distributed on March 8th, then updated with the same file name on March 9th without a version change.

	Title     : Frogbot
	Filenames : frogbot000.zip, skins.zip
	Version   : Beta 0.00
	Date      : 9 Mar 1998
	Author    : Robert Field
	Email     : frog@powerup.com.au
	Download  : www.telefragged.com/metro

-- readme.txt

The readme file was terse with fewer technical details than the Frogbot Physics release eariler.

It includes instructions for installing the bot, and lists the commands the user may use to manipulate the bots in the game.

The readme does suggest that a private beta of the bot had been distributed for testing to Timm Stokke of the Metropolis website, and Brent Phillips aka "Randar" of "Randar Bot Page" website.

This note, along with the odd numbered versions of later releases may suggest that even numbered releases (except 0.00 and including v0.02) were for private testing, and odd numbered releases (except 0.01) were used for public releases.

	Thanks
	------

	Timm 'Timmi' Stokke and Brent 'Randar' Phillips and the rest of the
	private beta test team for being so enthusiastic.

-- readme.txt




## Frogbot v0.03

The next version of the frogbot was released as frogbot003.zip.

The release was announced on blues news on March 23 1998, about two weeks after the previous release.

	Monday, March 23, 1998

	FrogBot for Quake
	Version 0.03 of the FrogBot is up on Metropolis Quake 1 & 2 bot news. The updated version of this Quake bot can now play on DM4 as well as DM6, supports deathmatch 1-5 modes (as in QuakeWorld), and adds "more" AI. I played it for a bit and it behaved surprisingly realistically (it played really well without having "digital aim").

-- <https://www.bluesnews.com/archives/march98-3.html>


This release was also announced on Redwood News on the same day.

	March 23, 1998

	Frogbot 0.3

	The Frogbot 0.3 has been released and can be found at Metropolis. I haven't tried this one yet so I don't know how it compares to other bots.

-- [http://redwood.stomped.com/398.html](https://web.archive.org/web/20011122033345/http://redwood.stomped.com/398.html) (archived November 22 2001)

Finally, the release was announced on inside3d, then the wrong author and version number were corrected in a news update.

	Latest News March 23rd

	Ribbit - Over at Metropolis, your pal and mine, Timm, has posted version 0.3 of the Frogbot by Mr. Elusive. Go get it.

	Whoops - D'oh. I wasn't thinking when I posted about the frog bot--the author is Robert 'Frog' Field, not Mr Elusive (Mr Elusive is the Omicron bot author..I think). Also, it's at version 0.03, not 0.3

-- [http://www.inside3d.com/mar23-mar24.html](https://web.archive.org/web/19980614161854/http://www.inside3d.com/mar23-mar24.html) (archived June 14 1998)

The wider announcement of the bot may be due to the growing interest and following in what was shaping up to be the Quake bot with most advanced client emulation seen to-date.

A copy of this release was donated to the Quake Bot Archive.

The release contains the same assortment of files, namely a readme and PAK file.

   3664 22 Mar  1998 readme.txt
 407884 22 Mar  1998 Pak0.pak

The readme file lists the release date as March 22 1998, one day before the announcement on news sites.

	Title		: Frogbot
	Filename	: frogbot003.zip
	Version	: Beta 0.03
	Date		: 22 Mar 1998
	Author	: Robert Field

-- readme.txt

This release contains a larger description about the bot and the goals of the project.

 	The Frogbot mod is my continuing attempt to create a bot that is believably human. I judge my efforts soley on the game product you play, and not on some theoretic discussions of AI implementation methods.

-- readme.txt

He comments that the AI for the bot is quite minimal, and that instead the focus is on the bot movement and making as close to a real player as possible.

	The current AI of the Frogbot is what I would regard as a minimal working model.

	[...]

 	The Frogbot is a 99.9% client emulation bot. To my knowledge it is the only QuakeC bot that accomplishes this. The missing 0.1% is that the Frogbot on rare occasions can get stuck on or near steps (if I didn't say this you may have never known this :).

-- readme.txt

There is no changelog in the readme, nor source code, so the specific nature of the changes in this release are not known.




## Frogbot v0.05

The next version of the frogbot was released as frogbot005.zip.

The release was announced on Blues News on March 29 1998.

	Sunday, March 29, 1998

	FrogBot

	Ribit! Version 0.05 of the FrogBot is up on the Metropolis.

-- <https://www.bluesnews.com/archives/march98-4.html>

The release was also announced on Inside3D on the same day.

	Latest News March 29th

	Frogbot v0.05 is now out. The almighty Quake 1 bot with the player moves is now even better featuring KasCam, better AI, and other goodies.

-- [http://www.inside3d.com/mar26-mar29.html](https://web.archive.org/web/19980614161937/http://www.inside3d.com/mar26-mar29.html) (archived June 14 1998)

A copy of this release was donated to the Quake Bot Archive.

The release contains the same assortment of files as the previous two releases.

 442191 29 Mar  1998 Pak0.pak
   4150 29 Mar  1998 readme.txt

The readme file lists the release date as March 29. This matches the timestamps of files in the release, and the release date on news sites.

This release comes one week after the previous major release.


	Title		: Frogbot
	Filename	: frogbot005.zip
	Version	: Beta 0.05
	Date		: 29 Mar 1998
	Author	: Robert Field
	Email		: frog@powerup.com.au

-- readme.txt

As with the previous release, there is no changelog. As such the changes that motivated this release are not known.




## Frogbot v0.07

The next version of the bot was distributed as frogbot007.zip.

The release was announced on May 08 1998 on Blues News. This is taken as the release date.

	Friday, May 8, 1998

	FrogBot

	Version 0.07 of the FrogBot, the state-of-the-art classic Quake AI playmate is out on the Frogbot homepage offering runes (for bots too), grapple (humans only), favorite weapon toggle (rl\shaft), teamplay 1-5 support, deathmatch 1-6 support, match mode, custom models if wanted, and more.

-- <https://www.bluesnews.com/archives/may98-1.html>


This release was also announced on Metropolis one day later.

It mentions a number of changes in the release and requests that all feedback be provided on the message boards.

	^last updated^09.may.98^

	Frogbot 0.07 released! Yikes, finally Frog has released a new version. Here are some of the new features..

		- runes (for bots too)
		- grapple (humans only)
		- fav. weapon: rl\shaft toggle
		- teamplay 1-5 support
		- deathmatch 1-6 support
		- cheat skills (aim better)
		- match mode (/w countdown)
		- custom models if wanted (for grappler, etc)
		- and more..

	Only downside I've found so far is the lack of new maps. Yeah, I know it sucks, but as Frog put it, "Sometimes a step backward must be taken to take two steps forward." Now, go play the damn thing, will ya?

	The QuakeWorld version will be delayed due to some bugs in the QWSV (not actually bugs, but stuff that made a frog qw port difficult. However, when the new QW is released, and if Zoid fixes the problem, you should see a QW version right around the corner.

	And remember.. if you find any bugs, report them using our Quake1 messageboard. Thank you. Now.. F R A G F E A S T !

-- [http://www.telefragged.com/metro/](https://web.archive.org/web/19980626082929/http://www.telefragged.com/metro/) (archived June 26 1998)

A copy of this release and its readme file cannot be located.








## Frogbot v0.09

The next version of the frogbot was released as frogbot009.zip.


The release was announced on Blues News on May 18 1998.

	Monday, May 18, 1998

	FrogBot
	Version 0.9 of the FrogBot, the AI playmate for Quake is now up on Frogbot homepage & Timm's rants, offering a bunch of enhancements. There was promise of a QuakeWorld compatible version this time out, but that's still in the works at this point.

-- <https://www.bluesnews.com/archives/may98-3.html>

It was also announced on the Metropolis homepage, again listing a changelog of bug fixes in the release.

The message notes the continued development on a Quakeworld version of the bot. This will become perhaps the biggest success of the game.

	^last updated^18.may.98^

	Frogbot 0.09 released! And this release adds something very cool never before seen in a QC bot.. selectable names! The full new feature list is..

		- Able to spawn a bot of any name or color you pick (high asii included).
		- Cheat aim skills above 100 to 200 (old 101 = 200 )
		- Replaced skill 102 by a lavacheat command
		- Fixed film@11 bug.
		- List the bots and their skills if they are in the level before you are.
		- Fixed timelimit in the match mode.
		- Fixed the deathmatch 4 quad bug.
		- Admin command.
		- More remote server commands.

	The QW version is still pretty dead, as Zoid didn't know how to fix the problem. We're still hoping, though (Atleast I am =)

	With the new editable bot profile thingy, I'm thinking of releaseing a "bot pack" with cool bots. If you have any good ones, feel freee to submit them. Oh, btw, check out my little frogbot match pic =)

	And remember.. if you find any bugs, report them using our Quake1 messageboard. Thank you. Now.. F R A G F E A S T !

-- [http://www.telefragged.com/metro/](https://web.archive.org/web/19980626082929/http://www.telefragged.com/metro/) (archived June 26 1998)

A copy of this release was donated to the Quake Bot Archive.

The contents of the release is quite different to previous release.

It contains the compiled game code (progs.dat), a readme file (readme.txt), config files (config.cfg, quake.rc, and frogbot.cfg) and many .bot files.

The .bot files are profiles for different bot "characters" supported in the game. Really, just configurable bot names.

  14861 18 May  1998 readme.txt
   3006 18 May  1998 config.cfg
 436780 18 May  1998 progs.dat
    264 18 May  1998 hello.nam
   1956 18 May  1998 quake.rc
    524 18 May  1998 frogbot.cfg
    462 17 May  1998 hello.bot
    217 17 May  1998 zap.bot
    277 17 May  1998 yoda.bot
    288 17 May  1998 thresh.bot
    337 17 May  1998 supman.bot
    313 17 May  1998 reptile.bot
    312 17 May  1998 nemesis.bot
    505 17 May  1998 killmach.bot
    362 17 May  1998 goldboy.bot
    288 17 May  1998 girlie.bot
    506 17 May  1998 genfail.bot
    336 17 May  1998 fraggod.bot
    241 17 May  1998 dude.bot
    325 17 May  1998 dragon.bot
    265 17 May  1998 dizzy.bot
    480 17 May  1998 corpgrin.bot
    217 17 May  1998 bro.bot
    481 17 May  1998 add2quak.bot

The readme file lists the release date as May 18 1998. This matches the timestamps for the newest files in the zip file and the announcements on news sites.

This release comes 10 days after the previous release.

	Title        : Frogbot
	Filename     : frogbot009.zip
	Date         : 18 May 1998
	Author       : Robert Field
	Email        : frog@powerup.com.au
	Download     : http://www.telefragged.com/metro/
	Next version : Probably not before July, since I have my uni exams finish at the end of June.

-- readme.txt

The readme file is expanded in scope.

It provides installation and usage instructions, then provides in-depth instructions regarding the .bot files and how to develop new bot characters using these custom files.

	In the frogbot directory you will see files will the .bot suffix. Executing one of these will spawn the bot with the information of that file (or any existing information such as skill if this isn't in the file). You may make your own .bot file and then execute it to spawn a bot to your liking. [...]

-- readme.txt

The release also supports many different deathmatch modes, including teamplay, which includes a suite of new commands to control bot teams.




## Frogbot v0.11

The next release is uncertain, although was probably 0.11 released as frogbot011.zip.

The only evidence for this release was a news post on Blues News on July 14 1998.

This date is corroborated in the readme file of the next release and is take as the probable release date.

	Tuesday, July 14, 1998

	New FrogBot for Quake  [11:41 AM EDT]
	Version 0.11 of the FrogBot for classic Quake is up on the Metropolis offering some bug-fixes and enhancements, as  well as a QuakeWorld version. I found the text on the site hard to read under Navigator, so you may want to try highlighting the text.

-- <https://www.bluesnews.com/archives/july98-2.html>

A copy of this release has not been located.





## Frogbot v0.11b

The next version of the frogbot was v0,.11b which was distributed as frogbot011b.zip.

This was a likely a bugfix release for the 0.11 release.

A copy of this release was donated to the Quake Bot Archive.

It contains a cleaner structure compared to the previous release. It is limited to the compiled game code for quake (progs.dat) and quake world (qwprogs.dat), a readme file (readme.txt), config files, and a bots directory for all of the bot profiles.

	   608 16 Dec 13:57 bots
	 16675 15 Jul  1998 readme.txt
	321888 15 Jul  1998 qwprogs.dat
	344492 15 Jul  1998 progs.dat
	   604 14 Jul  1998 frogbot.cfg
	  2021 15 Jun  1998 quake.rc
	  1808 12 Jun  1998 frontend.cfg

The readme lists the release date as Jul 14 1998. I believe this was for the previous release v0.11.

The most recent files in the release are dated one day later on July 15 1998, which is taken as the release date for this version.

	Title        : Frogbot
	Filename     : frogbot011b.zip
	Date         : 14 July 1998
	Author       : Robert Field
	Email        : frog@powerup.com.au
	Download     : http://www.telefragged.com/metro/

-- readme.txt

The readme was updated as can be seen by the newer file timestamp of thr 15th. The release filename is listed as frogbot011b.zip, although the filename in the installation instructions is listed as frogbot011.zip. This was probably the filename for the previous release.

	Create a directory called frogbot as a subdirectory in your Quake directory and unzip frogbot011.zip into it. [...]

-- readme.txt


The readme also lists a changelog, compared to the previous release, presumably v0.09.

The major focus for this release appears to be client emulation support for quakeworld, in addition to quake.

	What's new in version 0.11
	--------------------------

	- Colored bodies in GLQuake.
	- QuakeWorld version.
	- QuakeWorld emulation in normal Quake version.
	- Backpack retrieval bug fixed.
	- Better bot weapon selection.
	- Faster spawning of bots.
	- Some changes to AI.

-- readme.txt



## Frogbot v0.12a

The next version of the bot as v0.12 and was released as frogbot012.zip.

A series of bug fix releases followed, each released with the same filename and given a letter suffix, e.g. "b", "c". As such, we can rename this version as v0.12a to be consistent.

The release was was announced on October 16 1998. This is taken as the probably release date. This is more than 3 months after the previous release.

	Latest News October 16th

	Frog Bots- Frogbot v0.12 has been released. This contains many more options and supports a new map. FrogBot is the only bot still in development for Quake 1. Here is the site.

-- [http://inside3d.com/](https://web.archive.org/web/19981111184716/http://inside3d.com:80/) (archived November 11 1998)

The release was announced on Metropolis one day later.

The announcement helpfully includes a changelog for the new version, likely taken from the readme file.

The major takeaway for this release is the inclusion of the source code.

	Saturday, October 17, 1998

	Alright! The frogbot is out in a new version, this time 0.12! Get ready to rock and roll! New stuff includes..

	- Various miscellaneous bugs fixed.
	- ztndm3 support.
	- Bots can understand air movement on difficult jumps (ie. curved jump prediction).
	- Qizmo support for smoother Quakeworld play.
	- More friendly teammates (they hopefully won't try to steal items that you are waiting for).
	- msg= command in normal Quake, and msg command in Quakeworld now works.
	- Better bot jumping and ledge avoidance. Though I improved the jump prediction algorithm substantially, I also found (and fixed) quite a nasty jump bug. Basically, in 5 server frames each second a jump request was ignored. Hence either the jump was delayed or too late to make (the delay being the frame time of the server - this was quite bad in the Quakeworld version, which I hadn't tested adequately, since it has only 18.2 server frames per second).
	- Added experimental lookcheat command.
	- Added skinfix command.
	- Source included.

	Yepp, that's right, the source is now included! You QC gurus can now get crankin on adding your own features. But be sure to ASK FROG FOR PERMISSION BEFORE RELEASING ANYTHING! You can get the file from the download section. (be sure to grab ztndm3 while you're there too.. )

	ROCK!

-- [http://www.telefragged.com/metro/](https://web.archive.org/web/19981202161907/http://www.telefragged.com:80/metro/) (archived December 02 1998)

The release was also announced on blues news, mentioning that the source code was included n in the release.

	Saturday, October 17, 1998

	Quake FrogBot  [11:48 AM EDT]
	The Metropolis FrogBot homepage has the latest release of the one bot for classic Quake that remains in production, version 0.12 of the FrogBot ("I got better..."). The new release offers many fixes and enhancements, and the source code is included.

-- <https://www.bluesnews.com/archives/oct98-3.html>

A copy of this release has not been located.


## Frogbot v0.12b

A bug fix release was released.

It was referred to as 0.12 and released with the same filename on Metropolis as the previous release: frogbot012.zip. It was announced on October 18 1998, two days after the previous release.

	Sunday, October 18, 1998

	There was a tiny little bug in the 0.12 release, and the new version has been uploaded. The filename is the same, grab it at your left.

-- [http://www.telefragged.com/metro/](https://web.archive.org/web/19981202161907/http://www.telefragged.com:80/metro/) (archived December 02 1998)

Redwood News announced the release three days later and referred to it as version 0.12b and linked to a file on telefragged.com with the name frogbot012b.zip.

It is possible that Robert referred to it this way in a message board post.

	October 21, 1998

	Frogbot .12b

	Frogbot .12b is an update to this Quake 1 bot that fixes teamplay sharing and adds notes on compiling the bot into the zip. See the Frogbot Home page for more info.

-- [http://redwood.stomped.com/1098.html](https://web.archive.org/web/20000818062242/http://redwood.stomped.com/1098.html) (archived August 18 2000)

A copy of this release has not been located.

As such, the nature of the bug fix is not known




## Frogbot v0.12c

The next release was distributed with the same filename as the last two releases frogbot012.zip.

The release was announced as another bug fix release and was referred to as version 0.12c on Metropolis.

	Friday, October 23, 1998

	Another bug fixed, another version released. (0.12c) This time, it also includes some info for those who wants to compile the source. Check it out on your left. (same filename..)

	Go rock the frog.

-- [http://www.telefragged.com/metro/](https://web.archive.org/web/19981202161907/http://www.telefragged.com:80/metro/) (archived December 02 1998)

This was the last main release of the bot and source code. As such, it remains widely available online.

The release contains a src/ directory with the QuakeC source code and a bots/ directory for the bot profiles, as well as compiled game code, config files and readme files.

A new readme file is included describing the source code (srcnotes.txt)

  	1120 16 Dec 13:59 src
    608 16 Dec 13:59 bots
	360084 23 Oct  1998 progs.dat
	338272 23 Oct  1998 qwprogs.dat
	 20486 23 Oct  1998 readme.txt
	  2261 21 Oct  1998 srcnotes.txt
	   338 16 Oct  1998 quake.rc
	   122 14 Oct  1998 frontend.cfg
	   604 14 Jul  1998 frogbot.cfg

The readme lists the release filename as frogbot012c.zip, although it was widely distributed as frogbot012.zip, the filename adopted on Metropolis.

The readme lists the release date as October 23 1998, matching the file timestamps in the zip and the news announcement on Metropolis.

	Title        : Frogbot
	Filename     : frogbot012c.zip
	Date         : 23 October 1998
	Author       : Robert Field
	Email        : frog@powerup.com.au
	Download     : http://www.telefragged.com/metro/

-- readme.txt

A changelog is lised at the top of the readme and is identical to the one listed in the first release for v0.12, with the addition of one line:

	- noflash command.

-- readme.txt

The source code readme file provides technical details on how to compile the source code.

This was the last official release of the bot, although subsequent less official releases were made.




## Frogbot Demos

The next release was a series of demos distributed as frogbot_demo.zip.

The release contained pre-recorded demos of frogbot behavior in specific situations.

The release was announced on Metropolis on January 10 1999, more than 2.5 months since the last release.

	Saturday January 10 1999

	Frogbot mods has gotten hold of a few demos from Frog, showing off some new features that'll be included in the next version. I haven't check 'em out yet (downloading still), but I'd urge everyone to check it out. Wrecker over at FBMODS, said they rock. There's also some interesting new mods up at FBMODS, so check it out.

-- [http://home.telefragged.com/metro/](https://web.archive.org/web/19990203023029/http://home.telefragged.com/metro/) (archived February 03 1999)

These demos were mentioned in a later release which dated the release of the videos as January 09 1999, one day before the announcement on Metropolis.

	Why release this "version"?
	===========================

	Interest has been expressed in the demos of frogbot_demo.zip dated 1/9/99.

-- frogbot013.zip/readme.txt

A copy of this release has not been located.





## Frog Fix

The next release was a code fix distributed as frogfix1.zip.

I believe this was released by Robert Field, but I have no hard evidence.

The release contained a text single file (fix.txt)

 34787 29 Jan  1999 fix.txt

The text file is dated January 29 1999, matching the timestamp of the file in the zip.

The release is a bug fix for the code released in version 0.12c that crashed in some situations.


	Bug fix for Frogbot v0.12c and mods based on it
	===============================================

	Date: 29 Jan 1999
	-----------------

	Fixes:
	1) The crash caused when loading bots.
	2) The crash when changing level with bots still entering the level (one line change in execute_changelevel).
	3) Some glitches in maps (eg. e1m3).


	Substitute the following functions. Check if you have previously changed the original functions and adapt accordingly.

-- fix.txt

The bug fix was listed on the file section part of the "Frogbot Modifications" website known FMODS.

	Frog released the bugfix for version 0.12c. It fixes crashes when loading maps and some map bugs (e.g. e1m3)

-- [http://www.botepidemic.com/fmods/ofiles.htm](https://web.archive.org/web/20000818044633/http://www.botepidemic.com/fmods/ofiles.htm) (archived August 28 1999)








## Frogbot v0.13 Test

The next and final version of the frogbot was released as frogbot013.zip.

It was referred to as version 0.13 test and represents the source code for the frogbot used in the demos released in January 1999.

The release was announced on Blues News on April 27 1999.

	Tuesday, Apr 27, 1999

	New Frogbot [03:09 am ET]

	Frogbot's Modifications page has a new Frogbot 0.13 test version enhancing the AI in this Quake 1 playmate.

-- <https://www.bluesnews.com/cgi-bin/blammo.pl?mode=archive&display=19990426>

The release was also announced on Metropolis, two days later on the 29th.

	Tuesday April 29 1999

	Hey, it's only been a month or.. two. Yeh, well, sorry about that.
	Anyway, Frog has released a Frogbot 1.3 test version (yes, that is the same version that was used for those cool demos he released some time back). You can grab this sucker from the downloads page. There is quite a lot of new fancy stuff in there, although Frog does not recommend you guys to actually replace this version with the 0.12c version (or whatever frogmod you're using). Have fun with this one guys!

-- [http://www.telefragged.com/metro/](https://web.archive.org/web/19990508210848/http://www.telefragged.com/metro/) (archived May 08 1999)

The download page on the Metropolis webpage provides a description of the release, suggesting it is for mod developers rather than end users, e.g. a "technology demo".

	Frogbot v0.13 test

	This is how Frog himself put it,

	Interest has been expressed in the demos of frogbot_demo.zip dated 1/9/99. This is the build of the source, warts and all, that produced those demos. I would not suggest replacing current frogbot versions on your hard disk with this version. Though there are some things in this version that may be of interest to people. This release could be viewed as a technology demo, displaying certain bot abilities which have yet to be integrated into a coherent whole.

-- [http://www.telefragged.com/metro/frogbot_download.shtml](https://web.archive.org/web/19990503064109/http://www.telefragged.com/metro/frogbot_download.shtml) (archived May 03 1999)

As the last release of the bot, it remains widely available online.

The release contains the same general assortment of files as previous releases, as well as a zip file for the source code (src.zip) and the bot profiles (bots.zip). The readme file for the previous release, v0.12c was also included as that was the last official release of the bot.


   7072 26 Apr  1999 readme.txt
 418212 26 Apr  1999 qwprogs.dat
 491072 26 Apr  1999 progs.dat
 170074 26 Apr  1999 src.zip
   3846 25 Apr  1999 bots.zip
   1150 23 Dec  1998 console1.cfg
   1831 23 Dec  1998 alias.cfg
    138 17 Nov  1998 frontend.cfg
    354 17 Nov  1998 quake.rc
    864 12 Nov  1998 console2.cfg
  20486 23 Oct  1998 readme012c.txt
    604 14 Jul  1998 frogbot.cfg


The readme for this test version lists the release date as April 26 1999. This is one day before the announcement on Blues News, although matches the timestamps of some of the newest files in the zip file and is the likely release date.

	Title        : Frogbot test version (does not replace older frogbot versions)
	Filename     : frogbot013.zip
	Date         : 26 April 1999
	Author       : Robert Field
	Email        : frog@powerup.com.au
	Download     : http://www.telefragged.com/metro/

-- readme.txt

The release is clearly marked as a test version and not a replacement for prior versions.

This release is described as a "warts and all" release, including instructions on how to compile the code in order to achieve the behaviors observed in the demos released earlier in the year.

	Interest has been expressed in the demos of frogbot_demo.zip dated 1/9/99. This is the build of the source, warts and all, that produced those demos. I would not suggest replacing current frogbot versions on your hard disk with this version. Though there are some things in this version that may be of interest to people.
	This release could be viewed as a technology demo, displaying certain bot abilities which have yet to be integrated into a coherent whole.

-- readme.txt

Interestingly, the release also includes a "maze game", developed to test an array implementation in the QuakeC language.

	While not that polished, included is a maze game. It is only for the Quake version, but it has multiplayer capabilty.
	To play the maze game, type "arcade" at the console, then restart a map.
	Each time you start a map a maze will be randomly created. A feature of the maze algorithm that I have worked out is that it produces no direct dead ends and no isolated (ie. single dot) walls. This is to maximize playabilty.
	Movement is achieved by the same keys/buttons you use for Quake movement.

-- readme.txt






## Frogbot Editor (FBEdit)

Frogbot allowed the user to customize the bot profiles, like names and colors used by the bots.

Shortly after the release of version 0.09 of the Frogbot, a "Frogbot Editor" or FBEdit was released.

	This does not require a degree to use. It allows you to make bot files. I was asked to program this so you can easily make "fun names" for the bots. It is very easy to use, and the GUI was designed to be as error free, and clutter free as possible.

-- [http://qnm.telefragged.com/fbedit/fberead.shtml](https://web.archive.org/web/20001017212608/http://qnm.telefragged.com/fbedit/fberead.shtml) (archived October 17 2000)

The project was developed and maintained by Anthony Gary Browneller aka Tony, the author of the Quake Name Editor (QNE).

The goal of the project was to allow map editors and mod authors to easily prepare maps for use by the bot

	Frog Bot Editor was designed to make bot files for the FrogBot mod for Quake.

-- fbedit12.txt

Perhaps the first public version was announced on Metropolis on May 25 1998 as version 1.2.

	^last updated^25.may.98^

	Tony has been very cool, and designed a program to use for creating .bot files for use with the Frogbot. The program is very slick, easy to understand, and (if you have the VB5.0 dll's) under 50k! (If you don't have the .dll's, howver, you're looking at a rather large download.. Most people have the dll's installed on their system, though) Pretty l33t, huh? This program is a MUST for ANYONE wanting to create frogbot names, but doesn't know how to.. It's so easy, my bro could even use it =) Kudo's to Tony!

		@ Visual Basic 5.0 DLL's (not required for all users)
		@ Frogbot Editor (50kb)

	You might also want to check out Tony's webpage where he has a list of all his programs (QNM\QNM2 - "Fun name" editor for Q1\Q2, MOTD - a message of the day editor for quake2, and more) Btw, I'm getting Unreal today - I can't wait. I'll tell you guys how things were (either by a review (of the bots, AI, etc) or by just a rant.. we'll see..)

-- [http://www.telefragged.com/metro/](https://web.archive.org/web/19980626082929/http://www.telefragged.com/metro/) (archived June 26 1998)

The changelog for the editor lists version 1.0 being released on May 23 1998, although a copy of this has not been located and it is not confirmed whether it was released publicly.

	Version 1.0
	  May 23rd, 1998
	    Initial Release

-- fbedit12.txt

The final public version of the editor was 1.8, which was released on August 04 1998 after the v0.11 releases, but before the v0.12 releases of the frogbot.

	Version 1.8
	August 4th, 1998

-- fbedit18.txt



## Frogbot Mods (FBMODS)

After the release of the source code for Frogbot v0.12 and later v0.13, many extensions of the bot were developed.

Most extensions were focused on bringing the Frogbot into other mods, like CTF, Holy Wards, and more.

A website called FMODs was created and hosted as a subsite under Bot Epidemic to share news and releases of frogbot extensions

The site was created by Andrius Jovaisa aka "Wrecker" and hosted news, files, tutorials, discussions, and much more.

The layout of the website was a little chaotic, and contained many pages with many links to a wide array of mods.

	The layout of FMODS has no pattern. reading release dates might help to determine which FMOD is new. And searching for the title might help, as this page grows bigger and bigger. :)

-- [http://www.botepidemic.com/fmods/mods.htm](https://web.archive.org/web/19991130145659/http://www.botepidemic.com/fmods/mods.htm) (archived November 30 1999)





## Frogbot Source Code GPL

Years later, the frogbot remained the preferred bot for avid QuakeWorld players for training.

As such, the bot was included by default in modern quakeworld ports based on the open source version of the game engine released by id software in 1999.

Quake and Quakeworld engines were released under a permissive GPL license.

In 2007, Robert Field was asked if he would release his frogbot under the same permissive license so that it could be included in the GPL version of modern Quakeworld games.

He agreed and in October 2007, the frogbot was released under the GPL license.

It was announced on the popular quakeworld forum quakeworld.nu.


	JohnNy_cz  /  4 Oct 2007, 14:08

	Frogbot gets GPL

	An important step in QuakeWorld development has happened today. The author of the most popular computer opponent in QuakeWorld, Robert 'Frog' Field, has agreed to release his Frogbot mod as an open source under the GPL.
	Robert Field wrote:

		I give permission to release all versions of the Frogbot under the GPL (GNU General Public License).

	This is an open way to integrate frogbots more deepely into the client and server and improve and update it even more than Parboil in his Frogbot Clan Arena project did.

-- <https://www.quakeworld.nu/news/177/frogbot-gets-gpl>





## Release Timeline

* Frogbot Physics v0.00, frogphys00.zip, January 07 1998
* Frogbot Physics v0.01, frogphys001.zip, January 09 1998
* Frogbot v0.00, frogbot000.zip, March 09 1998
* Frogbot v0.03, frogbot003.zip, March 22 1998
* Frogbot v0.05, frogbot005.zip, March 29 1998
* Frogbot v0.07, frogbot007.zip, May 08 1998
* Frogbot v0.09, frogbot009.zip, May 18 1998
* Frogbot v0.11a, frogbot011.zip, July 14 1998
* Frogbot v0.11b, frogbot011b.zip, July 15 1998
* Frogbot v0.12a, frogbot012.zip, October 16 1998
* Frogbot v0.12b, frogbot012.zip, October 18 1998
* Frogbot v0.12c, frogbot012.zip, October 23 1998
* Frogbot Demos, frogbot_demo.zip, January 09 1999
* Frogbot Fix, frogfix1.zip, January 29 1999
* Frogbot v0.13, frogbot013.zip, April 26 1999


## References

* [http://www.telefragged.com/metro/interview_frog.html](https://web.archive.org/web/19981206021000/http://www.telefragged.com/metro/interview_frog.html) (archived December 06 1998)
* [http://prime.telefragged.com/metro/frogbot_intro.shtml](https://web.archive.org/web/20030908211402/prime.telefragged.com/metro/frogbot_intro.shtml) (archived September 08 2003)
* [http://www.telefragged.com/metro/](https://web.archive.org/web/19980626082929/http://www.telefragged.com/metro/) (archived June 26 1998)
* [http://www.telefragged.com/metro/](https://web.archive.org/web/19981202161907/http://www.telefragged.com:80/metro/) (archived December 02 1998)
* [http://www.botepidemic.com/fmods/ofiles.htm](https://web.archive.org/web/20000818044633/http://www.botepidemic.com/fmods/ofiles.htm) (archived August 28 1999)
* [http://www.inside3d.com/mar08-mar09.html](https://web.archive.org/web/19980614161728/http://www.inside3d.com/mar08-mar09.html) (archived June 14 1998)
* [http://www.inside3d.com/mar26-mar29.html](https://web.archive.org/web/19980614161937/http://www.inside3d.com/mar26-mar29.html) (archived June 14 1998)
* [http://www.inside3d.com/mar23-mar24.html](https://web.archive.org/web/19980614161854/http://www.inside3d.com/mar23-mar24.html) (archived June 14 1998)
* [http://inside3d.com/](https://web.archive.org/web/19981111184716/http://inside3d.com:80/) (archived November 11 1998)
* [http://redwood.stomped.com/1098.html](https://web.archive.org/web/20000818062242/http://redwood.stomped.com/1098.html) (archived August 18 2000)
* [http://www.planetquake.com/botshop/news/1998-01.html](https://web.archive.org/web/19991018233525fw/http://www.planetquake.com/botshop/news/1998-01.html) (archived October 18 1999)

