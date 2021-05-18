+++
title = "Peertube Problems"
date = "2021-05-17T16:26:46-07:00"
author = "ChrisLAS"
authorTwitter = "ChrisLAS" #do not include @
cover = ""
tags = ["", ""]
keywords = [""PeerTube,Failure ""]
description = "PeerTube is not working for us. We love it, but it's just not there yet... For us"
showFullContent = false
+++

# Some PeerTube Problems

I'll say right off the top, I hope PeerTube is the future of decentralized video on the web. I think it already should be the go to software for free software projects and events.

PeerTube solves the disadvantages to centeralized video control on the web in very innovative ways.

As they project descibes it self:

> PeerTube is a free and open-source, decentralized, federated video platform powered by ActivityPub and WebTorrent, that uses peer-to-peer technology to reduce load on individual servers when viewing videos.

In recent versions they've been working on real true P2P live streaming, and it's amazed me how far they've gotten it so fast.



## It's not a YouTube killer... Yet.

Where things star to fall-down for Jupiter Broadcasting is when your trying to operate at scale on an ongoing basis. Four or more shows a week, multiple team members, and live streams.

The software it self handels the work great, stability has been suprisingly good.


Our key problems with PeerTube as it is today, are these:

+ Unclear on how to scale management across multiple channels/shows
	+ I need an account for every show, plus a network account for live streams, plus my own personal account for comments and my own feed.
	+ And each member of Jupiter Broadcasting would need an account.
	+ It just becomes a lot to manage. And not super easy to automate. Which is a big deal to us.
+ Live stream support is GREAT for v1 support. But is still tricky to use, esp if you want to have a live stream auto publish, but for some reason that stream drops at some point. Your kind of locked out, you have to regen an API key, and that kind of locking out breaks service intergenerations like restream.io
+ The disk space is ~30G.
