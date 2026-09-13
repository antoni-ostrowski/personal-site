# my site
Visit it! - https://antost.dev

# projects

New project = new file in `content/projects/<name>.md`:

```md
---
title: "LocalStream"
summary: "One-line blurb shown on the homepage."
role: "Creator"          # small grey line under summary, with year
year: "2025/26"
weight: 1                # optional, higher shows first (default 0)
website: "https://antost.dev"                        # optional, display auto-shortened
repo: "https://github.com/antoni-ostrowski/localstream"  # optional, display auto-shortened
image: "/images/demo.png"    # optional banner (used as video poster if both set)
video: "/videos/demo.mp4"    # optional banner player (mp4)
technologies: ["Go", "Typescript"]  # optional plain list
gallery:                     # optional image grid
  - "/images/a.png"
  - "/images/b.png"
videos:                      # optional extra players (mp4)
  - "/videos/demo2.mp4"
---

Writeup in **markdown** here. Rendered as the article body.
```

Media files live in `static/` (`static/images/`, `static/videos/`) and are
referenced by URL (`/images/...`). Absolute `https://` URLs also work for
`video`/`videos` (use raw file links, e.g. release assets — not `.../blob/...` pages).

# dev

- mise run dev — local server + CSS watcher
- mise run build — production build


- Edit: layouts/, content/, assets/css/main.css, hugo.toml
- Don't touch: public/ (hugo output, ignored), static/css/main.css (tailwind output, ignored)
- Source static files (e.g. PDF) live in static/, committed

