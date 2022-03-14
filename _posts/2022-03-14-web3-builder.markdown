---
layout: default
title:  "Development Containers"
date:   2022-03-14 20:20:00 -0000
categories: containers projects
description: A not so short rant on a container I was forced to put together.
type: Project
---

## Containers

I'm actually quite new to building containers. I put together
my first real one for my full-time job
[here](https://github.com/Helioviewer-Project/helioviewer.org-docker)
since we didn't have any easy way to put together an environment for
testing.

Since then, I've been spinning up containers left and right for
various things, and my favorite part is that they're small (in size)!

## Web3 Builder

The newest container I've put together is [this one](https://hub.docker.com/repository/docker/dangarbri/web3-builder)
I built it specifically so I could make some contributions
to [status-im](https://github.com/status-im/status-react/pull/13150)
and there is somewhat of a story behind it.

To keep it short and sweet, once upon a time I had to free up 30GB of space
so I could have 50GB of space to install XCode which only takes up 16GB of space.
After that I had no space left! I suffered without space until I gave up and
uninstalled XCode so I could have some my storage back, but then the
Mac was useless to me for anything useful. No brew, no tools, no development.
Then came docker to the rescue, where I could have everything I need
to run whatever development environment I want for just a few GBs. And
since then I've been containerizing everything.