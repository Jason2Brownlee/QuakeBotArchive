# RoamBot

The RoamBot is a deathmatch bot released by Carson Sutton aka "Crimson" based on the BGBot.

As it's name suggests, it adds a roaming behavior to the bot, but it is important because it was used as a starting point for other bots. Bots such as the SamBot by Sam Stephens and DoomBot and bot movement code (called norse_movetogoal) developed and shared by Roscoe Sincero, and all the bots that further build on their work.

There appears to be only a single version of the RoamBot released as "roambot1.zip".

The archive contains the compiled game code (progs.dat), a readme file (roambot1.txt), a model file and wave file for ejecting shells from the shotgun, and a zip file for the source code (src.zip).

```
   4167  3 Sep  1996 roambot1.txt
 447772  3 Sep  1996 progs.dat
 116631  3 Sep  1996 src.zip
   2376 21 Aug  1996 SHELLHIT.WAV
   7060 10 Aug  1996 SHELCASE.MDL
```

The readme file lists the release date as September 3rd 1998 and this matches the timestamps of files in the archive.

```
Title    : roamBot
Filename : roambot1.zip
Version  : 0.9
Date     : 96/9/3, 12:15am MDT.
Author   : CARSON SUTTON ("Gwynn" on irc, "Crimson" to quake victims)
```

This also matches the FTP file timestamp on cdrom.com. The release was not announced on Usenet.

```
	roambot1.txt           03-Sep-96 00:49     3k
	roambot1.zip           03-Sep-96 00:50   251k
```

The version listed in the readme file is 0.9, although the release archive suggests 1.0. It is possible that other versions were created and not released or were released and there is no surviving record.

RoamBot was an extension of the BGBot v1.2, giving clear credit to the author of the BGBot "Punisher" (Robert DeFilppo) at the top of the readme file and in the description of the modification itself.

>	Punisher asked for better roaming AI for the basic bot design...I thought I'd take a crack at it with this very blunt hack.  Essentially BG Bot v1.2 with more unpredictable and intelligent roaming behaviour ...

-- roambot1.txt

The v1.2 release of the BGBot was made on September 1st 1996, meaning that the RoamBot was developed and released within two days.

The roaming behaviour is described at length in the readme.

In addition to better roaming, it offers better AI behavior such as target management, the ability to run and turn, support for doors and teleporters, and the ability to give up after a time limit of five seconds. The mod also supports ejecting shotgun shells "for fun".

```
- Bot follows its OWN target entity while roaming,
  thus direction of roaming bot not tied to
  creator or (last) target entity.  "Leader" entity
  assigned pseudo-random directional and "dead end"
  detection routines.  Standard turn left, turn right
  AI too predictable, so bot pulls a u-turn or heads
  off-center at obstacles.
- Bot RUNS instead of walks while roaming.  Makes
  them much more effective.
- Bot will turn around (180) at ledges/obstacles
  after timeout.
- Bot will go through doors and teleporters.
- Bot only hunts detected items if visible.
- Bot gives up hunting target after 5 secs. if
  no longer visible.
- Better heath, less idle noise, a little near-sighted
  (for game speed with more bots), etc.
- Added shotgun shells ejecting just for fun.
```

-- roambot1.txt



The roaming behavior is changed from "monster AI" to a more sophisticated procedure that selects entities close to the bot as targets to be hunted.

>	In this hack I simply added an independent goal entity for the bot to follow around when it can't find any items or targets. This "leader" simply moves around ahead of the bot, mapped onto the nearest obstacle along its path (wall, player, etc.), and decides on a new direction based on a not-quite-random heading change or timeout when the bot is a certain distance away.

-- roambot1.txt

I don't believe Carson released any other bots or Quake bots more generally before or after this contribution.



## Release Timeline

* Roambot v1.0, roambot1.zip, September 03 1996.



## References

n/a
