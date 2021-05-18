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

I hope PeerTube is the future of decentralized video on the web. I think it already should be the go-to software for free software projects and events.

PeerTube solves the disadvantages of centralized video control on the web in very innovative ways.

The project describes itself as:

> PeerTube is a free and open-source, decentralized, federated video platform powered by ActivityPub and WebTorrent, that uses peer-to-peer technology to reduce load on individual servers when viewing videos.

In recent versions, they've been working on real true P2P live streaming, and it's amazed me how far they've gotten it so fast.

![PeerTube_Logo](https://i.imgur.com/7DCY4ur.png)

## It's not a YouTube killer... Yet.

The software itself handles even demanding workloads great, stability has been surprisingly good. Even when we tried to really push the new live stream support.

Where things start to fall down for Jupiter Broadcasting is operating at scale, on an ongoing basis. Four or more shows a week, multiple team members, and live streams.

**Our key problems with PeerTube as is today:**

+ Unclear on how to scale management across multiple channels/shows
	+ I need an account for every show, plus a network account for live streams, plus my personal account for comments and my own feed.
	+ And each member of Jupiter Broadcasting would need an account.
	+ It just becomes a lot to manage. And not super easy to automate. Which is a big deal to us.
+ Live stream support is GREAT for v1 support. However it is still tricky to use, especially if you want to have a live stream auto-publish. If, for some reason, that stream drops at any point you are kind of locked out and have to regenerate an API key, which can break service integrations such as restream.io.
+ The disk space is ~30G and _growing_. - And that's with only two of our shows being test published for a few months.
+ There is no great way to mass-import. We want to bring our entire back-catalog online, but it would take a lifetime one video at a time.
	+ Some kind of directory import would be ideal. Import the videos and read title/description from a text file.
	+ Or an RSS feed import
	+ The current video import options are really nice, just need expanded for us.

## We're kind of a big deal... ;)

I think some of these pain points are almost a non-issue for simpler use cases. The project that makes the one off video from time to time, or the community event that wants a full free stack to stream and make talks available. PeerTube can crush those jobs. For that kind of work, it really is a YouTube killer in a box.

But for content creators putting out a lot of content, across various "channels" it is tricky and cumbersome to manage. 

The network effect is also an issue. Our viewers just started forgetting to use PeerTube, falling back into the habit of YouTube and TWiTCH instead. But I hope as more PeerTube instances pop up this issue starts to resolve itself faster than we typically see online. PeerTube's clever use of [ActivityPub](https://www.w3.org/TR/activitypub/) means there is a decentralized way for viewers to get notified about new content. And it just takes a core group of viewers to get a video noticed and rolling.

For now, we plan to keep testing PeerTube behined the scenes, trying out the new releases, and searching for ways to automate deploying content to PeerTube.

We're taking our public instance offline since it won't be getting the focus it deserves, and does not represent how excited we are about PeerTube and our intent to go all in once everything is ready.

Check back here in the future, you never know when we might give it a go again. 

### Previous PeerTube coverage

+ [Fedora to the Core | LINUX Unplugged 255 ](https://www.youtube.com/watch?v=BkmSD3Z0kUk&t=301s)

+ [Peering Into the Future | LINUX Unplugged 256 ](https://www.youtube.com/watch?v=ZUDSdeBretw&t=4946s)

+ [GNOME, GNOME on the Range | LINUX Unplugged 261 ](https://youtu.be/SE7NO3mbo9w?t=2666)

+ [Waxing On With Wendell | LINUX Unplugged 388](https://youtu.be/p3bEumYnnAo?t=2219)

### Feedback and Corrections

[Our contact page](https://linuxunplugged.com/contact)

-Chris
