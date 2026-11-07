# Akshay Shrivastava — Portfolio

Personal portfolio site. Static HTML/CSS/JS, no build step, no framework.

**Live:** https://akshayyy13.github.io/Portfolio/

## Stack

- HTML5, CSS (custom properties, no framework)
- Vanilla JS (scroll reveal, mobile nav, canvas hero texture)
- Fonts: Space Grotesk, Inter, JetBrains Mono (Google Fonts)

## Structure

```
.
├── index.html
└── assets/
    └── Akshay_Shrivastava_Resume.pdf   # linked from the "Download Resume" buttons
```

## Run locally

No build step — just open `index.html` in a browser, or serve it:

```bash
npx serve .
```

## Deploy

Drag the whole folder (not just `index.html`) into [Vercel](https://vercel.com/new) or push to a repo and enable GitHub Pages. The resume download and any future assets depend on the `assets/` folder living alongside `index.html`.

## Updating content

All content (experience, projects, skills, achievements) is hardcoded directly in `index.html` — no CMS or data file. Search for the relevant section by its `id` (`#projects`, `#experience`, etc.) to edit.
