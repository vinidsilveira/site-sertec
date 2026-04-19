# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static single-page website for **SerTec Refrigeração**, an air-conditioning and refrigeration services company in Sapucaia do Sul, RS, Brazil. No build tools, frameworks, or dependencies — the entire site lives in one file.

## Development

No build step required. Open `index.html` directly in a browser, or serve with any static file server:

```bash
# Python (built-in)
python -m http.server 8080

# Node.js (if available)
npx serve .
```

## Architecture

All content, styles, and scripts are in a single `index.html` (~2,000 lines). Structure:

- **CSS**: Embedded `<style>` block using CSS custom properties (`--primary`, `--accent`, `--bg`, etc.). Sections are delimited by `/* ── SECTION ── */` comments.
- **HTML**: Six `<section>` elements with IDs: `#inicio`, `#servicos`, `#sobre`, `#avaliacoes`, `#diferenciais`, `#contato`. The fixed `<header>` links to these anchors.
- **JS**: Inline `<script>` at bottom handling: header shadow on scroll, mobile hamburger menu, Intersection Observer entrance animations, contact form validation + WhatsApp redirect.

## Key Design Details

- **Color system**: `--primary: #0F172A`, `--accent: #0369A1`, with surface/text variants defined as CSS vars in `:root`.
- **Typography**: Google Fonts — Poppins (all weights). Fluid sizes via `clamp()`.
- **Contact form**: Does NOT submit to a backend. On submit, it constructs a `wa.me/555134524868` URL with the user's message and opens WhatsApp.
- **Assets**: Only one external asset — `logo-sertec.jpeg` in the project root.

## Business Context

- Company phone: (51) 3452-4868 | WhatsApp: 555134524868
- Services: installation, maintenance, repair, cleaning, gas refill (ar-condicionado & refrigeração)
- Copy and contact details are in Portuguese (pt-BR)
