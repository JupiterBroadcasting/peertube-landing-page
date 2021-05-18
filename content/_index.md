+++
title = "Peertube Problems"
date = "2021-05-17T16:26:46-07:00"
author = "ChrisLAS"
authorTwitter = "ChrisLAS" #do not include @
cover = ""
tags = ["", ""]
keywords = ["PeerTube","Failure"]
description = "PeerTube is not working for us. We love it, but it's just not there yet... For us"
showFullContent = false
+++

**-From the desk of ChrisLAS-**

# Some PeerTube Problems

I'll say right off the top, I hope PeerTube is the future of decentralized video on the web. I think it already should be the go-to software for free software projects and events.

PeerTube solves the disadvantages of centralized video control on the web in very innovative ways.

As the project describes itself:

> PeerTube is a free and open-source, decentralized, federated video platform powered by ActivityPub and WebTorrent, that uses peer-to-peer technology to reduce load on individual servers when viewing videos.

In recent versions, they've been working on real true P2P live streaming, and it's amazed me how far they've gotten it so fast.



## It's not a YouTube killer... Yet.

Where things start to fall down for Jupiter Broadcasting is when you're trying to operate at scale on an ongoing basis. Four or more shows a week, multiple team members, and live streams.

The software itself handles the work great, stability has been surprisingly good.


Our key problems with PeerTube as it is today, are these:

+ Unclear on how to scale management across multiple channels/shows
	+ I need an account for every show, plus a network account for live streams, plus my personal account for comments and my own feed.
	+ And each member of Jupiter Broadcasting would need an account.
	+ It just becomes a lot to manage. And not super easy to automate. Which is a big deal to us.
+ Live stream support is GREAT for v1 support. However it is still tricky to use, especially if you want to have a live stream auto-publish. If, for some reason, that stream drops at any point you are kind of locked out and have to regenerate an API key, which can break service integrations such as restream.io.
+ The disk space is ~30G and _growing_.

## We're kind of a big deal... :)

I think some of these pain points are almost a non-issue for simpler use cases.

But for content creators putting out a lot of content, across various "channels" it can be tricky to manage.

The network effect is also an issue. We found our viewers just started forgetting to use PeerTube, falling back into the habit of YouTube instead. But we hope as more PeerTube instances pop up this issue starts to resolve itself.

For now, we plan to keep testing PeerTube, trying out the new releases, and searching for ways to automate deploying content to PeerTube.

Check back here in the future, you never know when we might give it a go again. And when we do, we hope to go all in.


-Chris
