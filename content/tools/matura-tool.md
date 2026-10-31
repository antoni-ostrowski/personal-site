---
title: "matura-tool"
summary: "Keyboard-first trainer for matura maths with fuzzy search"
role: "Author"
year: "2026"
technologies: ["TypeScript", "Bun", "SQLite"]
repo: "https://github.com/antoni-ostrowski/matura-tool"
weight: 4
build:
  render: never
---

Self-hosted trainer for Polish matura (podstawa) maths. Type one fuzzy query — year, session, chapter, topic or task number, diacritics-insensitive — and get the exact task with hidden answer and step-by-step explanation. Tracks solved and flagged tasks; question bank scraped once into local SQLite.
