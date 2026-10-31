---
title: "Exam Stack"
summary: "Fully-offline exam platform for schools, battle-tested in a real exam"
role: "Co-Author"
year: "2026"
technologies: ["Go", "TypeScript", "SQLite", "Wails", "TanStack"]
badges: 2
weight: 8
---

<!-- repo: "https://github.com/antostryniu/exam-stack" -->

Portable exam platform that replaces paper exams with a locally-hosted web app — no cloud needed.
Teachers build exams in a Wails desktop Studio app, export an encrypted bundle, import it in Web app and run the exam over the school LAN with results stored locally in SQLite and exported to PDF.
This project was actually used in real exam ran by real institution and was proven very useful. It solved major problem of manual grading work, while doing everything offline-first.

It works on every major platform. It ships a Studio app and server bundle which includes start script, Web app compiled into one exec via Bun and other necessary files.

One of the most painfull lessons from this project is that shipping JS web apps as executables is not that trivial and I would not recommend it, but it was the requirement for this project.
