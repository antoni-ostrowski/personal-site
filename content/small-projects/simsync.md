---
title: "simsync"
summary: "Stateless Go library that fans out updates to exactly the clients viewing a resource"
role: "Author"
year: "2026"
technologies: ["Go", "htmx", "Redis"]
badges: 2
repo: "https://github.com/antoni-ostrowski/simsync"
weight: 4
build:
  render: never
---

Very simple library that provides a sync engine that uses provided backend for pub/sub & storage, and fans out events via plugged in handler.
Checkout [readme](https://github.com/antoni-ostrowski/simsync#simsync) for examples and demo.
