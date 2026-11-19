# Tools Portal

A showcase page for the tools and applications developed by **Habib AlMawali**.

It is a single, self-contained with no build step, no frameworks and no external requests (no CDN, no web fonts), so it also runs on an on-prem web server.

**Live site:** `https://al-mawali.github.io/tools-portal/`

---

## Features

- Card layout with foldable "About this tool" sections
- Tool flags (Public, Private, Open Source, Internal, Beta, New, Coming Soon, Maintenance, Deprecated) with filter chips
- Access-request dialog for private tools
- Site and per-tool version labels with changelogs
- Search, expand/collapse all, light/dark theme
- Fully responsive and keyboard accessible

## Project structure

```
tools-portal/
├── index.html            # The whole site (HTML + CSS + JS)
├── .nojekyll             # Tells GitHub Pages to serve files as-is
├── README.md             # This file
├── CHANGELOG.md          # Release history (mirror of the changelog in index.html)
└── docs/
    └── CONFIGURATION.md  # How to edit tools, flags, contact and versions
```


Developed by Habib AlMawali
