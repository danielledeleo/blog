---
title: "macOS Window Drag Hotkey"
date: 2024-05-18T16:55:15-04:00
draft: false
tags:
- macos
---

Sway and Hyprland let you drag windows around from any point with a held keyboard modifier. This setting lets you hold `Control ⌃ + Command ⌘` with the left mouse button to do the same in macOS. Log out or reboot to apply.

`defaults write -g NSWindowShouldDragOnGesture -bool true` 
