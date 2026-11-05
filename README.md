# Saadi Nour El Islem — Portfolio

Bilingual (Français / English) single-file portfolio website for Saadi Nour El Islem, a web developer.

## Overview

A one-page portfolio built entirely as a single HTML file. All CSS and JavaScript are inline, and the profile photo has been removed, so the whole site is truly portable — it works offline and can be dropped onto any static host without any build step.

The site has 5 sections:

- **Hero** — animated dark header with a particle background, a typing effect, and animated stat counters.
- **À propos** — a short biography.
- **Compétences** — skill cards plus skill tags.
- **Valeur** — personal values with checkmarks and vertical bars.
- **Contact** — six contact cards plus a contact form.

## Tech Stack

- HTML, CSS, JavaScript — plain, no frameworks, no compile step.
- Stack card: **React.js · Laravel · PHP · MySQL · JavaScript**.
- The "Développement Web" skill tags include **Laravel** and **React.js**.

## Files

- `index.html` — the entire website (single self-contained file).
- `assets/CV.pdf` — downloadable curriculum vitae.

## Run it locally

Open `index.html` directly in a browser, or serve the folder:

```bash
# Python 3
python -m http.server 8734
# then open http://localhost:8734
```

```bash
# Node.js
npx serve .
```

## Publish to GitHub

This is a static site, so you can publish it to any host for free:

- **GitHub Pages** — push this folder to a GitHub repo, then enable GitHub Pages in the repo settings and choose the `main` branch.
- **Netlify** — drag and drop the folder onto netlify.com.
- **Vercel** — connect the repo and deploy the workspace root.

## Contact

The contact form has no backend. Submissions open a pre-filled WhatsApp message to `213 674 610 356`.

```text
https://github.com/Saadi870-spec
```
