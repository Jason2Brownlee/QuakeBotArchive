# Wisp

The Wisp is a singleplayer helper bot that spawns a ball of lava that kills monsters with lightning strikes.

A fun aspect of the bot is that you can ride the lava ball as it floats around the level.

The Wisp mod was released by Iikka Paavolainen as the file "wisp.zip". The archive contained the source code (.qc files) and a readme (wisp.txt).

  2417  1 Sep  1996 WISP.TXT
 14146  1 Sep  1996 WISP.QC
 18503 31 Aug  1996 DEFS.QC
   472 26 Aug  1996 PROGS.SRC
 25269 26 Aug  1996 WEAPONS.QC

The readme file does not list a release date, although the public FTP timestamp is listed as August. 31st 1996.

	wisp.txt               31-Aug-96 14:31     2k
	wisp.zip               31-Aug-96 14:31    15k

-- [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived December 25 1996)

The oldest timestamp for files in the zip is September 1st 1996, which makes senses given differences in time zones between the server and the Iikka's local machine.

Iikka also announced the mod on the rec.games.computer.quake.editing Usenet group on August 31st with the title "Quake flying bot at ftp.cdrom.com".

The mod is described as a flying lava ball helper bot that you can also ride.

	Wisp is an experimental flying bot/toy that can be used against monsters and players, and you can even ride with it through the air. It flies semi-intelligently hunting for targets; my main interest was to try to get a good flight model/intelligence when I started coding this bot. It can also be frozen or recalled.

-- [Quake flying bot at ftp.cdrom.com](https://groups.google.com/g/rec.games.computer.quake.editing/c/7BxpmZzmsnc/m/4UFJVAw5AbcJ), rec.games.computer.quake.editing, 31 Aug 1996.

The bot is spawned in singleplayer as a lava ball that floats around near the player.

As you approach enemies, the ball selects them as a target and fires a lightning bolt until the enemy is dead.

The bot does get stuck and cannot easily ride elevators, but can easily be teleported to the current position or deactivated and reactivated at the current position.

It works well, giving you a sense of power as you walk through the level as enemies are smited from the sky for you.

The ball itself cannot be damaged by the player or by enemies, which is fine, but might be more fun if it could be killed.

Riding the ball is interesting. You sit on top as it fly's around the room zapping enemies. You cannot jump off, instead you must reissue the same command to return to normal walking.

The source files must be added to the quake game source code v1.01 and compiled before use.

Interestingly, it seems that the bot was developed independently and does not extend any other bot prior project at the time.

Reviewing the code, all of the logic is stored in about 330 lines of the file wisp.qc with very minor addition to weapons.qc to allow the bot to be controlled via impulse commands.

Iikka Paavolainen did not go on to release further versions of the wisp or other Quake mods, at least not publicly.

Other mods did add Wisp into their grab bag mods that combined many mods. Examples include KALQuake by Kenneth Livingston, Olofs QC Collection by Olof Svensson, and Glyde Quake by Randy D. Shoultz.



## Relevant Timeline

* MyBot v1.2, mybot12.zip, August 27 1996.
* MyBot v1.3a, mybot13a.zip, August 28 1996.
* BGBot v1.0, bgbot1.zip, August 29 1996.
* BGADMBot v1.01, bgadm101.zip, August 31 1996
* Wisp, wisp.zip, August 31 1996.


## References

* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (archived December 25 1996)
* [Quake flying bot at ftp.cdrom.com](https://groups.google.com/g/rec.games.computer.quake.editing/c/7BxpmZzmsnc/m/4UFJVAw5AbcJ), Iikka Paavolainen, 31 Aug 1996.