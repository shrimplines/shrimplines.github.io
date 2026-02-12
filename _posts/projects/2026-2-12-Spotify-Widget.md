---
layout: post
title: "Desktop Spotify Widget"
categories: projects
---

I found an old iPod in a box of electronics at home. I wasn’t alive when they were everywhere, but the click wheel just made sense in a way modern interfaces don’t. I thought maybe I should make something like that for my desktop… so here we are.

Right now it’s basically three buttons: skip forward, skip back, and pause/play. In classic Electron fashion, it’s frameless and floats above everything else. The goal was to have it connect to Spotify so the buttons actually do something. But the recent permissions, token rules, and the AI/dev update from February 11, 2026 made everything way harder (As I make this on Feb 12). For a while, it looked perfect and did absolutely nothing, with Spotify sending “playback of protected content is not enabled.” Joys of platform dependency. Now it’s really just a Spotify remote control, not a self-sufficient player.

Mostly, I wanted a tiny cozy project to mess around in Electron. Opening VS Code feels like coming home, even if nothing I make is serious yet. I kept the design simple and muted—grey casing, light shadow so it feels like a small, functional object on my screen instead of a demo.

The code is open if you want to mess with it (though I'll probably be updating it some time soon):

https://github.com/shrimplines/music-player/tree/main

README has instructions. It’s tiny, unfinished and cute, and exactly what it’s supposed to be.
