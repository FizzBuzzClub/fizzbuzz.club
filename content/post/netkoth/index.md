---
title: Network King of the Hill
draft: false
date: 2016-11-22
author: brimstone
tags: security
---

## Network King of the Hill

At the computer security conferences I attend, it's common for some sort of
CTF(Capture the Flag) contest to be run. These typically involve some sort of
binary file or VM, with multiple flags, strings of characters, embedded inside
them. To get points in this contest, one simply submits these flags to a
scoring system. The primary problem with this approach is the large amount of
time involved by typically one person to construct the binary file or VM.

To minimize this approach, [irongeek](http://www.irongeek.com/i.php?page=videos/aide2013/network-king-of-the-hill-netkoth-a-hacker-wargame-for-organizers-who-are-lazy-adrian-crenshaw-irongeek)
came up with a game mechanic that involves the scoring system looking for a
flag on the webpage hosted by the target VM instead. This way, a VM could be
constructed once, then reused for multiple contests. Participants are not only
trying to get their team flag on the target VM, but also secure the system
against other players and the operator running the contest.
