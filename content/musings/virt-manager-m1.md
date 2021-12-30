---
title: "virt-manager on M1 Macs"
date: 2021-12-30T02:09:38-05:00
draft: false
tags:
- virtualization
- macos
---
I found the easiest way to get `virt-manager` and `virt-viewer` to run on Monterey (M1) was to use a [separate Intel installation](https://stackoverflow.com/a/68443301/12217062) of homebrew. Then I looked through the recent forks of [jeffreywildman/homebrew-virt-manager](https://github.com/jeffreywildman/homebrew-virt-manager) for something that looked reasonably up to date and did the usual `brew tap` installation.
