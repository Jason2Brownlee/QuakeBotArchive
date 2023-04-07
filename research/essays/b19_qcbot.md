# QCBot

The QCBot was developed and released by Alan Kivlin aka "Virtuoso" aka "Strider".

It is not a bot per se, rather a single QuakeC file that allows bots to be treated as clients in the game. In turn, this allows bots to appear in the client score rankings (when pressing the "TAB" key) and for bots to be assigned meaningful colors.

As such, the release is sometimes referred to as "client emulation" or "rankings.qc" after the file that was released. It is referred to as "QCBot" because that is how the release was packaged.



## QCBot v001

The first version of the release had the filename qcbot001.zip.

A copy of this release has not been acquired.

We know of its existence because of a reposing of a message on Usenet, seemingly from Kivlin himself, commenting on how he shared version with Blue from Blues News.

The message appears to be a snippet of a conversation, probably taken from IRC or a message board announcing the second version of the release.


	=== Cut ===
	QCBOT002.ZIP5 / MAY / 1997
	Information and demo on getting QuakeC bots onto the rankings screen as well
	as changing the bots color!by Alan Kivlin (aka Virtuoso)

	>^^^^^^^^^^^^^^ ^^^^^^^^^^^^^^^^^^^^^^^^

	After emailing QCBOT001.ZIP to Blue @ Blue's News (www.bluesnews.com - best
	quake page in the world - heh I've followed blue a long time and I'm very
	pleased to see him get the success he deserves), I noticed a bug in
	clientNextAvailable(), its now fixed (I was allowing 17 clients instead of 16).
	I also see a couple of bots have been released namely TheOak (heh this botis
	very funny with all those Arnie wavs) and my original favorite bot of
	alltime The Eliminator (Cameron Newham was one of the first that coded any
	majorbot developments IMO) - I hope the authors will make use of the
	information I'm making available. Happy bot making - Quake Rules The Cosmos :)
	=== Cut ===

-- [BOTS!](https://groups.google.com/g/fido7.ru.game.doom/c/bpTlbP8dbdQ/m/JBYzyxY9LcMJ), fido7.ru.game.doom, Sasha Vinnikov, 11 May 1997 (updated for formatting)

It does not appear that this or subsequent releases were announced on Blues News, after checking the new archive around this time.

The release date of this first version is not known, although was probably early 1997.




## QCBot v002

The first version of the release had the filename qcbot002.zip.

Again, a copy of this release has not been acquired. (UPDATE: A copy has been located... I will update this ASAP)

Like the first version, we know of its existence given the reposting of a message from Kivlin announcing the second version.

The second version appears to fix a bug in the firs version.

	I noticed a bug in clientNextAvailable(), its now fixed
	(I was allowing 17 clients instead of 16

-- [BOTS!](https://groups.google.com/g/fido7.ru.game.doom/c/bpTlbP8dbdQ/m/JBYzyxY9LcMJ), fido7.ru.game.doom, Sasha Vinnikov, 11 May 1997

The message also suggest that bots had started using the release by this time, such as the Oak bot.

	I also see a couple of bots have been released namely TheOak (heh this botis
	very funny with all those Arnie wavs)

-- [BOTS!](https://groups.google.com/g/fido7.ru.game.doom/c/bpTlbP8dbdQ/m/JBYzyxY9LcMJ), fido7.ru.game.doom, Sasha Vinnikov, 11 May 1997

The Oak bot release around this time did not include a readme file, just compiled game code, leaving no credit to the change. One approach might be to decompile the Oak bot releases and check them for the ranking code, and if present, compare to the later release to see if differences exist.

The message lists the filename for the release and a release date as May 05, 1997.

	QCBOT002.ZIP 5 / MAY / 1997

-- [BOTS!](https://groups.google.com/g/fido7.ru.game.doom/c/bpTlbP8dbdQ/m/JBYzyxY9LcMJ), fido7.ru.game.doom, Sasha Vinnikov, 11 May 1997




## QCBot v003

The third and final version of this release was distributed as qcbot003.zip.

It was uploaded to ftp.cdrom.com into the quakec/bots/ directory. It remained in this directory and is still available in modern mirrors, such as from quaddicted.com.

	qcbot003.txt           07-Jun-97 12:54     1k
	qcbot003.zip           07-Jun-97 12:56   847k

* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19970609212728/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived June 09 1997)

I suspect the eariler versions were also uploaded to ftp.cdrom.com, although no trace remains.

The archive contains the source code that provides the bot client capabilities (RANKINGS.QC), a readme file (README.TXT) and demos of the capabilities that the release supports for the bots.

```
  685768  7 Jun  1997 50BOTS.DEM
  626943  7 Jun  1997 CLSTART1.DEM
  849469  7 Jun  1997 CLSTART2.DEM
   12716  7 Jun  1997 RANKINGS.QC
    7685  7 Jun  1997 README.TXT
 1515028  7 Jun  1997 SVSTART.DEM
```

The readme file distributed with the zip archive gives a terse summary of the release.

The readme includes a release date of June 07 1997, matching the timestamp of files in the archive and the ftp file timestamp. This gives further evidence that Kivlin upload the file himself to ftp.cdrom.com and that prior releases were uploaded likewise.

	07 / JUNE / 1997

	Updated QCBot information and demos with details for getting QuakeC bots onto
	the quake rankings screen as well as changing the bots color.

	Copyright (C) 1997 by Alan Kivlin.

-- qcbot003.txt

The release date also appeases in the header for the code file.

	/*
	==============================================================================
	RANKINGS.QC by Alan Kivlin <e-mail: alan.kivlin@cybersurf.co.uk>

	07 / JUNE / 1997

	Copyright (C) 1997 by Alan Kivlin.
	==============================================================================
	*/

-- RANKINGS.QC

The readme file in the zip contains an extensive description of the release.

Firstly, it comments that it is an update over previous release, giving credence to the snippet reposted on Usenet regarding previous releases.

	This is an update of my previously released information on implementing bots
	on the quake rankings screen.

-- README.TXT

Kivlin comments that he had a project to develop a Quake bot that behaves like a real client in the game, as opposed to the kludges required to simulate the bot acting like a client.

	My aim is to create a bot that moves like a real player, thinks like a real
	player (heh this isn't as impossible as it sounds) and hence it'll effectively
	play like a real player. Everything will be customisable and I mean
	everything, not just a simple skill variable.

-- README.TXT

He comments that he is new to the QuakeC code base and re-wrote the whole code base from scratch to understand it.

This is a big claim, and impressive if true.

	I learned QuakeC (about 4 months ago) by rewriting v1.06 in its entirety,
	removing all code not required for deathmatch play. I didn't change how it
	worked, all I did was reformat it to my own style. By doing this I eventually
	had a complete picture of how it all worked in my head, I was dreaming QuakeC
	for a while :)

-- README.TXT

It was this rewriting that gave him insight into how to allow bots to behave like real clients in the game.

	Since then I've managed to overcome *ALL* restrictions in bot movement.

	What you see in the demos, is a bot that's now using 100% physics movement
	(my previous release simulated physics movement most of the time by calling
	walkmove, it was very realistic but some levels have areas that a bot couldn't
	walk onto). Now I don't have to use walkmove or movetogoal at all for
	movement!

-- README.TXT

He goes on to describe a lot of the navigational capabilities of his own bots under development, as demonstrated in the demo files included in the release.

Included in this, is the ability for the bots to learn a level, much like the reaper bots were able to achieve.

	I've almost finished code that terraforms the level (dynamically) - this
	takes a small amount of time but it's amazing as once it's done the bot
	actually *KNOWS* the level - not only that, it can traverse the tree and seek
	out items it wants as it knows exactly where they are and how to get to them.

	This technique will probably never be as good as how a player knows the level
	but I believe it's better (faster?) than pathfinding and looking for items
	via findradius. Imagine what would be possible in Quake 2 if id Software coded
	into the bsp file this type of information and provided routines for
	traversing etc - Quake 2 would not only be great in deathmatch (for bots) but
	the creatures in single player could be incredibly level wise :)

-- README.TXT

The readme file ends with instructions on how to make use of the included rankings.qc file so bots appear like real clients in the game.

Sadly, it does not appear that Kivlin finished his bot or made the project public in any way.

He did contribute to QuakeC editing.

Comments by Kivlin can be seen on various quakec editing boards, like on telefragged.com and elsewhere, although captures by archive.org are spotty at best.

He also authored a tutorial for inside3d in May 1997 that showed how to make gibs and any quake items float in water.

	FLOATING QUAKE ENTITIES

	Would you like to see gibs, heads, dead bodies and backpacks float in water?
	Now you can by following this tutorial and with a little extra programming
	you could make other entities float (how about a grenade that starts to surface
	after it reaches the floor of the water).

-- [http://www.inside3d.com/qctut/lesson-14.html](https://web.archive.org/web/19981203072824/http://www.inside3d.com/qctut/lesson-14.html) (archived December 03 1998)

The code included in the tutorial, FLOATER.QC, includes a release date of May 12 1997, shortly after the release of qcbot002.zip and before the release of qcbot003.zip.

	FLOATER.QC by Alan Kivlin <e-mail;: alan.kivin@cyberiacafe.co.uk>

	12 / MAY / 1997

	Description of the Modification
	-------------------------------

	Routines for making an entity float to the surface of water.

	A floater will sink depending on its falling velocity, it will then float
	to the surface where it will bob up and down for around 30 seconds and
	finally it will sink until it hits the ground.

	Sometimes you'll find a floater will retain its avelocity, making it
	spin around while bobbing - I didn't code for anything like this. Also an
	entity will sometimes keep it's velocity_x or velocity_y.

-- [http://www.inside3d.com/qctut/lesson-14.html](https://web.archive.org/web/19981203072824/http://www.inside3d.com/qctut/lesson-14.html) (archived December 03 1998)

The client emulation or ranking.qc developed by Kivlin was widely adopted in bots developed after this point.

Some bots that include it include: Doombot, Darkbot, extensions to the Eliminator bots, extensions to the Reaper bots like Warbot, Cronobot, Frogbot, Frikbot, and the tutorbot.

Terry Hendrix, author of the Darkbot and editor behind the botshop website listed the release as "Client Emu Source", where "emu" is a contraction of emulation, giving it high importance among Quake bot development.

	Quake Client Emu Source
	Author: Alan Kivlin

	Our friend in the UK brought us the most widely known QuakeC bot hack, adding
	bots to the client scoreboard. I can't say how much this helped client emulation.

-- [http://www.planetquake.com/botshop/code.html](https://web.archive.org/web/20000417184231/http://www.planetquake.com/botshop/code.html) (April 17 1999)

It also appears as an entryt in the popular QuakeC Reference Manual developed by David Hesprich.

	Can QuakeC bots be listed in the player rankings, or have proper shirt and
	pants colors?

	Yes, but it requires a hack of the Quake network protocol. The bot must be
	assigned a client number from the pool available (there are maxplayers client
	numbers). The obvious downside to this is that is requires the bot to take a
	slot that ordinarily would be available for a human player.

	Once the bot has it’s own client number, it can be assigned it’s own colormap
	and broadcast it’s name and frags to the clients. Note that since the bot is
	not really a client, every time the bot’s colors, name, or frag count changes,
	the change must be forced by sending out another broadcast message.

	Alan Kivlin (alan.kivlin@cybersurf.co.uk) has an example of how this might be
	accomplished in his QCBot.

-- Page 58, [QuakeC Reference Manual](https://pages.cs.wisc.edu/~jeremyp/quake/quakec/quakec.pdf), David Hesprich aka "DarkGrue", February 4, 1998.




## Release Timeline

* QCBot v001, qcbot001.zip, ??? 1997
* QCBot v002, qcbot002.zip, May 05 1997
* QCBot v003, qcbot003.zip, June 07 1997


## References

* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19970609212728/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived June 09 1997)
* [BOTS!](https://groups.google.com/g/fido7.ru.game.doom/c/bpTlbP8dbdQ/m/JBYzyxY9LcMJ), fido7.ru.game.doom, Sasha Vinnikov, 11 May 1997
* [Re: colormaps](https://web.archive.org/web/19980216132437/http://jord.sbc.edu/qcboard/messages/137.html) (archived February 16 1998)
* [QuakeC Reference Manual](https://pages.cs.wisc.edu/~jeremyp/quake/quakec/quakec.pdf), David Hesprich aka "DarkGrue", February 4, 1998.
* [http://www.planetquake.com/botshop/code.html](https://web.archive.org/web/20000417184231/http://www.planetquake.com/botshop/code.html) (April 17 1999)
* [http://www.inside3d.com/qctut/lesson-14.html](https://web.archive.org/web/19981203072824/http://www.inside3d.com/qctut/lesson-14.html) (archived December 03 1998)



