# nikhilsharma-OM.github.io

Nikhil Sharma's academic job-market website. A static single-page site — no build step, no framework.

Design adapted from a template originally built for [Vishavdeep Sharma's site](https://github.com/vishavdeeps95/vishavdeeps95.github.io).

## File structure

```
├── index.html   ← the entire website (HTML + CSS + JS in one file)
├── assets/
│   ├── cv.pdf                        ← CV linked by the "CV" buttons
│   └── headshot_nikhil_sharma.png    ← profile photo
└── README.md
```

## How index.html is organized

The file is divided by HTML comment banners, in this order:
1. `DESIGN TOKENS` — CSS `:root` variables (colors, fonts, max width)
2. `NAVIGATION` — top nav bar
3. `HERO` — name, title, tagline, CV button, photo
4. `RESEARCH` — research interests + Job Market Paper / Under Review / Working Papers
5. `TEACHING` — instructor & TA experience
6. `TALKS` — conference presentations
7. `SERVICE & AWARDS` — academic service and awards
8. `CONTACT` — email, CV, address
9. `<script>` — scroll-reveal animation + active-nav highlighting

## Editing conventions

- **Add a publication:** copy one `<div class="pub">…</div>` block in the RESEARCH section and edit year, title, authors, status badge, abstract.
- **Add a talk / teaching row:** copy one `<div class="row">…</div>` block.
- **Restyle the whole site:** change the variables under `DESIGN TOKENS` only. `--accent` is the oxblood highlight; `--paper` is the page background (white).

## Updating the CV

Replace `assets/cv.pdf` with the new file (keep the same name) — the "CV" buttons already point to it.

## Deploy

Static hosting only, zero configuration. GitHub Pages serves this repo directly from `main` (`.nojekyll` disables Jekyll processing since this isn't a Jekyll site).
