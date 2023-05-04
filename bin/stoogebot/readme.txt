	     THE STANFORD GRAPHICS QUAKE PROJECT'S DEMO PROXY
                             Windows Version
			Written by Kekoa Proudfoot

Introduction
------------

This README file for the Stanford Graphics Quake Project's demo-recording
proxy.  The proxy snoops on network traffic and writes Quake demo files
based on what it (and the client connected to it) sees.  The proxy is used
as follows:

(1) Start the proxy
(2) Connect to the proxy
(3) Play Quake
(4) Disconnect from the proxy

Currently, there are versions of the proxy for IRIX, Linux, and Windows.

Starting the Proxy
------------------

On the command line, run the demo proxy by specifying a demo file name
prefix and a server name (with an optional colon followed by the port
number), e.g.:

C:\> dproxy demo sketch.stanford.edu

Note that, if you want to play Quake and record a demo on the same machine,
you may; however, if you do, don't run Quake with the -listen flag.

Connect to the Proxy
--------------------

From Quake, connect to the machine on which you started the proxy, e.g.:

] connect proxy.mydomain.com

Recording begins once you've connected to the proxy.  Files are stored
using the demo file prefix you specified when starting the proxy, with a
pair of digits and a .dem appended automatically.  One demo file will be
created per level of game play.

Play Quake
----------

I assume you know how to do this already.

Disconnect from the Proxy
-------------------------

On the Quake console, type "disconnect," and the recording of the demos
will stop.

Known Bugs
----------

Sometimes, the proxy and the client get confused.  The proxy thinks that a
connection has been established, while the client times out and thinks that
no connection has been made.  You can detect this condition by watching the
proxy output, and you can work around it by restarting the proxy.  A fix
for this bug is in the works.

When an error occurs on a Windows machine, the proxy might output a bogus
"No error" message rather than a somewhat more-detailed description of the
error.  This is due in part to laziness on behalf of the author, and in
part to the fact that Windows is not Unix.  Go complain to Bill Gates.

Author
------

This program was written by Kekoa Proudfoot.  The author can be reached by
e-mail at: kekoa@graphics.stanford.edu.

Copyright 1996, 1997 by Kekoa Proudfoot.  All Rights Reserved.

Permission is granted to use this program for recording Quake demos.
Permission is also granted to redistribute this program, as long as this
copyright notice accompanies the program and, unless you have the written
permission from the author, Kekoa Proudfoot, you do not derive any monetary
benefit from the program's distribution.
