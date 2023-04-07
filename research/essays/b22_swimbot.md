# Swimming Bot

The Swimming Bot or "Swimbot" is an extension to the Roambot and was developed by Greg Fukui aka "baloo the bear" aka "julias_child".



## Swimbot v1.0

We don't have a lot of information about the first version of the bot.

It may or may not have been released publicly, and if so, it may have had a release filename like swbot10.zip or swbot1.zip or something else entirely.

We know of the possible existence of the release given a changelog in the FILE_ID.DIZ file released in the v1.03 version of the bot.

	...
	Revision 1.01 fixes 1.0's broken roaming.

-- FILE_ID.DIZ


## Swimbot v1.01

Like the first version of the bot, we don't have evidence that this version of the bot was released publicly.

The release probably had the filename swbot101.zip to be consistent with later releases.

We know of the possible existence of the release given a changelog in the FILE_ID.DIZ file released in the v1.03 version of the bot.

	...
	Revision 1.01 fixes 1.0's broken roaming.

-- FILE_ID.DIZ

The changelog suggest that this version was a bug fix, repairing broken roaming code in the bot.

A fuller changelog is given in the readme file for version 1.03. The message does suggest that the bot was released publicly, asking any users of the prior version to switch to the updated version.

	Changes since version 1.0:  Revised botai.qc and bot_roam.qc
	to fix broken roaming (oops).  Also improved realism of bot
	swimming.  I hope anyone who tried revision 1.0 will still
	give this revision 1.01 a chance.

-- README.TXT



## Swimbot v1.02

Again, as with v1.0 and v1.01 of the bot, we only have knowledge of this release given mention in the version 1.03 changelog.

This release probably had the filename swbot102.zip. in order to be consistent with later releases.

	...
	Revision 1.02 fixes 1.01's broken single player.

-- FILE_ID.DIZ

The release suggests it fixes broken single player mode for the bot, e.g. using the bot as a helper.

A fuller changelog was given in the readme file for version 1.03.

It comments on extensive changes to the bot's AI, including support for bot teams.

	Changes since version 1.01:  Extensive changes to all bot
	AI code to improve cooperation between search, roam, and
	attack modes.  Bots find teleporters faster.  Bots fight
	underwater with less drowning.  Added AI for four 2-bot
	teams (when impulse 100'ed twice), bots help bots with the
	same netname, being especially hostile towards enemies of
	the twin.  A bot will even seek vengeance against the twin's
	killer.  Fixed broken single player teamplay (oops again).

-- README.TXT





## Swimbot v1.03

This version of the bot was released as swbot103.zip.

A copy of this release was found on the "Shareware Extravaganza 8" CDROM on CD 2 archived by archive.org and textfiles.com.

It includes a zip summary (FILE_ID.DIZ), a readme (README.TXT), compiled game code (PROGS.DAT), player model (PROGS/ directory) and shell casing sounds (SOUNDS/). It also contains the source code for the release, provided as SRC.ZIP in the PROGS/ directory.

     96 18 Nov  1996 SOUND
    160 18 Nov  1996 PROGS
   7104 29 Sep  1996 README.TXT
    790 29 Sep  1996 FILE_ID.DIZ
 470444 29 Sep  1996 PROGS.DAT

The release date in the summary file was listed as September 29 1996.

The readme files and compiled game code in the release have file time stamps that match. This was probably the public release date.

At this point that the mod was released, the Roambot on which this bot was based had been available for about one month, since September 03 1996. This suggests that all development on the bot and release of prior versions was contained to the month of September.

	Title    : Swimming Bot (Swimbot)
	Filename : swbot103.zip
	Version  : 1.03 (for Quake 1.01)
	Date     : 96/9/29
	Email    : baloo@kaiwan.com

-- FILE_ID.DIZ

The summary file appears complete and was probably prepared by the author of the mod, not by a third-party or automatically when the file was shared on BBSs.

The summary file describes the bot as an extension of the Roambot by Carson Sutton aka "Crimson" based on the BGBot.

The goal appears to be to add specific behaviors to the bot, such as the ability to "swim", giving the bot its name.

	This is a modification of Roambot, with bots that should:
	a) try to jump if stuck in place (on ledges, etc.)
	b) swim to the surface if underwater
	c) try to dodge while attacking
	d) break off attack if out of ammo or near-death

-- FILE_ID.DIZ

The bot also adds Multiskin support, so bots appear differently in deathmatch. This is mentioned in the summary file.

	Also incorporates Multiskin, and Holo, because I used them to skin the bots.

-- FILE_ID.DIZ

The changelog for the release describes improvement to the single player helper bot.

	Changes since version 1.02:  Improved single player bot
	by adding toggle impulse, and making bot hover around area
	in front of player instead of around player.

-- README.TXT

The readme provides an extensive credits section. In addition to crediting the authors of the Roambot and BGBot, it also credits the authors of the DMBot and TMBOt, progenitors of the BGBot.

Credit is given for the shell ejection code, as evidenced in the inclusion of model and sound files in the release, as well as the authors of the multiskin and holo mods.

The readme had an reasonably extensive section on installation instructions as well as a section on technical details of the bot.

He comments in the technical details section that he admired the RoamBot as the reason why he chose it as the basis for his bot.

	I liked the independent spirit of Carson Sutton's Roaming
	bot and just tried to make it a little better at handling
	non-combat situations (wandering into corners and getting
	stuck).

-- README.TXT

He then proceeds to explain how the SwimBot determines whether it is underwater or not and what to do about it.

	I ended up using traceline to allow a bot to identify
	if underwater or not.  The reason is that the entity
	flag, self.waterlevel, does not behave the same for monsters
	and bots, as for the player.  The player gets values
	0=out, 1=feet, 2=waist, and 3=head, but my bot could only
	get 0,-1=out, 1=inwater.  Apparently, monsters don't care
	about water except to splash around in it (and the watermon
	quakec patch didn't help at all).  To make matters worse,
	bots move in steps, so "swimming" means jumping, with the
	end result being that the bots don't swim realistically.
	Hey!  At least they'll drown/short-circuit if underwater
	too long, which is only fair, since the bots start blasting
	the player as soon as spawned.

-- README.TXT

The readme explains his ambition to expand the mod to support more advanced level navigation, such as using waypoints like the eliminator bot that had also been released in September 1996.

	Planned improvements:  Elimbot seems to be pretty neat,
	but it only works with maps for which it has waypoints.
	I want to try to make swimbot learn and remember its
	own waypoints.  (Hmmm, traces of Dungeon Keeper?).
	I don't know if this is possible, though, because the
	progs.dat keeps growing and growing, and swimbot still
	wont push buttons...

-- README.TXT





## Swimbot v1.04

The next and last version of Swimbot was released as swbot104.zip.

This version was uploaded to ftp.cdrom.com in the quakec/bots/ directory, where it remained part of the archive and where it appears today in modern mirrors.

	swbot104.txt           10-Oct-96 05:25     3k
	swbot104.zip           10-Oct-96 05:26   146k

-- [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived December 25 1996)

It was also included on the "Toolkit For Quake (QTool_0197)" CDROM.

The release is smaller, containing only the summary readme, the readme file, and the compiled game code.

This makes the mod challenging to use, requiring that the user copy the files from the previous release or locate the files from other mods and copy them over.

   3525 10 Oct  1996 readme.txt
    657 10 Oct  1996 file_id.diz
 476008 10 Oct  1996 progs.dat

This release does not include the model files or sound files required to use the mod. It also does not include the source code.

Some users liked the release enough to prepare a zip of the missing required files. An example is Dennis Plester aka "Den" on his website "Den's den" who released a "sbotstuf.zip" containing the missing files.

	You also need these support files, to make the Swimbots play, sbotstuff.zip (376 Kb).

-- [http://www.iinet.net.au/~den/swimbot.html](https://web.archive.org/web/19990223195820/http://www.iinet.net.au/~den/swimbot.html) (Archived February 23 1999)

The readme file lists the release date as October 10 1996. The timestamps of files on ftp.cdrom.com confirm this release date.

	Title    : Swimming Bot (Swimbot)
	Filename : swbot104.zip
	Version  : 1.04 (for Quake 1.06)
	Date     : 96/10/10
	Email    : baloo@kaiwan.com

-- file_id.diz


The focus of this release appears to be to update the code to support the v1.06 release of the QuakeC source code.

	Revision 1.04 includes lotsa minor tweaks and uses the 1.06 QuakeC source.

-- file_id.diz

The readme has a more elaborate version of the changelog, commenting on known limitations of the bot behavior.

	Changes since version 1.03:  Updated for Quake 1.06.
	Can now have up to four single player bots (may have
	some bugs still, one bot is still best).  Still no
	bot grenades or lightning.  Have only received a handful
	of comments about previous revs, so just the progs.dat
	this time.

-- readme.txt

The readme is much truncated compared to the previous release, with fewer installation instructions and technical details.

	Technical Details
	-----------------
	Trying to create more than 8 DM bots will get you to
	the console.  I gotta find a way to shrink the .dat
	file!  Report any bugs you may find.

-- readme.txt

This appears to be Greg Fukui's first and last quake mod, although it made an impact.


	Swim Bot, by Greg Fukui.

	Well, just for something different, these bots can swim, which is not an ability of all bots around. Of more merit though, is their great dress sense. Have you ever wanted to go head to head with Judge Dred, Duke Nukem (who?...), Predator or the Terminator? Well, here is your chance.

	As well as swimming, and great looks, these bots play well to boot. Like BG and Reaper, any level can be used to interact with your old mates.

-- [http://www.iinet.net.au/~den/swimbot.html](https://web.archive.org/web/19990223195820/http://www.iinet.net.au/~den/swimbot.html) (Archived February 23 1999)




## Release Timeline

* Swimbot v1.0, swbot1.zip, ???
* Swimbot v1.01, swbot101.zip, ???
* Swimbot v1.02, swbot102.zip, ???
* Swimbot v1.03, swbot103.zip, September 29 1996.
* Swimbot v1.04, swbot104.zip, October 10 1996.


## References

* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived December 25 1996)
* [http://www.iinet.net.au/~den/swimbot.html](https://web.archive.org/web/19990223195820/http://www.iinet.net.au/~den/swimbot.html) (Archived February 23 1999)




