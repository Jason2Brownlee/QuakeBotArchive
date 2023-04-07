# ZeusBot

Zeus or ZeusBot is a deathmatch bot developed by Jonathan E. Wright aka "Nelno" and "Nelno the Amoeba", who is also the author of the Cujo bot.

The ZeusBot is one of the first major bots of the first wave of bots. It offers complex behavior and saw wide adoption.




## ZeusBot v1.0

The first version of the ZeusBot was released as zeus10.zip.

An unzipped copy of the release was found on the "Power Tools for Quake" CD in the "MAIN_WPN/BOTS/ZEUS10/" directory. It also appears on the "Toolkit For Quake" (2nd edition) CD in the "QUAKEC/BOTS/" directory. Finally, it appears in the "Shareware Extravaganza 8 (Disk 8)" collection on CD 2.

The archive contains the compiled game code, a readme file and a zip of the source code, as well as bat files for installing and running the mod.

```
   5849  4 Aug  1996 ZEUS10.TXT
    593  4 Aug  1996 INSTALL.BAT
  48296  4 Aug  1996 SOURCE.ZIP
     20  4 Aug  1996 ZEUSBOT.BAT
 451912  4 Aug  1996 PROGS.DAT
```

The readme file lists the release date as September 4th 1996.

The timestamp for files in the zip is listed as the 4th of August, which is suspected to have been systematically adjusted to an incorrect date by some means.

```
Filename : ZEUS10.ZIP
Version  : 1.00
Date     : 96/9/04
Author(s): Jonathan E. Wright
```

-- zeus10.txt

Importantly, The "Toolkit For Quake" CD comes with an 00_INDEX.TXT file in the "QUAKEC/BOTS/" directory that lists the contents of the directory with seemingly original time stamps.

This file suggests the release date as September 28 1996.

```
zeus10.txt      5849 09-28-96  Description for zeus10.zip
zeus10.zip    186963 09-28-96  See description above.
```

-- [Toolkit For Quake (QTool_0197)/QUAKEC/BOTS/00_INDEX.TXT](https://web.archive.org/web/19970605102505/http://www.cdrom.com:80/titles/games/quake_t.htm)

This is confirmed by a similar file listing the contents of the "PDSL GAMERS TOOLKIT" CD and is taken as the public release date of the mod.

```
zeus10.txt      5849 09-28-96  Description for zeus10.zip
zeus10.zip    186963 09-28-96  See description above.
```

-- [Root Directory Of PDSL GAMERS TOOLKIT](http://cd.textfiles.com/pdsl/HELP/GAMERTK.TXT)

The readme credits the TMBot and DMBot as the basis for the extension and is described as a helper bot.

As an extension of the DMBot, it works successful in deathmatch, although primarily to assist the player, not as an opponent.

```
This mod creates a helper bot which will attack the player's
enemies and draw fire.  The bot attacks with a Lightning Gun,
which will not harm the player if he runs into it.

This bot is based in a big way on original code from DM Bot 1.0.
```

-- zeus10.txt

The extension appears to make the bot more useful in singl player mode, interacting more with the world.

```
þ The bot can draw enemy fire, lessening the amount of damage the player
  takes.
þ Seeks out monsters or other players and attacks them.
þ Will continue to attack as long as an enemy target is visible.
þ Will not attack teammates under Teamplay rules.
þ ZeusBot can follow the player through portals.
þ ZeusBot will activate trigger fields (such as light triggers and traps)
þ ZeusBot starts with a full suit of red armor.
```

-- zeus10.txt

It also appears to take on some capabilities of the Cujo bot, which the author had released nearly 3 weeks earlier. Specifically he ability of the bot to act like dynamic lamp to assist the player in dark places.

```
ZeusBot can glow, effectively lighting up everything around you.  You can
turn this on and off, so as not to give away your position in deathmatch.
```

-- zeus10.txt



## ZeusBot v2.0

The second version of the zeus bot was released, mostly likely with the filename zeus20.zip, or perhaps zeus20b.zip.

A copy of this release cannot be located, nor can the readme.

We cannot meaningfully speculate about the release date, other than after the first release. It was most likely released in October or November 1996, maybe even as late as December 1996.

We know of the existence of this release given its appearance in the changelog of later release, such as in the "ZEUSbot 2.02 beta" release (discussed later).

The note in the changelog suggests a complete re-write of the bot from the ground up, rather than as an extension of the DMBot.

```
Changes in version 2.0

While this is the second version of the Zeus bot this was truly the
first version of this code.  Seeing as Zeus 1.0 was based on the
TM bot and was my first attempt at doing anything with Quake C, it
doesn't really count as the same bot -- it just has the same name.
```

-- zeus202b.txt

Sadly, we don't know the extent of the changes in this early version or of the capabilities of the bot after this rewrite.

The release may or may not have been public, perhaps kept private, or perhaps released only on the author's personal homepage which was not captured by archive.org.



## ZeusBot v2.01

The second version of the ZeusBot was released, mostly likely with the filename zeus201.zip or maybe zeus201b.zip.

As with the previous release, no version of this release can be located, nor the readme file.

It probably appeared on the author's personal homepage and on ftp.cdrom.com, but no evidence can be found. Given that evidence can be found of the next release, zeus202b.zip, on ftp.cdrom.com, then this release too was probably uploaded to the server.

We know it existed because of its mention in the changelog part of readme files in later releases, such as v2.02b.

This release offers a number of behavioral improvements to the bot, such as "skill levels" and "target leading".

```
Changes in version 2.01

Skill levels implemented.
Target leading implemented.
Target missing and chance to hit implemented (for line-tracing
weapons such as the shotgun).
bots will no longer see invisible players unless they are attacked
by one.
enhanced ability to chase player out of sight
fixed weapon ranges so bot will fire from greater distances
```

-- zeus202b.txt







## ZeusBot v2.02b

The next release of the ZeusBot was zeus202b.zip.

Evidence of this release was found on ftp.cdrom.com in the file /pub/idgames2/00alltxt.tar.gz that contains a copy of all txt files, and is re-packaged nightly.

A copy of this file was captured by archive.org on 21st of December, 1996.

Additionally, evidence of the readme and zip versions of the release were found in the file /pub/idgames2/ls-laR.gz captured on the same day.

The release appears in the /newstuff directory.

```
./newstuff:
...
-rw-rw-r--  2 jschuur  ftp-id    16970 Dec 19 19:57 zeus202b.txt
-rw-rw-r--  2 jschuur  ftp-id   333493 Dec 19 18:02 zeus202b.zip
```

-- [http://www.cdrom.com/pub/idgames2/ls-laR.gz](https://web.archive.org/web/19961221100334/http://www.cdrom.com/pub/idgames2/ls-laR.gz) (archived December 21 1996)

It also appears in the bots directory.

```
./quakec/bots:
...
-rw-rw-r--  2 jschuur  ftp-id   16970 Dec 19 19:57 zeus202b.txt
-rw-rw-r--  2 jschuur  ftp-id  333493 Dec 19 18:02 zeus202b.zip
```

-- [http://www.cdrom.com/pub/idgames2/ls-laR.gz](https://web.archive.org/web/19961221100334/http://www.cdrom.com/pub/idgames2/ls-laR.gz) (archived December 21 1996)


A copy of the zip for this release cannot be located.

The readme lists the release date as the 20th of December, 1996.

```
=============================
Title    : ZEUSbot 2.03 beta
=============================

Filename : ZEUS203B.ZIP
Version  : 2.03
Date     : 12/20/96
Author   : Jonathan E. Wright aka Nelno the Amoeba
```

-- zeus203b.txt

The file timestamps on ftp.cdrom.com suggest one day earlier on the 19th, and is taken as the release date.

A new versioning convention is used for this release. It can be seen in the readme file, with the addition of "beta" to the release version number and in the release file name with addition of a "b" to the end of the release. This versioning system continues with later releases and may extend to prior releases, including their filenames.

As mentioned previously, the changelog for this and later release adds mention to two prior releases that could not be located, and that highlight a total rewrite of the bo.

The author now lists his personal homepage as the location to get the bot, as well as his other mods. Cujo version 1.3 was available at this time.

```
Home Page: http://trailerpark.com/phase1/nelno
           Check here for the latest updates to all my Quake mods:
           Zeus, Cujo, plasma gun, BFG, blaze gun and more.
           If you didn't get this mod from my site, it's likely
           that you don't have the latest version.
```

-- zeus203b.txt

The author also does not list the TMBot and DMBot in the credit sections, highlighting the entirely new direction he had taken with the project, starting in version 2.

```
Credits  : ID Software for designing Quake with Quake C!
           Otherwise, this bot was built from scratch.
```

-- zeus203b.txt


The version 2 of the mod was a major rewrite and it appears that the code for this version was being withheld.

```
This is a *MAJOR* update to the original ZEUSbot.  The old code, based
on the TMBot, was *completely* done away with.  The ultimate goal is to
provide an intelligent deathmatch opponent\helper bot.  Eventually, the
source WILL BE RELEASED, but until then, you'll have to get your tidbits
from the next release of Cujo.
```

-- zeus203b.txt

Jonathan had doubled down on the bot as a deathmatch opponent, although still supports the bot as a single player helper.

```
The ZEUSbot is both a helper bot and a deathmatch bot.  In single play
he will effectively annihilate just about anything that get's in his way,
and you'll be lucky if you can pick anything up before he does.
```

He also calls out the Reaper Bot by name as another top-level bot at this time and perhaps a peer with the ZeusBot in terms of capabilities at the time.

```
The ZEUSbot's death match capabilities are currently under development, but
it's still probably the most intelligent bot available, excepting Steven
Polge's excellent Reaper bot.
```

-- zeus203b.txt

This release lists many features of the bot including being able to use all weapons, pick up all items, jump into water, and much more.

The bot also uses the correct player animation and has smooth movement, a feature in which the author seemingly takes great pride.

```
Has *totally new* movement code which makes it the smoothest bot ever
made --   just as smooth as a player character, no jumpiness or blitting.
```

-- zeus203b.txt

The changelog for this release is extensive, listing many bug fixes and features.

It does include some of the authors other mods, such as the plasma gun weapon mod, perhaps more, like the blaze gun. These weapon mods were also incorporated into the authors other bot mod, the cujo bot.

```
can fire all of the standard weapons, plus the plasma gun (included in this mod).
```

-- zeus203b.txt

The readme also includes details about the author.

It is likely that this was done in response to many mod developers getting hired by game development companies at this time.

He lists his background with programming, a university computer science degree, and interest in writing music

```
I'm a 25 year old who's been programming computers for the last 15 years.  I
studied computer science at Clemson University and am currently designing
web pages for corporations in the Western North Carolina area.  Besides being
proficient in several programming languages -- 80x86 assembly, C and Pascal
being the most notable -- I also draw and write music in my spare time.
```

-- zeus203b.txt





## ZeusBot v2.03b

The next release of the ZeusBot was released as zeus203b.zip.

Evidence for this release was found on ftp.cdrom.com in the "/pub/idgames2/ls-laR.gz" list of all files captured by archive on December 21 1996.

The file is listed in the incoming/ directory, suggesting it had just been uploaded.

```
./incoming:
...
-rw-rw----  1 jschuur  ftp-id  339562 Dec 20 15:04 zeus203b.zip
```

-- [http://www.cdrom.com/pub/idgames2/ls-laR.gz](https://web.archive.org/web/19961221100334/http://www.cdrom.com/pub/idgames2/ls-laR.gz) (archived December 21 1996)

In an archive of the http://www.cdrom.com/pub/idgames2/quakec/bots/ webpage a few days later on Christmas day, the release can be seen.

```
zeus203b.txt           20-Dec-96 17:41    17k
zeus203b.zip           20-Dec-96 15:04   331k
```

-- [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived December 25 1996)

A copy of the release was donated to the Quake Bot Archive.

The version donated appeared to have been taken from a BBS as it had the telltale FILE_ID.DIZ file, added on the 26th of December and a "TMP.OUT" file added 6 months later. Also, the directory structure for the mod had been removed, where sound files, sprites and model files were all placed in the root directory instead of subdirectories.

    528 24 Jul  1997 TMP.OUT
     73 26 Dec  1996 FILE_ID.DIZ
   6515 20 Dec  1996 CONFIG.CFG
 561724 20 Dec  1996 PROGS.DAT
  18180 20 Dec  1996 ZEUS.TXT
   2676 20 Dec  1996 HUD_TAG.SPR
  39988 20 Dec  1996 HUD_BOX.SPR
   1516 20 Dec  1996 HUD_STAT.SPR
 306708 15 Dec  1996 ZEUS.MDL
   5560  5 Dec  1996 S_PLASMA.SPR
  11828  5 Dec  1996 PLASEXPL.WAV
   5780  5 Dec  1996 PLASMA.WAV

The readme file now has the filename "zeus.txt" instead of the expected "zeus203b.txt"

The source code is also missing from the release, as mentioned in the readme for the previous release.


    =============================
    Title    : ZEUSbot 2.03 beta
    =============================

    Filename : ZEUS203B.ZIP
    Version  : 2.03
    Date     : 12/20/96
    Author   : Jonathan E. Wright aka Nelno the Amoeba

-- zeus.txt

The release date is listed as December 20th 1996, which matches the upload date and timestamp in the bots/ directory.

The release so soon after the previous release, one day or even hours, suggests that it is a bug fix release.

The content of the changelog confirms this suspicion, highlighting the addition of a hUD (head-up display) and code that was causing the bot o get stuck in water.

    Changes in version 2.03

    . added the holographic HUD.

    . removed some of the water movement code.  It was getting Zeus
      stuck in places he used to do fine.  The end result is that he
      will get stuck more often when going for air.

-- zeus.txt






## ZeusBot v2.04

The next release of the ZeusBot was released as zeus204.zip.

This file is available via a download link on bluesnews.com, captured via archive.org.

BluesNews was, and remains, a popular gaming news website. It announced the release and linked to this version on January 8, 1997.

    ZeusBot, January 8, 1997

    ZeusBot author Nelno the Amoeba (obviously a self-esteem problem there)
    sends along word that ZeusBot 2.04 has been released (also available on
    QCHQ and Nelno's homepage). Here's what's new in this version.

-- [http://bluesnews.com/jan1.html](https://web.archive.org/web/19970204064523fw_/http://bluesnews.com/jan1.html) (archived 04 February 1997)

The archive contains a readme file, a changelog and a PACK file.

 944154  8 Jan  1997 PAK0.PAK
   3217  8 Jan  1997 WHATSNEW.TXT
  23829  8 Jan  1997 ZEUS.TXT

This shows a simplified layout to the mod, matching the  layout of the cujo bot mod by the same author, released around the same time (e.g. cujo v1.4.).

The PAK file contains the compiled game code, sprites, player models and sounds.

	progs.dat
	progs/hud_box.spr
	progs/hud_stat.spr
	progs/hud_tag.spr
	progs/player.mdl
	progs/s_plasma.spr
	sound/demon/dland2.wav
	sound/plasma/plasexpl.wav
	sound/plasma/plasma.wav
	sound/player/sucker.wav

-- PAK0.PAK

The release does not include source code.


The readme file lists release date as the 8th of January 1997, matching the date of announcement on bluesnews and the file timestamps in the zip file.

    Filename : ZEUS204.ZIP
    Version  : 2.04
    Date     : 1/8/7
    Author   : Jonathan E. Wright aka Nelno the Amoeba

-- zeus.txt

The header of the readme also lists the authors new homepage hosted on the Quake C HeadQuarters. This website and this directory in particular was not recorded by archive.org.

```
Go to the official Zeus bot page at Quake C HeadQuarters at:
http://www.qchq.com/zeus
```

-- zeus.txt

The author appeared to be receiving a lot of suggestions and help testing during this period. Credit is given to a few people in the readme.

This release supports multiple skins for the bot, allowing the user to choose the skin for the bot. This includes cycling through skins shipped with the release and extending the release with the addition of more skins.

A ZeusBot Camera was also introduced allowing you to see through the eyes of the bot in single or multiplayer.

    The ZeusBot Camera gives you a helper bot's view of the action.
    You can use the camera in either deathmatch or single play.

-- zeus.txt

The Holographic HUD refers to a display of the status of the helper bot in singleplayer.

    The Holographic HUD (Heads Up Display) is automatically enabled
    in single player and co-op games.  As long as you do not have
    a Zeus bot helper, the HUD bars will display your own status.
    Once you spawn a bot, the HUD will track the bot's status.  If
    your bot dies, the status bar will show your status again.

-- zeus.txt

Technical details are also reported, including an estimate of the total lines of code and the number of hours invested into the project.

    ==================
    Technical Details
    ==================

    Code: 7400 lines
    Time: ~80 hours (getting up there)

-- zeus.txt


The changelog for this version is very large at 64 lines.

Major changes were focused on the bot roaming AI.

    . MAJOR changes to the roaming AI.  Bot is now a lot better
      at getting out of rooms and finding new items.

-- zeus.txt




## ZeusBot v2.041

The next version of the bot was released as zeus2041.zip.

This version too must have been announced on bluesnews, but the announcement was changed for the subsequent release. The file was hosted in http://www.bluesnews.com/files/zeus2041.zip and captured vi archive.org.

The zip contains the three same files as the previous release.

 944306  9 Jan  1997 PAK0.PAK
  23910  9 Jan  1997 ZEUS.TXT
   3217  8 Jan  1997 WHATSNEW.TXT

The date in the readme file is listed as the 8th, the same as the previous release, although the timestamp of the files suggest perhaps the 9th, one day later.

    Filename : ZEUS2041.ZIP
    Version  : 2.041
    Date     : 1/8/7
    Author   : Jonathan E. Wright aka Nelno the Amoeba
    Email    : nelno@resurrection.com

-- zeus.txt

The small increment to the version number from 2.04 to 2.041 and short duration from the last release of one day suggests that this was a bug fix release.

The changelog confirms this, highlighting a bug fix to the new "bot view" feature.

    Changes in version 2.041

    . Fixed bot view.  It was the llamas again.



## ZeusBot v2.042

The next release was made as zeus2042.zip

It was announced on blues news on January 9th, commenting that it is a bug fix release.

    January 9, 1997

    ZeusBot 2.042

    There were a couple of small problems with the recent ZeusBot release
    (the DeathCam was disabled, and DM2 didn't work), so author Nelno the
    Amoeba has released ZeusBot 2.042 (also available on QCHQ). BTW, Nelno says
    he has no self-esteem problem--"It's actually supposed to be a really,
    really large amoeba..."

-- [http://bluesnews.com/jan1.html](https://web.archive.org/web/19970204064523fw_/http://bluesnews.com/jan1.html) (archived 04 February 1997)

The release was hosted on the blues news, linked from the announcement, and the file was captured by archive.org.

It was also the last release of the bot for some time. As such it was archived in many places, not least on CDs for BBS such as "Cream of the CROP 24" in the doom/ directory, available from [textfiles.com](http://cd.textfiles.com/cream/cream24/doom/zeus2042.zip) and [retroarchive.org](http://annex.retroarchive.org/cdrom/cotc-24/DOOM/ZEUS2042.ZIP).

The archive contained the same 3 files.

   9549  9 Jan  1997 WHATSNEW.TXT
 944278  9 Jan  1997 PAK0.PAK
  24405  9 Jan  1997 ZEUS.TXT

The file time stamp was the same as the previous bug fix release, suggesting that bluesnews probably announced the first bug fix release, then updated it to refer to the second bug fix releases on the same day.

This release fixes a few minor bugs, reported in the changelog.

    Changes in version 2.042

    . bots are no longer solid right after dying and until respawning.
    . bots don't keep going after weapons they already have when deathmatch
      is set to 2.
    . removed the debugging message that was popping up each time a bot died.
      It said "Damnit!" and fit well with what the bot might be thinking if
      it were capable of such.

-- zeus.txt




## Ion Storm

Releases of the Zeus Bot stopped around this time for many months.

The major reason may be because the author, Jonathan Wright, was hired as a lead programmer at Ion Storm.

This was the company started bu John Romero and Tom Hall after leaving id Software.

The rumor of Jonathan's hire was announced on bluesnews on February 23, 1997, and later confirmed.

	February 23, 1997

	A pretty reliable rumor has Nelno the Amoeba landing a job at Ion Storm.
    Congratulations to him, and a sincere big thanks to I.S. for making the
    dreams of so many deserving members of our community come true.

-- [Blues News, News Archive](https://www.bluesnews.com/archives/feb97-4.html), February 23, 1997

A few months later in May 1997, Jonathan reported via his .plan file that he would probably no longer work on ZeusBot and focus on his new work at new job.

	Final note: I still get a fair amount of mail asking me when the next Zeus
    bot will be released... as of right now, never. I have a really enhanced
    version that uses all the goodies like dynamic mapping and shortest paths
    laying around here, but I just don't have the time to test it out thoroughly
    and fix the little here and there problems. Sorry. If I get any free time
    that isn't spent working or eating, I might get around to it.

-- [Blues News, News Archive](https://www.bluesnews.com/archives/may97-2.html), Monday, May 12, 1997

Jonathan was there for about one year working on their first-person shooter called Daikatana.

There was a falling out in the company , and he and many developers left in mid 1998.


## ZeusBot v2.05

A new and final version of ZeusBot did come before the end of the year.

It was released as zeus205.zip and zeus205s.zip.

It was on ftp.cdrom.com, where it remained a part of the archive.

    zeus205.txt            03-Jun-97 18:50     1k
    zeus205.zip            03-Jun-97 18:47   370k
    zeus205s.txt           03-Jun-97 18:50     1k
    zeus205s.zip           03-Jun-97 18:47   213k

-- [http://www.cdrom.com:80/pub/idgames2/quakec/bots/](https://web.archive.org/web/19970609212728/http://www.cdrom.com:80/pub/idgames2/quakec/bots/) (archived June 09 1997)

The file contained the the readme, changelog, the PAK file containing the models, sounds, sprites and compiled game code. A separate progs directory was created for the payer model, allowing users to modify it for multi-skin support.

 746442  3 Jun  1997 PAK0.PAK
     96  3 Jun  1997 PROGS
   3542  3 Jun  1997 WHATSNEW.TXT
  30473  3 Jun  1997 ZEUS.TXT

The release date indicates the release was made on June 3rd, and this date matches the timestamps of files in the zip and the FTP timestamps.

    Filename : ZEUS205.ZIP
    Version  : 2.05
    Date     : 6/03/97
    Author   : Jonathan E. Wright aka Nelno the Amoeba

-- zeus.txt

The release was announced in Jonathan's .plan file (perhaps a planetquake or at ion storm) and was picked up and announced on blues news.

    Tuesday, June 3, 1997

    Zeus Lives

    Nelno the Amoeba passed along word that contrary to his previous statements,
    he has updated his famed Zeus bot with some cool new features, including a
    "reaperesque" ability to map the levels as they go along. He also updated
    his .plan to announce the event:

        Okay, so after telling everyone that Zeus was dead, I got tired of
        hearing all the sad pleas for another version of Zeus and went ahead
        and fixed up the 2.05 beta a bit. Now Zeus bots map out levels as they
        go and can find paths to items they have seen. They also do nifty things
        like avoid the hell out of grenades and rockets that you throw at them,
        have reaction times based on skill levels, limited vision and a number
        of other enhancements. Go to my Planet Quake page to read the specifics
        and get the latest zip files. One last enhancement worth noting: there
        is a server version available which doesn't use any new models or sounds a
        nd will allow anyone to log on to a server that is running the Zeus mod.
        I expect those of you who use it to at least tell me about it so that I
        can visit your server and spank you and Zeus down hard.

-- [http://www.bluesnews.com/q-news.shtml](https://web.archive.org/web/19970605010022/http://www.bluesnews.com/q-news.shtml) (archived June 05 1997)

Jonathan moved his personal website from qchq.com to planetquake.com as a directory under the /qca (quakec archive) subsite.

    Go to the official Zeus bot page at Quake C Archive at:
    http://www.planetquake.com/qca/zeus

-- zeus.txt


A server based version of the bot was also released as a separate file on the same day.

This allows the bot to be enjoyed by players by connecting to a server running the mod only.

    But if you're more the outgoing type, and you'd like bots on your server
    night and day, to keep the zombie people happy, download the server version.
    With it anyone will be able to connect to your server and get spanked by a
    Zeus bot, even if they aren't running the Zeus bot mod.

-- [http://www.planetquake.com/qca/zeus/zeus.htm](https://web.archive.org/web/19970607150610/http://www.planetquake.com/qca/zeus/zeus.htm) (archived June 07, 1997)

The server version is simpler, containing just the compiled game code, release notes and changelog.

 639992  3 Jun  1997 PROGS.DAT
  30820  3 Jun  1997 ZEUS.TXT
   7496  3 Jun  1997 WHATSNEW.TXT

The following day, bluesnews reported that Jonathan's .plan file had been updated to report a bug about a crashing bug when running the bot on very large maps.


	Wednesday, June 4, 1997

	Zeus Bug

	Nelno the (very large) Amoeba updated his .plan to point out a bug (feature) in the Zeus bot that can crash very large levels or games with multiple bots, and how to correct it.

-- [http://www.bluesnews.com/q-news.shtml](https://web.archive.org/web/19970605010022/http://www.bluesnews.com/q-news.shtml) (archived June 05 1997)

Jonathan claim he cannot release the source code for the bot as he expects to use it at his new job at ion storm in some way.

    Originally I had planned to release the entire source for the Zeus bot, but
    my employment with ION Storm has made that an impossibility, since Zeus
    contains a basic blueprint of some of the technology that will be used in
    our games.  Please don't ask for the source.  If I could release it I truly
    would, and I'm very sorry that I can't.  Please don't think I'm being stingy
    with my code.  I don't believe in holding things back when others can learn
    from them, but in this case I have little choice.

-- zeus.txt


The change log for this release is truly massive at 78 lines.

A key feature is that bots are able to explore and map the level as they explore.

This may put the bot's capabilities on par with the widely well regard reaper bot, and a fantastic way for Jonathon to sign-off on the bot.

    . bots now map out the level as they go.  They can follow the paths they
      have found, or break off randomly to search for new ones.  This makes
      them *much* faster at getting around.  They will kill you.

-- zeus.txt




## ZeusBot v2.05 Source

Although claiming he could never release the source, he did just that a few months later.

The source was released on September 15th 1997 as the file zeus_src.zip.

It was released on ftp.cdrom.com in the bots/ directory where it remained a permanent part of the archive going forward.

    zeus_src.txt           15-Sep-97 15:16     7k
    zeus_src.zip           15-Sep-97 15:16   188k

-- [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19980210215654/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived February 10 1998)

The archive only contains the source code for the release and a readme file.

```
   7035 15 Sep  1997 ZEUS_SRC.TXT
   7033 15 Sep  1997 README.TXT
   2598 15 Sep  1997 PROGDEFS.H
   8050  5 Jun  1997 HUD.QC
  11710  3 Jun  1997 WORLD.QC
 234070  3 Jun  1997 ZEUS.QC
  50667  3 Jun  1997 CLIENT.QC
  21187  3 Jun  1997 DEFS.QC
  31986  3 Jun  1997 ZEUSMAP.QC
  32965  3 Jun  1997 ITEMS.QC
     85 13 Apr  1997 RUN.BAT
  13416 31 Mar  1997 COMBAT.QC
  15759 30 Mar  1997 MISC.QC
   1370 20 Feb  1997 ZEUS.H
  28813 20 Feb  1997 WEAPONS.QC
  16065 19 Feb  1997 TRIGGERS.QC
    951 19 Feb  1997 PROGS.SRC
  17810 18 Feb  1997 DOORS.QC
   8157 18 Feb  1997 PLATS.QC
   3145 18 Feb  1997 BUTTONS.QC
  11073 15 Feb  1997 WIZARD.QC
  18352 15 Feb  1997 PLAYER.QC
    978  8 Jan  1997 QUAKE.STR
   1775  8 Jan  1997 QSTR.PAS
   7616 14 Dec  1996 FIGHT.QC
  15372 14 Dec  1996 AI.QC
  84785  8 Dec  1996 ZEUSENF.QC
   4501  7 Dec  1996 PLASMA.QC
   8996 26 Sep  1996 MODELS.QC
   4798 26 Sep  1996 MONSTERS.QC
  14657 26 Sep  1996 OGRE.QC
   9537 26 Sep  1996 OLDONE.QC
   7880 26 Sep  1996 SHALRATH.QC
  12725 26 Sep  1996 SHAMBLER.QC
   9825 26 Sep  1996 SOLDIER.QC
    450 26 Sep  1996 SPRITES.QC
   6062 26 Sep  1996 SUBS.QC
   7116 26 Sep  1996 TARBABY.QC
  20108 26 Sep  1996 ZOMBIE.QC
   1697 26 Sep  1996 AMTEST.QC
  12411 26 Sep  1996 BOSS.QC
   9904 26 Sep  1996 DEMON.QC
   9542 26 Sep  1996 DOG.QC
  10727 26 Sep  1996 ENFORCER.QC
   7747 26 Sep  1996 FISH.QC
    141 26 Sep  1996 FLAG.QC
  18298 26 Sep  1996 HKNIGHT.QC
    222 26 Sep  1996 JCTEST.QC
   9684 26 Sep  1996 KNIGHT.QC
```

The readme lists the release as source code for version 2.05 of the bot.


    ======================================
    Title    : ZEUSbot 2.05 Source Release
    ======================================

    Filename : ZEUS_SRC.ZIP
    Version  : 2.05
    Date     : 9/15/97
    Author   : Jonathan E. Wright aka Nelno the Amoeba
    Email    : nelno@resurrection.com, nelno@ionstorm.com

-- zeus_src.txt

The readme lists the release date as September 15th 1997, matching the timestamp of the public FTP and the oldest timestamp of files in the release.

The release was announced on bluesnews.

	Monday, September 15, 1997
	Zeus Source

	Jonathan "Nelno the Amoeba" Wright dropped a line to mention he has released
    the source code of his Zeus bot on his Homepage, as he promised he would
    earlier in his .plan.

-- <https://www.bluesnews.com/archives/sept97-2.html>

His planetquake .plan files have not survived as far as I can tell, and the reasons for the release are not known, given he was expecting to use the code at ion storm.

I suspect they did not get the okay from the lawyers or did not want to purchase it from him as IP and would prefer to develop everything from scratch, or something along those lines.

He comments that the had not looked at the code for a long time, and just wanted to get it out, likely as a global gesture  to support the community.

    I haven't even looked at the Zeus source for more than 3 months, and
    haven't been hardcore into it for more than 7 months, so unless you're
    just stumped, it might benefit you to look around the code yourself a
    bit before emailing me, because I may not have any idea what's going
    on either.

    And yes, I'm sure lots of it is unoptimize lumps of crap, so please
    don't email me telling me that I should have done this instead of that.
    Don't get me wrong -- I'm happy to hear suggestions for improving
    algorithms and such, but try not to nitpick my code, k?

-- zeus_src.txt




## Release Timeline

* ZeusBot v1.0, zeus10.zip, September 28 1996
* ZeusBot v2.0, zeus20.zip, 1996
* ZeusBot v2.01, zeus201.zip, 1996
* ZeusBot v2.02b, zeus202b.zip, December 19 1996
* ZeusBot v2.03b, zeus203b.zip, December 20 1996
* ZeusBot v2.04, zeus204.zip, January 08 1997
* ZeusBot v2.041, zeus2041.zip, January 09 1997
* ZeusBot v2.042, zeus2042.zip, January 09 1997
* ZeusBot v2.05, zeus205.zip, June 03 1997
* ZeusBot v2.05s, zeus205s.zip, June 03 1997
* ZeusBot v2.05 Source, zeus_src.zip, September 15 1997



## References

* [Root Directory Of PDSL GAMERS TOOLKIT](http://cd.textfiles.com/pdsl/HELP/GAMERTK.TXT)
* [Toolkit for Quake (2nd Edition)](https://web.archive.org/web/19970605102505/http://www.cdrom.com:80/titles/games/quake_t.htm) (archived June 05, 1997)
* [Toolkit for Quake (2nd Edition) CD](https://www.quaddicted.com/files/commercial/Toolkit%20For%20Quake%202nd%20Edition%20(QTool_0197).7z)
* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived December 25 1996)
* [http://www.cdrom.com/pub/idgames2/ls-laR.gz](https://web.archive.org/web/19961221100334/http://www.cdrom.com/pub/idgames2/ls-laR.gz) (archived December 21 1996)
* [http://www.cdrom.com/pub/idgames2/00alltxt.tar.gz](https://web.archive.org/web/19961221100133/http://www.cdrom.com/pub/idgames2/00alltxt.tar.gz) (archived December 21 1996)
* [http://www.bluesnews.com/q-news.shtml](https://web.archive.org/web/19970605010022/http://www.bluesnews.com/q-news.shtml) (archived June 05 1997)
* [http://www.planetquake.com/qca/zeus/zeus.htm](https://web.archive.org/web/19970607150610/http://www.planetquake.com/qca/zeus/zeus.htm) (archived June 07 1997)
* [Nelno's .plan File, Jonathan "Nelno the Amoeba" Wright - AI Programmer - September 1997 thru January 1998](http://dk.toastednet.org/dotPlan/Nelno_sep97_jan98.htm)

