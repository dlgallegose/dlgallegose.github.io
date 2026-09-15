# Damian Gallegos — Personal Website

Personal academic website built with [Quarto](https://quarto.org) and deployed via GitHub Pages.

🔗 **Live site:** https://dlgallegose.github.io

## About

A single-page site covering:

- Bio / introduction
- CV (with downloadable PDF and education summary)
- Research interests (Kolmogorov-Arnold Networks / machine learning)
- Skills & tools
- Contact information

## Built with

- [Quarto](https://quarto.org) — static site generator
- Custom theme via `_brand.yml` (colors, typography, favicon)
- Hosted on GitHub Pages (`gh-pages` branch)

*(For my actual skills/tech stack — ML frameworks, SQL, Flutter/Dart, etc. — see the [Skills & Tools](https://dlgallegose.github.io/#skills-tools) section on the site.)*

## Project structure

```
.
├── _quarto.yml       # Site/project configuration
├── _brand.yml        # Color palette, typography, favicon
├── index.qmd         # All page content
├── styles.css         # Custom CSS
├── images/            # Headshot, favicon
└── files/              # Downloadable CV (PDF)
```

## Local development

Requires [Quarto](https://quarto.org/docs/get-started/) and Python installed.

Preview the site locally with live-reload:

```bash
quarto preview
```

Render the static site (output goes to `_site/`):

```bash
quarto render
```

## Deployment

The site is published to GitHub Pages from the `gh-pages` branch. To publish a new version after editing content:

```bash
quarto publish gh-pages
```

This renders the site and pushes the result to `gh-pages`, updating the live site at https://dlgallegose.github.io.
