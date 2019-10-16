Auto LAN IPv6
-------------
This 'project' is forked from the (Free) [AutoLan by MY Developers](#) as such, all credit for the original library should go to them. _Note: The orginal site/project is sadly no longer available._


Ponywolf Updates
----------------
* Reorganized the codebase removing redundent files and packaging up the client/server files
* Added Pong Demo 4 as base project for easy testing
* Fixed 40+ non-breaking errors in client/server, should pass ZeroBrane's static analyzer
* Reorganized the README.md file
* Removed link to MY Developers as it is a phishing site now :(

To Do
-----
* Option to use [ZeroConf plugin](https://marketplace.coronalabs.com/corona-plugins/zeroconf) for discovery
* Simplify the events that get kicked off by AutoLan


The Roaming Gamer Updates
--------------------------

This repository contains various examples and modified files that came out of [this disucssion](https://forums.coronalabs.com/topic/63788-autolan-ipv6). In short, AutoLan was developed for an earlier version of Lua Sockets (2.0) and when LuaSockets 3.0 came out, it stopped working.

Several experts worked on this and came up w/ solutions to the issue.  Those solutions are provided here for future reference and posterity.

Warning
--------
* If you are running Corona 2016.2833 (uses socket3) or later, you must run the pong demo on separate devices for it to work.  You can run both instances on the same machine for versions before that.
* There is no guarantee of suitability for use or functionality attached to this content.

Thanks To
-------
* MY Developers for original code
* scottrules44 for code modes and 'pong demo' changes
* Joshua Quick for insights on socket.udp() versus socket.udp4() versus socket.udp6() and other coding insights
* Rob Miracle for his help on a separate slack channel
* Roaming Gamer for the organizing and post the IPV6 changes
* ...everyone else who pitched in with ideas and insights