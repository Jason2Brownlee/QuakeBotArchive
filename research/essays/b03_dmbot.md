# DM Bot

The DM Bot or "DMBot" was created by Nathaniel Gorham and was one of the very first dedicated QuakeC deathmatch bots.

There was only a single release of the bot v1.0 with the filename dmbot1.zip.

The archive contained three files, a readme (dmbot1.txt), the compiled game code (progs.dat) and the game source code (source.zip).

   4604 25 Aug  1996 DMBOT1.TXT
  45782 25 Aug  1996 SOURCE.ZIP
 444240 25 Aug  1996 PROGS.DAT

The source.zip file looks a lot like the source file distributed with the TMBot which provided the bass for this mod.

 28390 25 Aug  1996 BOTAI.QC
 33981 24 Aug  1996 CLIENT.QC
  8547 24 Aug  1996 BOT.QC
 11111 21 Aug  1996 WORLD.QC
  2450 21 Aug  1996 BOT.H
 15298 21 Aug  1996 TRIGGERS.QC
 17659 21 Aug  1996 PLAYER.QC
  7855 21 Aug  1996 PLATS.QC
   962 21 Aug  1996 IMPULSE2.QC
 17774 21 Aug  1996 DEFS.QC
  6374 21 Aug  1996 SUBS.QC
   692 21 Aug  1996 PROGS.SRC
  1597 21 Aug  1996 BOT_EXT.QC
 24072 18 Aug  1996 WEAPONS.QC

The release date in the readme was August 23rd 1996.

The timestamps of the files in the archive were two days later on August 25th, and the FTP timestamp on an archive of cdrom.com/pub/idgames2/quakec/bots was one day later, although very late at night.

	dmbot1.txt             24-Aug-96 23:34     4k
	dmbot1.zip             24-Aug-96 23:34   175k

I expect the release was the 24th, although near midnight and perhaps past midnight onto the 25th in Nathaniel Gorham's local timezone.

I could find no announcement of the release on usenet archives.

The mod provides a deathmatch opponent.

The readme makes it clear that code base was based on the TMBot by the brothers Micheal and Tim Polucha which was in turn based on the HoloSelf v1.0.

Given the date of release (24th), it suggests that the DM bot was developed as an extension to the TMBot v1.0 as v1.1 of the TMBot was not released until the 25th and perhaps distributed on the 26th.

Nathaniel comments that he made very little change to the mod to transform the single player helper TMBot into a deathmatch opponent.

	... extremely little work, altered a serval [SIC] lines of code to make it attack other players instead of monsters

He summarizes the change he made, indicating that the bot will see players as enemies and will avoid attacking players on the same team.

	This bot is basically a small hack of Mike and Tim Polucha's Automated Helper Bot, by changing a small portion of the code I was able to reconfigure the bot to attack other players in deathmatch, and to be able to distinguish between team members and enemy team members.

This suggests that no additional AI logic was added.

The bot can be spawned in single player mode where it will attack monsters.

The bot is spawned where you stand and if you walk away, it will run to catch up.

It uses the enforcer model like the TMBot and is not solid meaning you can walk right through it as with the TMBot v1.0. Unlike the TMBot, it will fire nails at enemies instead of laser bolts.

In deathmatch mode, the bot is spawned in the same way. Shotgun shells pass right through the bot, but projectiles will injure and kill it, like nails.

Reviewing the code confirms that the DMBot is a modification of the TMBot v1.0.

A diff of the code with TMBot v1.0 shows that only three files were changed: bot.qc, botai.qc and client.qc.

The bot.qc file was modified to set the bot's team to be the same as the players' to aid in preventing the bot from attacking players on the same team in team deathmatch.

The botai.qc file was modified to change the bot from attacking with laser bolts to firing nails. Importantly, the BotFindTarget function used to locate a target to attack for the bot was updated to allow the bot to select clients (players) as targets, and to avoid attacking clients that are on the same team as the bot.

Finally, client.qc was updated to provide a bot-specific obituary, for example:

	Brad was killed by Tom's bot

The bot will attack other players, but not the player that spawned the bot. This functionality appears to be the same in kind (but not the same code) as that introduced in TMBot 1.1. This makes the bot a helper for both single player and deathmatch, but not a deathmatch opponent.

As such, it technically cannot be classified as a "deathmatch bot" (e.g. opponent), but instead a "deathmatch helper bot".

Nevertheless, another bot released on the same day was a deathmatch opponent bot. It was called the MyBot.

I could not find evidence that Nathaniel developed additional QuakeC mods.

Nevertheless, in a comment on the quake-c mailing lists suggests he was considering a second version of his DMBot.

The following was written by Nathaniel in response to suggestions for further developing bot AI generally. Nathaniel's comments are interleaved with the original question.

	On Sun, 25 Aug 1996, Eric J. Fisher wrote:

	> Mr.Toad wrote:
	>
	>   hey all...
	>      just had a couple rad ideas about some quake c changes... here we go:
	> remember the method you used to control troops in C&C?
	> it would be something like this...
	> (crosshair location is key to where is selected)
	> the player points his crosshairs at soldier.. hit impulse key
	> move crosshair to desired location.. hits another impulse (or same with some
	> implementation)
		I'm working on it, but I think I want to keep it to one bot per
	player.  Right now just one bot can easily wipe someone out quickly if
	they are not careful.  (Also, my next version will have optional
	rocketlauncher and lightning gun attachments) <big evil grin>

	> soldier moves there... pretty straight forward.. best control of entire
	> fireteam... remember how fast
	> you moved soldiers around in C&C? this would be the ideal movement method
	> for many bots...

		Yep, I'm working on this now using the traceline command to spawn
	a navpoint at whatever the traceline hits. Also another good function
	PARTOL, stand at one patrol waypoint, and point and the other and have the
	bot run back and forth looking for trouble.

	> of course they would have enough AI to react to being fired upon. another
	> impulse would be to stop all

		Done in the next version, added a part to the pain code that sets
	the current enemy to the owner of the attack that hit the bot.

	> actions.... an impulse to attack.... and even an impulse to SCATTER!
		Doing that too.  Also with the traceline command. I hope.

	> is it  location? or entity?
		Hmm, good plan, it should make handling the new parts of the
	controls pretty easy.

	> pretty simple... but I am not a good C programmer ( yet :) )... anyone wanna
	> take this up?...
	> the logic here is simple...
	> maybe someone will take this up... plus with the impulses up top...

			Yup, I'm working on it as part of the next version for
	DMBOT, but if anyone wants to do it for me I'll let you :)


			-Nathaniel Gorham-
	Author of the TMBOT hack aka DMBOT

-- [Quake C Mailing List Archive](https://web.archive.org/web/19990427113042/http://www2.csn.net/~rudeseal/quakec/quakeclist826-828.zip), August 26 to August 28 1996 (archive)



## Relevant Timeline

* QuakeC source code v1.01, qcc.tar.gz, July 25, 1996.
* HoloSelf v1.0, holo1.zip, August 11, 1996.
* HoloSelf v2.0, holo2.zip, August 14, 1996.
* TMBot v1.0, tmbot1.zip, August 22, 1996.
* DMBot v1.0, dmbot1.zip, August 24, 1996.


## References

* [dmbot1.zip](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/bin/dmbot1.zip)
* [http://www.cdrom.com/pub/idgames2/quakec/bots/](https://web.archive.org/web/19961225222455/http://www.cdrom.com/pub/idgames2/quakec/bots/) (internet archive)
* [Quake C Mailing List Archives](https://web.archive.org/web/19990427113042/http://www2.csn.net/~rudeseal/quakec/list.html), seal-industries.com (archive)
* [Quake C Mailing List Archive](https://internet archive.archive.org/web/19990427113042/http://www2.csn.net/~rudeseal/quakec/quakeclist826-828.zip), August 26 to August 28 1996 (internet archive)




