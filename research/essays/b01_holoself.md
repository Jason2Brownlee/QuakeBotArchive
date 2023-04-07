# HoloSelf

The "HoloSelf" mod is not a quake bot, but is an import precursor to some of the very first quake bots.



## HoloSelf v1.0

HoloSelf is a Quake modification for multiplayer that allows you to create a hologram of yourself briefly to fool other players.

	Adopted from the holoduke idea, this mod allows you to create a clone image of yourself and briefly fool your opponents.

-- Holo.txt, from holo1.zip.

It was inspired by the hologram in Duke Nukem 3D called Holoduke that operated in the same way.

The hologram use cells (for the lighting gun) and will only last 10 seconds before disappearing.

This mod was developed and released by Perecli Manole aka "Bort".

> HoloSelf QuakeC Mod v1.0                   8/10/96
> By: Perecli Manole AKA: Bort

-- Holo.txt, from holo1.zip.

The first version was distributed in the file holo1.zip on the public FTP site ftp.cdrom.com under the directory /pub/quake/misc/ that later became /pub/idgames2/quakec/misc/.
(how do you know this?)

The release included the source code (Holo.qc), a compiled game code (progs.dat) file and a readme file (Holo.txt). The readme is dated August 10th 1996, although the timestamps of the files in the archive is August 11th which is taken as the release date.

      642 11 Aug  1996 Holo.txt
   412168 11 Aug  1996 progs.dat
     2647 11 Aug  1996 Holo.qc

-- holo1.zip

The hologram works by creating a new entity when he impulse command is issued. Ten cells (ammo for the lightning) gun are required to create the hologram and are deduced from the players ammo. The created entity uses the players model and a single specific frame of animation from the model. The entity does not think for ten seconds after which it is removed from the game.



## HoloSelf v2.0

An updated version was distributed in the file holo2.zip.

This release contained the same files although is dated August 14th 1996. It was uploaded to ftp.cdrom.com/pub/idgames2/quakec/misc/ and timestamped "15-Aug-96 00:01".

The readme was updated to reflect the change to v2.00, but the release date was not changed and the nature of the change was not described.

     1094 14 Aug  1996 Holo.txt
   412744 14 Aug  1996 progs.dat
     3440 14 Aug  1996 Holo.qc

-- holo2.zip

Reviewing a diff of the "Holo.qc" file with the same file in the previous version reveals the change.

Normally, when a player is still in a multiplayer game, his model moves slightly to show signs that the game is running. The first version of the HoloSelf mod created a player model that does not move, and instead remains unnaturally still.

Version 2.00 of the mod updates the created hologram to use the players standing animation, making the hologram more believable to other players.

The mod eventually became "Bort's QuakeC Mod" that included the hologram as well contributions from other mods other changes like the grappling hook (morning star).

The HoloSelf mod does provide a good starting point for a bot as it is a deathmatch modification that uses a command to create a new player-like entity. Seemingly, all that is required is to animate the entity with some real thinking, at least that is perhaps how the first bot developers viewed the situation.

It was used as the basis for some of the very first bots, namely the TMBot, MyBot, and the DMBot.

I'm curious how he got the word out about the release. I could not find any discussion on the usenet archives.

## Relevant Timeline

* QuakeC source code v1.01, qcc.tar.gz, July 25, 1996.
* HoloSelf v1.0, holo1.zip, August 11, 1996.
* HoloSelf v2.0, holo2.zip, August 14, 1996.
* TMBot v1.0, tmbot1.zip, August 22, 1996.


## References

* [http://www.cdrom.com/pub/idgames2/quakec/misc/](https://web.archive.org/web/19961225222607/http://www.cdrom.com/pub/idgames2/quakec/misc/) (internet archive)
* [holo1.zip](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/bin/holo1.zip)
* [holo2.zip](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/bin/holo2.zip)




