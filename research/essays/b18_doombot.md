# Doombot

The Doombot was developed by Roscoe Sincero aka "Legion".

The bot later turned into a package of code to help other bot developers called "Bot Movement". It transformed again into a project template for bot development called the "Bot Skeleton".

The Bot Movement project in particular became an important development that was used in many other bots developed around the same time, and later.




## Doombot

The first public release of the doombot that can be identified was doombot.zip.

It was uploaded to ftp.cdrom.com.

A record of the release was captured by archive.org, noting the presence of the release in the idgames2/newstuff/ directory.

	doombot.txt            31-May-97 12:10     8k
	doombot.zip            30-May-97 15:20   1.3M

-- [http://www.cdrom.com/pub/idgames2/newstuff/](https://web.archive.org/web/19970605145825/http://www.cdrom.com/pub/idgames2/newstuff/) (archived June 05 1997)

From the FTP file size, we can see that it was large for a bot, over one megabyte. Most bots released were 100-200 kilobytes.

The release contains media material required to play the bot, such as player model and sounds.

We know that later releases require files from this larger release. It suggest that later releases may be simplified, including just a readme file, compiled game code, and any additional mead files. The smaller file sizes in later release support these ideas, as do notes in the last release.

	NOTE: the clients NEED to download DOOMBOT.ZIP and DMBT21B1.ZIP.

-- dmbt21b3.txt

The FTP timestamp suggests that the date was May 30 1997, followed one day later by a readme file.

The large size of the release may have resulted it being rejected from being placed in the quakec/bots/ directory and perhaps removed from the server. This is disappointing as this release is required to use the subsequent releases that only contain the compiled game code.

It may or may not have been the first public version of the bot. Records of releases are sparse, filenames differ across releases, and some release were not public, making it more challenging than average to piece together a history for this bot.

A copy of this release has not been located.




## Doombot v0.20b2

The second public version of the bot that can be identified was dmbt20b2.zip.

It was uploaded to ftp.cdrom.com and its presence was captured by archive.org in the quakec/bots directory.

	dmbt20b2.txt           06-Jun-97 16:43    19k
	dmbt20b2.zip           06-Jun-97 16:40   179k

-- [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19970609212728/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived June 09 1997)

It was also captured in the /idgames2/newstuff/ directory.

	dmbt20b2.txt           06-Jun-97 16:43    19k
	dmbt20b2.zip           06-Jun-97 16:40   178k

-- [http://ftp.sunet.se/pub/pc/games/idgames2/newstuff/](https://web.archive.org/web/19970615152340/http://ftp.sunet.se:80/pub/pc/games/idgames2/newstuff/) (archived June 15 1997)

The FTP timestamp suggests that the date was June 06, 5 days after the previous release. If the cadence of later releases is representative, e.g. about 5 days between releases, this may in fact be the second release of the bot.

A copy of this release has not been located.




## Doombot v0.20b3

The next public version of the bot was released as dmbt20b3.zip.

The release was uploaded to ftp.cdrom.com. It was captured by archive.org in the /idgames2/incoming/ directory before being placed into the /quakec/bots/ directory.


	dmbt20b3.txt           10-Jun-97 17:13    13k
	dmbt20b3.zip           10-Jun-97 17:13   185k

-- [http://ftp.sunet.se/pub/pc/games/idgames2/incoming/](https://web.archive.org/web/19970615152257/http://ftp.sunet.se/pub/pc/games/idgames2/incoming/) (archived June 15 1997)

The FTP timestamp suggests that the date was June 10 1997, about 4 days after the previous release and has a sequential version in the filename.

The changelog listed in a later release also records it as a public release.


	v0.20b2 --> v0.20b3
	...

-- dmbt21b3.txt

The change log for this releases is quite extensive. It includes support for cooperative play, support for buttons, random movement and much more.


	- better looking text file
	- added coop support
	  - monsters can now "see" the bots
	  - bots can now "see" the monsters
	- bot recognizes buttons now and can press them if they choose to
	  - previously, it presses buttons by "accident".
	- bot moves around more randomly now
	- the amount of time bot searches for an item has been reduced
	...

-- dmbt21b3.txt

A copy of this release has not been located.




## Doombot v0.21b1

The next version of the bot was v0.21b1.

We know of its existence given its mention in the changelog for a later release.

This changelog, mentions the version and that it was not made public.

	v0.20b3 --> v0.21b1 (unreleased)
	...

-- dmbt21b3.txt

Given the release naming convention, if it was archived, it would have a filename like "dmbt21b1.zip". In fact, even though the version is marked as "unreleased", a filename is listed in the changelog that matches this expectation.


	With dmbt21b1.zip

	a) copy progs.dat into doombot directory
	  - this will overwrite the older progs.dat in doombot.zip
	...

-- dmbt21b3.txt

Again, the changelog for this release is extensive.

The focus appears to be the addition of two other mods to the bot mod, the grappling hook and the cujo bot.

	...
	- added P. Manole's grappling hook v2.2 patch
	...
	- added J. Wright's Cujo bot v1.4 patch
	...

-- dmbt21b3.txt

The changelog also explicitly mentions that it is an upgrade, just compiled game code, and that the doombot.zip is required to play the mod.

	- if you use this patch on a server, the clients would need to
	 download DOOMBOT.ZIP and DMBT21B1.ZIP from ftp.cdrom.com or get
	 these files from you.

-- dmbt21b3.txt

A copy of this release has not been located.






## Doombot v0.21b2

The next version of the bot was v0.21b2.

As with the previous version of the bot, we know of its existence of this version given its mention in the changelog for a later release.

Also like the previous version it was probably not released publicly.

	v0.21b1 --> v0.21b2 (unreleased)
	...

-- dmbt21b3.txt

The changelog suggests it was probably a bug fix release and involved removing the cujo bot from the mod that was only just added in the v0.21b1 release.

	- REMOVED Cujobot ...

-- dmbt21b3.txt

A copy of this release has not been located.




## Doombot v0.21b3

The next version of the bot was v0.21b3, released as dmbt21b3.zip.

This was the last public release of the doombot.

This version was uploaded to ftp.cdrom.com into the /quakec/bots/ directory, where it remains in modern mirrors of the directory.


	dmbt21b3.txt           14-Jun-97 15:08    31k
	dmbt21b3.zip           14-Jun-97 15:07   377k

-- [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19980210215654/http://www.cdrom.com:80/pub/idgames2/quakec/bots/) (archived February 10 1998)

The archive contains the compiled game code (PROGS.DAT), a readme file (DMBT21B3.TXT), configuration files, as well as sound and model files, presunably a subset of what was included in the original doombot.zip.

  31509 14 Jun  1997 DMBT21B3.TXT
 662268 14 Jun  1997 PROGS.DAT
     96 12 Jun  1997 TEXT
    550 11 Jun  1997 AUTOEXEC.CFG
    128 11 Jun  1997 SOUND
    256 11 Jun  1997 PROGS
   1932 11 Jun  1997 CONFIG.CFG
    285  6 Jun  1997 BOT.CFG

The release date in the readme file is listed as June 14 1997. This matches the FTP file timestamps and the file date of the game code and readme in the zip file.

Interestingly, this date is also Roscoe's birthday, as noted in the readme.

	Title    : Doombot
	Filename : dmbt21b3.zip
	Version  : 0.21b3
	Date     : June 14, 1997, my birthday
	Author   : Roscoe A. Sincero

-- dmbt21b3.txt

The readme for this release contains information on prior public and private versions of the bot, as we have noted so far.

This version of the bot has stripped away all of the unneeded files, giving the release the slimmer size of just under 400 kilobytes.

The release is still not complete, requiring the player model from the doombot.zip release, that was not kept in the bots/ directory probably because of its large size.

	What's New v0.21b2 --> v0.21b3

	...
	I've changed the archive so that all the files you REALLY need is here.  Only the player.mdl is missing.  You'll need to download doombot.zip for that file.  Text files for the individual patches are also contained in doombot.zip so I suggest you get it.

-- dmbt21b3.txt

The requirement for the doombot.zip is mentioned right at the top of the readme file.

	You'll need to download doombot.zip.  This contains the *.wav and *.mdl files not contained in this archive.  It also contains various text files, too.

	The file can be downloaded from

		ftp.cdrom.com/pub/quake/quakec/bots/doombot.zip

-- dmbt21b3.txt

The inclusion of the link suggests that the zip was at least present in the quakec/bots/ directory on June 14 1997.

It was not present in the next closest capture by archive.org eight months later on February 10 1998.

* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19980210215654/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived February 10 1998)


Interestingly, this release also sees the re-addition of the cujo bot to the mod.

	ADDED CujoBot back in.  Here is the reason:
		- I was able to fix that crash problem whenever I spawned too many bots at once.
		- Cujo no longer eats gibs as a result

-- dmbt21b3.txt

Roscoe credits many other bot developers in the readme file, including Cameron Newham author of the Eliminator, Carson Sutton author of the RoamBot, Jonathan Wright author of Cujo, Alan Kivlin author of the QCBot rankings.qc file. He also credits authors of the mods incorporated into the Doombot, like Respawn, Grappling Hook, and Throwing Axe.

He describes his bot as a hybrid of the Roambot, itself based on the BGBot, and the Eliminator bot.

	This is an Eliminatorbot/Roambot hybrid with added movement when attacking as well as additional search functions and attack functions not present in either of the original two bots.  Hope you like it.

-- dmbt21b3.txt

Source code is not included in the release.

A message in the readme suggest that he had no intention of releasing the source code at least until it could be cleaned up. This is a common refrain from may not developers at the time.

He also suggests that the doombot might be part of a large mod in development called "legion of doom", however it does not appear to have been released publicly.

	I will not be releasing the source until I am finish fine-tuning the essential elements of the package.  [...]  I originally planned to release the source along with the legion of doom modification but the progs.dat for this package alone is over 644k.  The progs.dat for the L.O.D. is over 1000k.  So right now, it appears I won't be combining the L.O.D. and this modification together.

-- dmbt21b3.txt




## Bot Movement v0.30

There were no further releases of the doombot.

Instead, Roscoe started a new project called "Bot Movement".

The first public version was v0.30 released as botmove.zip.

He announced it in a series of message on Usenet, starting in June 29 1997, about 2 weeks after the last release of the doom bot.

The project is akin to Alan Kivlin's QCBot release of rankings.qc that adding bot support for client emulation, e.g. adding bots to the scoreboard in deathmatch.

The Bot Movement project released one code file that allows the bot to navigate over different terrain in a quake map better than previous possible.

Specifically, it allowed improvement movement over broken ground and handing of water.

The code file provided a drop-in replacement for the "movetogoal", which he called "norse_movetogoal", probably after another bot in development called "NorseBot".

The release was uploaded to ftp.cdrom.com into the incoming/ directory.

	To everyone, I just released botmove.zip. It features a new movetogoal function to replace the original movetogoal. If you are thinking of making a bot of your own, I encourage you to download botmove.zip. It contains the source code for the function as well as three demos showing BGBot with its enhanced movement. You can download it at ftp.cdrom.com/pub/quake. It is currently in the incoming directory. I am not sure where the file would be placed but I think it will be moved to /pub/quake/quakec/bots.

-- [Roscoe A. Sincero](https://groups.google.com/g/rec.games.computer.quake.playing/c/7kJXfH-x7E4/m/SUYh339rV6UJ), rec.games.computer.quake.playing, 29 June 1997.

The release also include demo files showing the behavior of the BGBot making use of the improvement movement.

	... The package contains the source and three demos showing BGBot with the enhanced movement. The new movetogoal function (called norse_movetogoal) allows the bot to move on broken ground, swim in water, swim up for air, jump out of water easily and jump over gaps. It also allows the bot to move in one direction while simultaenously face another. See the demos for example.

-- [Roscoe A. Sincero](https://groups.google.com/g/rec.games.computer.quake.quake-c/c/CLqxO5G7RWo/m/nNwYnadlynoJ), rec.games.computer.quake.quake-c, 29 June 1997.

Roscoe comments that he is collaborating on a new Quake bot project that will make use of the new movement code. The project is with Terry Hendrix aka "Dark_Skye", author of the Darkbot.

	The norse_movetogoal will be used in the new bot project that Dark_Skye,
	author of Darkbot, and I are working on. The project when completed
	will have two types of bots. One bot will fight almost like Doombot
	while the other will fight almost like Darkbot. The roaming AI will be
	identical for both. It is only the fighting styles that is different.

-- [Roscoe A. Sincero](https://groups.google.com/g/rec.games.computer.quake.quake-c/c/CLqxO5G7RWo/m/nNwYnadlynoJ), rec.games.computer.quake.quake-c, 29 June 1997.

A few days later, the file was still not moved into the quakec/bots/ directory, and it is possible that it never made it.

	The file to download is botmove.zip. As of today, the file can be downloaded even though it is not in the correct directory.

-- [Roscoe A. Sincero](https://groups.google.com/g/rec.games.computer.quake.playing/c/jrL9Cs2jiOY/m/GkhEXpw0fZoJ), rec.games.computer.quake.playing, 1 July 1997

THe next day on July 02 1997, Roscoe comments that he has sared working on a new version of the release.

He also comments that he believes the next version of the Oak bot will make use of the new movement routine.


	heheh. Well, they'll be using my new norse_movetogoal, I think. (Just
	received e-mail, I think they were successful in integrating the
	function). So look for The Oak to be able to swim. I'm now working on
	v0.31 (v0.30 is out). It is actually better than the one I just
	released. The splashing noise is really reduced this time:) For real,
	no joke. Really.

-- [Roscoe A. Sincero](https://groups.google.com/g/rec.games.computer.quake.playing/c/jrL9Cs2jiOY/m/rwVgsD2EqJoJ), rec.games.computer.quake.playing, 2 July 1997

A copy of this release could not be located.


## Bot Movement v0.31

The next version of Bot Movement was v0.31, released as btmv31.zip.

This is a different release filename compared to the previous release with botmove.zip.

This release was uploaded to ftp.cdrom.com and made it into the quakec/bots/ directory, where it remains in modern mirrors.

	btmv31.txt             04-Jul-97 09:41    17k
	btmv31.zip             04-Jul-97 09:40   484k

-- [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19980210215654/http://www.cdrom.com:80/pub/idgames2/quakec/bots/) (archived February 10 1998)

The release contain the source code file (BOTMOVE.QC), readme file (BTMV31.TXT) and many demo files.

  17022  4 Jul  1997 BTMV31.TXT
    192  4 Jul  1997 PROGS
  99570  3 Jul  1997 BOTMOVE.QC
 114542  3 Jul  1997 RPBOT0.DEM
  80594  3 Jul  1997 ROAM0.DEM
 131834  3 Jul  1997 BGBOT3.DEM
 237968  3 Jul  1997 BGBOT2.DEM
 332941  3 Jul  1997 BGBOT1.DEM
 344961  3 Jul  1997 BGBOT0.DEM
 304051  3 Jul  1997 ZEUS3.DEM
 259402  3 Jul  1997 ZEUS2.DEM
 353165  3 Jul  1997 ZEUS1.DEM
 233513  3 Jul  1997 ZEUS0.DEM


The readme lists the release date as July 03 1997. This matches the timestamps of the demo files and code file in the zip file. The readme in the zip and the FTP file timestamps list July 04 1997 as release date, one day later.


	Title    : norse_movetogoal functions (bot demos and code)
	Filenames: btmv31.zip, botmove.zip
	           botmove.zip contains additional demos

	           READ THE EXTRACTION DIRECTIONS!!!!
	           Zeus demos require files in the progs subdirectory.

	Version  : 0.31
	Date     : July 3, 1997
	Author   : Roscoe A. Sincero
	Email    : legion@keg.zymurgy.org

-- btmv31.txt

This release includes demos of the BGBot and ZeusBot making use of the new movement code, with demos of the Repaer and Roam bots as counter examples of less effective movement code.

	This mod provides an alternative function to ID's movetogoal function.  This will allow any bot to swim, move on broken ground, jump over gaps and other "tricks" that the original movetogoal function could not do.  In short, if you are making a bot, this new function will give an appearance that your bot is intelligent.  Unlike most other bots, this new function will allow your bot to move in one direction while facing another.  The roambot demo features this ability.

-- BTMV31.TXT

This was the last release of the Bot Movement project.





## Bot Skeleton v0.22

The next bot project released by Roscoe was called "Bot Skeleton".

The first version was released as btsk22.zip.

This was a project template for developing a quake bot and appears to be a morph and extension of his prior Doombot and Bot Movement projects.

	My new bot project called the Doombot Bot Skeleton Project is now ready for its initial release. Its purpose is to help others make their own bot. The only thing missing is an AI to go along with the other functions.

-- [To fellow Bot Makers](https://groups.google.com/g/rec.games.computer.quake.misc/c/emS920FQHOU/m/IhK8KXb0IYMJ), rec.games.computer.quake.misc, Roscoe A. Sincero, 17 July 1997

The first version may not have been uploaded to ftp.cdrom.com, but was announced on Usenet on July 17 1997.

	This bot patch is, however, a working skeleton. It contains a small portion of BGBot's AI so all you need to do is to compile it (the source is included) and play it. The modified BGBot will not search for items. I'll be uploading it to ftp.cdrom.com. I wanted to do it today but the archive maintainer will be at QuakeCon so all uploaded are disabled until Sunday at the earliest. When I finally upload it, the file should be in /pub/quake/quakec/bots directory.

-- [To fellow Bot Makers](https://groups.google.com/g/rec.games.computer.quake.misc/c/emS920FQHOU/m/IhK8KXb0IYMJ), rec.games.computer.quake.misc, Roscoe A. Sincero, 17 July 1997

It included source code for getting started with a bot, including the movement code, as well as the demos like those that appeared in the Bot Movement project, perhaps some of the same files.

	The file to look for is called btsk22.zip. It contains the source code and 10 demos showing off the new movement plus 4 demos of Zeus bot and 1 demo of the reaperbot. I suggest you take a look at the strafe1.dem and strafe2.dem for some real bot strafing without using walkmove.

-- [To fellow Bot Makers](https://groups.google.com/g/rec.games.computer.quake.misc/c/emS920FQHOU/m/IhK8KXb0IYMJ), rec.games.computer.quake.misc, Roscoe A. Sincero, 17 July 1997

A copy of this release cannot be located.

It is possible that it never made it to cdrom.com, instead only offered for direct email distribution from Roscoe himself.

	If you want to have a copy now, e-mail me and I will send it to you as an attachment. See .sig below for address.

-- [To fellow Bot Makers](https://groups.google.com/g/rec.games.computer.quake.misc/c/emS920FQHOU/m/IhK8KXb0IYMJ), rec.games.computer.quake.misc, Roscoe A. Sincero, 17 July 1997






## Bot Skeleton v0.23

The next version of the Bot Skeleton was v0.23 distributed as btsk23.zip.

This can be confusing, because the release filename is very close to the filename used for the final release of the BotSkin bot, botskn22.zip.

The file was uploaded to ftp.cdrom.com in the bots/ directory, where it remains in modern mirrors of the directory.

	btsk23.txt             23-Jul-97 13:47    17k
	btsk23.zip             23-Jul-97 13:21   824k

-- [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19980210215654/http://www.cdrom.com:80/pub/idgames2/quakec/bots/) (archived February 10 1998)

The release contains source code for the project template (SRC.ZIP), a readme file (BTSK23.TXT), many demos and some model files and sounds required to support the template.

  17094 23 Jul  1997 BTSK23.TXT
   1987 23 Jul  1997 CONFIG.CFG
  75476 23 Jul  1997 ATTACK2.DEM
  80752 23 Jul  1997 ATTACK1.DEM
 191909 23 Jul  1997 ATTACK.DEM
 147664 22 Jul  1997 SRC.ZIP
    192 22 Jul  1997 PROGS
     96 22 Jul  1997 SOUND
    342 22 Jul  1997 QUAKE.RC
 152311 22 Jul  1997 BGE1M8.DEM
 209243 22 Jul  1997 BGE1M5.DEM
 284340 22 Jul  1997 BGE1M2.DEM
 106895 22 Jul  1997 BGE1M1.DEM
 240189 22 Jul  1997 BGSTART.DEM
 274090 21 Jul  1997 TRAJ1.DEM
 114542  3 Jul  1997 RPBOT0.DEM
 304051  3 Jul  1997 ZEUS3.DEM
 259402  3 Jul  1997 ZEUS2.DEM
 353165  3 Jul  1997 ZEUS1.DEM
 233513  3 Jul  1997 ZEUS0.DEM


The readme mentions the release date as July 22 1997, about 5 days after the first public release. Many files in the zip a have a similar timestamp, including the source. The FTP file timestamp is one day later on July 23 1997 and is taken as the release date.


	Title    : Bot Skeleton v0.23
	Filenames: btsk23.zip

	Version  : 0.23
	Date     : July 22, 1997
	Author   : Roscoe A. Sincero

-- btsk23.txt

The readme provides a good description of the project and its goals.

	This package contains the source code for a skeleton code to help you make your own bot.  The only thing missing from the code is its own AI.  However, this is a working skeleton code.  I inserted a portion of BGBot's AI into the code.  (The bot will NOT search for items.)  It is assumed that you will add in your own AI and remove BGBot. Or if you wish, you can add the remaining portions of  BGBot's AI so it can search for items.  Just because it can't search for items like health or armor, don't assume it can't pick these items up by accident or that they can't fight very well.  (See attack.dem)

-- btsk23.txt

The readme includes a changelog, listing the changes in this release compared to the prior 0.22 version, mostly changes to the AI and bug fixes, many with reference to specific demo files to show off the result.

	- added minor trap avoidance code.  Bot will attempt to avoid traps that shoot from ceiling.  (See bge1m5.dem)

-- btsk23.txt

The features of the code template are quite elaborate, listing large bot features items from a) through q).

Features include Alan Kivlin's ranking code, Roscoe's own movement code, and much more.

It seems Roscoe intended to continue work on the Doombot, and a possible Norsebot, reserving them specifically in the readme file.

	You are encouraged to add your AI into the code.  Please name your bot package to something OTHER than Doombot or Norsebot.

-- btsk23.txt

Nevertheless, if work on these bots did continue, it was not made public.



## Inside3D and Reaper Bot Tutorials

At around this time, Roscoe Sincero was occasionally credited with the news on Blues News.

Some second hand comments from Blue suggest that Roscoe was in fact contributing to news on "The Scrap Heap" website run by Terry Hendrix. This site was lost, although eventually transformed into the botshop on planet quake.

In late 1997 or early to mid 1998, Roscoe began contributing news to the "Inside3D" website and became one of its main contributors through 1998.

Around this time, there was active development decompiling and extending the reaper bot.

Roscoe contributed to this effort, with frequent messages on Usenet, as well as start of a series of tutorial on Inside3D called the "Reaperbot Improvement Protocol v0.11 (RIP v0.11)"

	This is apparently the first attempt in improving the reaperbot since December 1996. I have seen several people asking questions publically concerning the issue of making a compilable reaperbot source. Other than people misleading others (I hope it wasn't deliberate), I have not seen one individual actually provide concrete information on HOW to do this.

	...

	It is hoped that this how-to guide, this tutorial will help you in making YOUR copy of the reaperbot a better one. The emphasis here is on the word 'YOUR'.

-- [http://www.inside3d.com/qctut/rip1.html](https://web.archive.org/web/19980614164404/http://www.inside3d.com/qctut/rip1.html) (archived June 14 1998)

Although these tutorials were posted on Inside3D, they may have originated on "The Scrap Heap", or syndicated to both sites simultaneously.

	This tutorial is broken up into several parts. Each week a new part of the lesson will be posted. Visit Inside3D or Scrap Heap for your weekly reaperbot fix.

-- [http://www.inside3d.com/qctut/rip1.html](https://web.archive.org/web/19980614164404/http://www.inside3d.com/qctut/rip1.html) (archived June 14 1998)

The Reaperbot Improvement Protocol became a series of 13 tutorials, and Roscoe authored the first three.

Modern mirrors of these tutorials can be found on [insideqc.com](https://www.insideqc.com/qctut/):

* R.I.P 1 - First Part of the Reaperbot Improvement Protocol.
* R.I.P 2 - Second part of the Reaperbot Improvement Protocol.
* R.I.P 3 - Third part of the Reaperbot Improvement Protocol
* R.I.P 4 - Speaking Bots!
* R.I.P 5 - Last Man Standing
* R.I.P 6 - Add new weapons to the Bots!
* R.I.P 7 - Add Dm4 rules to your bots!
* R.I.P 8 - Fix some of the things that bug you on Teamplay!
* R.I.P 9 - Want flyin' bots, you've got flyin' bots. [rocket flyin']
* R.I.P 10 - Random Skilled bots
* Bot Wind Tunnels fix
* R.I.P 11 - enable the bot model to "yaw" like a real player
* R.I.P 12 - a set of improvements for the reaper bot

This work on writing tutorials on how to modify the reaper bot decompiled source code may have resulted in the start of another bot project, this one called the "Elima-Reaper".

A review of a private beta of this project was written by Timm Stokke aka "Mr?", editor and contributor at Inside3D at the time.

	Reaper: Elima-Reaper - The best modified Reaper version? Elima-Reaper - [Mr?]

-- [http://www.inside3d.com/qc/index.html](https://web.archive.org/web/19980614152709/http://www.inside3d.com/qc/index.html) (archived June 14 1998)

It appeared to be a modified reaper bot that added elements from the reaper bot.

Sadly, it does not appear that a public version of the bot was ever released.

	The Final words - I think i can call this the best modified reaper. With all it's features, and bug fixes, it's a joy to play against. BUT, what i can do not like about this patch is that it is very slow with many bots, because of the new movement code. I guess all we can do is to wait for the dll's which are gonna run like 10 times faster than QC. Oh, and Steve, if you read this, please let Roscoe release this patch!! Thank you.

-- [http://www.inside3d.com/qc/patch9-1.html](https://web.archive.org/web/19980614155325/http://www.inside3d.com/qc/patch9-1.html) (archived June 14 1998)

Roscoe made a large contribution to Quake bot development with his movement code, skeleton projects, and reaper bot tutorials.

Later bots give credit to the movement code specifically or were inspired by it, such as Darkbot, Omicron, Frikbot, and more.

Additionally, a rash of reaper bot extensions appeared shortly after the RIP tutorial series was posted.

	Roscoe Sincero's norsebot "botmove" package is passively used in DarkBOT.

-- darkbot.html, darkbot-fnl-q2.tar.gz

	Roscoe A. Sincero: lots of ideas for the movement code and several other points of inspiration

-- OBOTS.HTM, obots100.zip

	Credits  : Roscoe A. Sincero (legion) for DoomBot movement code (norse_movetogoal)

-- readme.txt, frikbt04.zip.




## Release Timeline

* Doombot, doombot.zip, May 30 1997
* Doombot v0.20b2, dmbt20b2.zip, June 06 1997
* Doombot v0.20b3, dmbt20b3.zip, June 10 1997
* Doombot v0.21b1, dmbt21b1.zip, June ?? 1997 (not public)
* Doombot v0.21b2, dmbt21b2.zip, June ?? 1997 (not public)
* Doombot v0.21b3, dmbt21b3.zip, June 14 1997
* Bot Movement v0.30, botmove.zip, June 29 1997
* Bot Movement v0.31, btmv31.zip, July 04 1997
* Bot Skeleton v0.22, btsk22.zip, July 17 1997
* Bot Skeleton v0.23, btsk23.zip, July 23 1997


## References

* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19970609212728/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived June 09 1997)
* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19980210215654/http://www.cdrom.com:80/pub/idgames2/quakec/bots/) (archived February 10 1998)
* [http://www.cdrom.com/pub/idgames2/newstuff/](https://web.archive.org/web/19970605145825/http://www.cdrom.com/pub/idgames2/newstuff/) (archived June 05 1997)
* [http://ftp.sunet.se/pub/pc/games/idgames2/newstuff/](https://web.archive.org/web/19970615152340/http://ftp.sunet.se:80/pub/pc/games/idgames2/newstuff/) (archived June 15 1997)
* [http://ftp.sunet.se/pub/pc/games/idgames2/incoming/](https://web.archive.org/web/19970615152257/http://ftp.sunet.se/pub/pc/games/idgames2/incoming/) (archived June 15 1997)
* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19980210215654/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived February 10 1998)

* [To fellow Bot Makers](https://groups.google.com/g/rec.games.computer.quake.misc/c/emS920FQHOU/m/IhK8KXb0IYMJ), rec.games.computer.quake.misc, Roscoe A. Sincero, 17 July 1997
* [Roscoe A. Sincero](https://groups.google.com/g/rec.games.computer.quake.playing/c/7kJXfH-x7E4/m/SUYh339rV6UJ), rec.games.computer.quake.playing, 29 June 1997.
[Roscoe A. Sincero](https://groups.google.com/g/rec.games.computer.quake.playing/c/jrL9Cs2jiOY/m/GkhEXpw0fZoJ), rec.games.computer.quake.playing, 1 July 1997
* [Roscoe A. Sincero](https://groups.google.com/g/rec.games.computer.quake.quake-c/c/CLqxO5G7RWo/m/nNwYnadlynoJ), rec.games.computer.quake.quake-c, 29 June 1997.
* [Roscoe A. Sincero](https://groups.google.com/g/rec.games.computer.quake.playing/c/jrL9Cs2jiOY/m/rwVgsD2EqJoJ), rec.games.computer.quake.playing, 2 July 1997

* [http://www.inside3d.com/qctut/rip1.html](https://web.archive.org/web/19980614164404/http://www.inside3d.com/qctut/rip1.html) (archived June 14 1998)
* [http://www.inside3d.com/qc/patch9-1.html](https://web.archive.org/web/19980614155325/http://www.inside3d.com/qc/patch9-1.html) (archived June 14 1998)
* [QuakeC tutorials](https://www.insideqc.com/qctut/)
