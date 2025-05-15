# Terminator Bot

The **Terminator Bot** or "TERMINATOR" is a client-side Quake bot developed by Olivier Montanuy.

It is deathmatch assistant, rather than a deathmatch opponent, e.g. a helper bot.

## Early Versions

There may have been earlier public versions of the bot that are not currently know.

The bot was hosted on <http://www.ens.fr/~cridlig/bot/> which was not archived, meaning we have no record of releases that may have been present.

Olivier Montanuy was also involved in the "Unofficial Quake Specs" and "Quake C Specs" documentation projects from an early stage.

For example:

> August 8th 1996
>
> Quake C Specs Updated\
> Up to version 3 now, by Olivier Montanuy, available, as always on the Quake C Page.

-- https://www.bluesnews.com/archives/august96.html

These were hosted on <http://www2.csn.net/~rudeseal/quakec/> and <http://www.sni.net/~rudeseal/quakec/> which may also have hosted early versions of the bot. Unfortunately, neither of these sites were archived.

These projects eventually migrated to <http://www.gamers.org/dEngine/quake/> along with the bot at <http://www.gamers.org/dEngine/quake/Qbot>.


## Version 0.7

This version of the bot was released as `trmbot07.zip` (binary).

Version 0.7 was mentioned via a link in the announcement of v0.8 on Blues News October 17th 1996 (see below)

> ...
> Terminator 'bot 0.7 (286 KB)	The executable for Win95, SUN O/S and AIX.

A local copy of the files was hosted and linked:

* ftp://bluesnews.com/pub/client_bots/trmbot07.zip

Sadly, this file was not archived.


The source release for v0.8 includes a `bot.txt` that (mistakenly?) lists version 0.7.

```text
             TERMINATOR

     a Quake Bot and Deathmatch assistant
                  by
      Olivier.Montanuy@wanadoo.fr


	    (Version 0.7)
```

-- botsrc08.zip/bot.txt




## Version 0.8

This version of the bot was released as `trmbot08.zip` (binary) and `botsrc08.zip` (source).

It was probably released on October 14 1996 based on the date of files in the binary release.

It was uploaded to cdrom.com (and mirrored) into the directory `/idgames2/utils/network_serial/client_bots/` on November 17 1996.

```text
[TXT] trmbot08.txt                                       1996-10-17 20:00  9.3K
[   ] trmbot08.zip                                       1996-10-17 20:00  127K
```

-- https://www.gamers.org/pub/games/idgames2/utils/network_serial/client_bots/

Version 0.8 was mentioned on Blues News October 17th 1996:

> Client Side 'Bot II
>
> Joel Baxter, AKA lemurboy, wrote in to point out that the Terminator wasn't as I wrote, the first client-side 'bot, since AE_Playmate, and C/S Bot, came before it. D'oh! True enough, stories about each of these are actually buried in Blue's archives (BTW, gonna add a search feature soon). I had a bad day today (guess this is a good place to thank Matt Armistead for pointing out the six typos in one story and Jeff Borenstein for catching a bad link in another). While we're clearing the client 'bot air, there's also ZaphBot, based on C/S, born October 8, 1996. It does seem fair to say that the Terminator is probably the most advanced of these client 'bots (I'll wait for the corrections on that...). Here's the corrected story:
>
> The Terminator 'bot, the most advanced client-side 'bot to date, has been created by Olivier Montanuy (Thanks to Joost Schuur for letting me know). Client-side means no Quake C is required, it just connects to the game as a player. There are also commands that servers can use to disallow such 'bots. All in all, the kind of terrific effort we expect from Olivier. Here's the text file. You can also play in "proxy mode" where the 'bot connects to the game, and you connect to the 'bot, which allows the 'bot to govern some of your "reflexes." As Whaleboy of QuakeX points out:
>
>    "didja know what?? This BOT supports proxies!! In other words, I don't have to disconnect from my LAN and connect via modem on my main machine to play Quake anymore... I just put it on my server and away I go! :)"
>
> Download the Terminator from Blue's FTP site:
>
> Terminator 'bot 0.7 (286 KB)	The executable for Win95, SUN O/S and AIX.\
> Terminator 'bot 0.8 (126 KB)	The executable for Win95 only.\
> Source Ver. 0.8 (129 KB)	The source code.
>
> Olivier's comment on the source code:
>
>    "You will find it very confusing. It is a temporary release, most comments are missing."

-- [http://bluesnews.com/oct2.html](https://web.archive.org/web/19970204064939/http://bluesnews.com/oct2.html) (archived)

A local copy of the files was hosted and linked:

* ftp://bluesnews.com/pub/client_bots/trmbot07.zip
* ftp://bluesnews.com/pub/client_bots/trmbot08.zip
* ftp://bluesnews.com/pub/client_bots/botsrc08.zip

Sadly, this file was not archived.

Contents of the binary:

```text
-rw-rw-r--  0 0      0      275352 13 Oct  1996 bot.exe
-rw-rw-r--  0 0      0        9568 14 Oct  1996 bot.txt
```text

The readme contains no release date or change log in formation.

Contents of the source:

```text
-rw-rw-r--  0 0      0        9348 23 Sep  1996 bot.txt
-rw-rw-r--  0 0      0       66656 13 Oct  1996 BOT.IDE
-rw-rw-r--  0 0      0         398 13 Oct  1996 Makefile
-rw-rw-r--  0 0      0        6266 13 Oct  1996 udp.h
-rw-rw-r--  0 0      0        2093 22 Sep  1996 qkthink.h
-rw-rw-r--  0 0      0        3505 20 Sep  1996 qkptomsg.h
-rw-rw-r--  0 0      0        1135 13 Oct  1996 qkpto.h
-rw-rw-r--  0 0      0         728 14 Sep  1996 qkpak.h
-rw-rw-r--  0 0      0       23824  2 Oct  1996 common.c
-rw-rw-r--  0 0      0        3183  1 Oct  1996 qkmsg.h
-rw-rw-r--  0 0      0        2180 29 Sep  1996 qkmove.h
-rw-rw-r--  0 0      0        3830 29 Sep  1996 qkmath.h
-rw-rw-r--  0 0      0        2996 29 Sep  1996 qkentbot.h
-rw-rw-r--  0 0      0        2798 29 Sep  1996 qkent.h
-rw-rw-r--  0 0      0         818 27 Sep  1996 qkdta.h
-rw-rw-r--  0 0      0        5720 30 Sep  1996 qkdefs.h
-rw-rw-r--  0 0      0        6176 13 Oct  1996 qkbspprt.h
-rw-rw-r--  0 0      0        5963 29 Sep  1996 qkbspdef.h
-rw-rw-r--  0 0      0        1757 13 Oct  1996 qkbsp.h
-rw-rw-r--  0 0      0         738  2 Sep  1996 qkbotpto.h
-rw-rw-r--  0 0      0        2365 14 Sep  1996 qkbotmsg.h
-rw-rw-r--  0 0      0        3985 29 Sep  1996 qkbot.h
-rw-rw-r--  0 0      0        2266 11 Sep  1996 files.h
-rw-rw-r--  0 0      0        3117 27 Sep  1996 defines.h
-rw-rw-r--  0 0      0        4994 31 Aug  1996 data.h
-rw-rw-r--  0 0      0        8676  6 Oct  1996 common.h
-rw-rw-r--  0 0      0       24344 13 Oct  1996 udp.c
-rw-rw-r--  0 0      0        5527 30 Sep  1996 test.c
-rw-rw-r--  0 0      0       30488 13 Oct  1996 qkthink.c
-rw-rw-r--  0 0      0       31688 13 Oct  1996 qkpto.c
-rw-rw-r--  0 0      0       10413 26 Sep  1996 qkpak.c
-rw-rw-r--  0 0      0       27132 29 Sep  1996 qkmsgbot.c
-rw-rw-r--  0 0      0       10371 26 Sep  1996 qkmsg.c
-rw-rw-r--  0 0      0        9517 29 Sep  1996 qkmove.c
-rw-rw-r--  0 0      0        9083 30 Sep  1996 qkmath.c
-rw-rw-r--  0 0      0       11106 13 Oct  1996 qkent.c
-rw-rw-r--  0 0      0        4110 22 Sep  1996 qkdta.c
-rw-rw-r--  0 0      0        5373 13 Oct  1996 qkclient.c
-rw-rw-r--  0 0      0       23591 13 Oct  1996 qkbspprt.c
-rw-rw-r--  0 0      0       14439 13 Oct  1996 qkbsp.c
-rw-rw-r--  0 0      0       27764 13 Oct  1996 qkbot.c
-rw-rw-r--  0 0      0       12584 27 Sep  1996 data.c
-rw-rw-r--  0 0      0        3292 13 Sep  1996 qkmsgbot.h
-rw-rw-r--  0 0      0         118 13 Oct  1996 qkbspway.h
```

Known links for this version of the bot follow.

Binary:

* ftp://bluesnews.com/pub/client_bots/trmbot08.zip
* http://bluesnews.com/files/trmbot08.zip
* http://ftp.gamers.org/pub/games/idgames2/utils/network_serial/client_bots/trmbot08.zip
* http://ftp.sunet.se/pub/pc/games/idgames2/utils/network_serial/client_bots/trmbot08.zip
* http://ftp.telepac.pt/pub/idgames2/utils/network_serial/client_bots/trmbot08.zip
* http://quakemecca.simplenet.com/files/downloads/files/downloads/trmbot08.zip
* http://quakemecca.simplenet.com/files/downloads/trmbot08.zip
* http://redwood.gatsbyhouse.com/files/trmbot08.zip
* http://redwood.stomped.com/files/trmbot08.zip
* http://web.ukonline.co.uk/Members/jc.burton/trmbot08.zip
* http://www.bluesnews.com/files/files/trmbot08.zip
* http://www.bluesnews.com/files/trmbot08.zip
* http://www.gameaholic.com/deicide/download.cgi?/utils/network_serial/client_bots/trmbot08.zip
* http://www.gamers.org/pub/games/idgames2/utils/network_serial/client_bots/trmbot08.zip
* http://www.gamers.org/pub/idgames2/utils/network_serial/client_bots/trmbot08.zip
* http://www.time2quake.com/filez/utils/network_serial/client_bots/trmbot08.zip
* https://www.quaddicted.com/files/idgames2/utils/network_serial/client_bots/trmbot08.zip
* https://www.quaddicted.com/files/tools/idgames2_utils/network_serial/client_bots/trmbot08.zip

The binary also appears on the "Quake 'em" CD in the directory `/QUAKE/PROGRAMS/TRMBOT08/`.

Source:

* ftp://bluesnews.com/pub/client_bots/botsrc08.zip
* http://www.bluesnews.com/files/botsrc08.zip
* http://www.bluesnews.com/files/files/botsrc08.zip

## Version 0.9

This version of the bot was released as `trmbot09.zip` (binary).

It was probably released on November 04 1996, based on dates in the binary release.

Version 0.9 was mentioned on Blues News November 12th 1996:

> Terminator Updated
>
> There's a new version of Olivier Montanuy's cool client-side bot the Terminator. Client-side means that unlike QuakeC bots like the reaper, this bot doesn't need to be run off the server. It just logs into the game like an ordinary player. Here's the Terminator Bot Version 0.9. What's new:
Changes since version 0.8
>
> 	Not much, mostly bug fixes. The bug that plagged the Unix/Linux/WindozeNT version seems dead.  You can now customise the name and color of the bot, and in automatic mode, the bot will try to reconnect every minute (in case the server goes down).
>
> Thanks to Joe E. Powell for sending the word (yep he does stuff other than code QSpy... I even played him in QuakeWorld the other day!!).

-- [http://bluesnews.com/nov2.html](https://web.archive.org/web/19970204064756/http://bluesnews.com/nov2.html) (archived)

A local copy of the file was hosted and linked:

* ftp://bluesnews.com/pub/client_bots/trmbot09.zip

Sadly, this file was not archived.

Olivier announced that he had released the source code for his bot on Usenet.

It may have been for this version:

```text
Olivier Montanuy, 30 Nov 1996

I have released the sources of a Quake client/server bot
on htpp://www.ens.fr/~cridlig/bot/index.html
It compiles under various flavours of Unix, and even on
win95, but is now developped exclusively under Linux ;-)
FYI, a Quake bot is nothing more than an automatic player.
Not a great AI, but in proxy mode *you* provide the AI, and
the bot provides the reflexes. It's somewhat efficient.

Olivier Montanuy
recently converted to Linux (both for work and leisure).
```
-- [comp.os.linux.development.apps](https://groups.google.com/g/comp.os.linux.development.apps/c/B6JGX2YWlGc/m/L8447N3nlHYJ)

File content:

```text
-rw-rw-r--  0 0      0      276292  4 Nov  1996 bot.exe
-rw-rw-r--  0 0      0       11281  4 Nov  1996 bot.txt
```

The readme does not include a release date, but does include a changelog since 0.8:

```text
-------------------------
CHANGES SINCE VERSION 0.8
-------------------------

 Not much (I've not been able to work on it more than a few hours):
  - the Unix/Linux network initialisation bug is dead. RIP.
  - bot will react if you fire it with nail guns.
  - in -auto mode, if connect fails, the bot will try again every minute.
  - you can customise the name and color of the bot.
```

-- trmbot09.zip/bot.txt


Known links for this version of the bot follow:

* ftp://bluesnews.com/pub/client_bots/trmbot09.zip
* ftp://ftp.torget.se/pub/games/quake/quakec/trmbot09.zip
* http://bluesnews.com/files/trmbot09.zip
* http://lhx.clanpages.com/trmbot09.zip
* http://redwood.gatsbyhouse.com/files/trmbot09.zip
* http://redwood.stomped.com/files/trmbot09.zip
* http://www.bluesnews.com/files/files/trmbot09.zip
* http://www.bluesnews.com/files/trmbot09.zip
* http://www.calvarium.com/quakebots/trmbot09.zip
* http://www.gamers.org/dEngine/quake/Qbot/trmbot09.zip

## Version 0.91

This version of the bot was released as `trmbot09.tgz` (binary), and `botsrc09.zip` and `botsrc09.tgz` (source).

It was probably released on November 04 1996 based on the date of files in the binary release. This is the same date as the previous release. Either the previous release was updated/replaced with this release with the same filename or both releases occurred on the same day.

I think the latter (released on same day) as all versions of `trmbot09.zip` that I acquire are identical (same md5 hash).

Version 0.91 was mentioned on Blues News on December 27th 1996:

> Bot Mania
>
> Thanks to Jim "Howley" Rowley for the news that Cameron Newham has released his source code for the Eliminator Bot (124 KB) on his homepage. Also, while poking around for this, I noticed on the Terminator Bot Page that Olivier Montanuy has updated his client-side bot, the Terminator to version 0.91 (227 KB) here's the read me) which features bug fixes from version 0.9. Here's the source: zip (130 KB), or tar (114 KB).

-- [http://bluesnews.com/dec3.html](https://web.archive.org/web/19970204064650/http://bluesnews.com/dec3.html) (archived)

A copy of the files were hosted locally and linked, as follows:

* http://www.ens.fr/~cridlig/bot/
* http://bluesnews.com/files/trmbot09.tgz
* http://bluesnews.com/files/bot091.txt
* http://bluesnews.com/files/botsrc09.zip
* http://bluesnews.com/files/botsrc09.tgz

Thankfully, the files were archived.

Interestingly, although the release is noted as v0.91, the filenames are for v0.90.

Content of `trmbot09.tgz`:

```text
-rwxr-xr-x  0 olivier users   85772  4 Nov  1996 bot
-rwxr-xr-x  0 olivier users   11281  4 Nov  1996 bot.txt
```

The readme lists the version as 0.9 and lists changes since v0.8.

It is not clear what changed in this version.


Content of `botsrc09.zip`:

```text
-rw-rw-r--  0 0      0       11281  4 Nov  1996 bot.txt
-rw-rw-r--  0 0      0       23678 27 Oct  1996 qkbspprt.c
-rw-rw-r--  0 0      0       14480  3 Nov  1996 qkbsp.c
-rw-rw-r--  0 0      0       28585  4 Nov  1996 qkbot.c
-rw-rw-r--  0 0      0       12616 27 Oct  1996 data.c
-rw-rw-r--  0 0      0       23971  3 Nov  1996 common.c
-rw-rw-r--  0 0      0       24414  3 Nov  1996 udp.c
-rw-rw-r--  0 0      0        5712 27 Oct  1996 test.c
-rw-rw-r--  0 0      0       30489  3 Nov  1996 qkthink.c
-rw-rw-r--  0 0      0       31462 27 Oct  1996 qkpto.c
-rw-rw-r--  0 0      0       10413 26 Sep  1996 qkpak.c
-rw-rw-r--  0 0      0       27133 27 Oct  1996 qkmsgbot.c
-rw-rw-r--  0 0      0       10371 26 Sep  1996 qkmsg.c
-rw-rw-r--  0 0      0        9517 29 Sep  1996 qkmove.c
-rw-rw-r--  0 0      0        9083 27 Oct  1996 qkmath.c
-rw-rw-r--  0 0      0        6079 27 Oct  1996 qkclient.c
-rw-rw-r--  0 0      0        4149 27 Oct  1996 qkdta.c
-rw-rw-r--  0 0      0       11115 27 Oct  1996 qkent.c
-rw-rw-r--  0 0      0        6275 27 Oct  1996 udp.h
-rw-rw-r--  0 0      0        2093 22 Sep  1996 qkthink.h
-rw-rw-r--  0 0      0        3504 27 Oct  1996 qkptomsg.h
-rw-rw-r--  0 0      0        1135 13 Oct  1996 qkpto.h
-rw-rw-r--  0 0      0         728 14 Sep  1996 qkpak.h
-rw-rw-r--  0 0      0        3293 27 Oct  1996 qkmsgbot.h
-rw-rw-r--  0 0      0        3183  1 Oct  1996 qkmsg.h
-rw-rw-r--  0 0      0        8699  3 Nov  1996 common.h
-rw-rw-r--  0 0      0        3976 27 Oct  1996 qkmath.h
-rw-rw-r--  0 0      0        3249 21 Oct  1996 qkentbot.h
-rw-rw-r--  0 0      0        2798 29 Sep  1996 qkent.h
-rw-rw-r--  0 0      0         818 27 Sep  1996 qkdta.h
-rw-rw-r--  0 0      0        5751 22 Oct  1996 qkdefs.h
-rw-rw-r--  0 0      0         118  4 Nov  1996 qkbspway.h
-rw-rw-r--  0 0      0        6167 27 Oct  1996 qkbspprt.h
-rw-rw-r--  0 0      0        5954 27 Oct  1996 qkbspdef.h
-rw-rw-r--  0 0      0        1757 13 Oct  1996 qkbsp.h
-rw-rw-r--  0 0      0         970 25 Oct  1996 qkbotpto.h
-rw-rw-r--  0 0      0        2353 27 Oct  1996 qkbotmsg.h
-rw-rw-r--  0 0      0        3846 21 Oct  1996 qkbot.h
-rw-rw-r--  0 0      0        2266 11 Sep  1996 files.h
-rw-rw-r--  0 0      0        3552 27 Oct  1996 defines.h
-rw-rw-r--  0 0      0        4994 31 Aug  1996 data.h
-rw-rw-r--  0 0      0        2180 29 Sep  1996 qkmove.h
-rw-rw-r--  0 0      0       67378  4 Nov  1996 BOT.IDE
-rw-rw-r--  0 0      0          59  4 Nov  1996 qkbspway.c
```

Content of `botsrc09.tgz`:

```text
-rwxr-xr-x  0 olivier users   23971  4 Nov  1996 common.c
-rwxr-xr-x  0 olivier users   12616  4 Nov  1996 data.c
-rwxr-xr-x  0 olivier users   28585  4 Nov  1996 qkbot.c
-rwxr-xr-x  0 olivier users   14480  4 Nov  1996 qkbsp.c
-rwxr-xr-x  0 olivier users   23678  4 Nov  1996 qkbspprt.c
-rwxr-xr-x  0 olivier users      59  4 Nov  1996 qkbspway.c
-rwxr-xr-x  0 olivier users    6079  4 Nov  1996 qkclient.c
-rwxr-xr-x  0 olivier users    4149  4 Nov  1996 qkdta.c
-rwxr-xr-x  0 olivier users   11115  4 Nov  1996 qkent.c
-rwxr-xr-x  0 olivier users    9083  4 Nov  1996 qkmath.c
-rwxr-xr-x  0 olivier users    9517  4 Nov  1996 qkmove.c
-rwxr-xr-x  0 olivier users   10371  4 Nov  1996 qkmsg.c
-rwxr-xr-x  0 olivier users   27133  4 Nov  1996 qkmsgbot.c
-rwxr-xr-x  0 olivier users   10413  4 Nov  1996 qkpak.c
-rwxr-xr-x  0 olivier users   31462  4 Nov  1996 qkpto.c
-rwxr-xr-x  0 olivier users   30489  4 Nov  1996 qkthink.c
-rwxr-xr-x  0 olivier users    5712  4 Nov  1996 test.c
-rwxr-xr-x  0 olivier users   24414  4 Nov  1996 udp.c
-rwxr-xr-x  0 olivier users    8699  4 Nov  1996 common.h
-rwxr-xr-x  0 olivier users    4994  4 Nov  1996 data.h
-rwxr-xr-x  0 olivier users    3552  4 Nov  1996 defines.h
-rwxr-xr-x  0 olivier users    2266  4 Nov  1996 files.h
-rwxr-xr-x  0 olivier users    3846  4 Nov  1996 qkbot.h
-rwxr-xr-x  0 olivier users    2353  4 Nov  1996 qkbotmsg.h
-rwxr-xr-x  0 olivier users     970  4 Nov  1996 qkbotpto.h
-rwxr-xr-x  0 olivier users    1757  4 Nov  1996 qkbsp.h
-rwxr-xr-x  0 olivier users    5954  4 Nov  1996 qkbspdef.h
-rwxr-xr-x  0 olivier users    6167  4 Nov  1996 qkbspprt.h
-rwxr-xr-x  0 olivier users     118  4 Nov  1996 qkbspway.h
-rwxr-xr-x  0 olivier users    5751  4 Nov  1996 qkdefs.h
-rwxr-xr-x  0 olivier users     818  4 Nov  1996 qkdta.h
-rwxr-xr-x  0 olivier users    2798  4 Nov  1996 qkent.h
-rwxr-xr-x  0 olivier users    3249  4 Nov  1996 qkentbot.h
-rwxr-xr-x  0 olivier users    3976  4 Nov  1996 qkmath.h
-rwxr-xr-x  0 olivier users    2180  4 Nov  1996 qkmove.h
-rwxr-xr-x  0 olivier users    3183  4 Nov  1996 qkmsg.h
-rwxr-xr-x  0 olivier users    3293  4 Nov  1996 qkmsgbot.h
-rwxr-xr-x  0 olivier users     728  4 Nov  1996 qkpak.h
-rwxr-xr-x  0 olivier users    1135  4 Nov  1996 qkpto.h
-rwxr-xr-x  0 olivier users    3504  4 Nov  1996 qkptomsg.h
-rwxr-xr-x  0 olivier users    2093  4 Nov  1996 qkthink.h
-rwxr-xr-x  0 olivier users    6275  4 Nov  1996 udp.h
-rwxr-xr-x  0 olivier users     484  3 Nov  1996 makefile
```

The `bot.txt` and `BOT.IDE` files do not appear in this source `botsrc09.tgz` release although it does include a `makefile`.

No differences in the file content, although dates do not match between the two source releases.


Known links for this version of the bot follow.

trmbot09.tgz:

* http://bluesnews.com/files/trmbot09.tgz
* http://www.bluesnews.com/files/files/trmbot09.tgz
* http://www.bluesnews.com/files/trmbot09.tgz
* http://www.gamers.org/dEngine/quake/Qbot/trmbot09.tgz

botsrc09.zip:

* http://bluesnews.com/files/botsrc09.zip
* http://www.bluesnews.com/files/botsrc09.zip
* http://www.bluesnews.com/files/files/botsrc09.zip
* http://www.gamers.org/dEngine/quake/Qbot/botsrc09.zip

botsrc09.tgz:

* http://bluesnews.com/files/botsrc09.tgz
* http://www.bluesnews.com/files/botsrc09.tgz
* http://www.bluesnews.com/files/files/botsrc09.tgz
* http://www.gamers.org/dEngine/quake/Qbot/botsrc09.tgz


## Version 0.92

No information is known about this release, although it is speculated to exist given the existence of 0.91 and 0.93.


## Version 0.93

Version 0.93 was mentioned in text on Olivier Montanuy's personal webpage <http://perso.wanadoo.fr/montanuy/>:

> Changes since version 0.93
>
> I fixed a bug which prevented the bot to appear correctly in the list of quake servers. It actually appeared in the list, but using address 0.0.0.0 instead of it's real address, so your Quake client could not connect to it.
>
> I have provided some additional instructions for Windows 95 users, that should work also under Windows NT and Windows 98. But the recommended system for running the bot is Linux, since Windows is a TCP/IP nightmare.
>
> I have not modified the (rather stupid) AI of the bot. No time for this, sorry.

-- [http://perso.wanadoo.fr/montanuy/bot/index.html](https://web.archive.org/web/20010504115657/http://perso.wanadoo.fr/montanuy/bot/index.html) (archived)

Filenames or links for this version have not been located.

## Version 0.94a

Version 0.94b was mentioned in the readme file for v0.96:

```text
--------------------------
CHANGES SINCE VERSION 0.94a
--------------------------

 - bug fix to make SLIST usable
 - Improved IP aliasing support (fixed a bug that prevented the use of IP aliasing).
 - Possibility to modifiy the Ip address of the bot, considered as a fake Quake server.
```

-- [http://perso.wanadoo.fr/montanuy/bot/bot.txt](https://web.archive.org/web/20010508095204/http://perso.wanadoo.fr/montanuy/bot/bot.txt) (archived)

No files or links for this version have been located.

## Version 0.94b

Version 0.94b was mentioned in the readme file for v0.96:

```text
--------------------------
CHANGES SINCE VERSION 0.94b
--------------------------

 - removed a bug that prevented the printing of funky names
 - added a verbosity option, to print messages only when desired.
   printing messages during game play can make the bot slower.
```

-- [http://perso.wanadoo.fr/montanuy/bot/bot.txt](https://web.archive.org/web/20010508095204/http://perso.wanadoo.fr/montanuy/bot/bot.txt) (archived)

No files or links for this version have been located.

## Version 0.95

Version 0.95 was mentioned in the readme file for v0.96:

```text
--------------------------
CHANGES SINCE VERSION 0.95
--------------------------
 - small bug fixes
 - Compiled under Visual C++ 5.0, Linux glibc2
```

-- [http://perso.wanadoo.fr/montanuy/bot/bot.txt](https://web.archive.org/web/20010508095204/http://perso.wanadoo.fr/montanuy/bot/bot.txt) (archived)

No files or links for this version have been located.

## Version 0.96

This version was released as `trmbot96.zip` and `quake-termbot-0.96-1.i386.rpm` (binary) and `termbot-src-096.tar.gz` and `quake-termbot-0.96-1.src.rpm` source.

It was probably released on September 29 1999 based on dates in the release archives.

Version 0.96 of was hosted on Olivier Montanuy's personal webpage <http://perso.wanadoo.fr/montanuy/>:

> Terminator Bot for Quake\
> Version 0.96\
> ...\
> Description	File	Explanations\
> General Informations	bot.txt	A readme file, with detailed explanations.\
> Bot v0.96	trmbot96.zip	A ZIP file, containing only the executables for Windows95, 98, NT.\
> Bot v0.96	quake-termbot-96-1.i386.rpm	A RPM file, containing the executable for Linux (Mandrake, RedHat 6.0), that installs in /usr/local/games/quake. Install it with rpm -i quake-termbot-*.i386.rpm\
> Source code version 0.96	termbot-src-096.tar.gz or quake-termbot-0.96-1.src.rpm	The source code of the thing. I hope you will like it.

-- [http://perso.wanadoo.fr/montanuy/bot/index.html](https://web.archive.org/web/20010504115657/http://perso.wanadoo.fr/montanuy/bot/index.html) (archived)

Links include:

* http://perso.wanadoo.fr/montanuy/bot/bot.txt
* http://perso.wanadoo.fr/montanuy/bot/trmbot96.zip
* http://perso.wanadoo.fr/montanuy/bot/quake-termbot-0.96-1.i386.rpm
* http://perso.wanadoo.fr/montanuy/bot/termbot-src-096.tar.gz
* http://perso.wanadoo.fr/montanuy/bot/quake-termbot-0.96-1.src.rpm

Some of these files were archived: `bot.txt`, `quake-termbot-0.96-1.src.rpm` and `quake-termbot-0.96-1.i386.rpm`.

Whereas `trmbot96.zip` and `termbot-src-096.tar.gz` were not archived

Contents of `quake-termbot-0.96-1.i386.rpm`:

```text
-rwxr-xr-x  1 1093   231    292421 29 Sep  1999 usr/local/games/quake/bot
-rw-r--r--  1 1093   231      9359 29 Sep  1999 usr/local/games/quake/bot-win95.txt
-rw-r--r--  1 1093   231     13381 29 Sep  1999 usr/local/games/quake/bot.txt
-rw-r--r--  1 1093   231    187392 29 Sep  1999 usr/local/games/quake/proxy.exe
-rwxr-xr-x  1 1093   231     62385 29 Sep  1999 usr/local/games/quake/qpak
-rwxr-xr-x  1 1093   231    143820 29 Sep  1999 usr/local/games/quake/qwproxy
-rw-r--r--  1 1093   231    252928 29 Sep  1999 usr/local/games/quake/termbot.exe
```

The readme does not include a release date, but does list a changelog since 0.95.

Contents of `quake-termbot-0.96-1.src.rpm`:

```text
-rw-r--r--  1 1093   231      2503 29 Sep  1999 quake-termbot.spec
-rw-r--r--  1 1093   231    390927 29 Sep  1999 termbot.tar.gz
```

Contents of `termbot.tar.gz`:

```text
drwxr-xr-x  0 montanuy popusers    0 29 Sep  1999 termbot/
-rw-r--r--  0 montanuy popusers 3514 25 May  1998 termbot/defines.h
-rw-r--r--  0 montanuy popusers 17983 30 May  1998 termbot/LICENSE
-rw-r--r--  0 montanuy popusers  2166 23 Dec  1996 termbot/qkbotmsg.h
-rw-r--r--  0 montanuy popusers  5773 25 Nov  1996 termbot/qkbspdef.h
-rw-r--r--  0 montanuy popusers  9786 28 Jun  1998 termbot/qkbspway.c
-rw-r--r--  0 montanuy popusers  4454  4 Jun  1998 termbot/qkdta.c
-rw-r--r--  0 montanuy popusers   872 31 May  1998 termbot/qkdta.h
-rw-r--r--  0 montanuy popusers 11597 28 Jun  1998 termbot/qkent.c
-rw-r--r--  0 montanuy popusers  2389 23 Dec  1996 termbot/qkentbot.h
-rw-r--r--  0 montanuy popusers  9195  4 Jun  1998 termbot/qkmove.c
-rw-r--r--  0 montanuy popusers 10016 30 May  1998 termbot/qkmsg.c
-rw-r--r--  0 montanuy popusers 25324 28 Jun  1998 termbot/qkmsgbot.c
-rw-r--r--  0 montanuy popusers  1036 24 Dec  1998 termbot/qkpak.h
-rw-r--r--  0 montanuy popusers  3517 31 May  1998 termbot/qkptomsg.h
drwxr-xr-x  0 montanuy popusers     0 10 Aug  1999 termbot/pak/
-rw-r--r--  0 montanuy popusers  2066 10 Aug  1999 termbot/pak/pak.plg
-rw-r--r--  0 montanuy popusers  3392 10 Aug  1999 termbot/pak/pak.dsp
drwxr-xr-x  0 montanuy popusers     0 29 Sep  1999 termbot/pak/Debug/
-rw-r--r--  0 montanuy popusers 33792 10 Aug  1999 termbot/pak/Debug/vc50.idb
-rw-r--r--  0 montanuy popusers 147968 10 Aug  1999 termbot/pak/Debug/pak.exe
-rw-r--r--  0 montanuy popusers   5856 13 Jun  1998 termbot/test.c
-rw-r--r--  0 montanuy popusers  27682  4 Jun  1998 termbot/udp.c
-rw-r--r--  0 montanuy popusers   1353  9 Jun  1998 termbot/infos.txt
-rw-r--r--  0 montanuy popusers   6423  4 Jun  1998 termbot/udp.h
-rw-r--r--  0 montanuy popusers  24868 10 Aug  1999 termbot/common.c
-rw-r--r--  0 montanuy popusers   5027 30 May  1998 termbot/data.h
-rw-r--r--  0 montanuy popusers    240 25 Nov  1996 termbot/dos2unix.c
-rw-r--r--  0 montanuy popusers   2172 25 Nov  1996 termbot/files.h
-rw-r--r--  0 montanuy popusers  10855  4 Aug  1999 termbot/.depend
-rw-r--r--  0 montanuy popusers  30368  4 Aug  1999 termbot/qkbot.c
-rw-r--r--  0 montanuy popusers  14082 28 Jun  1998 termbot/qkbsp.c
-rw-r--r--  0 montanuy popusers   1779  2 Dec  1996 termbot/qkbsp.h
-rw-r--r--  0 montanuy popusers  23051 26 Dec  1997 termbot/qkbspprt.c
-rw-r--r--  0 montanuy popusers   5948 25 Nov  1996 termbot/qkbspprt.h
-rw-r--r--  0 montanuy popusers    111 30 Nov  1996 termbot/qkbspway.h
-rw-r--r--  0 montanuy popusers   2752 23 Dec  1996 termbot/qkent.h
-rw-r--r--  0 montanuy popusers   8731  4 Jun  1998 termbot/qkmath.c
-rw-r--r--  0 montanuy popusers   3830  4 Jun  1998 termbot/qkmath.h
-rw-r--r--  0 montanuy popusers   2112 25 Nov  1996 termbot/qkmove.h
-rw-r--r--  0 montanuy popusers   3092 30 May  1998 termbot/qkmsg.h
-rw-r--r--  0 montanuy popusers   3305 23 Dec  1996 termbot/qkmsgbot.h
-rw-r--r--  0 montanuy popusers  12064 24 Dec  1998 termbot/qkpak.c
-rw-r--r--  0 montanuy popusers  30072 28 Jun  1998 termbot/qkpto.c
-rw-r--r--  0 montanuy popusers   1080 25 Nov  1996 termbot/qkpto.h
-rw-r--r--  0 montanuy popusers  29770  4 Aug  1999 termbot/qkthink.c
-rw-r--r--  0 montanuy popusers   2022 25 Nov  1996 termbot/qkthink.h
-rw-r--r--  0 montanuy popusers   6777  1 Feb  1997 termbot/todo.txt
drwxr-xr-x  0 montanuy popusers      0 29 Sep  1999 termbot/Debug/
-rw-r--r--  0 montanuy popusers  66560 10 Aug  1999 termbot/Debug/vc50.idb
-rw-r--r--  0 montanuy popusers 252928 10 Aug  1999 termbot/Debug/termbot.exe
-rw-r--r--  0 montanuy popusers   8921 28 Jun  1998 termbot/common.h
-rw-r--r--  0 montanuy popusers  13381 29 Sep  1999 termbot/bot.txt
drwxr-xr-x  0 montanuy popusers      0 10 Aug  1999 termbot/Release/
-rw-r--r--  0 montanuy popusers  13054 31 May  1998 termbot/data.c
-rw-r--r--  0 montanuy popusers   3814  2 Dec  1996 termbot/qkbot.h
-rw-r--r--  0 montanuy popusers    961 23 Dec  1996 termbot/qkbotpto.h
-rw-r--r--  0 montanuy popusers   5655 29 Sep  1999 termbot/qkdefs.h
drwxr-xr-x  0 montanuy popusers      0 10 Aug  1999 termbot/proxy/
-rw-r--r--  0 montanuy popusers   1433 10 Aug  1999 termbot/proxy/proxy.plg
-rw-r--r--  0 montanuy popusers   3719 10 Aug  1999 termbot/proxy/proxy.dsp
drwxr-xr-x  0 montanuy popusers      0 29 Sep  1999 termbot/proxy/Debug/
-rw-r--r--  0 montanuy popusers  50176 10 Aug  1999 termbot/proxy/Debug/vc50.idb
-rw-r--r--  0 montanuy popusers 187392 10 Aug  1999 termbot/proxy/Debug/proxy.exe
-rw-r--r--  0 montanuy popusers   1264 29 Sep  1999 termbot/Makefile
-rw-r--r--  0 montanuy popusers  26208 13 Jun  1998 termbot/qwmsg.c
-rw-r--r--  0 montanuy popusers   7223  7 Jun  1998 termbot/qwproxy.c
-rw-r--r--  0 montanuy popusers   6689 28 Jun  1998 termbot/qkmain.c
-rw-r--r--  0 montanuy popusers   2105 20 Jan  1999 termbot/pak.c
-rw-r--r--  0 montanuy popusers  12087  7 Sep  1998 termbot/.depend.bak
-rw-r--r--  0 montanuy popusers   2660 13 Jun  1998 termbot/qwdefs.h
-rw-r--r--  0 montanuy popusers   9936  9 Jun  1998 termbot/md4.c
-rw-r--r--  0 montanuy popusers   1683 10 Jun  1998 termbot/qwmsg.h
-rw-r--r--  0 montanuy popusers   9359 27 May  1998 termbot/bot-win95.txt
-rw-r--r--  0 montanuy popusers   6373  3 Jun  1998 termbot/crc.c
-rw-r--r--  0 montanuy popusers   5528  7 Sep  1998 termbot/qwmagic.c
-rw-r--r--  0 montanuy popusers    221  9 Jun  1998 termbot/qwmagic.h
-rw-r--r--  0 montanuy popusers   2503 29 Sep  1999 termbot/quake-termbot.spec
-rw-r--r--  0 montanuy popusers   4230 10 Aug  1999 termbot/termbot.dsp
-rw-r--r--  0 montanuy popusers    913 10 Aug  1999 termbot/termbot.dsw
-rw-r--r--  0 montanuy popusers 107520 10 Aug  1999 termbot/termbot.ncb
-rw-r--r--  0 montanuy popusers  59904 10 Aug  1999 termbot/termbot.opt
-rw-r--r--  0 montanuy popusers   1623 10 Aug  1999 termbot/termbot.plg
```

## Release Timeline

* Terminator v0.7, trmbot07.zip, ??? 1996
* Terminator v0.8, trmbot08.zip, botsrc08.zip, October 14 1996
* Terminator v0.9, trmbot09.zip, November 04 1996
* Terminator v0.91, trmbot09.tgz, botsrc09.zip, botsrc09.tgz, November 04 1996
* Terminator v0.92, ?, ? ????
* Terminator v0.93, ?, ? ????
* Terminator v0.94, ?, ? ????
* Terminator v0.95, ?, ? ????
* Terminator v0.96, trmbot96.zip, quake-termbot-0.96-1.i386.rpm, termbot-src-096.tar.gz, quake-termbot-0.96-1.src.rpm,  September 29 1999

## References

* [Terminator Bot for Quake 0.96](https://web.archive.org/web/20010504115657/http://perso.wanadoo.fr/montanuy/bot/index.html) (archived)
* [Terminator Bot for Quake 0.9](https://www.gamers.org/dEngine/quake/Qbot/)

