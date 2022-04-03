---
layout: default
title:  "Gnome Scaling Settings"
date:   2022-04-03 14:45:00 -0000
categories: GNOME
description: How to fix scaling in gnome.
type: Patch
---

## TL;DR;
Run this and then reboot.
```bash
gsettings set org.gnome.mutter experimental-features "['scale-monitor'framebuffer']"
```

Before:
![Settings screen before modification](/assets/images/settings-before.png)

After:
![Settings screen after modification](/assets/images/settings-after.png)

## Back Story

I recently installed [PureOS](https://www.pureos.net/) on my
laptop. I chose PureOS since it's written in 100% free and open source
and the idea of "hackable" OS was exciting. My first issue was because
it's 100% free and open source it was missing a proprietary wifi
driver, but that's a different story.

PureOS comes with the GNOME desktop environment which is actually very
nice. It runs much smoother on my poor cheap laptop than Windows 10
could. I've actually been comparing it a lot to a Mac (for better or
worse) for how it makes my laptop feel. One of the bigger problems
that I just found the solution for is the scaling factors.

The built-in options allow for setting the scale to 100%, which makes
everything too small for my little 1080p screen. All the way up to
200% which makes everything to big for my little 1080p screen. I
decided I'd give it a shot to try to fix this myself so I went over to
gnome's [settings
repository](https://gitlab.gnome.org/GNOME/gnome-control-center)
where I found that it was already an [open
issue](https://gitlab.gnome.org/GNOME/gnome-control-center/-/issues/1351)
with an "experimental" solution.

There is some discussion about some blurry apps when you enable
fractional scaling. And I am also running into that now, and I hope it
doesn't become too big of an issue. For now, not having to find the
zoom button for every app is great!

Hope this helps someone else with the same problem.