# TM Bot

The TM Bot or TMBot was the first publicly released QuakeC-based Quake bot and was based on the HoloSelf mod.


## TMBot v1.0

The first version of the mod, version 1.0, was released as tmbot1.zip.

The archive contained the compiled game code (progs.dat), the source code for the game code (source.zip) and a readme file (tmbot1.txt).

I could not locate an original version of the distribution, only a redistributed version, the contents of which are listed below.

```
	  44381 29 Oct  1996 SOURCE.ZIP
	     17 24 Aug  1996 FILE_ID.DIZ
	   4787 21 Aug  1996 TMBOT1.TXT
	 440272 21 Aug  1996 PROGS.DAT
```

-- tmbot1.zip

The version of the release that I acquired was probably uploaded to a BBS, where the description file "FILE_ID.DIZ" was added, e.g. on August 24th, and the embedded zip file was probably touched in late October.

An unpacked version of the TMBot v1.0 is also provided on the "Eternal Darkness" CDROM in the directory mods/bot/. This was a CD of addons released in September 1996.

The source.zip file contains 14 code files, all but one dated 21st of August.

```
	 11111 21 Aug  1996 WORLD.QC
	 19619 21 Aug  1996 BOTAI.QC
	  8469 21 Aug  1996 BOT.QC
	  2450 21 Aug  1996 BOT.H
	 15298 21 Aug  1996 TRIGGERS.QC
	 17659 21 Aug  1996 PLAYER.QC
	  7855 21 Aug  1996 PLATS.QC
	   962 21 Aug  1996 IMPULSE2.QC
	 17774 21 Aug  1996 DEFS.QC
	 32232 21 Aug  1996 CLIENT.QC
	  6374 21 Aug  1996 SUBS.QC
	   692 21 Aug  1996 PROGS.SRC
	  1597 21 Aug  1996 BOT_EXT.QC
	 24072 18 Aug  1996 WEAPONS.QC
```

-- tmbot1.zip/source.zip

The mod was created and released by two bothers Micheal and Tim Polucha, although Micheal is acknowledged as being the programmer. No doubt the "TM" in the mod name comes from Tim and Michael.

In the readme file, the brothers mention that the release is their first Quake mod.

> This is our first Quake C mod. We plan to do some more as time allows. If you use our code as a basis for another mod, or if you have some ideas for improvements or other mods, please let us know, we would be very interested.

-- tmbot1.txt

The readme marks the release date as August 21st 1996, and the date-times of the game code and readme file match this. The file was probably uploaded the following day, August 22nd.

This release was just under one month after the release of the game source code by id Software and about a week and half after the release of the first HoloSelf which is credited in the readme file.

The mod is described as an automated helper bot for single player.

> Automated Helper Bot or Player 2 on only one computer! With this advanced AI you can conquer any level of Quake. TM Bot is based on the Enforcer Model. Just activate the bot and he'll be completely automated, or you can take control and wreak some havoc with multi-player fun.

-- tmbot1.txt

The readme directly credits Perecli Manole aka "Bort", author of the HoloSelf mod, version 1.0. At the time of release a second version of the HoloSelf mod had been released, but perhaps the brothers development had begun with the first version and there was little need to adapt it after the second version was released.


>	Title    : TM Bot
>	Filename : tmbot1.zip
>	Version  : 1.00
>	Date     : 96/8/21
>	Author(s): Micheal Polucha (co-designer, coder)
>	           Tim Polucha (co-designer, playtester)
>	Email    : mpolucha@earthlink.net
>
>	Credits  : HoloSelf v1.0
>	            by Perecli Manole
>	            Perecli@ix.netcom.com
>
>	           Quake-C specification and HTML version.
>	 	    by Olivier Montanuy
>	            Olivier.Montanuy@wanadoo.fr

-- tmbot1.txt

Interestingly, the bot allows both automatic and manual control. Automatic mode uses bot AI, whereas manual mode allows the player to control the bot, allowing it to take damage leaving the player unharmed.

Usefully, the bot will seek out the player if it gets too far away, and there is a command which will automatically teleport the bot to the player's current position.

Micheal announced the release of the bot on Usenet on August 22nd in rec.games.computer.quake.announce with the title "NEW MOD!! Bot-Like Features! TMBOT1" sharing the contents of the readme file.

It is interesting that the Usenet post has "Bot-Like Features" in the title of the message. It presupposes knowledge of "bot features". Perhaps there was already discussion of quake bots, perhaps on Usenet. It may even suggest an earlier Quake bot that has not yet been identified.

He also posted a message on the same day in rec.games.computer.quake.editing with the title "TM Bot 1 - Quake C AI" asking if anyone else is working on advanced artificial intelligence.

>	I've just finished version 1.00 of a Quake C Bot/Companion.
>	Check it out at:
>
>	ftp://ftp.cdrom.com/.5/idgames2/quake/quakec/bots/tmbot1.txt
>	ftp://ftp.cdrom.com/.5/idgames2/quake/quakec/bots/tmbot1.zip
>
>	Has anyone else been working on improving the AI of the monsters/bots
>	using Quake C?
>
>	-Micheal Polucha

-- [TM Bot 1 - Quake C AI](https://groups.google.com/g/rec.games.computer.quake.editing/c/CCoT-6kWaeM/m/HKsXcHuq-kcJ), rec.games.computer.quake.editing, Micheal Polucha, 22 Aug 1996.

In a follow-up message, he corrects the download links for the bot on the cdrom.com public FTP server:

>	Sorry, the actual links are:
>
>	ftp://ftp.cdrom.com/.5/idgames2/quakec/bots/tmbot1.txt
>	ftp://ftp.cdrom.com/.5/idgames2/quakec/bots/tmbot1.zip

-- [TM Bot 1 - Quake C AI](https://groups.google.com/g/rec.games.computer.quake.editing/c/CCoT-6kWaeM/m/HKsXcHuq-kcJ), rec.games.computer.quake.editing, Micheal Polucha, 22 Aug 1996.

It is interesting that the server already has a directory for bots. This too is either evidence of pre-existing Quake bots or the anticipation of the development of Quake bots.

The majority of the bot is in three source files bot.qc (mostly manual control of the bot), bot_ext.qc (some bot trigger handling) and botai.qc (mostly automatic control of the bot), with definitions defined in bot.h. The remaining .qc files list minor changes to integrate the bot into the game.

Single player with the bot is fun.

The bot is spawned with a command and looks like an enforcer. It is not solid allowing the player to walk through it.

When enemies are encountered it will run towards them and shoot laser bolts at them until they are dead. It cannot take damage and cannot become the target of the monsters. The bots laser bots can hit and damage the player if you stand between it and its enemy.

It can be a little tedious waiting for the bot to walk over to you before going down a lift. Nevertheless, the bot works as advertised.




## TMBot v1.1

A second version of the mode was released a few days later with the file tmbot11.zip.

The readme lists the version as v1.1 and the release date as August 26th 1996, five days after the first release, and the timestamps of the files in the archive match this release date.

>	Title    : TM Bot
>	Filename : tmbot1.zip
>	Version  : 1.1
>	Date     : 96/8/26

-- tmbot11.txt

I note, the readme lists the distribution filename as "tmbot1.zip" instead of "tmbot11.zip".

Like the first version, the archive contains a readme (in this case tmbot11.txt), a zip with the game source code (source.zip), and a compiled version of the source code (progs.dat).

```
	  44173 26 Aug  1996 SOURCE.ZIP
	 450104 26 Aug  1996 PROGS.DAT
	   1185 26 Aug  1996 FEATURES.TXT
	   5055 26 Aug  1996 TMBOT11.TXT
```

-- tmbot11.zip

The source files appear to have been last touched the day before on August 25th.

```
	 14391 25 Aug  1996 BOT.QC
	 16584 25 Aug  1996 BOTAI.QC
	  2889 25 Aug  1996 BOT.H
	  6284 25 Aug  1996 BOTAI2.QC
	   713 24 Aug  1996 PROGS.SRC
	  1332 24 Aug  1996 IMPULSE2.QC
	 17578 24 Aug  1996 DEFS.QC
	 17646 24 Aug  1996 PLAYER.QC
	 15294 24 Aug  1996 TRIGGERS.QC
	  6368 24 Aug  1996 SUBS.QC
	  3552 24 Aug  1996 BOT_EXT.QC
	 24099 24 Aug  1996 WEAPONS.QC
	 17352 23 Aug  1996 DOORS.QC
	  2988 23 Aug  1996 BUTTONS.QC
	 11111 21 Aug  1996 WORLD.QC
	  7855 21 Aug  1996 PLATS.QC
```

-- tmbot11.zip/source.zip

Availability for the mod is listed at the end of the readme and includes be both ftp.cdrom.com in the bots/ directory, and at www.stomped.com.

>	ftp://ftp.cdrom.com/.5/idgames2/quakec/bots/
>	http://www.stomped.com/files.htm

-- tmbot11.txt

Checking the archived URL cdrom.com/pub/idgames2/quakec/bots/, we can see that the upload timestamp for tmbot11.zip and tmbot11.txt matches the release date in the readme.

```
		tmbot11.txt            26-Aug-96 10:56     4k
		tmbot11.zip            26-Aug-96 11:03   176k
```

As with v1.0, Michael posted to Usenet to announce the release, sharing the contents of the readme on rec.games.computer.quake.announce on August 27th with the title "TMBOT 1.1 ..Bot with Source.

The distribution includes a new file that lists the features and known bugs (features.txt).

>	TM Bot v 1.1
>
>	Features:
>
>		1. Manual or automatic control of the bot.
>		2. Bot can draw enemy fire.
>		3. Seeks out monsters and attacks them.
>		4. Can activate trigger fields on the floor (like
>		   the lights on E1M1 when going down the spiral ramp).
>		5. Can trigger some platforms.
>		6. Can open doors.
>		7. Can go through teleport portals.
>		8. Tries to return to player when player gets too
>		   far away.
>		9. DM/Co-op mode toggle.
>
>	Bugs:
>
>		1. Bot will sometimes shoot you in the back.
>		2. Bot cannot push buttons on the wall.
>		3. Bot cannot jump.
>		4. Bot cannot walk over broken ground.
>		5. Bot sometimes gets lost.
>		6. Certain functions (i.e. teleport, move, etc.)
>		   interrupt the dying process giving you a ghost bot
>		   that is insubstantial and unkillable.
>		7. Level changes may not be handled correctly by my code
>		   (Bot may not be deactivated, just lost).
>
>	If you find a new bug that is not listed here, please send the bug
>	report to mpolucha@earthlink.net. If yours is the first report for the
>	bug, we'll give you credit for reporting it. Also, if you have a
>	solution for a known or newly discovered bug, please feel free to
>	submit that as well.

The update contains a number of changes, interesting changes which can be summarized as:

* A command to toggle the bot between cooperate and deathmatch modes.
* Increase in the walking speed for the bot.
* The bot is now solid and cannot be walked through by the player.

They also list some minor features they plan for the v1.2 release and long list of changes they intend for v2.0 of the mod. Sadly neither a v1.2 or v2.0 were ever released by the brothers.

It is clear from the comments in the readme that the brothers are getting feedback and bug fixes from the community. They call out thanks for both suggestions for following releases and fixes for minor issues with the bot incorporated into v1.1.

>	Orientation of bot is now always level. (Thanks to Anders Dalvander for reporting this.)

Playing this newer version is better.

Now that the bot is solid it means you and monsters can shoot it and it can take damage and die, requiring you to spawn a new bot.

When playing single player you can set the bot to deathmatch mode which causes it to ignore the enemies. In deathmatch mode, it will fight other players on your behalf.

Although simple, the TM Bot provides a important basis for a large family tree of bots.

In a note on Usenet by Tim (under Michael's account) on September 5th 1996, it is clear there is already a burgeoning deathmatch bot mod community.

>	... My brother and I are working on our own patch that will have some of the features other DM bots have and maybe a few they don't.
>
>	- Tim Polucha

The brothers decision to upload it to public locations (cdrom.com and stomped.com) announcement of the bot in multiple Usenet groups (rec.games.computer.quake.announce amd rec.games.computer.quake.editing) helped with adoption and subsequent extensions of the bot, founding a whole linage of bots.

Critically, two other bots were released between TMBot v1.0 and TMBot v1.1, and they were both focused on deathmatch. They were the MyBot and the DMBot.

I don't believe either brother continued their efforts on Quake development, at least not publicly. I could find Michael Polucha in QuakeC and not discussions later in the year and early in the 1997, but no further announcements of bot or mod releases.

A few months later, Tim commented that he'd like to collaborate on more mods, but he does not know QuakeC programming.

>	...
>	My brother and I created
>	TMBOT...though now he hasn't got the time to work on it anymore :(. I'd
>	still like to work on quakec stuff but I really don't have much
>	programming knowledge. Anybody want to work on QuakeC..ie a group of
>	people? Mostly all that I could do would be to help with design concepts
>	(and boy do I have a lot of concepts...hmm) I believe a few people have
>	written us already...but I really haven't said yes or no...I'd like to
>	get a whole lot of people working on this..Some people for bots, others
>	for levels...graphics...models etc.. Anybody interested?
>
>	If interested please reply to this in news and to my email address at:
>	Mpol...@earthlink.net
>
>	Thanks in advance,
>	Tim Polucha

-- [rec.games.computer.quake.editing, Micheal Polucha, 1 Oct 1996](https://groups.google.com/g/rec.games.computer.quake.editing/c/oBId-aNBplM/m/uTZKX5CJFSwJ).


## Relevant Timeline

* QuakeC source code v1.01, qcc.tar.gz, July 25, 1996.
* HoloSelf v1.0, holo1.zip, August 11, 1996.
* HoloSelf v2.0, holo2.zip, August 14, 1996.
* TMBot v1.0, tmbot1.zip, August 22, 1996.
* TMBot v1.1, tmbot11.zip, August 26, 1996.


## References

* [tmbot1.zip](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/bin/tmbot1.zip)
* [tmbot11.zip](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/bin/tmbot11.zip)
* [FILE_ID.DIZ](https://en.wikipedia.org/wiki/FILE_ID.DIZ), Wikipedia.
* [NEW MOD!! Bot-Like Features! TMBOT1](https://groups.google.com/g/rec.games.computer.quake.announce/c/SwOl7gmcaQQ/m/j-Vu_EkhI-8J), rec.games.computer.quake.announce, Micheal Polucha, 22 Aug 1996.
* [TM Bot 1 - Quake C AI](https://groups.google.com/g/rec.games.computer.quake.editing/c/CCoT-6kWaeM/m/HKsXcHuq-kcJ), rec.games.computer.quake.editing, Micheal Polucha, 22 Aug 1996.
* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (internet archive)



