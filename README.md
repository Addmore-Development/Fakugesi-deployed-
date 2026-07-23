# Fak'ugesi 2026 — African Digital & Innovation Festival Website

The official multi-page website for the **Fak'ugesi African Digital & Innovation Festival 2026**, built with HTML, CSS, and vanilla JavaScript.

## 🌐 Overview

This site showcases the festival's programme, signature events, resources, venues, and partners, with a consistent visual design system carried across every page.

## 📁 Project Structure

```
Fakugesi 2026/
├── index.html                  # Homepage
├── about.html                  # About the festival
├── festival-programmes.html    # Full programme listing
├── resources.html              # Resources & downloads
├── venues.html                 # Venue information
├── tickets.html                # Ticketing page
│
├── sig-awards.html             # Signature: Awards
├── sig-dalakhona.html          # Signature: Dala Khona
├── sig-fakugesipro.html        # Signature: Fak'ugesi Pro
├── sig-immersive.html          # Signature: Immersive
├── sig-jamz.html                # Signature: Jamz
├── sig-pitchathon.html         # Signature: Pitchathon
│
├── nav.js                      # Shared navigation component & link handling
├── footer.js                   # Shared footer component
│
├── discover/                   # Discover section assets
│   ├── imgs/
│   └── pdf resource/
├── fonts/                      # InterDisplay typeface files
└── images/                     # Site imagery
```

## 🎨 Design System

- **Typography:** `InterDisplay`
- **Core colours:** `--navy`, `--lavender`
- **Layout constant:** `--band: 248px` (used for footer/header banding)
- **Motifs:** Cross-icon accents, reveal-on-scroll animations, Ken Burns hero effects
- **Typographic reference:** `about.html` "Who We Are" styling (`.who-title`: 50px/900, `.who-body`: 14px/1.75 line-height) is the base standard applied across signature pages
- **Responsive breakpoints:** 1024px, 768px, 480px

## 🧩 Shared Components

- **`nav.js`** — Injects the site navigation, includes a global click interceptor with `isExempt()` logic to allow downloads/PDFs/external links to bypass SPA-style routing.
- **`footer.js`** — Injects the shared footer, including partner logos and contact information, aligned to the `--band` layout constant.

## 🛠️ Tech Stack

- HTML5
- CSS3 (custom properties / design tokens)
- Vanilla JavaScript (no framework/build step)

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Addmore-Development/Fakugesi-deployed-.git
   ```
2. Open `index.html` in a browser, or serve locally with any static server, e.g.:
   ```bash
   npx serve .
   ```

## 📄 License

© Fak'ugesi African Digital & Innovation Festival. All rights reserved.