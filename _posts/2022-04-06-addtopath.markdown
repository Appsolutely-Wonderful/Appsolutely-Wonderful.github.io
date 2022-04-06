---
layout: default
title: "addtopath"
date: 2022-04-06 16:45:00 -0000
categories: Tools
description: Automatically add folders to your PATH environment variable
type: Tool
---

See the gist [here](https://gist.github.com/dangarbri/ba337448cf54282f51bb6b5682d143d9)

I wrote up this script really quick as I find myself often downloading
binaries that I don't want to force copy to /usr/bin all the
time. This script lets you quickly add items to your .bashrc.

Running this:
```bash
addtopath somefolder "Contains commands for XYZ"
```

Will append the following text to your .bashrc
```bash

# Contains commands for XYZ
export PATH=/full/path/to/somefolder:$PATH
```
