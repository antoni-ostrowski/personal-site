---
title: "LocalStream"
summary: "Simple, local desktop music player"
role: "Author"
year: "2025/26"
technologies: ["Go", "Wails", "Typescript", "React", "SQLite"]
repo: "https://github.com/antoni-ostrowski/LocalStream"
videos:
 - "/videos/localstream.mp4"
weight: 5
---


It's cross-platform desktop app with interesting architecture - it's using [Wails](https://wails.io/) framework, which allows for building apps with Go core as main process orchestrator and Web technologies for rendering UI using system provided web engine.

It's one of my biggest project yet sitting at about 10k LOC, supports stuff like favourite tracks, playlists, adding local files as source, queue etc.

Main problems I ran into
- speed of parsing file metadata - for bigger library like mine (~2k files) the sync part could take few minutes, but turned out it was already faster than most of other OSS local music players I tried :).
- it was my first time implementing music playback and it was quite interesting, I used [Beep](github.com/gopxl/beep) library.

