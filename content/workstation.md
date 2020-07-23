---
title: "Workstation"
date: 2020-07-23T01:59:44-04:00
draft: false
---

# My Gemini/blogging workstation

Although I do my day to day work on a MacBook, I have a deep soft spot for ThinkPads. My old X60T (swapped out with a X61S motherboard) is the perfect distraction-free blogging device for a more civilized age.

It has a small SATA SSD (that runs at SATA 3 speeds thanks to Middleton's ThinkPad BIOS mods). The Intel Core 2 Duo L7500 runs at a blistering 1.60GHz. free tells me I have 4 GiB of memory installed. The display is a mere 1024x768 pixels across a sprawling 12 inches. 

The X60 series doesn't have a trackpad, only a trackpoint and some scratchy mouse buttons below the spacebar. It's great because my fingers never leave the keyboard. The keyboard itself is really quite lovely, albeit a smidge smaller than a typical ThinkPad keyboard. I keep hitting F1 instead of Escape, though.

## Operating System

I wanted to be at least as minimal in my choice of software as I was in my choice of device, so I went with Alpine Linux. I fiddled around with Debian for a while, but a few things drew me back to Alpine. The package manager is stupidly fast, especially noticable on this old hardware and it doesn't use systemd. I don't particularly mind systemd, but the goal here is ultimate simplicity, not the kitchen sink. WiFi wasn't a hassle to configure, and I have full disk encryption setup as well.

For my desktop manager, I effectively don't have one. Here are the X11 apps I have installed:

* openbox
* xterm
* xfce4-terminal
* firefox

That's it. I also installed picom as a compositor. Firefox is only there so I can preview my blog in realtime and look up documentation or help for fun Linux problems. I did not bring over my password manager so I won't be tempted to login more distracting sites.

## Terminal setup
I have my .xinitrc setup to launch xfce4-terminal like so:

```
picom &
xfce4-terminal --hide-scrollbar --hide-menubar --fullscreen &
openbox
```

Running it this way lets me easily configure things like fonts and colourschemes. As much as I'd like to use kmscon or just plain old text mode, this works out better and looks a lot prettier. xfce4-terminal can also be configured to hide the X11 cursor automatically and it has a pretty minimal tab layout. 

## Text editor
vim

## Other software
* zsh (with ohmyzsh)
* git
* go
* python3
* normal linux build-essential stuff
* amfora (to browse gemini sites)

This is all I need to get started on building out a blog.

