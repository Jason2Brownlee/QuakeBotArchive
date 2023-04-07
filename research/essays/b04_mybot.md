# MyBot

The MyBot mod was created by Stephen Vanterpool and was an extension of the TMBot.

It may just be the first dedicated deathmatch bot, an opponent that turns multiplayer deathmatch into a single player game.

The mod started as an extension and improvement to the TMBot single player helper bot, although was modified to support deathmatch play against the player in the third release, which became the focus of the mod in subsequent releases.

Rather than trying to create a simulation of a human opponent, the bot is more like playing a clever monster while in deathmatch gameplay mode.

I was able to track down five versions of the MyBot that were publicly released between the end of August and early September 1996.

All of the releases, were found on a CD titled "Power Tools for Quake (Europe)" located on the internet archive. Timestamps on the CD suggest that it was created March 1997 and perhaps distributed soon after. Only the last release, MYBOT16, can be found elsewhere on the internet.

1 Mar  1997 MYBOT
1 Mar  1997 MYBOT16
1 Mar  1997 MYBOT13A
1 Mar  1997 MYBOT11
1 Mar  1997 MYBOT12

There may have been additional releases as well as a private beta releases, although no confirmation has been made.

Let's take a closer look at the releases.




## MyBot v1.0

The version of the mod was released with the filename mybot.zip.

The archive included a readme file (readme.txt) a copy of the readme from the TMBot v1.0 (tmbot1.txt), the compiled game code (progs.dat) and the game source code (src.zip).

    510 24 Aug  1996 readme.txt
   4787 24 Aug  1996 tmbot1.txt
 123521 24 Aug  1996 src.zip
 442156 24 Aug  1996 progs.dat

The src.zip contains all of the source code for the mod.

  2598 24 Aug  1996 progdefs.h
 22465 24 Aug  1996 Botai.qc
   931 24 Aug  1996 Progs.src
 20533 24 Aug  1996 Botai.q
  8476 24 Aug  1996 Bot.qc
 11111 21 Aug  1996 World.qc
  2450 21 Aug  1996 Bot.h
 15298 21 Aug  1996 Triggers.qc
 17659 21 Aug  1996 Player.qc
  7855 21 Aug  1996 Plats.qc
   962 21 Aug  1996 Impulse2.qc
 17774 21 Aug  1996 Defs.qc
 32232 21 Aug  1996 Client.qc
  6374 21 Aug  1996 Subs.qc
  1597 21 Aug  1996 Bot_ext.qc
 24072 18 Aug  1996 Weapons.qc
  4605  9 Aug  1996 Readme.txt
  6630  9 Aug  1996 Chain.qc
 28937  6 Aug  1996 Items.qc
  7945 24 Jul  1996 Fish.qc
 18750 24 Jul  1996 Hknight.qc
   237 24 Jul  1996 Jctest.qc
  9966 24 Jul  1996 Knight.qc
 15760 24 Jul  1996 Misc.qc
 10373 24 Jul  1996 Models.qc
  5034 24 Jul  1996 Monsters.qc
 15129 24 Jul  1996 Ogre.qc
  9675 24 Jul  1996 Oldone.qc
  8131 24 Jul  1996 Shalrath.qc
 13104 24 Jul  1996 Shambler.qc
 10121 24 Jul  1996 Soldier.qc
   512 24 Jul  1996 Sprites.qc
  7350 24 Jul  1996 Tarbaby.qc
 11085 24 Jul  1996 Wizard.qc
 20635 24 Jul  1996 Zombie.qc
 15268 24 Jul  1996 Ai.qc
  1776 24 Jul  1996 Amtest.qc
 12808 24 Jul  1996 Boss.qc
  3051 24 Jul  1996 Buttons.qc
  6415 24 Jul  1996 Combat.qc
 10279 24 Jul  1996 Demon.qc
  9917 24 Jul  1996 Dog.qc
 17774 24 Jul  1996 Doors.qc
 11090 24 Jul  1996 Enforcer.qc
  7617 24 Jul  1996 Fight.qc

The readme file for the mod is very simple and does not include a release date. The timestamp of files in the archive is August 24th 1996 and this will be taken as the release date for the mod as no corroborating FTP timestamp can be located.

Further, releases of the bot were not announced on Usenet.

This may be the first publicly released extension of the MyBot, appearing two days after the TMBot appeared publicly on August 22nd.

The mod is described as a simple modification of the TMBot that will fire grenades at zombies.

	I modified the tmbot qc mod to shoot grenades at zombies.

-- readme.txt, mybot.zip

This is a desirable modification as the Enforcer model in the TMBot will only fire laser bolts and zombies must be gibbed in order to be completely killed. Having the bot fire grenades at zombies will achieve this.

At this point, the bot is still a helper bot for single player.


## MyBot v1.1

A follow-up MyBot release had the filename mybot11.zip, containing theme same files although with a timestamp updated for August 25th, one day later.

    749 25 Aug  1996 readme.txt
 119255 25 Aug  1996 src.zip
 442476 25 Aug  1996 progs.dat
   4787 24 Aug  1996 tmbot1.txt

The changelog indicates minor changes such as the bot being stronger and going into pain less often, as well as a tweak to the AI to change targets when injured by another monster during an attack.

	New features since my first mod.
	1. The bot goes into pain a lot less often
	2. If the bot is attacking a target and is hit by
	another target then the bot attacks the new attacker
	(phew)
	3. The bot is three times stronger!

-- readme.txt, mybot11.zip


Stephen, the author of the mod, discussed this version on the quake-c mailing list, hosted by Robert Dean Rudeseal on seal industries.

His email, retrieved from the mailing list archive, appears to be a reply to Nathaniel Gorham and describes his MyBot as an extension of TMBot, like Nathaniel's DMBot.

There is evidence that both authors were active on this mailing list.


	check out mybot11.zip on ftp.cdrom.com
	Its a mod of the same tmbot your bot is based on.
	Ive done some interesting stuff with it.
	Its harder to kill (life 300), it goes into pain less (great for fighting
	fiends and ogres)
	Right now i have it so impulse 105 reports the bots health. but thats not
	in mybot11.zip
	It also recognizes when it has been hit.
	It is also set to say target terminated when it kills a target. But i
	noticed a bug.
	It reports target terminated when the target is lost from view :(.
	I was trying to set it to search for health when it has less then 50 out of
	its total 300 hit points, but i can't get it to do it.
	If you like it please tell me!

	If you use the stuff i did Or my idea, please tell me.
	and please  e-mail me updates on the bot before you release it publically
	:)!
	I might come up with some ideas!

-- Quake C Mailing List Archive, August 26 to August 28 1996 (archive)
https://web.archive.org/web/19990427113042/http://www2.csn.net/~rudeseal/quakec/quakeclist826-828.zip

The quake-c mailing list archive is incomplete, I'm not able to acquire all of it.

As such, no earlier or later versions of the MyBot mod were mentioned in the parts of the archive that survived. It is likely that the first version of the mod was also discussed and possible announced on there.





## MyBot v1.2

Then next version was released as mybot12.zip.

It contained the same files, although instead of a copy of the TMBot v1.0 readme file it contained a copy of the v1.1 readme (tmbot11.txt). It also included a shell casing model (shelcase.mdl), developed in this case by Steve Bond.

   1087 27 Aug  1996 readme.txt
 454388 27 Aug  1996 progs.dat
   5055 26 Aug  1996 Tmbot11.txt
 119255 25 Aug  1996 src.zip
   7060 10 Aug  1996 Shelcase.mdl

The presence of these files suggests that the bot was updated to use the more recent version of the TMBot v1.1 that was released on August 26th, and includes a modification bullet shell casing ejection, which was a popular addition at the time.

The oldest timestamp of files in the archive is August 27th, two days after the previous release, which we will take as the release date of the bot.

An important change listed in the changelog part of the readme file indicates that the bot will target any player in deathmatch mode.

This tiny change transforms the bot from helper into deathmatch opponent. Perhaps the first deathmatch bot.

	... sending the bot into deatchmatch [SIC] mode makes the bot target !any! player. Even you! (see how tough your bot really is)



## MyBot v1.3a

The next and penultimate version was released as mybot13a.zip and contains the same assortment of files.

 129311 28 Aug  1996 src.zip
   1704 28 Aug  1996 readme.txt
 454388 27 Aug  1996 progs.dat
   5055 26 Aug  1996 Tmbot11.txt
   7060 10 Aug  1996 Shelcase.mdl

The oldest timestamp in the file is August 28th, the next day, and is taken as the probable release date.

The readme makes it clear that the focus of the mod has shifted from a helper bot for single player, to an opponent for deathmatch play.

	... in deathmatch  the bot will appear in player start points and will attack you on sight! (automatically goes into deathmatch mode)

Step-by-step instructions are provided for starting a deathmatch game and spawning a bot to fight against.

	*****INSTRUCTIONS*****
	To play deathmatch against the bot,
	while the demo is playing, bring down the console (~),
	then type DEATHMATCH 1
	then type MAP "MAPNAME"    (eg: e1m2)
	the e1 represents the episode 1
	and m2 represents the  second mission

The important changes in this release are the faster movement and firing by the bot (no doubt to increase its difficulty) and the automatic respawning of the bot after it dies or is killed in deathmatch.

The latter seems to be a programming triumph by the developer as it is stated in all capitals.

	THE BOT ACTIVATES AUTOMATICALLY AND RESPAWNS IN THE PLAYER SPOTS WHEN IT IS KILLED



## MyBot v1.6

The next and final release of the bot was in the file mybot16.zip.

This release included the same files although did not include a zip file of the source code. This is surprising. Was it intentional because of the early success of the bot, or an accidental omission?

Also, the readme file was renamed "mybot14.txt" suggesting that perhaps a version 1.4 was publicly released or used as a private beta release, although no record of a "mybot14.zip" can be found.

   7060  2 Sep  1996 Shelcase.mdl
   2003 27 Jul  1996 mybot14.txt
 458508 27 Jul  1996 progs.dat
   5040 23 Jul  1996 Tmbot11.txt

The oldest timestamp of files the archive is September 2nd 1996. This matches the FTP timestamp from the archive of cdrom.com/pub/idgames2/quakec/bots/ and can be taken as the release date.

	mybot16.txt            02-Sep-96 15:52     1k
	mybot16.zip            02-Sep-96 15:52   139k

The changelog in the readme file highlights important additions for deathmatch, including the ability to compete against more than one bot at a time.

	... multiple bots allowed!

The bot AI was also improved allow it to seek out and acquire additional health and armor during a deathmatch fight, and to fire its weapon while moving.

	bot can pick up health and armour
	bot searches for health while no enemys targeted
	moves WHILE FIRING!

Interestingly, the readme now lists 7 tests of the bot, suggesting that a small community had developed around the releases and were sending Stephen feedback.

	testers:
	FRAGNSTIN
	darkvampirehunter
	evilive
	fragnstin
	macdaddy
	tasslehoff
	nightpup

The feedback was probably private, e.g. direct via email. I cannot find any discussion of the mod on usenet and no reference to the testers in the archive of the quake-c mailing list that survived.

Starting a deathmatch game, the bot can be added by issuing the command "impulse 100".

This spawns one bot that uses the Enforcer model and shoots laser bots.

Unlike the Enforcer monster, the bot fires many laser bots at once and at a faster rate. It also appears to move faster, perhaps running after the player.

The bot can be gunned down and will become deactivated once killed, requiring a new bot to be added to the game. I did not see it respawn by itself, this may be a single player feature.

Usefully, you can issue the command multiple times to add more than one bot to the game and the bots will fight each other as well as you.

This may have been Stephen's only publicly released Quake mod. It does not appear that any subsequent releases of this or other mods were made and no one appears to have picked up where the MyBot left off.


## Relevant Timeline

* QuakeC source code v1.01, qcc.tar.gz, July 25, 1996.
* HoloSelf v1.0, holo1.zip, August 11, 1996.
* HoloSelf v2.0, holo2.zip, August 14, 1996.
* TMBot v1.0, tmbot1.zip, August 22, 1996.
* DMBot v1.0, dmbot1.zip, August 24, 1996.
* MyBot v1.0, mybot.zip, August 24 1996.
* MyBot v1.1, mybot11.zip, August 25 1996.
* TMBot v1.1, tmbot11.zip, August 26, 1996.
* MyBot v1.2, mybot12.zip, August 27 1996.
* MyBot v1.3a, mybot13a.zip, August 28 1996
* MyBot v1.6, mybot16.zip, September 02 1996.


## References

* [Quake C Mailing List Archives](https://web.archive.org/web/19990427113042/http://www2.csn.net/~rudeseal/quakec/list.html), seal-industries.com (archive)
* [Quake C Mailing List Archive](https://web.archive.org/web/19990427113042/http://www2.csn.net/~rudeseal/quakec/quakeclist826-828.zip), August 26 to August 28 1996 (archive)
* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (internet archive)






