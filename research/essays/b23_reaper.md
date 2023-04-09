# Reaper Bot

The Reaper Bot may be the most popular, widely used, and celebrated quake bots.

It can be argued that good bots were developed before the reaper (e.g. the BGBot and Eliminator bots), and perhaps better bots were developed after the reaper (e.g. Omicron, Frogbot, and Frikbot), but the impact of the bot was so great that it is still preferred by many players even 25 years later.

The reaper bot was developed by Steven Polge, then a programmer at IBM.

	This is my first publicly distributed quakeC patch.
	I design router software and protocols for a living.

-- REAPRB05.TXT

He was later hired by Epic Megagames to bring his advanced AI to Unreal which put a halt to the development of the bot, at least by Steve. The bot lived on by tenacious engineers that reversed engineered the source code and updated it further, resulting in controversy.





## Reaper Bot v0.5

The first public release of the reaper bot was reaprb05.zip.

The release was announced on BluesNews on October 3rd 1996.

The announcement mentions the release being available via cdrom.com and a copy of the release readme file was hosted on bluesnews.com, although does not appear to have been captured by archive.org.

> October 3rd
> ...
>
> New 'Bot
> Got an email from Steven Polge describing his new 'bot called The Reaper Bot. It sounds awesome (read the text file). The author is eager for feedback. I can't wait to get home Friday to try it, and give him some. On CDROM.COM.

-- [http://bluesnews.com/sept5.html](https://web.archive.org/web/19970204065158/http://bluesnews.com/sept5.html) (Archived February 04 1997)

The release was also announced on "Gnowknayme's Quake Page" on October 3rd in a news post that links directly to "reaprb05.zip" hosted on ftp.cdrom.com in the /pub/idgames2/quakec/bots/ directory.

> 10/03/96
>
> Reaper Bot
>
> There's a new 'bot in town called the Reaper Bot. It sounds like the most advanced 'bot so far. It learns levels, has variable difficulty settings, understands doors, teleporters, triggers, and platforms. It won't keep trying to get something that it can't reach, and even runs away for health and ammo when it gnows it's in trouble. I can't wait to try this one out, but I'm in NT now, so Quake is a no-go. I'll get back on this one when I get into DOS. If you want to pick it up, it's on CDROM.COM.

-- [http://www.geocities.com/TimesSquare/Arcade/1975/quake.htm](https://web.archive.org/web/19990203053917/http://www.geocities.com/TimesSquare/Arcade/1975/quake.htm) (archived February 03 1999).

A copy of this release can be found on the "[DP Tool Club CD ASC #03, 08, 31-34](https://archive.org/details/dptoolclub-cdasc)" CDROM in the /vrac/ directory.

The reaprb05.zip release contains the compiled game code (progs.dat) and a readme file (reaprb05.txt). It also contains a file_id.diz, suggesting that this version of the release was distributed via BBS before distribution on the CDROM.

```
     70  1 Sep  1996 FILE_ID.DIZ
 490248  1 Sep  1996 PROGS.DAT
   7540  1 Sep  1996 REAPRB05.TXT
```

The files in the archive are dated September 01 1996. This is different from the release date in the readme file.

Additionally, a version of the release was packaged with another release called "MSKIN" and released in 4 parts and distributed on BBSs. A copy of this release can be located on "Shareware Extravaganza 8 (Disk 8)" collection on CD 2, archived on textfiles.com in the files MSKIN1.ZIP, MSKIN2.ZIP, MSKIN3.ZIP, MSKIN4.ZIP.

This package was described as "Multiskinner pro" that includes a "very intelligent" quake bot.

	Multiskinner pro. create your individual
	quake-match faces or use 20 pre-done. bonus:
	player-bot (VERY INTELLIGENT) [D0S/WIN95]
	[10/10/96] [X/4]

-- FILE_ID.DIZ

Unzipping the files ultimately reveals a bot/ subdirectory that contains the compiled game code (PROGS.DAT) and readme (REAPRB05.TXT) for this version of the reaper bot.

These files too are dated September 01 1996.

```
   7540  1 Sep  1996 REAPRB05.TXT
 490248  1 Sep  1996 PROGS.DAT
```

The release date for the bot described in the readme was September 16th 1996, which is surprising, given that the bot was released and announced on October 3rd 1996.


	Title    : The Reaper Bot
	Filename : reaprb05.zip
	Version  : 0.5
	Date     : 96/09/16
	Author   : Steven Polge

-- REAPRB05.TXT

No source code is included in the release, or is ever included in any release of the reaper bot.

In the readme, Steve comments that he has been working on the bot for about 3 weeks for about two and a half hours per day.

	Build time: 3 weeks of about 2.5 hours/day = about 50 hours so far...

-- REAPRB05.TXT

This puts the 16th of September about 17 days before the first public release date in early October. This, and the fact the version number for the release was v0.5 suggests that there were probably at least 4 private releases of the bot, perhaps shared with a small group of friends or beta testers.

No credits to beta testers or other source code is given in the readme. In fact, he is clear to comment that all code was entirely his own.

	The QuakeC modifications included in this archive are entirely my own design.

-- REAPRB05.TXT

Steve does not hold back in his description of the bot.

He describes it as the most advanced bot available, highlighting its ability to navigate and operate any given level, circle strafe (an intermediate skill in multiplayer), and to choose appropriate weapons while fighting.

> This may be the most advanced bot opponent currently available.  It learns levels as it plays them, picks up and uses all items, roams around.  It understands doors, teleports, triggers, and buttons.  It will jump off ledges, and avoids landing in lava (understanding the gravity level).  When fighting you, it picks the best weapon it has, and strafes, circles or charges.  Variable skill levels are provided (skill 3 is very tough).

-- REAPRB05.TXT

The bot is described as being able to perform "dynamic level learning", as opposed to Eliminator bots need for waypoints to be explicitly placed into maps.

	* Dynamic level learning
		- Bots build internal map of level as they play, and use
		it to roam around, go find weapons, hunt opponents, etc.

-- REAPRB05.TXT

This is more advanced than a simple monster code for fighting the player, such as that used by BGBot and similar.

The bot uses "dynamic waypoints" to navigate the level, a clever approach.

> The roaming AI uses dynamically placed botpaths to move from place to place.  The botpath node placement is optimized to guarantee a valid path followable by the bot, while bounding the number of botpath nodes.  Botpath routes are dynamically merged to minimize the number of botpath nodes.  Multiple spanning trees point in the upstream route direction for routing updates.  These routes can be used to go to both static and moving goals (e.g. players).  Loop detection and avoidance is implemented both for bots following the paths, and for routing updates.  I'm currently implementing route caches to improve performance, and to instantly provide the bot with the route to the "best" (based on distance and type) item of a given class (e.g. health, armor, weapons).

-- REAPRB05.TXT

The bot also is more advanced in the way it fights the player, called "combat AI".

	* Combat AI
		- charges, strafes, circles based on its weapon, enemy's
		weapon, the distance between them, and whether enemy
		is running away.
		- picks best weapon depending on range (only uses rocket
		launcher at close range if it doesn't have anything else
		good, and health+armor is high)
		- will even if needed go after health, ammo, or a weapon
		in the middle of combat!
		- trys to avoid combat if health or ammo low, and it
		thinks it can escape
		- avoids combat with invulnerable enemies

-- REAPRB05.TXT

He describes the use of "fuzzy logic" for decision making within the bot.

>	The combat and local goal setting AI uses heuristics with fuzzy logic for decision making.  I am currently working on supporting learned behaviour based on combat success for the combat AI, as well as the hunting AI.

-- REAPRB05.TXT

The bot was widely regarded immediately with comments on Usenet and on quake websites.

This release was linked in the "Quake C Files" section on canvasnet.com with a local link to "reaprb05.zip" hosted on ftp.canvasnet.com. The bot was described as having "incredible AI" and perhaps "too good" even as a cheater. This notion of bots cheating and this bot in particular cheating, remained an often discussed point.

> Reaper Bot 0.5
>
> This patch has incredible AI which lets the bots actually figure out and understand the levels as they explore them. Unfortunately these bots are just tooooo good! Even at the easiest skill level, a one-on-one fight is very tough to win. The bots don't seem to act very naturally, moving quickly to dodge your fire and cut you down. If you think you're the Quake master, try this bot and you'll be humbled. Either that, or you'll be screaming "These bots CHEAT!!!!"

-- [http://canvasnet.com/quake/qc.htm](https://web.archive.org/web/19990116234332/http://canvasnet.com/quake/qc.htm) (archived January 16 1999)

Not all users had an early time with this release.

A news post was shared on redwood news on October 6th, commenting that the v0.5 of the bot causes crashes.

> ==October 6== 11:35a.m. CDT
>
> Anybody seen these bugs in the reaper bot .5? If I use it in single player, after a few minutes, it crashes out to DOS. In multiplayer, it locks up Quake after a little while. Also, on e1m1 I had this bot that was kind of flashing in and out of existence. He was stuck running around in an area but even though he could hurt me, I couldn't do a thing to him, so I just had to avoid him when I went by. Fortunately he'd run out of ammo and could only hurt me at close range. Also, it seems the bots are very jumpy, like one second they're (while strafing) they're in one spot and then they disappear and appear 5 feet over. Net play is better than that. It makes aiming difficult.

-- [http://redwood.gatsbyhouse.com/quake/1096.html](https://web.archive.org/web/19970327200948/http://redwood.gatsbyhouse.com/quake/1096.html) (archived March 27 1997)






## Reaper Bot v0.6

The next version of the reaper bot was released as reaprb06.zip.

The release was anticipated at QuakeC Headquarters (QHQ).

A pre-release announcement was shared by Mouser on Usenet in the group rec.games.computer.quake.playing sat that the next release of the reaper bot, version 0.6 was due to be released that week.

	Hello Quakematchers,
	---QHQ Exclusive------QHQ Exclusive------QHQ Exclusive---

	QHQ just uploaded new info on the upcoming Reaper Bot v0.6. The bot
	will be released later this week and will be at QHQ A.S.A.P.

	Come and see what the new fixes and bugs are from v0.5:

	http://www.kinglink.com/qhq/news.html

	or directly to the info at:
	http://www.kinglink.com/qhq/reaper.html


	Also visit our main Game site at:
	http://www.kinglink.com

	--Mouser

-- [*New Reaper Bot Beta v0.6 info at QHQ!*](https://groups.google.com/g/rec.games.computer.quake.playing/c/3Zhx62Et-O4/m/mrf3h8CuKJAJ), rec.games.computer.quake.playing, Mouser, 9 Oct 1996.

Sadly the QHQ was not captured by archive.org and all of the news, reaper-specific webpages, and forums discussion the reaper bot have been lost.

This version of the bot does not appear to have been announced on BluesNews, although all other versions were.

The "Excalibur's Rumbles" quake page has a news section that mentions the release of the v0.6 of the bot on October 12 and and links to the release of ftp.bluesnews.com and links to the readme file for the release.

	10-12-96

	Reaper Bot 0.6: An update to one of the most popular bots is out.
	Get the Reaper Bot 0.6 here, or read the txt file.

-- [http://www.geocities.com/TimesSquare/6514/oct3.htm](https://web.archive.org/web/20010505143115/http://www.geocities.com/TimesSquare/6514/oct3.htm) (archived May 05 2001)

The release was announced on Redwood news on October 13th 1996, with a link to a local copy of the reaprb06.zip file.

	==October 13== 9:00p.m. CDT

	The Reaper Bot .6 has been released as well.
	Thanks to Kris Bowen for letting me know.

-- [http://redwood.gatsbyhouse.com/quake/1096.html](https://web.archive.org/web/19970327200948/http://redwood.gatsbyhouse.com/quake/1096.html) (archived March 27 1997)

A copy of this released was downloaded as an attachment on Usenet shared by Robert Heaney on 25 Oct 1996.

	Hey, Steve. Here's the latest Reaper Bot that I found over at Stomped.
	It's a pretty cool enemy bot for DM practice.

-- [bots?](https://groups.google.com/g/rec.games.computer.quake.editing/c/s70A0DBLMxI/m/gvG-48rcmpoJ), rec.games.computer.quake.editing, Robert Heaney, 25 Oct 1996

This release contains a readme file (Reaprb06.txt), compiled game code (Progs.dat) and a changelog that lists changes from the last version (B06chg.txt).

```
   8674 11 Sep  1996 Reaprb06.txt
 500088 11 Sep  1996 Progs.dat
   1828  5 Jun  1996 B06chg.txt
```

The readme lists the release date as October 12th 1996, matching the announcement on "Excalibur's Rumbles" and is taken as the release date. The file timestamps in the release are a close match, listing September 11th, with one file having a release date of June 5th. Perhaps this file was prepared by Steve on a different system.

	Title    : The Reaper Bot
	Filename : reaprb06.zip
	Version  : 0.6
	Date     : 10/12/96
	Author   : Steven Polge

-- Reaprb06.txt

The reaper is good, much better than other bots at the time in terms of combat.

As such, there was much murmuring that the bots cheat.

Steve addresses this directly in the readme file.

> Note:  This bot does not cheat!  At higher skill levels, it rarely misses, and shoots at the maximum rate allowed to players, but it never shoots faster than allowed or causes more damage on hits than normal.  It also does not move faster than players.

-- Reaprb06.txt

In the changelog, steve mentions that he'd had little time to work on the bot in recent time, likely given travel for his day job. He mentions that he anticipates big changes in the next release, version 0.7 that includes teamplay, player skins,
and route caching.

	Reaprbot Beta v0.6

	I was out of town last Thursday to Sunday, so I've
	had limited time to work on the bots.  I wanted to
	release fixes to the most common bugs asap.
	Version 0.7 will probably have teamplay, skins,
	and route cacheing. (BTW, route cacheing will
	be a big improvement to the AI)

-- B06chg.txt

A major change in this release is the fix for the crashing bug reported by many players.

The changelog lists many improvements to the AI such as improved jumping, roaming, door handling, combat AI, and so on.

	* Improved bot combat AI - specifically in going after
	items during combat, or trying to get away from
	more powerful opponents

-- B06chg.txt

The lack of a change log for the previous version and the presence of a changelog with this and all later versions further support that the version 0.5 release was the first public release of the bot.






## Reaper Bot v0.7

The next version of the reaper bot was released as reaprb07.zip.

The release of version 0.7 of the bot was anticipated one week in advance and promoted at QHQ.

A pre-release announcement was shared on Usenet in the rec.games.computer.quake.playing group, much like the pre-release announcement of the v0.6 release.

	Hello Quake fans!,
	QHQ will be releasing the new 0.7 version of the Reaper Bot within
	7-10 days! And yes the changes will be much more substantial than the
	update from 0.6.

	Go to QHQ to find the latest:

	http://www.kinglink.com/qhq/

	Thanks and have a wonderful day!

	-`Mouser

-- [*Reaper Bot Beta v0.7 to be released soon at QHQ!*](https://groups.google.com/g/rec.games.computer.quake.playing/c/bfg0Ttu5mpg/m/AiWAuwHgyGEJ), rec.games.computer.quake.playing, Mouser, 15 Oct 1996.

The message suggests that the poster, "Mouser" (perhaps Kris Bowen), had inside information on what to expect in the next release. This may be information shared by Steve on QHQ, perhaps in forum posts.

This pre-release announcement was also shared on BluesNews five days later.

	October 20th

	Reaper 0.7
	Kris Bowen of QHQ says that the new Reaper 'Bot will be released within the
	next week (on QHQ), and will feature more substantial changes than the 0.6 upgrade.

-- [http://bluesnews.com/oct3.html](https://web.archive.org/web/19970204064949/http://bluesnews.com/oct3.html) (Archived February 04 1997)

The release notes for this release where shared one day before the release on QHQ, although this has been lost. This pre-release of notes was announced on Blues News on October 23.

	October 23rd

	Reaper Release Notes
	There are release notes for the upcoming Reaper 'Bot 0.7 on QHQ.
	Thanks to Monty Gonzalez (FRAGaLOT) for the word.

-- [http://bluesnews.com/oct3.html](https://web.archive.org/web/19970204064949/http://bluesnews.com/oct3.html) (Archived February 04 1997)

The actual v0.7 release was announced on Blues News on October 24th.

The announcement includes links to the zip archive, changelog, and readme file all hosed on ftp.bluesnews.com. The changelog and readme were captured by archive.org.

	October 24th

	Reaper 0.7
	Break out the root beer sCary, it's party time. The new beta of the Reaper,
	version 0.7, is out. Download it right here. Thanks to the author,
	Steven Polge for sending it along. Here's what's new, and here's the readme.

-- [http://bluesnews.com/oct3.html](https://web.archive.org/web/19970204064949/http://bluesnews.com/oct3.html) (Archived February 04 1997)

This release was also announced on Redwood news on October 24th with locally hosted links to the readme, changelog and zip file.

	==October 24== 10:19p.m. CDT

	It's here! New Reaper Bot v.7. Check out the readme and find out what's new.
	Download reaprb07.zip.

-- [http://redwood.gatsbyhouse.com/quake/1096.html](https://web.archive.org/web/19970327200948/http://redwood.gatsbyhouse.com/quake/1096.html) (archived March 27 1997)

This version of the bot was shared on the "Toolkit For Quake (QTool_0197)" CDROM in the /QUAKEC/BOTS/ directory.

The "/QUAKEC/BOTS/00_INDEX.TXT" file on the CD records the timestamps of the file, likely matching the timestamps of the files when uploaded to ftp.cdrom.com.

	reaprb07.txt    9930 10-25-96  Description for reaprb07.zip
	reaprb07.zip  157750 10-25-96  See description above.

A copy of this release is also on the "Shareware Extravaganza 8 (Disk 8)" CDROM collection on CD 2, archived on textfiles.com.

Other BBS-based released of quake mods include this release including BOTZQU released as BOTZQU01.ZIP and BOTZQU02.ZIP that contains the reaper, zeus bot, and other mods, described as "BOTZ 'N STUFF FOR QUAKE". It is also included in QLAB released in a series of files from QLAB01.ZIP to QLAB07.ZIP, described as "QUAKE-LAB".

All versions of the release have the same contents and files have the same unreliable timestamps from June and September 1996.

The release contained a readme (Reaprb07.txt), changelog (B07chg.txt), compiled game code (Progs.dat) and configuration file (Reaper.cfg).

```
 463156  5 Sep  1996 Progs.dat
   3356 17 Jun  1996 B07chg.txt
   9930 15 Jun  1996 Reaprb07.txt
    572 15 Jun  1996 Reaper.cfg
```

The config file provided easy to remember alias commands for managing the bots and bindings for keyboard short cuts for the most common activities, such as adding bots and checking scores.

	alias addbot "impulse 205"
	alias add4bots "impulse 208"
	alias observer "impulse 212"
	alias not_observer "impulse 213"
	alias updatebots "impulse 214"
	alias verbosebots "impulse 215"
	alias quietbots "impulse 216"
	alias restrict "impulse 218"
	alias superrestrict "impulse 219"
	alias scores "impulse 210"
	alias frags "impulse 220"
	alias skinup "impulse 200"
	alias skindown "impulse 201"
	alias skinon "impulse 202"
	alias skinoff "impulse 203"

	bind b addbot
	bind n add4bots
	bind m scores
	bind v verbosebots
	bind [ skinup
	bind ] skindown
	bind p skinon

-- Reaper.cfg

The readme lists the release date as October 20th 1996. This may be the anticipated release date, but does not match the date the file was announce on news sites (24th) or the timestamps for the files on the "Toolkit For Quake" CDROM (25th). This date is probably relevant to the pre-release of the readme and changelog.

The bot was probably publicly released on the 24th.

	Title    : The Reaper Bot
	Filename : reaprb07.zip
	Version  : 0.7
	Date     : 10/20/96
	Author   : Steven Polge

-- Reaprb07.txt

The readme credits Dennis Noordsji for his player multiskin "concepts", perhaps incorporating Dennis's code from his "MultiSkin" patch into the bot, allowing players, and in this case bots, to have different skins (textures).

	Dennis Noordsji for the skins code concepts.

As mentioned in the changelog for the previous version, this release features support for teamplay and configurable skins for the bots.

The readme lists commands for changing bot skins, and instructions on how to add bots to teams.

	TEAMPLAY
		This release supports teamplay.  When teamplay is
		on, IMPULSE 1XX no longer functions as above.
		All bots added with IMPULSE 205 or IMPULSE 208
		belong to the bot only team.  IMPULSE 1XX sets the
		number of bots on each player's team to XX (must be no
		greater than 15).  Bots on your team will have the same
		color as you (and the same skin, if you're using skins).

-- Reaprb07.txt

Although this release supports multiskin for bots, a player model with skins was not distributed with the mod. This is surprising, adding an additional level of difficulty for the user to unlock this feature. Instead, instructions are provided on how to add such a model to the mod.

	SKINS
		I did not include a player.mdl with skins.  Get one from
		a skins mod, and put it in a /progs subdirectory of the
		directory where you put the reaperbot quakec progs.dat.

-- Reaprb07.txt

The changelog for this release is long.

In addition to bug fixes and describing the changes and added commands for multiskin and teamplay, the bot now supports caching routes. That is, the dynamic waypoints created by the bots while exploring the level are preserved and used the next time the level is played.

	* Route cacheing structure and initial
	implementation:  It doesn't do a whole lot yet,
	but it will allow some *very cool* AI
	improvements

-- B07chg.txt





## Reaper Bot v0.75

The next version of the reaper bot was released as reaprb75.zip.

Steve engaged in discussions of the bot and expected futures on forums on QHQ. These forums have been lost, but we have reference from this from posts on Blues News.

On October 26th, it was reported that Steve was gathering feedback and suggestions for future versions of the bot on the message board.

Given that the reaper was taking off, having the discussion happen on QHQ was really a coop for the owners of the site.

	October 26th

	QHQ's Reaper Forum
	QHQ and Reaper 'bot author Steven Polge have put up a message forum for everyone to post their thoughts on the Reaper. You can go and post what you think would be an improvement, and just maybe your idea could be in a future release of the Reaper bot.

-- [http://bluesnews.com/oct4.html](https://web.archive.org/web/19970204065011/http://bluesnews.com/oct4.html) (Archived February 04 1997)

From this discussion was mention the possibility of the mod adding the popular grappling hook, shared again second hand on Blues News 5 days later.

	October 31st

	QHQ's Reaper Forum Pays Dividends
	Kris Bowen of QHQ sends along word that QHQ's Message Forum has a response
	from Reaper Author Steve Polge describing possible future features of the
	Reaper bot as well as work being done on the 'bot currently. He says he hopes
	to support the grappling hook, and capture the flag in future versions!

-- [http://bluesnews.com/oct4.html](https://web.archive.org/web/19970204065011/http://bluesnews.com/oct4.html) (Archived February 04 1997)

The v0.75 version was announced on Blues News on November 2nd 1996. The news post shared a link to this version of the bot hosted on ftp.bluesnews.com which was not captured by archive.org.

> November 2nd
> Reaper Bot 0.75
> The new Reaper bot is out, download it right here. Thanks to author Steven Polge for sending it, and for passing along some comments:
>
> 	"Here's reaper v0.75. Much smoother strafing, and much better skill control. Skill 0 plays much easier now. With the new aiming, its possible to win shotgun battles with the bot (if you circle and strafe a lot) at most skills. I hope you enjoy..."
>
> Sounds like a big step towards having play more like a human. Cool. I'm gonna wait till after my hardware project to check it out though: I'm replacing my IDE drive with SCSI (so if you never hear from me again, I'll just be another sad victim of an upgrade gone bad...).

-- [http://bluesnews.com/nov1.html](https://web.archive.org/web/19970204064729/http://bluesnews.com/nov1.html) (archived February 04 1997)

The release was also announced on Redwood news on November 2nd, with locally hosed links to the zip file (reaprb75.zip) and changelog (B75chg.txt).

	==November 2== 12:00p.m. CST

	New Reaper Bot!!!! .75 of the Reaper Bot is out.
	Download reaprb75.zip now and enjoy. You can also read what's changed.
	Thanks to Chris Roberts of Seismic Spew for emailing me about it.

-- [http://redwood.gatsbyhouse.com/quake/1196.html](https://web.archive.org/web/19970327200928/http://redwood.gatsbyhouse.com/quake/1196.html) (archived March 27 1997)

A copy of this release could not be located at the time of writing.

The quakemecca.simplenet.com website had a page deviated to the reaper bot.

	The Reaper Bot is another great Quake Bot. The magic behind this bot is that
	it learns the level as it plays!

-- [http://quakemecca.simplenet.com/reaper.htm](https://web.archive.org/web/19970530185051/http://quakemecca.simplenet.com/reaper.htm) (archived May 30 1997)

The page must have been updated as different versions of the bot were released because by the time it was captured by archive,rg in 1997, it had a link to the last version of the bot, yet kept a link to the readme file for the v0.75 release. Thankfully, this readme file was captured by archive.org.

The readme file listed the release date as November 2nd, matching the announcement on Blues News and Redwood Quake.


	Title    : The Reaper Bot
	Filename : reaprb75.zip
	Version  : 0.75
	Date     : 11/02/96
	Author   : Steven Polge

-- reaprb75.txt

It is interesting that Steve chose to release this version as 0.75 instead of 0.80. It suggests that it have been a smaller release, perhaps just bug fixes.

Although the readme file for the release has been located, the changelog file (B75chg.txt) has not, so we don't know the full extent of the changes in this release.

	Changes from Beta 0.7 to Beta 0.75 are described in B75CHG.TXT, included in this archive.

-- reaprb75.txt

(UPDATE: A copy of this file has been located. This section will be updated ASAP)



## Reaper Bot v0.8

The next version of the reaper bot was released as reaprb80.zip.

The release of version 0.8 was pre-announced by Kris Bowen on QHQ and shared second hand on BluesNews on November 12th 1996.

The news post links to a dedicated page for the reaper bot on QHQ, although no version of the page has survived.

>	November 12th
>
>	Reaper 0.8 This Weekend
>	Kris Bowen, one of the proprieters of QHQ informs me that there's exclusive info about version 0.8 of everybody's favorite bot, The Reaper. The new version is expected sometime this weekend...

-- [http://bluesnews.com/nov2.html](https://web.archive.org/web/19970204064756/http://bluesnews.com/nov2.html) (archived February 04 1997)

The version 0.8 of the reaper bot was announced on Blues News on November 16th.

The announcement links to a version of the zip (reaprb80.zip) hosted on ftp.bluesnews.com, as well as the readme file (reaprb80.txt) and changelog (b08chg.txt) hosted on the http website. The readme and changelog were captured by archive.org.

>	November 16th
>
>	Reaper 0.8
>	The new version of everyone's favorite playmate Steven Polge's fabulous Reaper bot 0.8.Thanks to Immortal for letting me know. Here the text file, and here's what's new.

-- [http://bluesnews.com/nov3.html](https://web.archive.org/web/19970204064809/http://bluesnews.com/nov3.html) (archived February 04 1997)

This release was announced on Redwood Quake on November 16th with locally hosted links to the zip file, readme and changelog.

>	==November 16== 11:55a.m. CST
>
>	New Reaper Bot is out. Here are the changes. You can download reaprb80.zip from here. Thanks to Kris Bowen for telling me.

-- [http://redwood.gatsbyhouse.com/quake/1196.html](https://web.archive.org/web/19970327200928/http://redwood.gatsbyhouse.com/quake/1196.html) (archived March 27 1997)

A copy of this release was located on cd.textfiles.com in the directory /thegreatunsorted/old_apps/dos_games/. This was clearly a collection of files acquired from various locations and not yet organized.

	The Unsorted Collection

-- <http://cd.textfiles.com/thegreatunsorted/.name>

The release contains the same files as the 0.7 release, with the addition of a spin specification text file (Skinspec.txt) and a text file describing how to setup a dedicated server for the mod (Dedserv.txt). The configuration file was changed to "Autoexec.cfg", the convension for additional commands to be loaded by the mod, instead of "config.cfg", the main configuration file.

```
 479616 15 Nov  1996 Progs.dat
  11385 14 Nov  1996 Reaprb80.txt
   1915 14 Nov  1996 B08chg.txt
   1481 12 Nov  1996 Skinspec.txt
    582 19 Aug  1996 Autoexec.cfg
   1382  1 Jul  1996 Dedserv.txt
```

The timestamps for the files are listed as the November 1996, with the latest date being the 15th. This matches the release date in the readme file and is close to the actual release date on the 16th announced on quake news sites.


	Title    : The Reaper Bot
	Filename : reaprb80.zip
	Version  : Beta 0.8
	Date     : 11/15/96
	Author   : Steven Polge

-- Reaprb80.txt

Steve Gibson aka "sCary" on the "Quakeholio" Quake news website corresponded with Steven Polge about the bot's strafing behavior. Steven Polge responded with technical details about the functions he is calling in QuakeC to allow the bot to strafe.

The comments suggest that the discuss occurred before the v0.8 release was distributed, e.g. he says "In version 0.8, I'll add a special intermediate strafe think ...". Perhaps this email conversation occurred prior to the 15th of November, and was shared 10 days layer by Steve Gibson on the site, probably with permission.

> Reaper 0.8 10/25/96 8:35pm
>
> As all of you guys who play with the reaper bot know, *the* largest problem with the bot is the strafe movements. I asked Steve Polge about this and what his plans were, here is part of what he said:
>
> 	So far, my strafing fixes have focused on unnatural strafing (e.g. the bot changing directions faster than physics allow). The other strafing problem is that strafing uses a different quake move call (walkmove() instead of movetogoal()). This is because I can control the direction the bot is facing when I use walkmove(). However, walkmove is an instantaneous move (no intervening frames). Therefore, since the bot thinks every 0.1 seconds, his strafing gets updated at 10 fps. In version 0.8, I'll add a special intermediate strafe think, to increase the strafing updates to 20 fps, which should be adequate...

-- [http://www.quakehole.com/frames/oldnews.html](https://web.archive.org/web/19971210064427/http://www.quakehole.com/frames/oldnews.html) (archived December 10 1997)


The changelog lists improves to the AI teamplay, as well as many bug fixes.

	* Improved team AI - teammate bots
	will call for help, or warn other bots
	to run away

-- B08chg.txt

The caching of bot routes, key to navigation, also saw a large update.

	* Improved route caching
		- bots are less likely to
	get distracted if seeking something
	they really want.
		- better route update
	propagation.
		- age entries in bot route cache.
		- improved route following
	through teleports.

-- B08chg.txt

Interestingly, Seve added the ability for the bots to dynamically adjust their skill based on how well or poorly the player is performing.

	* If skill == 1 (the console skill setting,
	not the individual bot skill), then bots
	auto-adjust their skill based on
	sucess/failure against players

-- B08chg.txt

The skin specification provides instructions on how to create and add skins for the bots. It references Mike Kelly's REAPERSKN.ZIP release.

	Player.mdls for use with Reaper bots
	(see bottom of note for recommended design of skins)

	1. File: REAPERSKN.ZIP available at ftp.cdrom.com/pub/quake/graphics/mdl
	   Author:  Mike Kelly
	   Description:  The skins are just different colored normal player textures.
		If you want to differentiate the bots, but like the normal quake guy
		skin, this is the player.mdl for you.

-- Skinspec.txt




## Reaper Bot v0.81

The next and final version of the reaper bot was released as reaprb81.zip.

This version of the reaper bot was announced on BluesNews on November 17th, one day after the previous release, suggesting it was a bug fix release.

A copy of the zip file (reaprb81.zip) was linked to on ftp.bluewsnews.com and was not captured by archive.org.

> November 17th
>
> Don't Fear The Reaper
> Nothing to be afraid of, his bugs have been fixed (you knew I'd work that headline in some day, didn't you?). Here's Reaper bot 0.81. Thanks to Steven Polge, the Dr. Frankenstein of the Reaper (Dr. Reaperstein?) for sending it along.

-- [http://bluesnews.com/nov3.html](https://web.archive.org/web/19970204064809/http://bluesnews.com/nov3.html) (archived February 04 1997)

This release was also mentioned on Redwood news on November 17th linking to a local version of the zip file (reaprb81.zip).

> ==November 17== 10:00p.m. CST
>
> Also from blue's (I figure everybody knows the URL by now so I'm being lazy). The bugs in Reaper Bot .8 have been fixed in Reaper Bot .81.

-- [http://redwood.gatsbyhouse.com/quake/1196.html](https://web.archive.org/web/19970327200928/http://redwood.gatsbyhouse.com/quake/1196.html) (archived March 27 1997)

The file was uploaded to ftp.cdrom.com.

A few days later on the 22nd of November, a /reaper/ subdirectory was created in the bots/ directory for the reaper bot release, and a plethora of bot skin releases that were made.

	Major changes made to the directory structure of
	ftp://ftp.cdrom.com/pub/idgames2:
	...
	11/22/96 'quakec/bots/reaper' created.

-- [http://cdrom.com/pub/idgames2/CHANGES](https://web.archive.org/web/19961221100153/http://cdrom.com/pub/idgames2/CHANGES) (archived December 25 1996)

The v0.81 release of the bot was placed in this directory where it remained and can still be found in modern mirrors, such as on quaddicted.com.

	reaprb81.txt	1996-Nov-19 00:00:00	11.1K	text/plain
	reaprb81.zip	1996-Nov-19 00:00:00	163.1K	application/zip

-- <https://www.quaddicted.com/files/idgames2/quakec/bots/reaper/>

The release contains all the same files as the previous release without change, except the compiled game code.

```
 481376 17 Nov  1996 PROGS.DAT
  11385 14 Nov  1996 Reaprb80.txt
   1915 14 Nov  1996 B08chg.txt
   1481 12 Nov  1996 Skinspec.txt
    582 19 Aug  1996 Autoexec.cfg
   1382  1 Jul  1996 Dedserv.txt
```

In fact, even the readme and changelog were not touched for this release.

	Title    : The Reaper Bot
	Filename : reaprb80.zip
	Version  : Beta 0.8
	Date     : 11/15/96
	Author   : Steven Polge

-- Reaprb80.txt

It was a bug fix release, although we don't know the nature of the bug that it fixed.

This final version of the bot became the de facto recommended bot for many years.

Blues News made it the feature bot on their bot guide webpage, where it remains so even today.

>	Spotlight
>
>	The Reaper Bot
>
>	The ReaperBot, by Stephen Polge, is by far the best bot available. The superior AI of the Reaper allows it to learn your particular style of play and adapt to take advantages of your weaknesses. The Reaper is difficult to kill because it is excellent at avoiding your shots, but is then deadly accurate with the placement of its own shots. Poolge ceased development of the Reaper at version 0.81, but it is still the best bot available. Poolge is now working for Epic on their much anticipated release, Unreal.

-- [https://www.bluesnews.com/guide/bots.htm](https://web.archive.org/web/19980129073716/https://www.bluesnews.com/guide/bots.htm) (archived January 29 1998)






## Epic Megagames

Development on the reaper bot halted abruptly because Steven Polge was hired away from IBM to work on a new game.

A message on the 9th of December 1996 shared on Blues News commented that Steve had been hired by Epic Megagames to work on their upcoming game Unreal.

> December 9th
>
> Don't Fear the Reaper: Hire His Creator
> Steven Polge, author of the famed Reaper Bot, has been hired by Epic Megagames to do enemy AI programming for their upcoming Quake competitor, Unreal. This is according to Shadows (thanks to Brad Dietz aka Nighthawk).

-- [http://bluesnews.com/dec1.html](https://web.archive.org/web/19970204064557/http://bluesnews.com/dec1.html) (archived February 04 1997)

This was a secondhand message, originally posed on another gaming website focused on Unreal news called "shadows". The news post was likely based on messages on the "Epic Megagames Forum", that may have since been lost.

Discussion by Cliff Bleszinski in his book "Control Freak" comments that Unreal did not have any AI at the time and that he was responsible for finding and hiring Steve to join Epic to add AI to the game.

> There's no better example than the arrival of brainy computer engineer Steve Polge. At this point in development, we didn't have any artificial intelligence for the baddies who roamed our dangerous planet.

-- Page 97, [Control Freak](https://www.google.com/books/edition/Control_Freak/yZ-SEAAAQBAJ), Cliff Bleszinski, 2022.

This move to Epic was eventually confirmed by Steve himself with a message to Blues News.

In his message, Steve comments that he will not be working on the Reaper Bot any more or releasing any further versions as he might be using some of the ideas in his work at Epic.

> December 11th
>
> End of the Reaper Bot Line
>
> The father of the famed Reaper Bot, Steven Polge (Dr. Reaperstein), sends along word that he will no longer have time to update the Reaper Bot, now that he had signed on with Epic (makes sense).
>
> 	"...I am really looking forward to this opportunity. I was only able to spend a relatively small amount of time on the reaper, because of work and life. I hope to be able to do some really cool stuff, and make single player (and multiplayer) more immersive and more fun. BTW, I am very impressed with the Unreal engine and editor.

> Best of luck, Steven.

-- [http://bluesnews.com/dec1.html](https://web.archive.org/web/19970204064557/http://bluesnews.com/dec1.html) (archived February 04 1997)


A day later he commented later in December 1996 that he has no plans to release the source code for the bot.

> December 12th
>
> No Plans to Release Reaper Source
>
> 	I got a response from Reaper Bot author Steven Polge to my question about whether he was planning to release the source to his "baby," and this was his response:
>
> 	"I have not released the source for the reaper bot, and at this point I will probably not do so..."

-- [http://bluesnews.com/dec1.html](https://web.archive.org/web/19970204064557/http://bluesnews.com/dec1.html) (archived February 04 1997)



## Decompiled Source Code

Although development by Steve stopped, development on the reaper bot did not.

Tenacious programmers started to use the decompile capability of some of the modern QuakeC compilers to reverse engineer compiled game code back into .qc files for some mods.

This method was applied to the reaper bot, initially to fix bugs in the code, specifically the infamous disappearing weapons bug.

Decompiling the reaper source code was being discussed and performed by developers on Usenet.

For example, in reply to a question on how to decompile the reaper bot into source, Ken Alverson replied on 12 June 1997 that indeed he had done it.

> >Hello there..
> >
> >Does anyone of you know how to de-compile Reaper bots, without any
> >errors when compiling??
> >Please answer!! :o)
>
> Yes.
> Ken
>
> On the other hand, I know Steven Polge, and I don't want to give out his code if he does not want it given out. Decompiling the code is not hard. Yes, even decompiling it to a compilable form.

-- [Ken Alverson](https://groups.google.com/g/rec.games.computer.quake.quake-c/c/pb_PTSRMLts/m/ZU7OrEA7BycJ), rec.games.computer.quake.quake-c, 12 June 1997.

Bent Svendsen aka "Decker" also replied that he had done it also.

	>>>Does anyone of you know how to de-compile Reaper bots, without any
	>>>errors when compiling??
	>>You won't give up, eh?! ;-)
	>well, it's simple enough, you've just got to know how to fix the code
	I know, I've already done it. I was just teasing him :-) He've got my
	code by now, so that should shut him up.

	Med venlig dansk hilsen
	Decker
	http://home1.inet.tele.dk/decker

-- [decker](https://groups.google.com/g/rec.games.computer.quake.quake-c/c/pb_PTSRMLts/m/Pad54I7vZPoJ), rec.games.computer.quake.quake-c, 20 June 1997.

Decker went on to release some of the first public extensions of the reaper bot, such as the addition of reaper bots to the quake mission pack "Scourge of Armagon" (hipreap3.zip) in August 1997, then later the addition of reaper bots to the painkeep mod (pkbot.zip) in 1998.

Eventually the broader community started to cotton-on that modified reaper bots were available.

Word reached Steve Polge at Epic perhaps around early September 1997, who was very unhappy about the situation.

Stephen Heaslip aka "Blue" from Blues News reached out to Steven for comment.


> Friday, September 5, 1997
>
> Reaping the Reaper
>
> Though the last version was released quite some time ago, impressively, the Reaper still represents the state of the art in bot AI (reinforcing the impression that Epic made a savvy move hiring Reaper author Steven Polge). Recent days have seen a rush of announced modified versions of the Reaper Bot, as well as the addition of Reaper-esque AI to other bots, and the announcement by someone that he was working on the "next version of the Reaper." It is pretty safe to say that it is not a coincidence that this comes shortly after the source code for the Reaper had been successfully reverse-compiled. Though it is nice to think of the state of the Reaper being advanced, Steven Polge never did want to release the source. I wrote Dr Reaperstein and asked for his reaction to the modified versions of his work, and whether he would now release the Reaper source:
>
> 	It's unfortunate that many people have little respect for the work and stated position of others. The documentation included with the Reaper bot mod clearly states that it is not to be modified, and I have never authorized anyone to release any modifications. I appreciate the many individuals who have requested to release mods but have not done so in regard to my wishes. The reaper bot code is very much incomplete and unfinished, and as I will soon be releasing the source to a much better AI in Unreal, I still do not intend to release the reaper bot source.
>
> I'm sure that it will eventually become an impossible policy to follow, but I'll try and comply with Steven's wishes and not help publicize projects that have used his work against his wishes.

-- <https://www.bluesnews.com/archives/aug97-5.html>


Steve must have received a lot of email about the subject.

In a reply a few days later, he commented that he did not have a problem with people modifying the bot for their own personal use.

This was shared publicly, such as on blues news and became de facto permission for people to modify the bot for themselves.

> Sunday, September 7, 1997
>
> A brief follow up to yesterdays barrage of electronic opinions on the Reaper de-compiling issue: Drywall of Inside3D.wrote Reaper author Steven Polge and determined that there was no problem with his site's Improving the Reaper series because:
>
> 	"I don't have any problem with people modifying the reaper bots for their own personal use"

-- <https://www.bluesnews.com/archives/sept97-1.html>


Shortly after, there were rumors that Quake 2, which was in development, was using the reaper as a basis for the enemies in the game.

It's a strange rumor and was quickly disabused by Christian Antkow aka "Disruptor" from id software via email.

> Tuesday, September 9, 1997
>
> though I don't believe for a second the rumor in their Day Two coverage saying the Quake II monster AI was "ripped" from the Reaper source (thanks BlindSide.BC). I was going to contact Disruptor to ask him to respond to this, and then I received mail from Oblivius, who had already asked him this very question. Here is Disruptor's reply to the question of whether there was any truth to that rumor:
> ...No. Considering that;
>
> 	a) We've never seen the reaper bot source and
> 	b) Quake II doesn't use QuakeC

-- <https://www.bluesnews.com/archives/sept97-1.html>

The mystery deepened, when it was revealed by John Cash at id software, that he had received a copy of the source code for the reaper bot from Steve Polge, but deleted it when Steve started working for Epic.

> Tuesday, September 9, 1997
>
> John Cash
>
> ...
>
> Also, John sent along an email to completely clarify the Reaper bot AI issue:
>
> Actually Disruptor wasn't totally correct, but it was just because of something he didn't know.
>
> I was talking with Steve Polge back when he was still with IBM. He did send me a version of the Reaper bot source at that time. We agreed that it was for research only and that I would not release or use it without his permission. When he changed jobs shortly thereafter I figured it was best for both of us if I didn't even use it as a research base. So, even though I did have the source I never inhaled.. ummm, used it. Nobody else here even had access to it so I can safely state that nobody at id has ever seen the source (I hadn't yet had the time to look at it when he made his job change). I just wanted to make this clear so that Steve doesn't think that there's something fishy going on. He's a good guy doing good work.

-- <https://www.bluesnews.com/archives/sept97-1.html>

All of this discussion on quake news sites resulted in a lot of public attention on the reaper bot and the ability to recompile the source.

As such, it resulted in a flurry of reaper bot extensions, called "reaper bot hacks" were released through the end of 1997.

> Latest News November 8th
>
> Reaper Bot Hacks - Here is a list of urls to the various reaperbot hacks that can be downloaded from the Internet. These are the ones I know about, and so it may not be complete. If you know others, please do not hesitate to e-mail me the complete url. Make sure that the hack is PUBLICALLY available and not a private copy meant for personal use. You will probably not see this list posted at any of the "official" news web sites. Some might call it a "news" blackout on the reaperbot hacks. Since some of the hacks are already available at CDROM.COM and have been for MONTHS (like the Hipnotic-Reaperbot hack), it is quite silly to try to keep it a secret.

	...

-- [http://www.inside3d.com/nov08-nov09.shtml](https://web.archive.org/web/19980614160010/http://www.inside3d.com/nov08-nov09.shtml) (archived June 14 1998)

One year after the release of reaper v0.81, Roscoe Sincero aka "Legion" posted an update on inside3d.com celebrating the release and sharing code on how to fix the two most infamous bugs in the final release of the bot: the "disappearing weapons bug" and the "silent jumping bug".

> Latest News November 17th
>
> Happy Birthday - Today is the 1 year anniversary of the release of v0.81, the final version, of the famed Reaperbot. It was the first bot to feature dynamic waypoint spawning--this means that the bot can "learn" the map as it roams. To celebrate its birthday, here are the corrections to two of the most famous bugs ever seen in any bot:
>
> 	Disappearing weapons bug: Look for the function weapon_touch in the file called items.qc. After the declarations of the variables, add this following line of code:
>
> 		if (other.classname != "player" && other.classname !="dmbot") return;
>
> 	Silent Jumping: Look for the function BotJump in the file called botmove.qc. Near the bottom of this function but BEFORE the line that says "return ( TRUE );" add this line of code:
>
> 		if (jmpv_z > 200) sound (self, CHAN_BODY, "player/plyrjmp8.wav", 1, ATTN_NORM);
>
> 	Note: the check for the z component of the velocity is not really necessary, but to paraphrase what a true QuakeC guru once told me: "It is good programming style to check for certain things even if you think it won't happen."
>
> Of course, this requires you to decompile the reaperbot since Polge stated at least twice that he will not release the source code. He also said that it is okay for you to modify your personal copy of the reaperbot for personal use. This means that he is not authorizing you to release your changes to the public. Naturally, the geniuses among us who appointed themselves the ethical guardians of the Quake community will tell you that this means you can not decompile the reaperbot. I will let you decide. I am not delusional enough to think that I should decide what you can do in the privacy of your own home. We have tutorials on decompiling the reaperbot if you are interested.

-- [http://www.inside3d.com/nov16-nov17.shtml](https://web.archive.org/web/19980614160135/http://www.inside3d.com/nov16-nov17.shtml) (archived June 14 1998)

In fact, insideqc.com had a whole series of tutorials on how to decompile and update the reaper bot, called the "Reaperbot Improvement Protocol" or R.I.P. for short.

At least 10 tutorials were written in the series.





## Release History

* Reaper Bot v0.5, reaprb05.zip, October 03 1996.
* Reaper Bot v0.6, reaprb06.zip, October 12 1996.
* Reaper Bot v0.7, reaprb07.zip, October 24 1996.
* Reaper Bot v0.75, reaprb75.zip, November 02 1996.
* Reaper Bot v0.80, reaprb80.zip, November 16 1996.
* Reaper Bot v0.81, reaprb81.zip, November 17 1996.



## References

* [http://bluesnews.com/sept5.html](https://web.archive.org/web/19970204065158/http://bluesnews.com/sept5.html) (Archived February 04 1997)
* [http://bluesnews.com/oct3.html](https://web.archive.org/web/19970204064949/http://bluesnews.com/oct3.html) (Archived February 04 1997)
* [http://bluesnews.com/oct4.html](https://web.archive.org/web/19970204065011/http://bluesnews.com/oct4.html) (Archived February 04 1997)
* [http://bluesnews.com/nov1.html](https://web.archive.org/web/19970204064729/http://bluesnews.com/nov1.html) (archived February 04 1997)
* [http://bluesnews.com/nov2.html](https://web.archive.org/web/19970204064756/http://bluesnews.com/nov2.html) (archived February 04 1997)
* [http://bluesnews.com/nov3.html](https://web.archive.org/web/19970204064809/http://bluesnews.com/nov3.html) (archived February 04 1997)
* [http://bluesnews.com/dec1.html](https://web.archive.org/web/19970204064557/http://bluesnews.com/dec1.html) (archived February 04 1997)
* [Control Freak](https://www.google.com/books/edition/Control_Freak/yZ-SEAAAQBAJ), Cliff Bleszinski, 2022.
* [*New Reaper Bot Beta v0.6 info at QHQ!*](https://groups.google.com/g/rec.games.computer.quake.playing/c/3Zhx62Et-O4/m/mrf3h8CuKJAJ), rec.games.computer.quake.playing, Mouser, 9 Oct 1996.
* [*Reaper Bot Beta v0.7 to be released soon at QHQ!*](https://groups.google.com/g/rec.games.computer.quake.playing/c/bfg0Ttu5mpg/m/AiWAuwHgyGEJ), rec.games.computer.quake.playing, Mouser, 15 Oct 1996.
* [http://www.geocities.com/TimesSquare/Arcade/1975/quake.htm](https://web.archive.org/web/19990203053917/http://www.geocities.com/TimesSquare/Arcade/1975/quake.htm) (archived February 03 1999).
* [http://www.geocities.com/TimesSquare/6514/oct3.htm](https://web.archive.org/web/20010505143115/http://www.geocities.com/TimesSquare/6514/oct3.htm) (archived May 05 2001)
* [bots?](https://groups.google.com/g/rec.games.computer.quake.editing/c/s70A0DBLMxI/m/gvG-48rcmpoJ), rec.games.computer.quake.editing, Robert Heaney, 25 Oct 1996
* [http://redwood.stomped.com/1096.html](https://web.archive.org/web/20010304105531fw/http://redwood.stomped.com/1096.html) (archived March 04 2001)
* [http://redwood.gatsbyhouse.com/quake/1196.html](https://web.archive.org/web/19970327200928/http://redwood.gatsbyhouse.com/quake/1196.html) (archived March 27 1997)
* [http://www.quakehole.com/frames/oldnews.html](https://web.archive.org/web/19971210064427/http://www.quakehole.com/frames/oldnews.html) (archived December 10 1997)


