# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static HTML/CSS website for Trailbreak, a boutique legal and strategic advisory firm for frontier technologists. This is a self-hosted clone of the original Webflow site, designed for deployment on Cloudflare Pages.

## Project Structure

```
trailbreak-web/
├── index.html      # Single-page website
├── styles.css      # All styling
└── images/         # All assets (logo, icons, backgrounds)
```

## Development Commands

```bash
# Local preview
python3 -m http.server 8080

# Then open http://localhost:8080
```

## Deployment

Hosted on Cloudflare Pages, connected to this GitHub repo. Any push to `main` triggers automatic deployment.

**Domain:** trailbreak.xyz

## Design Notes

- Dark theme (#060606 background)
- Typography: Cormorant Garamond (headings), Inter (body)
- Accent color: #3898ec (contact button)
- Single-page layout with fade-in animations on load

## Making Changes

- **Text edits:** Update `index.html` directly
- **Style changes:** Modify `styles.css`
- **Images:** Place in `images/` folder, reference from HTML/CSS

After changes, commit and push to deploy automatically.
