# BGADM Bot

The BGADM Bot bot was created by George Leithner aka "Detour" as an extension to the BGBot.


## BGADMBot v1.0

George released the first version of the BGADMBot as bgadmbot.zip by uploading it to cdrom.com.

No reference to the the original version cn be located.

We know of its existence because George added a note to the release of hte second version to not download the first version and that he is attempting to have it removed.

>	DO NOT DOWNLOAD "BGADMBOT.ZIP"...I am trying to get the administration at cdrom.com to delete it.

-- [BGADMbot V.101 - One Player Deathmatch!](https://groups.google.com/g/rec.games.computer.quake.misc/c/k-qn9Kkc2hc/m/6xgvnP1s4dAJ), rec.games.computer.quake.misc, 1 Sept 1996.

A similar note is provided near the top of the readme for the v1.01 release:

>	*** NOTE *** THIS VERSION FIXES A MAJOR BUG IN VERSION 1.0..PLEASE DELETE ALL COPIES OF THAT VERSION!

It was a deathmatch bot and its capabilities of this release were summarized separately in the readme file for the subsequent release:

```
Version -1.00  BGADMBOT
      Designed for a one player deathmatch environment
      If hit, will sometimes get pissed and attack the attacker.
      Respawning(after death, keeps the old bots info and respawns it)
      250 health for bots and players - to keep it more interesting and
              challenging
```

-- bgadm101.txt

Sadly, the webmasters of cdrom.com must have carried out his request before the release could be distributed elsewhere.

We can only guess at the release date of this first version. At the latest, it was released on the same day as the next release, e.g. August 31st 1996, although was probably a day before on the 30th.



## BGADMBot v1.01

The second release of the BGADMBot was released as the file bgadm101.zip.

The archive contains the game source code (.qc files) and a readme file (bgadm.txt).

A compiled version of the game code was not distributed. This means that the user must acquire a compiler, compile the code, and create the mod directory before being able to play the bot. This is a higher than average barrier to entry and may have meant few people tried it out.

```
  4466 31 Aug  1996 BGADM.TXT
  5499 31 Aug  1996 BOT.QC
 24231 31 Aug  1996 BOTAI.QC
   922 31 Aug  1996 PROGS.SRC
 34458 31 Aug  1996 CLIENT.QC
   685 31 Aug  1996 IMPULSE2.QC
  2061 31 Aug  1996 BOT.H
 23785 31 Aug  1996 DEFS.QC
 16054 30 Aug  1996 TRIGGERS.QC
  8221 28 Aug  1996 PLATS.QC
 11507 28 Aug  1996 WORLD.QC
 30289 28 Aug  1996 ITEMS.QC
 18225 28 Aug  1996 PLAYER.QC
  6374 28 Aug  1996 SUBS.QC
   690 28 Aug  1996 BOT_EXT.QC
 24072 18 Aug  1996 WEAPONS.QC
  7945 25 Jul  1996 FISH.QC
 18750 25 Jul  1996 HKNIGHT.QC
   237 25 Jul  1996 JCTEST.QC
  9966 25 Jul  1996 KNIGHT.QC
 15760 25 Jul  1996 MISC.QC
 10373 25 Jul  1996 MODELS.QC
  5034 25 Jul  1996 MONSTERS.QC
 15129 25 Jul  1996 OGRE.QC
  9675 25 Jul  1996 OLDONE.QC
  8131 25 Jul  1996 SHALRATH.QC
 13104 25 Jul  1996 SHAMBLER.QC
 10121 25 Jul  1996 SOLDIER.QC
   512 25 Jul  1996 SPRITES.QC
  7350 25 Jul  1996 TARBABY.QC
 11085 25 Jul  1996 WIZARD.QC
 20635 25 Jul  1996 ZOMBIE.QC
 15268 25 Jul  1996 AI.QC
  1776 25 Jul  1996 AMTEST.QC
 12808 25 Jul  1996 BOSS.QC
  3051 25 Jul  1996 BUTTONS.QC
  6415 25 Jul  1996 COMBAT.QC
 10279 25 Jul  1996 DEMON.QC
  9917 25 Jul  1996 DOG.QC
 17774 25 Jul  1996 DOORS.QC
 11090 25 Jul  1996 ENFORCER.QC
  7617 25 Jul  1996 FIGHT.QC
```

The readme does not list a release date. The oldest timestamps for files within the archive suggest a release date on or after August 31st 1996.

The timestamps for the files the archive of cdrom.com/pub/idgames2/quakec/bots/ confirm this date.

```
bgadm101.txt           31-Aug-96 19:42     4k
bgadm101.zip           31-Aug-96 19:44   115k
```

George also announced on Usenet in the rec.games.computer.quake.misc group with the title "BGADMbot V.101 - One Player Deathmatch!" on September 1st, one day later.

```
BG Automatic DeathMatch opponent

Deathmatch without other players? It's now possible with the help of
bots!! These bots act just like regular Deathmatch players(only
slightly stupider)..Based on TMbot and BGbot, these bots have
primitive AI, but they still whoop butt...Spawn about 8 or more of
these babies in your favorite level, and you will be challenged!

[...]

The file to get is BGADM101.ZIP from

ftp://cdrom.com
```

-- [BGADMbot V.101 - One Player Deathmatch!](https://groups.google.com/g/rec.games.computer.quake.misc/c/k-qn9Kkc2hc/m/6xgvnP1s4dAJ), rec.games.computer.quake.misc, 1 Sept 1996.

The readme describes the mod as an extension of the BGBot and gives due credit to the prior bots TMBot and DMBot.

BGADM is an acronym that stands for the "BG Automatic DeathMatch Opponent", suggesting both that it is an extension of the BG Bot, and that it is specifically designed to be an opponent for deathmatch as opposed to a helper bot for singleplayer and deathmatch like the TMBot and DMBot.

The goal stated in the readme is a deathmatch opponent, to transform deathmatch into a singleplayer game style.

```
I wanted instant, automatic, halfway smart deathmatch opponents
for one player - ME! This modification of Punisher's BGbot takes the bots
and alters them for a "pseudo" deathmatch environment.  Now you can have a
full fledged deathmatch - by yourself!
```

-- bgadm101.txt

The release fixes a seemingly fatal error the author made in the first version. Really, the bug it just caused the bot to spawn where it died, rather than randomly.

```
Version -1.01  Due to a last minute housekeeping task, I caused a bug
               which would respawn a bot in the place it died, instead
               of the deathmatch starts..This preety much made the game
               lame..THIS BUG HAS BEEN FIXED!!
               If you have the old version,please delete it..
```

-- bgadm101.txt

It may be one of the first deathmatch opponent focused QuakeC mods, and is claimed as such by the author "Detour" in a Usenet post in late September 1996.

>	... Like I said, ive made these changes on BGBOTS....But I gave up bot editing due to lack of time (See the FIRST deathmatch bots: BGADM)

-- [Where to find Bot Editing](https://groups.google.com/g/rec.games.computer.quake.editing/c/5f5Lczws_yc/m/gqwQKFHKRQsJ), rec.games.computer.quake.editing, 29 Sept 1996.

Playing the BGADMBot feels like deathmatch play.

A bot can be spawned into a deathmatch style game. The bot uses the enforcer model and can walk around, pick up items and shoot and kill the player.

Spawning more than one bot is possible and bots will target and fight each other.

The AI is very basic, where the bots will stand still once they have selected a target and shoot until either they or their target is killed. Further, the bots get stuck easily and are unable to jump off ledges or navigate out of rooms.

George did have ambition to continue, listing a number of future enhancements he would like to see in the readme file.

```
*FUTURE ENHANCEMENTS*
I couldn't get it to rank the bots.  I did however make some modifications
      which will make it easier to do bot rankings.
The AI could always be improved.  Sometimes these bots will do stupid
      things.
I'm working on random spawning..this will reduce telefrags and also add
      a little spice to the game...Currently its using the SelectSpawnPoint
      for deathmatch info
Will I ever improve anything? dunno.  The little lady is getting jealous
      of my puter :)
```

-- bgadm101.txt

Other than receiving a credit in BGBot v2.0, it does not appear that George continued his public Quake bot or mod development efforts.



Relevant Timeline

* MyBot v1.2, mybot12.zip, August 27 1996.
* MyBot v1.3a, mybot13a.zip, August 28 1996.
* BGBot v1.0, bgbot1.zip, August 29 1996.
* BGADMBot v1.01, bgadm101.zip, August 31 1996
* BGBot v1.1, bgbot1.zip, September 01 1996.
* BGBot v1.2, bgbot12.zip, September 01 1996.
* MyBot v1.6, mybot16.zip, September 02 1996.
* BGBot v1.25, bgbot125.zip, September 03 1996.
* BGBot v1.3, bgbot13.zip, September 03 1996.
* BGBot v1.5, bgbot15.zip, September 06 1996.
* BGBot v1.6, bgbot16.zip, September 13 1996.
* BGBot v1.20a, bgbot20a.zip, September 29 1996.

References

* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (internet archive)
* [BGADMbot V.101 - One Player Deathmatch!](https://groups.google.com/g/rec.games.computer.quake.misc/c/k-qn9Kkc2hc/m/6xgvnP1s4dAJ), rec.games.computer.quake.misc, 1 Sept 1996.
* [Where to find Bot Editing](https://groups.google.com/g/rec.games.computer.quake.editing/c/5f5Lczws_yc/m/gqwQKFHKRQsJ), rec.games.computer.quake.editing, 29 Sept 1996.

