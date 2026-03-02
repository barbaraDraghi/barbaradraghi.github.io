# Barbara Draghi — Personal Academic Website

Source code for [https://barbaradraghi.github.io](https://barbaradraghi.github.io), built with Jekyll and deployed on GitHub Pages.

## Overview

This website includes:

- A custom Jekyll setup (`theme: null`) with reusable layouts/includes
- A homepage with intro, contact buttons, portrait, and section cards
- Dedicated pages for:
  - Research publications and collaborations
  - Coffee & Learn video episodes
  - Events & Talks (data-driven from YAML)
  - Contact & CV
- Light/dark theme toggle with `localStorage` persistence

## Live Site

- [https://barbaradraghi.github.io](https://barbaradraghi.github.io)

## Run Locally

Prerequisites:

- Ruby + Bundler installed

Commands:

```bash
bundle install
bundle exec jekyll serve
```

Open:

- `http://127.0.0.1:4000`

## Content & Navigation

- Main navigation is configured in `_data/nav.yml`
- Events & Talks entries are managed in `_data/events.yml`
- Main content pages live in `pages/`
- Homepage content lives in `index.md`

## Project Structure

```text
barbaradraghi.github.io/
├── _config.yml
├── Gemfile
├── index.md
├── README.md
├── _data/
│   ├── events.yml
│   └── nav.yml
├── _includes/
│   ├── episode.html
│   ├── footer.html
│   ├── head.html
│   ├── header.html
│   ├── nav.html
│   └── publication.html
├── _layouts/
│   ├── default.html
│   ├── home.html
│   └── page.html
├── assets/
│   ├── Barbara Draghi_CV.pdf
│   ├── css/
│   │   └── style.css
│   └── images/
│       ├── bg.webp
│       ├── profile.jpg
│       └── profile.png
├── pages/
│   ├── coffee-learn.md
│   ├── contact-cv.md
│   ├── events-talks.md
│   ├── projects.md
│   └── research.md
└── _site/                       # generated build output
```

## Notes

- `pages/projects.md` exists but is currently not shown in the nav menu.
- The site uses `jekyll-seo-tag` via the `github-pages` gem dependency.
