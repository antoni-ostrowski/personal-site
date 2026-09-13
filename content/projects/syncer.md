---
title: "Library Syncer"
summary: "Personal tool for syncing music library"
role: "Author"
year: "2026"
technologies: ["Go", "htmx", "SQLite"]
gallery:
- "/images/syncer.png"
repo: "https://github.com/antoni-ostrowski/library-syncer"
weight: 3
---

Personal tool that syncs my music library.
It's a server that periodically fetches latest state of google sheet that contains music metadata and urls, it downloads missing files and updates local db to stay in sync (also handles deletions and updates of course).
It lets me not have to worry about manualy downloading music and tagging it with artwork and metadata, I just add google sheet via web UI and and my library is  kept in sync.
