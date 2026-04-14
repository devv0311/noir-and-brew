# ✦ Noir & Brew

**A specialty café landing page for a fictional venue in Koregaon Park, Pune.**

Live demo → [noir-and-brew.netlify.app](https://noir-and-brew.netlify.app)

---

## Overview

Noir & Brew is a dark, editorial-styled landing page for a specialty coffee café. The project focuses on atmosphere-first design — using a monochrome color palette, deliberate typography, and subtle motion to reflect the brand's "slow morning, quiet corner" positioning.

Built as a frontend portfolio project simulating a real client brief for a local hospitality business.

---

## Sections

| Section | Description |
|---|---|
| **Navbar** | Fixed header with smooth-scroll links and mobile hamburger menu |
| **Hero** | Full-screen headline with dual CTAs — menu scroll and WhatsApp reservation |
| **Marquee Ticker** | Infinite scrolling banner listing café highlights (Nitro Cold Brew, Single Origin Beans, etc.) |
| **Our Story** | About section with stat counters (4.9★ rating, 60+ menu items, 4 years in Pune) |
| **Menu** | 4-category grid — Filter & Pour-Over, Cold Brew Bar, Baked In-House, All-Day Plates — with pricing |
| **Why Come Back** | Feature highlights (late hours, flexible seating, no minimum order, private events) |
| **Testimonials** | 3 customer reviews with star ratings |
| **Visit Us** | Contact section with address, hours, phone, email, Google Maps embed, and WhatsApp/Call CTAs |

---

## Features

- Fixed navbar with mobile hamburger toggle
- WhatsApp reservation CTA linked with a pre-filled message
- Infinite CSS marquee ticker with no JavaScript
- Scroll-triggered reveal animations using `IntersectionObserver`
- Google Maps embed for location
- Fully mobile-responsive layout

---

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic structure across all sections |
| CSS3 | Dark theme, CSS variables, Flexbox/Grid, keyframe marquee animation |
| Vanilla JavaScript | Hamburger nav toggle, scroll reveal via `IntersectionObserver` |
| Netlify | Static site deployment |

---

## Project Structure

```
noir-and-brew/
├── index.html
├── style.css
└── script.js
```

---

## Design Decisions

- **Dark palette** — near-black backgrounds with off-white text to match the brand's moody, upscale feel
- **Marquee ticker** — CSS-only infinite scroll, no JS library required
- **WhatsApp CTA** — practical for a local café context where direct messaging is the primary booking method
- **Minimal color accent** — single warm accent color used sparingly to guide the eye without breaking the dark aesthetic

---

## Getting Started

```bash
git clone https://github.com/devv0311/noir-and-brew.git
```

No dependencies, no build step — open `index.html` in a browser.

---

## Author

**Dev Choudhary** — [github.com/devv0311](https://github.com/devv0311)
