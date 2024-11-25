# BotSkin

The BotSkin bot was developed by Warren Cheung aka "WACko" based on the BGBot.

Warren was a friend of Tony Tang aka "The TangMaster", the developer of the Victim Bot.

There were 14 releases of this bot over about two and a half months in late 1996, although only 4 of the 14 releases survive.

Its a interesting bot both because it extends the popular BGBot, but also because the intense development that it underwent during such a short amount of time.




## BotSkin 1.0

The first version of BotSkin was released as botskn10.zip.

A copy of the release can be found on "Shareware Extravaganza 8 (Disk 8)" collection on CD 2.

The release contains compiled game code (PROGS.DAT) a summary readme (README.TXT) a description of the mod (BOTSKN10.TXT), a player model file (PROGS/) and QuakeC source code (SRC.ZIP). A BBS file (FILE_ID.DIZ) was added later describing the contents of the zip file.

```
 123608 28 Oct  1996 SRC.ZIP
     96 28 Oct  1996 PROGS
    160 28 Oct  1996 FILE_ID.DIZ
    415 19 Sep  1996 README.TXT
   3344 19 Sep  1996 BOTSKN10.TXT
 439812 19 Sep  1996 PROGS.DAT
```

The readme file lists the contents of the mod, including the BGBOT16.TXT file, which was not present in the release.

	This package should include:

	Please unzip with -d and in its own subdir of your
	Quake directory

	README.TXT      You're looking at it!
	BOTSKN10.TXT    Info file===Read this FIRST!
	PROGS.DAT       Compiled QuakeC code
	PROGS\PLAYER.MDL        Player model with the skins
	SRC.ZIP         Source Code zipped up
	BGBOT16.TXT     Info file on BGbot 1.6
	                        The bot code is based on this

-- README.TXT

The release was probably distributed publicly on ftp.cdrom.com, allowing it to eventually be downloaded and re-distributed on BBSs and then added to the Shareware Extravaganza CDROM.

The fuller readme lists the release filename as botskin10.zip and the version as 1.1.

It is possible that this release is in fact version 1.1 of the mod, repackaged or accidentally packaged as a 1.0 release.

	Title    : BotSkin
	Filename : botskin10.zip
	Version  : 1.1
	Date     : Sept 17 1996
	Author   : WACko
	Email    : wac@intergate.bc.ca
	Credit   : Tony Tang - general support and beta tester

-- BOTSKN10.TXT

The readme lists the release date as September 17 1996.

A much later release that includes a changelog for all releases to that point lists the release date as September 19th. This matches the timestamp of the compiled game code and text files in the release and is the probable release date of the file.

Tony Tang, author of the Victim bot is listed as a beta tester of this mod. Tony's first release of his own bot will not be released until September 24th.

The mod is describes as building upon BGBot and mentions BGBot v1.6. This is quite plausible as this version of the BGBot was released about 2 weeks before.

A list of changes from the BGBot was listed in a changelog released for a later version (2.0) of the mod. These notes match the "Technical Details" section of the BOTSKN10.TXT readme file in the release.

THese notes describes changes such as the ability to pickup and use all weapon, jump high into the air, and for the integration of the "Multiskin" mod, to allow the bots to use different player skins. This likely gives the bot it's name, e.g. "botskin" for bots that have different player skins.


	***ver 1.0! (Sept 19 1996)
	(mostly BGbot additions/bugfixes)
	-now uses all the player death scenes
	-Picks up all the weapons and fires them all now
	(needs work-really bloated code)
	-fixed the jump so he can't jump in midair
	-leaves behind a body when it dies
	-some ai tweaks which probably don't do much
	(increased range to hunt items
	added a shortrange hunt for weapons)
	-mods in: botai.qc
	-skin code based on Multiskin 1.1 :support for multiple skins added
	     -modified: bot.qc, world.qc, items.qc, player.qc

-- botskn20/REVISION.TXT

The readme file lists details of the skins included

	-currently four skins available
	(0)     Hero from Quake	(ID Software)
	(1)     Duke Nukem 	(~ßuke <mbuckton@Direct.Ca>)
	(2)     T-800 		(Dan Bickell <danbickell@loop.com>)
	(3)     Judge Dredd 	(Unknown)
	(4)	Stormtrooper 	(Dan Bickell <danbickell@loop.com>)
	More coming along...

-- BOTSKN10.TXT

The author's personal homepage is listed as http://www.nethosting.com/~wacko/quake/botskin.htm but does not appear to have been captured by archive.org.




## BotSkin 1.1

The next version of the bot was released as botskn11.zip.

No hard evidence of the public release of this bot can be located.

We know of the existence of this release because it is mentioned in the changelog file released with version 2.0.

Many versions of the bot were released and changelog entries were included with release dates that can be corroborated. There is no reason not to believe that all versions of the bot were released publicly, such as on ftp.cdrom.com and the author's homepage.

This version of the bot was released 5 days later and included bug fixes to the AI, including the bots be able to die in lava and their deathmatch scores printed on the console.

	***ver 1.1! (Sept 24 1996)
	-bots die in lava!
	-bots ranked scores printed to console (use ~)
	-bots no longer print frags on death- use impulse 101
	-stays with chosen skin and has appropriate name
	        (the Flash looks like the Flash)
	-jumps more often and more intelligently
	        (almost immediately when stuck)

-- botskn20/REVISION.TXT

It should be noted that this is the same date of release of the Victim Bot by Tony Tang, Warren's beta tester and friend. Both friends were developing and releasing bots on this day.


## BotSkin 1.2

The next version of the bot was released as botskn12.zip.

A copy of this release has not been located.

We know about this release given its mention in the REVISION.TXT file released with version 2.0.

The release was developed and distributed on the same day as the previous 1.1 release in order to fix a major bug.


	***ver 1.2! (Sept 24 1996)
	-fixed MAJOR bug in Skin name printing code

-- botskn20/REVISION.TXT

The author had many homepages over the years, tracked down through links in archive.org.

One was located at modena.intergate.ca/personal/wac/ and had an archive of old news dating back to 1996 and the release of some his bots.

* [The Old News Archives Index](https://web.archive.org/web/20030907074851/http://modena.intergate.ca/personal/wac/news/oldnews.htm) (archived Marc 04 2001)

Sadly, this archive does not include a capture of the webpage dedicated to the bot.

Nevertheless, the v1.2 release of the bot was mentioned in the news section, matching the release date from the changelog of September 24th 1996.

	Sept 24 1996
	...
	QuakeC BOTSkin page UPDATE to v 1.2 BUGFIX in Programming section

-- [http://modena.intergate.ca/personal/wac/news/sept96.htm](https://web.archive.org/web/20010305112420/http://modena.intergate.ca/personal/wac/news/sept96.htm) (archived March 05 2001)




## BotSkin 1.3

The next version of the bot was released as botskn13.zip.

The release was publicly distributed, probably on ftp.cdrom.com, and eventually shared on BBS.

Many BBSs often shared lists of files on Usenet, often daily.

Mentino of this release of the BotSkin appears in one of these lists of files on Usenet, dated from 5th of November 1996 on the "Tesla's Tower BBS".

	BOTSKN13.ZIP 370,564 Quake: - BotSkin Info [././.] New ./././L/./. (by
	GamesNet) This has been a little doodling project
	when I'm not doing homework to learn C. Plus, wanted
	skins without ten megs of ram.

-- [Tesla's Tower BBS](https://groups.google.com/g/spk.file/c/mkQ_LwkLg5k/m/GImWg_zsyu0J), Larry Evans, spk.file, 5 Nov 1996.

The same file with the same description also appears on in a file list shared around the same time by "The Dominion BBS".

	BOTSKN13.ZIP 370,564 Quake: - BotSkin
	Info [././.] New ./././L/./. (by GamesNet)
	This has been a little doodling project when
	I'm not doing homework to learn C. Plus,
	wanted skins without ten megs of ram.

-- [Today, Monday 11-04-96](https://groups.google.com/g/spk.file/c/rsMS7yVlcFg/m/sWl9SFWtg2YJ), The Dominion BBS, spk.file, 4 Nov 1996.

The date of distribution on BBS is expected to be much delayed compared to the actual release on public FTP websites.


The changelog from version 2.0 lists this release as being made public on September 29 1996.

The release included bug fixes based on feedback from users, and the ability for bots to evade during an attack by jumping.

	***ver 1.3! (Sept. 29 1996)
	-fixed bug stopping bots from dying/respawning in lava/slime!
	-bots now evade during attack.  Very annoying evasive jumping.
	-weapons firing now corrected (hopefully)
	        - thanks lando <lando@apollo.ruralnet.net.au>
	-bots now print telefragger's name! (see triggers.qc)

-- botskn20/REVISION.TXT





## BotSkin 1.4

The next version of the bot was released as botskn14.zip.

Like the previous version, it was distributed on BBSs, two of which publicized their file lists on Usenet.

	BOTSKN14.ZIP 370,349 Quake: - BotSkin Info [././.] New ./././L/./. (by
	GamesNet) This has been a little doodling project
	when I'm not doing homework to learn C. Now that I
	have 20 megs of ram, I can't really say whether it
	runs on 8 megs anymore so feedback would be
	appreciated!

-- [Tesla's Tower BBS](https://groups.google.com/g/spk.file/c/bLbgWNVGY-U/m/GOGriNWYtzsJ), Larry Evans, 17 Nov 1996.


Both the Tesla's Tower BBS and The Dominion BBS appeared to have distributed the same file, given the file size information and description.


	BOTSKN14.ZIP 370,349 Quake: - BotSkin
	Info [././.] New ./././L/./. (by GamesNet)
	This has been a little doodling project when
	I'm not doing homework to learn C. Now
	that I have 20 megs of ram, I can't really
	say whether it runs on 8 megs anymore so
	feedback would be appreciated!

-- [Today, Saturday 11-16-96](https://groups.google.com/g/spk.file/c/IMPklo6HC-s/m/PjulXOr7_-cJ), The Dominion BBS, 16 Nov 1996


The changelog from version 2.0 lists the release date as October 6, a week after the last release.

There is more evidence that the bot is improving given feedback from players of the mod.

	***ver 1.4! (Oct. 6 1996)
	-shrunk code by calling player attack routines!
	-MAJOR speed increase - start running cause they're moving!
	        - thanks lando <lando@apollo.ruralnet.net.au>
	-only one bot created at a time to reduce telefrags on start
	-removed bot limit-you can now make as many bots as you like
	-fixed install instructions
	        - thanks SkurV <skurv@cris.com>
	-now makes appropriate screams in slime <g>

-- botskn20/REVISION.TXT


**Historical Links:**

* http://web.ukonline.co.uk/Members/jc.burton/botskn14.zip

## BotSkin 1.5

The next version of the bot was released as botskn15.zip.

Unlike the previous two releases, no evidence for it appears on Usenet.

The changelog for the v2.0 release lists the release date as October 9, 1996, 3 days after the previous release.

The major change for this release was the adoption of the v1.06 of the QuakeC source code, released by id Software on September 30 1996.

	***ver 1.5 (Oct. 9 1996)
	-bots now use the monster colormap
	-bots now make sound when picking up items!
	-NOW for Quake 1.06!
	-NEW! Remove Bot function added!
	-corrected weapon refire rates(sometimes buggy?)
	-fire leading code is lethal!

-- botskn20/REVISION.TXT




## BotSkin 1.6

The next version of the bot was released as botskn16.zip.

The changelog from version 2.0 lists the release date as October 11 1996, only 2 days after the previous release. The releases are coming fast.

The major change in this release is the support for team deathmatch.


	***ver 1.6 (Oct. 11 1996)
	-bots will no longer telefrag on respawn like players
	-Remove Bots now uses teleporter fog to look cooler
	-now supports TEAMPLAY! Sorry, new impulses AGAIN <groan>

-- botskn20/REVISION.TXT


**Historical Links:**

* http://web.ukonline.co.uk/Members/jc.burton/botskn16.zip


## BotSkin 1.7

This version of the bot was released as botskn17.zip.

We have a copy of the subsequent version of the bot, version 1.8, which has a changelog that lists the changes for this release as well.

In it, it lists the additions of new commands for creating and removing bots, as well as showing commands.

The big change seems to be the support for bot skill levels and a fix for showing the team play scores.


	New in Version 1.7
	------------------
	-impulses for creating bots, showing scores, removing bots,
	        changing skins can be used while dead
	-fixed Readme.txt Impulse #s-they go from 100-104
	-bots should now move more smoothly
	-forgot to mention it before-moves while firing (since 1.4?)
	-helperbots in teamplay now have their own names
	-implemented skill levels (affects speed and leading)
	        WARNING:  at skill levels higher than 1 , bots may move
	                faster than players.  I'm not sure, but I'm
	                willing to listen to feedback
	-FIXED teamplay scores:teamplay shows scores for three teams:
	         Two player teams (and their helperbots) and a
	         seperate BOTS team

-- BOTSKN18.TXT

The changelog shared in version 2.0 lists the release date for this version as October 15th.


	***ver 1.7 (Oct. 15 1996)

-- botskn20/REVISION.TXT





## BotSkin 1.8

The next version of theBotSkin  was released as botskn18.zip.

A copy of the bot can be found on the "Toolkit For Quake (QTool_0197)" CDROM.

The 00_INDEX.TXT file in the QUAKEC/BOTS/ directory on  the CDROM lists timestamps that likely match the timestamps that the file was uploaded to ftp.cdrom.com as October 19th 1996.

	botskn18.txt    6672 10-19-96  Description for botskn18.zip
	botskn18.zip  376980 10-19-96  See description above.

-- QUAKEC/BOTS/00_INDEX.TXT, Toolkit For Quake (QTool_0197)

The file was also distributed on the "PDSL GAMERS TOOLKIT" CDROM. A copy of this CD cannot be located at the time of writing, but a file lsiting the contents of the CDROM survives, and lists the filenames and timestamps, matching the "Toolkit For Quake" CDROM.

	botskn18.txt    6672 10-19-96  Description for botskn18.zip
	botskn18.zip  376980 10-19-96  See description above.

-- Root Directory Of PDSL GAMERS TOOLKIT
http://cd.textfiles.com/pdsl/HELP/GAMERTK.TXT

The file was also distributed on BBSs.

We can see evidence of this in the lists of files posted to Usenet, such as on Tesla's Tower BBS.


	BOTSKN18.ZIP 379,925 Quake: - BotSkin (for Quake 1.06) Info [././.] New
	./././L/./. (by GamesNet) Originally a BGBot(1.6)
	hack, this little project started with the
	inclusion of skins to help distinguish between the
	bots. Now includes improved combat ai, fixed attack
	code, all the death animations, bodies that stay and
	MORE! Just added: Teamplay! Make a team of bots and
	go head to head with your HelperBots!

-- [Tesla's Tower BBS](https://groups.google.com/g/spk.file/c/bLbgWNVGY-U/m/lxFRQOrq204J), Larry Evans, 21 Nov 1996.

The same file was distributed on the The Dominion BBS.

	BOTSKN18.ZIP 379,925 Quake: - BotSkin (for Quake 1.06)
	Info [././.] New ./././L/./. (by GamesNet)
	Originally a BGBot(1.6) hack, this little
	project started with the inclusion of
	skins to help distinguish between the bots.
	Now includes improved combat ai, fixed attack
	code, all the death animations, bodies that
	stay and MORE! Just added: Teamplay! Make a
	team of bots and go head to head with your
	HelperBots!

-- [Today, Wednesday 11-20-96](https://groups.google.com/g/spk.file/c/IMPklo6HC-s/m/FN3jqG6VoFEJ), The Dominion BBS, 20 Nov 1996

The release contains the compiled game code (PROGS.DAT), readme summary (README.TXT), detailed readme file (BOTSKN18.TXT) and the player model with multiskin support (PROGS/)

```
     96 10 Dec 10:52 PROGS
   6672 18 Oct  1996 BOTSKN18.TXT
    326 18 Oct  1996 README.TXT
 440284 15 Oct  1996 PROGS.DAT
```

The readme file lists the release date as October 18, one day before the FTP timestamps.

The readme also lists the

	Title    : BotSkin (for Quake 1.06)
	Filename : botskn18.zip
	Version  : 1.8
	Date     : Oct 18 1996
	Author   : WACko

-- BOTSKN18.TXT


The date from the readme matches the date from the changelog distributed with version 2.0.

	***ver 1.8 (Oct. 18 1996)
	...

-- botskn20/REVISION.TXT

This version may have been uploaded to the author's personal homepage on this date and public FTP a day later.

The small changelog suggests that this was a bug fix release.


	New in Version 1.8
	------------------
	-THANK YOU ADAM VARNE... The Impulses were STILL wrong...
	        the CORRECT impulses should go from 100-103
	        Sorry to all those who just couldn't get this patch
	        to work.

-- BOTSKN18.TXT

Unlike the first release of the bot, this release does not include the source code.

This is mentioned as simplifying this for newbies"in the readme file. The source is said to be available on the author's homepage.

	WHAT! NO SOURCE CODE??!!  To simplify things
	for all the newbies out there, I'll be releasing
	just the compiled source.  Don't worry, you
	QuakeC programmers out there, the source is
	NOT being withheld.  It's available on the
	BOTSKIN HOMEPAGE(see bottom) and ME!! through
	e-mail.  Just ask.  All I'd like is a little
	recognition.

-- BOTSKN18.TXT

THe author lists two links for personal homepages. One was not captured, and the other was captured, although no record of the bot or source code survives.

The readme also list credits Tony Tang and suggests keeping an eye out for his VictimBot "coming soon", although by this time the bot had been out for nearly one month.

	Credit   : Tony Tang - Look out for VictimBot- Coming Soon!

-- BOTSKN18.TXT


**Historical Locations:** (addon CDs)

* Quake 'em
	- /QUAKE/PROGRAMS/BOTSKN18/
* Toolkit For Quake 2nd Edition
	- /QUAKEC/BOTS/BOTSKN18.ZIP


## BotSkin 1.9

The next version of the bot was announced as coming soon in a news post on the authors' webpage on October 23.

	Oct 23 1996
	...
	QuakeC BOTSkin page updates now at the TOP OF THE PAGE! New version REAL SOON!

-- [http://modena.intergate.ca/personal/wac/news/nov.htm](https://web.archive.org/web/20010305112645/http://modena.intergate.ca/personal/wac/news/nov.htm) (archived March 05 2001)

The release was made two days later on October 25, according to the changelog distributed with version 2.0.

this release contained bug fixes and the addition of a new cowboy bot skin.

	***ver 1.9 (Oct. 25 1996)
	-Partial Fix - EDICT overload crash.  The bots now wait a
	        random time before coming back in...like players
	        instead of instantaneous respawn...so go for broke.
		I can get around 80 or so without crashing
		(but don't ask about playability)
	-Added fix for counting number of swimming monsters from 1.06a
	-New skin: the COWBOY!
	-Sorry Adam VARN (see below for incorrect spelling)

-- botskn20/REVISION.TXT





## BotSkin 2.0

The next version of the bot was released as botskn20.zip.

A copy of this bot appears on thee "Cream of the Crop 23" CDROM as well as the "Cream of the Crop 24" CDROM. Both of these are collections of software that were shared on BBSs at the time. The release also appears on the Shareware Extravaganza 8 (Disk 8)" collection on CD 2.

The release was distributed on the "PDSL GAMERS TOOLKIT" CDROM and a text file listing the contest of the CDROM lists filesizes and release dates that likely match the release dates the file was uploaded to ftp.cdrom.com. In this case, the file is dated October 27th.


	botskn20.txt    7478 10-27-96  Description for botskn20.zip
	botskn20.zip  391428 10-27-96  See description above.

-- [Root Directory Of PDSL GAMERS TOOLKIT](http://cd.textfiles.com/pdsl/HELP/GAMERTK.TXT)

The release also appears on the "Toolkit For Quake (QTool_0197)" CDROM.

The index text file lists the same file sizes and timestamps as the "PDSL GAMERS TOOLKIT" CDROM.

	botskn20.txt    7478 10-27-96  Description for botskn20.zip
	botskn20.zip  391428 10-27-96  See description above.

-- QUAKEC/BOTS/00_INDEX.TXT, Toolkit For Quake (QTool_0197)

It is surprising that v1.8 and 2.0 appear on the "Toolkit For Quake (QTool_0197)" CD but the v1.9 does not. Perhaps the v1.9 was not released publicly or was not released on ftp.cdrom.com, whereas the other two release were.

The zip file contains the compiled game code (PROGS.DAT), release summary (README.TXT), readme file (BOTSKN20.TXT), changelog (REVISION.TXT) and player model with multiskin support (PROGS/PLAYER.MDL)

```
     96 10 Dec 10:52 PROGS
    373 27 Oct  1996 README.TXT
   7478 27 Oct  1996 BOTSKN20.TXT
   3900 27 Oct  1996 REVISION.TXT
 440788 27 Oct  1996 PROGS.DAT
```

The readme file lists the release date as October 27th. This matches the timestamps of the files in the zip file and the timestamps on various CDROMs on which the release was distributed.

	Title    : BotSkin (for Quake 1.06)
	Filename : botskn20.zip
	Version  : 2.0
	Date     : Oct 27 1996
	Author   : WACko
	Email    : wac@intergate.bc.ca

-- BOTSKN20.TXT

As we have seen, the changelog released with this version is complete all the way back to v1.0 and provides useful insight into the nature of the changes in release, as well as the release date.

The change log for this version suggest that this release involved changes to the AI to allow the bot to use all power ups to to improve its usage of strafing during attacks.


	***ver 2.0 (Oct. 27 1996)
	-unimportant: # of bots running printed when
	        new bots created
	-should now use ALL POWERUPS!
	-attempts to check for lava before jumping...
	-strafing code is in...time for new tactics
	-bots will now strafe (at cl_sidespeed)
	-bots yaw at whatever speed in cl_yawspeed
	-bots now run at whatever speed in cl_forwardspeed

-- botskn20/REVISION.TXT

**Historical Locations:** (addon CDs)

* Toolkit For Quake 2nd Edition
	- /QUAKEC/BOTS/BOTSKN20/

**Historical Links:**

* ftp://ftp.torget.se/pub/games/quake/quakec/botskn20.zip


## BotSkin 2.1

The version of the bot was probably released as botskn21.zip, or perhaps btskn21.zip given the filename used in the next and final release.

No record of this release survives, other than mention in the changelog for the next release, version 2.2.

The release date is listed as November 3 1996 and the release appears to be a bug fix for bot movement and refire rates.

	***ver 2.1 (Nov 3 1996)
	-fixed refire rates...now uses nailguns to FULL
	        advantage...
	-fixed the ultra fast movement...bots accelerate
	        properly at sv_acceleration for those
	        physics nuts. Affects strafing as well
	        as forwards/backwards
	-got around to giving credit for the skins

-- btskn22/REVISION.TXT



## BotSkin 2.2

The next and final version of the bot was released as btskn22.zip.

This is a different naming convention from all prior releases. We would expect the release to have the filename "botskn22.zip".

The release was distributed on ftp.cdrom.com in the bots/ directory where it remained, even with modern mirrors of the archive.


	btskn22.txt            04-Nov-96 21:37     7k
	btskn22.zip            04-Nov-96 21:39   383k

-- [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived December 25 1996)

The file also appears on the "Cream of the Crop 23" CDROM.

The release contains the same assortment of compiled game code, readme files and player model with multiskin support.

```
     96 10 Dec 10:52 PROGS
   7779  4 Nov  1996 BOTSKN22.TXT
   4521  4 Nov  1996 REVISION.TXT
    373  4 Nov  1996 README.TXT
 440796  4 Nov  1996 PROGS.DAT
```

The readme lists the release date as November 4th, one day after the v2.1 release. This is confirmed by the tiemstamps of files in the zip file, on the FTP, and in the changelog readme.

	Title    : BotSkin (for Quake 1.06)
	Filename : botskn22.zip
	Version  : 2.2
	Date     : Nov 4 1996
	Author   : WACko

-- BOTSKN22.TXT

The release appears to fix a major bug when running more than few bots that cases a stackoverflow.


	***ver 2.2 (Nov 4 1996)
	-This one's just a MAJOR bug fix...didn't notice
	        it until i tried my "let's load 20 bots"
	        test...this one fixes a stack overflow
	        which kept people from loading more than
	        two or three bots w/o crashing
	        forgot to comment out a line

-- btskn22/REVISION.TXT

Sadly, the source code was not included in this release and cannot be retrieved from archives of the authors personal homepages.

**Historical Locations:** (addon CDs)

* CD Zone March 1997
	- /Patches/Quake/addons/btskn22.zip
* Time of Reckoning
	- /QUAKE/BOTS/BOT-SKIN.ZIP

**Historical Links:**

* ftp://flinux.tu-graz.ac.at/pub/idsoftware2/quakec/bots/btskn22.zip
* ftp://ftp-new.labyrinth.net.au/pub/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.cdrom.com/pub/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.compulink.co.uk/pub/games/id/quake/quakec/bots/btskn22.zip
* ftp://ftp.datacomm.ch/pub/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.edu.sollentuna.se/pub/games/quake-stuff/quakec/bots/btskn22.zip
* ftp://ftp.epix.net/pub/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.gamers.org/pub/games/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.iis.com.br/pub/mirror/Quake/quakec/bots/btskn22.zip
* ftp://ftp.il.waw.pl/pub/quake/quakec/bots/btskn22.zip
* ftp://ftp.intercity.dk/pub/mirrors/quake/quakec/bots/btskn22.zip
* ftp://ftp.lib.siu.edu/pub/mirrors/idsoftware/quakec/bots/btskn22.zip
* ftp://ftp.livewire.com.au/pub/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.pioneer.wnyric.org/pub/quake/quakec/bots/btskn22.zip
* ftp://ftp.powerup.com.au/pub/games/quake/quakec/bots/btskn22.zip
* ftp://ftp.ram.net.au/pub/quake/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.sci.fi/pub/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.stomped.com/pub/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.sunet.se/pub/pc/games/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.task.gda.pl/pub/games/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.telepac.pt/pub/idgames2/quakec/bots/btskn22.zip
* ftp://ftp.tu-clausthal.de/pub/msdos/games/quake-mirror/quakec/bots/btskn22.zip
* ftp://mirror.aarnet.edu.au/pub/idgames2/quakec/bots/btskn22.zip
* ftp://sunsite.doc.ic.ac.uk/packages/idgames2/quakec/bots/btskn22.zip
* http://ftp.gamers.org/pub/games/idgames2/quakec/bots/btskn22.zip
* http://ftp.sunet.se/idgames2/quakec/bots/btskn22.zip
* http://ftp.sunet.se/pub/pc/games/idgames2/quakec/bots/btskn22.zip
* http://ftp.telepac.pt/pub/idgames2/quakec/bots/btskn22.zip
* http://sunsite.doc.ic.ac.uk/Mirrors/ftp.cdrom.com/pub/quake/quakec/bots/btskn22.zip
* http://sunsite.org.uk/packages/idgames2/quakec/bots/btskn22.zip
* http://www.cdrom.com/pub/idgames2/quakec/bots/btskn22.zip
* http://www.gameaholic.com/deicide/download.cgi?/quakec/bots/btskn22.zip
* http://www.gamers.org/pub/games/idgames2/quakec/bots/btskn22.zip
* http://www.gamers.org/pub/idgames2/quakec/bots/btskn22.zip
* http://www.time2quake.com/filez/quakec/bots/btskn22.zip
* https://www.quaddicted.com/files/idgames2/quakec/bots/btskn22.zip

## Qmon

Reading new archives of later incarnations of the author's homepage, we can see that this bot was the first, but perhaps not the last bit of mod development for Quake.

About one year later in September 1997, Warren started development on an advanced quake monster, which he dubbed "Qmon".

	Sept 21 1997

	A really Alpha Quake Monster Patch...
	Yup, looks like I got around to doodling with my monster patch. Anyhow,
	there's some noticeably differences (heh heh...the fiends...) so I thought
	I may as well release version 0.01 of Qmon - the Monsters Strike Back!
	Look for the accelerated Ogres and the rearmed Fiends. Download the progs.dat
	here.

-- [http://modena.intergate.ca/personal/wac/news/sept97.htm](https://web.archive.org/web/20010305112044/http://modena.intergate.ca/personal/wac/news/sept97.htm) (archived March 05 2001)

I suspect it was a smart monster that used ideas developed as part of his BotSkin project.

An update release for the bot was shared two days later.

	Sept 23 1997

	Alpha 2 of Qmon
	Not much today other than homework, so I decided to post this second alpha of
	my quake mod. Grab Qmon ver 0.02 from here. Still no text file, but a couple
	additions. The grunts have a reloading frame (and an extra deathly
	action...), the Hell Knights have some more frames and so do the Ogre.
	Plus, you can attack Chthon...although he's on the tough side. I think I'll
	tone him down a bit...

-- [http://modena.intergate.ca/personal/wac/news/sept97.htm](https://web.archive.org/web/20010305112044/http://modena.intergate.ca/personal/wac/news/sept97.htm) (archived March 05 2001)

The description suggest that the project involved updating all of the monsters in quake to be more challenging.

	Sept 24 1997

	QMon Alpha 3
	OK... I here's another Alpha (notice I say alpha...that's because it's not
	really fully functional, or even half decent functional) version of my mod.
	This one has a fully working version of Chthon included, with the
	possibility of pain! So go jump to E1M7 and attack him with regular
	weapons!! He has about 3000 health, so about 30+ rockets... Anyhow, you
	can still use the lightning poles, but that's kinda cheap...they do about
	1000 damage. Heh - the skill level makes a big difference. Easy is your
	regular old non-leading fire Chthon. Try out skill 1, skill 2 for a realy
	workout, and if you're really suicidal, it's pretty tough to get up to the
	2nd floor on skill 3... Grab Qmon003 try him out!

A day later, and another update to the mod was released.

-- [http://modena.intergate.ca/personal/wac/news/sept97.htm](https://web.archive.org/web/20010305112044/http://modena.intergate.ca/personal/wac/news/sept97.htm) (archived March 05 2001)

And again, another day later.

The work probably provided a good distraction from homework.

	Sept 25 1997

	Qmon Alpha 4 is out
	HAHA. Bluesnews would be having a fit with my daily patch updates. Anyhow,
	Qmon 0.04 has been released. Today's special effect is the destroyable door!
	Yes, almost all the doors (except the secret ones) can be DESTROYED! So if
	you just can't find that key, or happen to want to wreak some havok on the
	poor level designer's head, feel free to pump a couple rockets and vaporize
	the door. Each one can hold off about 4 rockets. And when I mean vaporize,
	I literally mean vaporize. Haven't managed to get the door to gib or anything
	yet - it just pulls an Obi-wan Kenobi disappearing trick.

-- [http://modena.intergate.ca/personal/wac/news/sept97.htm](https://web.archive.org/web/20010305112044/http://modena.intergate.ca/personal/wac/news/sept97.htm) (archived March 05 2001)

The mod seems to be moving away from smart monsters and more into a grab bag of ideas, in this case destroyable doors.

A fifth and final release of the patch was released 4 days later.

	Sept 29 1997

	Slow day, so you know what's coming
	Okay, so you may not know. But anyhow, here's the new version 0.05 of my Qmon
	patch for downloading. As a bonus, here's a sample text file describing the
	progress so far. I think I'll hack up a page for it if this continues...

	A little explanation for the Chthon changes...Tangmaster and I were
	discussing possible changes, so here he is. His missile is faster (but still
	has a tendency to slam into walls :( but so do your missiles ;) Anyhow,
	finally got the lightning things to make sense - they now HEAL him.
	Completely. I suggest you take them out if you really want to fight Chthon.

-- [http://modena.intergate.ca/personal/wac/news/sept97.htm](https://web.archive.org/web/20010305112044/http://modena.intergate.ca/personal/wac/news/sept97.htm) (archived March 05 2001)


The releases of the Qmon qmon001.zip to qmon005.zip were only made on his personal webpage and do not appear to have been uploaded to ftp.cdrom.com or elsewhere. They were not captured by archive.org and appear to have been lost.




## Release Timeline

* BotSkin v1.0, botskn10.zip, September 19 1996
* BotSkin v1.1, botskn11.zip, September 24 1996
* BotSkin v1.2, botskn12.zip, September 24 1996
* BotSkin v1.3, botskn13.zip, September 29 1996
* BotSkin v1.4, botskn14.zip, October 06 1996
* BotSkin v1.5, botskn15.zip, October 09 1996
* BotSkin v1.6, botskn16.zip, October 11 1996
* BotSkin v1.7, botskn17.zip, October 15 1996
* BotSkin v1.8, botskn18.zip, October 18 1996
* BotSkin v1.9, botskn19.zip, October 25 1996
* BotSkin v2.0, botskn20.zip, October 27 1996
* BotSkin v2.1, botskn21.zip, November 03 1996
* BotSkin v2.2, btskn22.zip , November 04 1996


## References

* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived December 25 1996)
* [Tesla's Tower BBS](https://groups.google.com/g/spk.file/c/mkQ_LwkLg5k/m/GImWg_zsyu0J), Larry Evans, spk.file, 5 Nov 1996.
* [Today, Monday 11-04-96](https://groups.google.com/g/spk.file/c/rsMS7yVlcFg/m/sWl9SFWtg2YJ), The Dominion BBS, spk.file, 4 Nov 1996.
* [Tesla's Tower BBS](https://groups.google.com/g/spk.file/c/bLbgWNVGY-U/m/GOGriNWYtzsJ), Larry Evans, 17 Nov 1996.
* [Today, Saturday 11-16-96](https://groups.google.com/g/spk.file/c/IMPklo6HC-s/m/PjulXOr7_-cJ), The Dominion BBS, 16 Nov 1996.
* [Tesla's Tower BBS](https://groups.google.com/g/spk.file/c/bLbgWNVGY-U/m/lxFRQOrq204J), Larry Evans, 21 Nov 1996.
* [Root Directory Of PDSL GAMERS TOOLKIT](http://cd.textfiles.com/pdsl/HELP/GAMERTK.TXT)
* [http://modena.intergate.ca/personal/wac/news/sept96.htm](https://web.archive.org/web/20010305112420/http://modena.intergate.ca/personal/wac/news/sept96.htm) (archived March 05 2001)
* [The Old News Archives Index](https://web.archive.org/web/20030907074851/http://modena.intergate.ca/personal/wac/news/oldnews.htm) (archived March 04 2001)


