# Frikbot

The Frikbot was developed by Ryan Smith aka "FrikaC".

It may be the last major bot development project for Quake.

The goal of the project, as started by Ryan, is to provide a bot toolkit to allow quake mod developers to easily add bots to mods.

This is a different goal from Omicron that aimed to provide an optimal opponent and from Frogbot that sought near perfect client emulation.

	FrikBot fills a niche in the grand scheme of things, not as being the best bot to play, but as a toolkit for other coders to make use of in their own work. Because of this, my bot gets a lot of attention by two separate groups: people who love to play old, dead mods where the addition of bots would have made a world of difference, and secondly by authors making totally new mods. My fans usually come from one group or the other.

-- [http://www.inside3d.com/?show=November-1999](https://web.archive.org/web/20001211145700/http://www.inside3d.com/?show=November-1999) (archived December 11 2000)

Given the goal of the bot, it was used widely and incorporated into a vast number of mods by both Ryan himself and via an active Frikbot community.

Ryan worked in game development on Prey 2 and other games at Human Head Studios.

	I've had the pleasure of writing a large portion of the AI systems for Prey 2 and other titles at Human Head Studios.

-- [http://www.frikac.com/?page_id=28](https://web.archive.org/web/20170410174820/http://www.frikac.com/?page_id=28) (archived April 10 2017)



## Frikbot v0.01

The first version of the Frikbot was v0.01.

It was probably released publicly and distributed with the filename frikbt01.zip.

No public record of this release exists, so we cannot be sure it was made public or remained private.

We can strongly suspect the existence of this release given the sequential nature of subsequent releases and from the changelog in the readme file of later releases.



## Frikbot v0.02

The next version of the Frikbot was v0.02.

It was probably released publicly and distributed with the filename frikbt02.zip.

We know about this release given the changelog included later release that lists the changes in this version of the prior v0.01 version.

	Changes since v0.01
	-------------------
	* Bot's Water Jumping now works.
	* Bug where any weapon fired using self.v_angle would fire at the wrong pitch
	* Error in the comment telling you how to install fixed
	* General improvements in the comment.

-- frikbt04.zip/readme.txt

A copy of this release has not been located and we cannot be entirely sure it was released publicly.



## Frikbot v0.03

The next version of the Frikbot was v0.03.

It was probably released publicly and distributed with the filename frikbt03.zip.

We know about this release given the changelog included later release that lists the changes in this version of the prior v0.02 version.


	Changes since v0.02
	-------------------
	* Bot's Water Jumping really works now!
	* Improved roaming
	* Different chat messages and bot names
	* Improved comments throughout the code
	* KickABot(); implemented to remove bots from the server
	* Numerous bug fixes

-- frikbt04.zip/readme.txt

A copy of this release has not been located and we cannot be entirely sure it was released publicly.



## Frikbot v0.04

The next version of the Frikbot was 0.04 released publicly as frikbt04.zip.

The release, and many subsequent releases can be found in modern mirrors of ftp.telefragged.com, such as on Quaddicted and [Dukeworld](https://dukeworld.com/telefragged/inside3d/frikbot/).

The release contains two files, a readme file (readme.txt) and a PAK file (pak0.pak).

 595262 23 May  1999 pak0.pak
   4268 23 May  1999 readme.txt

The PAK file contains sounds, compiled game code (progs.dat), and source code for the bot (src/bot.qc, src/bot_move.qc, src/bot_rank.qc).

	progs.dat
	sound/demon/dland2.wav
	sound/misc/h2ohit1.wav
	src/bot.qc
	src/bot_move.qc
	src/bot_rank.qc

It is surprising that the source code was released in this way. The user would have to know that the source is in the PAK and use a specialty program to unpack the files before use.

The readme file lists the release date as May 23 1999. This matches the timestamps of files in the zip file.

	Title    : FrikBot
	Filename : frikbt04.zip
	Version  : 0.04
	Date     : 5-23-99
	Author   : Ryan "Frika C" Smith

-- readme.txt

The readme gives credit to Roscoe Sincero aka "legion" for his bot movement code, Alan Kivlin aka "Virtuoso" for his bot rankings code, and Coffee for his Tutor bot for inspiration.

The Frikbot was probably developed from scratch with inspiration from other bots at the time.

This release and all subsequent releases were not uploaded to ftp.cdrom.com. They were released from the authors homepage for the project at http://rds.simplenet.com/frika/.

This website was not captured by archive.org, so we don't know how the bot was announced or about prior releases and related files that may have been released on the site.

The bot is described in the readme as "active like a player" as much as possible. This is achieved by implementing the bot by calling the same QuakeC functions used to control the player.

	This bot takes a unique approach. Unlike all other bots I've seen, FrikBot actually pretends to be a player. When he fires his weapon, it's the same function that the player uses. It is all done through his button flags. In other words, the bot fakes all client functions, he looks like a Quake client not only to the people in the game, but also to the Quake C. So why did I make him fake client behavior? Well with him using  all the player code, he automatically works with hundreds of mods with a few short lines of code added or changed. This bot will play by the game rules of nearly every mod out there. (though he doesn't always know the rules however)

-- readme.txt

The readme list a changelog for this release compared to the prior v0.0e version, listing a number of bug fixes.

	Changes since v0.03
	-------------------
	* Bot targeting moved to a priority system
	* Bots now fight in a variety of fight styles (circle strafe, hold distance)
	* Bots have a delayed sight time
	* Bug involving clients being added/removed after a bot has spawned fixed
	* Bots select weapons via impulses, chance of discharge in water lowered
	* Copyright permissions, new readme format.

-- readme.txt

It is clear from this point that the bot was intended to be used by other mod authors to add bots to their programs.

The source code for the bot provides comments with upgrade instructions for mod developers.

	To upgrade a mod using FrikBot 0.01, 0.02 or 0.03, simply replace all bot*.qc files with the ones provided and recompile

-- pak0.pak/src/bot.qc




## Frikbot v0.05

The next version of the bot was 0.05 released publicly as frikbt05.zip.

This release included the PAK file (pak0.pak) and readme file (readme.txt) as with the prior release, although the compiled game code (progs.dat) and source code (.qc) are included in the base directory in this release.

	  23342  9 Jun  1999 bot.qc
	   4953  8 Jun  1999 readme.txt
	 512960  8 Jun  1999 progs.dat
	  10574  8 Jun  1999 bot_rank.qc
	  82485  7 Jun  1999 bot_move.qc
	   2432 23 May  1999 pak0.pak
	   9140  6 Jul  1997 KC18DOC.TXT

The PAK file in this case only contains the two sound files.

	sound/demon/dland2.wav
	sound/misc/h2ohit1.wav

The readme for the release lists the release date June 07 1999.  The latest file timestamp in the release is June 09, which is taken as the release date.

	Title    : FrikBot
	Filename : frikbt05.zip
	Version  : 0.05
	Date     : 6-7-99
	Author   : Ryan "Frika C" Smith

-- readme.txt

This release introduces the KasCam chase camera for the bot developed by Karel Suhajda aka "Kashua", and includes the readme file for the mod (KC18DOC.TXT).

The changelog lists a number of bug fixes.


	Changes since v0.04
	-------------------
	* Implementation of fisible(); a minor improvement over the id standard visible code.
	* A bug where in very open levels, the bots would not switch targets upon death, fixed
	* Impulse comands moved to a function inside bot.qc, to aid in future updates/changes
	* Waypointing disabled in single player
	* Bots use client connect again!
	* Bots know how to play teamplay deathmatch. Set teamplay to nozero and enjoy!
	* KasCam included in progs.dat

-- readme.txt

The author's homepage is now hosted as a subside on a popular gaming server.

	Department 187 at http://www.mdqnet.net/dept187/

-- readme.txt

The site was not captured by archive.org, other than a message six months later indicating that the site had closed down.

	Department 187 has closed it's doors.

-- [http://www.mdqnet.net/dept187/frikbot.htm](https://web.archive.org/web/20000118183214/http://www.mdqnet.net/dept187/frikbot.htm) (archived January 18 2000)

Sometime between mid 1999 and 2000 Ryan began contributing news directly to the mdqnet.net news website, including releases of his own bot.




## Frikbot v0.06

The next version of the Frikbot was 0.06 released as frikbt06.zip.

The release contained the same general assortment of files as the prior release, including source code, readme, compiled game code and PAK file.


 518268 26 Jun  1999 progs.dat
  28385 26 Jun  1999 bot.qc
  82709 26 Jun  1999 bot_move.qc
   5305 26 Jun  1999 readme.txt
  11422 26 Jun  1999 bot_rank.qc
   2432 23 May  1999 pak0.pak

The readme file lists the release date as June 26 1999, matching the timestamps of files in the zip.

	Title    : FrikBot
	Filename : frikbt06.zip
	Version  : 0.06
	Date     : 6-26-99
	Author   : Ryan "Frika C" Smith

-- readme.txt

The readme provides a list of changes from the previous version.


	Changes sinve v0.05
	-------------------
	* Bot colors show in GL Quake!! Woohoo!!
	* Implementation of fov(). Bots now have a limited field of view.
	* Bots also have damn good hearing :)
	* Bot angles correspond to their view.
	* FL_ONGROUND hacks allow better compatibility with some mods.
	* Bots have a new fightstyle.
	* In teamplay, bots will choose the enemy team with the fewest players when using impulse 101
	* Misc. bug fixes and movement hacks.

-- readme.txt





## Frikbot v0.07

The next version of the bot was v0.07 released publicly as frikbt07.zip.

The release contained the same assortment of files as the previous release.


 517864 28 Jul  1999 progs.dat
   7133 28 Jul  1999 readme.txt
  38680 28 Jul  1999 bot.qc
   1693 28 Jul  1999 upgrade.txt
  54654 27 Jul  1999 bot_move.qc
  11593 18 Jul  1999 bot_rank.qc
   2432 23 May  1999 pak0.pak

The readme lists the release date as July 28 1999. The latest file timestamp in the zip is one day later on July 28 1999, which is taken as a the release date.

	Title    : FrikBot
	Filename : frikbt07.zip
	Version  : 0.07
	Date     : 7-28-99
	Author   : Ryan "Frika C" Smith

-- readme.txt


The bot may be seeing wider adoption and in turn Ryan is probably receiving may comments and suggest.

The credits section of the readme lists thanks to many handles, most of which have developed their own bots or soon will.

	All the people who helped me test this bot and made suggestions!
	  Especially: Wazat, Ze0, Kupop, MaNiAc, Kryten, and Asdf

-- readme.txt

The changelog for this release is more substantial than previous releases.


	Changes since v0.06
	-------------------
	* Bots viewing angle performed more realistically
	* Code restructuring, please pay attention to the upgrade.txt and the new instructions in the comment.
	* Finally corrected some troubles with the norse movement, including water jumping and gobs of wasted code.
	* Integrated botcam. Use impulse 103 to activate.
	* Corrected a bug in the installtion comment
	* Bots are thrown around by explosions, I can't believe I missed this before :(
	* Bots will switch weapons less often to make some mods less confusing
	* Bots will switch to a "close range weapon" sometimes rather than backing off in fightstyles 1 & 3
	* New bot roaming method called "Hook Navigation", bugs are still being ironed out on this new roaming concept.
	* fisible() improved to work properly with SOLID_BSP objects
	* Bots will attack secret doors, & buttons . Helps immensly in some levels.
	* Implementation of "scratch1" to adjust bot framerates
	* Bots will automatically stagger their think times against other bots so they all don't execute their think at the same time, causing a major slowdown.
	* Implementation of check_forward() to improve (ahem) standard roaming.
	* Special guest appearance of "JamesBond" as a bot name, in honor of the version number (0.07)
	* Misc. other bug fixes

-- readme.txt

The readme lists a detailed changelog available as a finger from mdqnet.net, although sadly the archive of the .plan files have not been saved.

	A detailed buglist can be obtained by fingering frika-c@mdqnet.net

-- readme.txt



## Frikbot v0.08

The next version of the bot was v0.08 released as frikbt08.zip.

This version of the bot was announced on inside3d.com, highlighting the bot as easy to integrate into other Quake mods.

	News Update Sunday, September 19

	New FrikBot - update by Kryten

	A new version of the FrikBot, for classic Quake, has been released today. FrikBot is a unique bot designed to plug-in to other mods. By changing a few lines in the code, the bot can play the mod in a matter of minutes. Useful to Quake C coders, the bot has a number of dedicated supporters that have placed the bot in a wide range of mods, including Future Versus Fantasy and other Q1 greats

-- [http://www.inside3d.com/?show=September-1999](https://web.archive.org/web/20001211163900/http://www.inside3d.com/?show=September-1999) (archived December 11 2000)

The release has a different assortment of files. In this case, the QuakeC source has increased from 3 files in the previous release to 6 files in this release. The release also includes the compiled game code, a readme and an upgrade readme file (upgrade.txt).

The PAK file containing sound files has been removed.

   1233 19 Sep  1999 upgrade.txt
  14445 19 Sep  1999 bot.qc
   7943 19 Sep  1999 readme.txt
  15614 19 Sep  1999 bot_phys.qc
  16215 19 Sep  1999 bot_ai.qc
 473708 19 Sep  1999 progs.dat
   4891 18 Sep  1999 bot_move.qc
   8639 17 Sep  1999 bot_rank.qc
   8239 16 Sep  1999 bot_way.qc

The readme lists the release date as September 19 1999, matching the dates of most files in the zip file.

	Title    : FrikBot
	Filename : frikbt08.zip
	Version  : 0.08
	Date     : 9-19-99
	Author   : Ryan "Frika C" Smith

-- readme.txt

The remade lists the changes in this version.

Notable is the removal of the Norse movement code from Roscoe, likely allowing the sound files to be removed.

	Changes since v0.07
	-------------------
	* Removal of Norse movement. Gone. Started work on new movement AI from scratch.
	* scratch1 is no longer valid. Don't use it.
	* Implementation of ported Quake physics (don't ask, don't tell is all I will say)
	* Bots are now MOVETYPE_WALK. They said it couldn't be done, hah!
	* Massive code restructuring, moved code into many files instead of cramming it into three. This was done to really help more with development than anything else.
	* Various bug fixes. I can't even remember half of them.
	* This is a major rewrite of most of the bot.

-- readme.txt




## Frikbot v0.09 Test

Prior to the next version a beta test was released as frik9tst.zip.

This release was not made public, but was distributed to a select number of beta testers.

A copy of this release was donated to the Quake Bot Archive.

It contained the compiled game code only.

This single file was had the timestamp of November 12 1999, two months after the previous release and months before the next release. It is likely that there were many beta releases of the 0.09 version of the bot during this time.

 487808 12 Nov  1999 progs.dat





## Frikbot v0.09

The next public version of the Frikbot was 0.09 released as frikbt09.zip.

This release was announced on mdqnet.net by Ryan himself. At this point, he was a contributor to the news on this site.

	February 22, 2000 - Post by Frika-C

	17:16 | FrikBot 0.09 FULL is out!! Weird, huh?!

	Wow it's been quite a while since I released an update to the FrikBot, too long some might say. Well here it is, likely to be the final edition of FrikBot, Frikbot 0.09! For those of you who don't already know, the FrikBot is a bot designed for QuakeC mod authors, or fans of old mods, that can be easily incorporated into just about any project with only a handful of lines of code that need to be added or changed. FrikBot will turn 1 year old in under a month, and it sure has come a long way in this last year. Anyway, enough talk, go download the spanky new FrikBot on the FrikBot page.

-- [http://www.mdqnet.net/](https://web.archive.org/web/20000226193121/http://www.mdqnet.net/) (archived Feruary 26 2000)

This release was also announced on inside3d on the same day.

	News Update Tuesday, February 22

	Frikbot 0.09 - update by Kryten

	FrikBot version 0.09 has just been released. The FrikBot is a QuakeC bot designed for mod authors or fans of older, no longer maintained Q1 modifications. It can easily be incorporated into just about any mod and you can have it up and playing in a few minutes. To demonstrate it's ability, there are a number of examples of the bot in such classics as Painkeep and Deathmatch Essentials on the homepage. The new version includes: new waypointing, more robust pathing, merged QuakeWorld and normal Quake code, and a truck load of bug fixes.

-- [http://www.inside3d.com/?show=February-2000](https://web.archive.org/web/20001211052900/http://www.inside3d.com/?show=February-2000) (archived December 11 2000)

The release contained 7 source code files, a readme and upgrade instructions, as well as compiled game code for quake (progs.dat) and compiled game code for quake world (qwprogs.dat).

 287048 22 Feb  2000 qwprogs.dat
 503400 22 Feb  2000 progs.dat
  24738 22 Feb  2000 bot_ai.qc
  23025 22 Feb  2000 bot_qw.qc
  19880 22 Feb  2000 bot_misc.qc
  14822 22 Feb  2000 bot_way.qc
  15089 22 Feb  2000 bot_phys.qc
   5399 22 Feb  2000 bot_move.qc
   2038 22 Feb  2000 upgrade.txt
  24542 22 Feb  2000 bot.qc
  13088 22 Feb  2000 readme.txt

The readme lists the release date as February 22 2000, matching the timestamps of files in the zip and news announcements.

	Title    : FrikBot
	Filename : frikbt09.zip
	Version  : 0.09
	Date     : 2-22-2000
	Author   : Ryan "Frika C" Smith

-- readme.txt

The readme contains an apology for the delay in the release, which was about 5 months since the 0.08 release.

He comments that this will probably be the last release of the bot.

	It has been many months since the last version of the FrikBot. I apologize for letting 0.09 just sit around for so long, but Real Life (tm) syndrome, and many other projects garnered for my attention. This will probably be the last edition of FrikBot as a QC bot. With the engine code out, I've already been porting my code to become a plug-in engine bot. As an engine bot, you'll be able to use the bot with any mod automatically. Currently this project is codenamed "FrikBot 2000". Do not ask too much about this as of yet. I am still not certain if I even have the time to devote to it.

The readme contains a changelog for this version. Major changes include support for bot skill levels and quakeworld support.

	Changes since v0.08
	-------------------
	* Skill settings. 0 = Easy, 1 = Normal, 2 = Hard, 3 = Nightmare
	* COOP is back! Bots play coop very poorly.
	* Better all around navigation
	* New chat code, might be replaced. Too bulky and buggy
	* Loads of new AI code
	* New teamplay AI (it isn't much, really)
	* Merged QW and NQ versions of the bot. Now everyone can't complain that I don't update the QW version enough :)
	* Rankings problems corrected. Quake will not crash after players enter/leave. Players joinging a game in progress will be able to see the bot's scoreboard.
	* Minor changes and bug fixes throughout

-- readme.txt





## Frikbot v0.09b

The next version of the bot was v0.09b released as frkbt09b.zip.

This has a slightly different filename naming convention from previous releases, e.g. "frikbtxx". The "b" suffix suggests a minor bug fix release and that 0.10 may be reserved for something larger.

There is no evidence that there was a v0.09a release.

The release was announced by Ryan on mdqnet.net.

	May 17, 2000, 03:02 | Frika-C

	I've put up a new FrikBot 0.09b, a FrikBot Waypoint Studio, an update to FrikQCC 2.2 and a DOS version of FrikQCC to boot. Also check out a new mod listed on the "3rd party mods". That is all.

-- [http://www.mdqnet.net/](https://web.archive.org/web/20000520015554/http://www.mdqnet.net/) (archived May 20 2000)

The release was also announced on inside3d.

	News Update Wednesday, May 17

	FrikBot - update by Kryten

	Frika C released an update to his Quake-C plugin bot, the FrikBot, yesterday. The update corrects several bugs reported to, and discovered by the author. In addition he also released FrikBot Waypoint Studio, an editor for the waypoints on the bot. If that weren't enough, he also released an upgrade to his FrikQCC, version 2.2. You can find all this on the FrikBot page.

-- http://www.inside3d.com/?show=May-2000 (archived December 11 2000)
https://web.archive.org/web/20001211121500/http://www.inside3d.com/?show=May-2000


 285212 17 May  2000 qwprogs.dat
 395796 16 May  2000 progs.dat
  13229 16 May  2000 readme.txt
  24291 15 May  2000 bot.qc
  15357 14 May  2000 bot_phys.qc
  22955 14 May  2000 bot_qw.qc
  14234 14 May  2000 bot_way.qc
  23289 14 May  2000 bot_ai.qc
  19611 31 Mar  2000 bot_misc.qc
   5764 14 Mar  2000 bot_move.qc
   2038 22 Feb  2000 upgrade.txt

The readme lists the release date as May 16 2000.

The oldest file timestamp in the zip is May 17, matching the news announcements for the release and is taken as the release date.

	Title    : FrikBot
	Filename : frikbt09a.zip
	Version  : 0.09b
	Date     : 5-16-2000
	Author   : Ryan "Frika C" Smith

-- readme.txt

The changelog does not give any specifics other than suggesting it is a bug fix release.

	Changes since v0.09
	-------------------
	* Bug fixes, most submitted by observant users of the bot. Thanks everyone!

-- readme.txt



## FrikbotX Pre-Release

The next release of the bot was to be v0.10, called FrikbotX or FBX for short.

	This release (nicknamed FrikBotX or simply FBX) represents several months of slow off and on work and is the 10th (or 12th - I'm not sure) and final release of the bot. FrikBot X, much like the infamous Frogbot relies heavily on hand-built waypoints for excellence in combat. It can however run without them, and it will attempt to create it's own waypoints as it plays. This is not recommended however.

-- gbx.zip/readme.html

Pre-release demo files were released as fbxdem.zip and fbxrj2.zip.

A copy of fbxdem.zip was acquired.

It contained a demo file (fbxdem.dem) and a readme file (fbxdemo.txt).

     667 25 May  2001 fbxdemo.txt
 2011996 25 May  2001 fbxdem.dem

The timestamps of the files in the zip was May 25 2001, taken as the release date of the demos.

The readme comments that the demo shows the behavior of the updated version of the bot.

	Alright, I guess I should give a little more taste of what is in store for you at QuakeExpo. This is me and my crappy game playing skills against a skill 2 FrikBot X.

-- fbxdemo.txt




## FrikbotX (FBX) v0.10.0

The next version of the the bot, dubbed FBX was v0.10.0 released as fbx.zip.

It was released as part of the Quake Expo 2001 and announced on the expo news page.

	FrikBotX has been released!
	News posted by Akuma at Fri Jul 27, 2001 08:32:50

	It's been a painfully long time in coming, but FrikBotX has finally been released over at FrikaC's booth!

	Need convincing that it's all that? Well, the other beta testers and I are pretty unanimous in saying that it's quite possibly the best bot. Ever. As realistic as the Omicron bot, if not more so, and it's a plugin bot (as always)! So, it's still easy to implement into your own mods, either if you're upgrading from an older version or using it as new.

	Enough babbling, GET IT!!

-- [http://qexpo.condemned.com/index.php?command=archive](https://web.archive.org/web/20020206230712/http://qexpo.condemned.com/index.php?command=archive) (archived February 06 2002)

A new webpage was created as a subsite on botepidemic.com for the Frikbot, which hosted this new version.

The new homepage provided a description of the bot as the 10th version and that all source code for the bot has been released into the public domain for general use.

	FrikBot X represents the 10th installment of this bot. With this possibly final version, FrikBot has been redesigned to be appealing to mod makers and casual players alike. Comprehensive documentation is included with the bot, covering all aspects of it's operation. Full source to the bot has also been included and is released into the public domain, which means the bot can be used for whatever project license and royalty free.

-- [http://www.botepidemic.com/frikbot/](https://web.archive.org/web/20011214084133/http://www.botepidemic.com/frikbot/) (archived December 14 2001)

The release contained 9 source code files (.qc), compiled game code for quake and quake world, a readme HTML file (readme.html), Windows bat files and a license document (gnu.txt).


	  23035 27 Jul  2001 bot_qw.qc
	  28792 27 Jul  2001 bot.qc
	 331244 27 Jul  2001 qwprogs.dat
	 613088 27 Jul  2001 progs.dat
	  44800 27 Jul  2001 readme.html
	  34526 27 Jul  2001 bot_ed.qc
	     51 26 Jul  2001 glrun.bat
	     47 26 Jul  2001 run.bat
	  14142 26 Jul  2001 bot_misc.qc
	  23208 26 Jul  2001 bot_ai.qc
	   8957 26 Jul  2001 bot_fight.qc
	  19809 26 Jul  2001 bot_way.qc
	  16967 25 Jul  2001 bot_phys.qc
	  11313 25 Jul  2001 bot_move.qc
	     96 14 Nov  2000 progs
	  14969 21 Dec  1999 gnu.txt

The readme HTML listed the release date as July 27 2001.

This matches the oldest file timestamps in the zip file and the announcement on the Quake Expo 2001 news site.

The release filename was listed as "frikbtx.zip", consistent with prior release but it was actually released as fbx.zip.

	Title:		FrikBot X
	Filename:	frikbtx.zip
	Version:	0.10.0
	Date:		7-27-2001
	Author:		Ryan "Frika C" Smith

-- readme.html

The readme states that this truly is the final version of the bot and not to expect anything further.

	This is the final version of FrikBot. I mean it this time. Really. Stop looking at me like that. This is it.

-- readme.html

An extras file was also released with the bot as fbxextra.zip.

This release provided waypoint information for the bot on the standard deathmatch maps.


	 12660 27 Jul  2001 readme.txt
	 46456 27 Jul  2001 readme.html
	   108 27 Jul  2001 bot.cfg
	   193 27 Jul  2001 maps.cfg
	    57 27 Jul  2001 dpplay.bat
	   103 27 Jul  2001 mapqc.txt
	   829 27 Jul  2001 upgrade.txt
	  3270 26 Jul  2001 map_dm6.qc
	  7646 25 Jul  2001 map_dm3.qc
	  2275 19 Jul  2001 map_dm5.qc
	  2259 19 May  2001 map_dm1.qc
	  2343 19 May  2001 map_dm4.qc
	  4183 14 May  2001 map_dm2.qc
	  9140  6 Jul  1997 KC18DOC.TXT





## FrikbotX (FBXa) v0.10.1

The next version of the bot was 0.10.1 or FBXa, released as fbxa.zip.

It was released as a tweaked version of the bot released as the Quake Expo 2001 and included the extra map waypoints that were previously released as separate download.

	This is an updated version of FBX (over what was released at qexpo). The built in waypoints have been tweaked some, and a slew of bug fixes appear throughout the code. Unlike the version released at the expo, this version is NOT distributed under the terms of the GNU GPL. FBX is now public domain.

-- [http://www.botepidemic.com/frikbot/](https://web.archive.org/web/20011214084133/http://www.botepidemic.com/frikbot/) (archived December 14 2001)

The files in the release includes source code, may waypoints, readme files, bat files and compiled game code.

 333680  6 Aug  2001 qwprogs.dat
 615748  6 Aug  2001 progs.dat
   3429  6 Aug  2001 map_dm6.qc
  47383  5 Aug  2001 readme.html
  11950  5 Aug  2001 bot_move.qc
   4794  5 Aug  2001 map_dm2.qc
   2439  5 Aug  2001 map_dm1.qc
   2564  5 Aug  2001 map_dm5.qc
  14822  5 Aug  2001 bot_misc.qc
  20491  1 Aug  2001 bot_way.qc
  23707  1 Aug  2001 bot_qw.qc
  23842  1 Aug  2001 bot_ai.qc
  17649  1 Aug  2001 bot_phys.qc
   9639  1 Aug  2001 bot_fight.qc
  35208  1 Aug  2001 bot_ed.qc
  29610  1 Aug  2001 bot.qc
     87 27 Jul  2001 bot.cfg
    193 27 Jul  2001 maps.cfg
    829 27 Jul  2001 upgrade.txt
     51 26 Jul  2001 glrun.bat
     47 26 Jul  2001 run.bat
   7646 25 Jul  2001 map_dm3.qc
   2343 19 May  2001 map_dm4.qc
     96 14 Nov  2000 progs
   9140  6 Jul  1997 KC18DOC.TXT

The readme HTML file lists the same release date as the previous release, which I believe was mistakenly not updated.

The oldest filenames in the release are dated August 06 2001, which is taken as the release date.

	FrikBot X
	Filename:	fbxa.zip
	Version:	0.10.1
	Date:		7-27-2001
	Author:		Ryan "Frika C" Smith

-- readme.html

Like the FBX release, this release does not include a changelog.






## FrikbotX (FBXb) v0.10.2

The next version of the Frikbot we will list as v0.10.2, to be sequential from the previous version. It is also known as FBXb and was released as fbxb.zip.

The release was listed in a new update on the Frikbot homepage on inside3d.com, dated November 22 2004.

	November 22, 2004, 3:19 am    FBXb Release

	A new version of the FrikBot has been released. This is a bugfix update that removes serious problems discovered throughout the bot's last 3 years in the public eye. I can't believe I'm updating it after all this time. The new version can be downloaded from the FBX homepage.

-- [http://www.inside3d.com/frikbot/](https://web.archive.org/web/20041204010350/http://www.inside3d.com/frikbot/) (archived December 04 2004)

The release contained the source code in a src/ subdirectory as well as the same assortment of files. The map waypoint files were not included in this release.

     96 22 Nov  2004 progs
    192 22 Nov  2004 src
 271544 22 Nov  2004 qwprogs.dat
 513184 21 Nov  2004 progs.dat
  48640 21 Feb  2002 readme.html
     87 27 Jul  2001 bot.cfg
    193 27 Jul  2001 maps.cfg
     51 26 Jul  2001 glrun.bat
     47 26 Jul  2001 run.bat
   9140  6 Jul  1997 KC18DOC.TXT

The readme HTML file does not appear to be updated from the previous release, listing the same filename, version, and release date from three years before.

	Title:		FrikBot X
	Filename:	fbxa.zip
	Version:	0.10.1
	Date:		7-27-2001
	Author:		Ryan "Frika C" Smith

-- readme.html






## FrikbotX (FBXc) v0.10.3

The next version of the bot we will call 0.10.3 ot be consistent with the prior versions.

It is also called FBXc and was released as fbxc.zip.

No public announcement of the release can be located, although it may have been released in association with Quake Expo 2006 in some way.

The release contains the same assortment of files as the previous release, with the addition of a complete readme file (readme.txt) in addition to the readme HTML file (readme.html).

 334052 19 May  2006 qwprogs.dat
  48632 19 May  2006 readme.html
  12937 19 May  2006 readme.txt
 622116 19 May  2006 progs.dat
    192 19 May  2006 src
     96 19 May  2006 progs
     87 27 Jul  2001 bot.cfg
    193 27 Jul  2001 maps.cfg
     51 26 Jul  2001 glrun.bat
     47 26 Jul  2001 run.bat
   9140  6 Jul  1997 KC18DOC.TXT

The readme HTML lists the release date from FBX, the release filename from FBXA and version 0.10.2.

I suspect the version number was updated from the the version number of the FBXb release which had mistakenly ha not been updated. This leads to this version being mistakenly listed as 0.10.2, when it is in fact 0.10.3.

	Title:	FrikBot X
	Filename:	fbxa.zip
	Version:	0.10.2
	Date:	7-27-2001
	Author:	Ryan "Frika C" Smith

-- readme.html

The readme flie lists the correct release filename, the mistaken the version as 10.2 instead of 0.10.3, and a release date of May 19 2006. This release matches the oldest date in the zip and is taken as the release date.

	Title    : FrikBot X
	Filename : fbxc.zip
	Version  : 10.2
	Date     : 5-19-2006
	Author   : Ryan "Frika C" Smith

-- readme.txt

The readme contains a changelog and lists the release as updating a modest feature.

	Changes since v0.10.2
	---------------------
	* Updated bot_ed.qc to use FRIK_FILE extension.

-- readme.txt



## Release Timeline

* Frikbot v0.01, frikbt01.zip, ???
* Frikbot v0.02, frikbt02.zip, ???
* Frikbot v0.03, frikbt03.zip, ???
* Frikbot v0.04, frikbt04.zip, May 23 1999
* Frikbot v0.05, frikbt05.zip, June 09 1999
* Frikbot v0.06, frikbt06.zip, June 26 1999
* Frikbot v0.07, frikbt07.zip, July 28 1999
* Frikbot v0.08, frikbt08.zip, September 19 1999
* Frikbot v0.09 test, frik9tst.zip, November 12 1999
* Frikbot v0.09, frikbt09.zip, February 22 2000
* Frikbot v0.09b, frkbt09b.zip, May 17 2000
* FBX demo, fbxdem.zip fbxrj2.zip, May 25 2001.
* FBX v0.10.0, fbx.zip fbxextra.zip, July 27 2001
* FBX v0.10.1, fbxa.zip, August 06 2001
* FBX v0.10.2, fbxb.zip, November 22 2004
* FBX v0.10.3, fbxc.zip, May 19 2006



## References

* <https://dukeworld.com/telefragged/inside3d/frikbot/>
* [FBX Dissection](https://web.archive.org/web/20070217161728/http://forums.inside3d.com/viewtopic.php?t=153&sid=59fd11952820d4f532231a867191cca7) (archived February 17 2007)
* [Quake Expo 2006](https://web.archive.org/web/20070503052009/http://www.quakeexpo.com/index.php?showall=1), Archived News (archived May 03 2007)
* [http://www.inside3d.com/?show=November-1999](https://web.archive.org/web/20001211145700/http://www.inside3d.com/?show=November-1999) (archived December 11 2000)
* [http://www.mdqnet.net/ftp/frikbot/](https://web.archive.org/web/20001009022144/http://www.mdqnet.net/ftp/frikbot/) (archived October 09 2000)
* [http://www.mdqnet.net/](https://web.archive.org/web/20000226193121/http://www.mdqnet.net/) (archived Feruary 26 2000)
* [http://www.frikac.com/?page_id=28](https://web.archive.org/web/20170410174820/http://www.frikac.com/?page_id=28) (archived April 10 2017)
* [Ryan Smith](https://www.linkedin.com/in/ryan-smith-65b36944/), LinkedIn.


