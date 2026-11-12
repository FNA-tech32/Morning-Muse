# ☕ Morning Muse — Artisanal Coffee & Bakery Since 1982

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Design-Fully%20Responsive-brightgreen.svg?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![Dark Mode](https://img.shields.io/badge/Dark%20Mode-Auto%20Detect-333333.svg?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](./LICENSE)

> **Morning Muse** is a refined, multi-page website for an artisanal UK coffee house and bakery chain. Established in 1982, Morning Muse combines ethically sourced single-origin coffee roasts, loose-leaf artisan teas, and freshly baked pastries with warm, plant-filled sanctuaries located across **Brighton**, **London**, and **Manchester**.

---

## 📖 Table of Contents

- [Overview & Story](#-overview--story)
- [Website Pages & Features](#-website-pages--features)
- [Contact Details & Alternative Communication Channels](#-contact-details--alternative-communication-channels)
- [Branch Locations](#-branch-locations)
- [Technology Stack](#-technology-stack)
- [Project Directory Structure](#-project-directory-structure)
- [Getting Started & Local Setup](#-getting-started--local-setup)
- [Accessibility & Responsive Design](#-accessibility--responsive-design)
- [Customization Guide](#-customization-guide)
- [Credits & License](#-credits--license)

---

## 🌟 Overview & Story

Morning Muse was born out of a lifelong passion for artisan coffee culture. Founded by Ryan in the bohemian heart of Brighton's North Laine, the café has blossomed into a cherished destination for coffee connoisseurs, casual meetups, and quiet afternoon study sessions.

### Brand Highlights:
- **Artisan Micro-Roasting**: Direct-trade specialty arabica beans roasted weekly to preserve nuanced origin profiles.
- **Warm & Green Spaces**: Intentionally styled interiors featuring cozy seating, lush botanicals, and warm acoustic environments.
- **Community-First Hospitality**: Friendly, passionate baristas dedicated to crafting every cup with latte art and care.

---

## 🖥️ Website Pages & Features

The website is structured into 5 cohesive, high-performance static pages:

### 1. Home (`index.html`)
- **Minimalist Hero Viewport**: Clean typography highlighting the brand motto *"What better way to espresso yourself"*.
- **Quick Dual Action Buttons**: Direct navigation to explore the menu (`Treat Yourself`) or jump straight to the contact desk (`Contact Us`).
- **Instant Hotline Preview**: Displays central telephone and WhatsApp quick links directly on the landing screen.
- **Adaptive Hero Art**: Utilizes `<picture>` / responsive `srcset` with modern WebP compression for sub-second load times.

### 2. Menu (`pages/menu.html`)
- **Extensive Offerings**: Organised categories covering Hot Espressos, Specialty Teas, Iced Refreshers, Artisanal Desserts, and Seasonal Signature Drinks (such as the Winter Pumpkin Latte).
- **Responsive Card Grid**: Multi-column fluid layout with prices, flavor profiles, and allergen-friendly notes.
- **Takeaway & Catering Banner**: Immediate order instructions with primary phone and alternative WhatsApp order links.

### 3. Gallery (`pages/gallery.html`)
- **Visual Portfolio**: Curated photography showcasing hand-poured latte art, flaky pastries, and café interiors.
- **Interactive Double-Click Zoom**: Vanilla JavaScript zoom interaction enabling patrons to inspect details with ease on desktop and touch devices (`scripts/gallery.js`).
- **Touch-Friendly**: Built with CSS `touch-action: pan-y` for fluid mobile swiping.

### 4. Locations & Contact Hub (`pages/locations.html`)
- **Weekly Schedule**: Standard opening hours table (Mon–Thu: 9:00am–5:00pm, Fri: 9:30am–4:30pm).
- **Branch Profiles**: Individual sections for Brighton, London, and Manchester with localized photography, exact street addresses, and direct branch phone and email.
- **Dedicated Primary & Alternative Contact Hub (`#contact`)**:
  - **Primary Contact Desk**: Central headquarters line, general email, customer service hours, and direct call buttons.
  - **Alternative Channels**: Fast WhatsApp takeaway line, order confirmation email, private hire & catering desk, wholesale bean subscriptions, and 24/7 emergency dispatch.
  - **Quick Inquiry Form**: Interactive feedback and table inquiry form with channel and branch preference selection.
- **Site-Wide Footer**: Brand summary, explore links, and quick communication contact details.

### 5. About Ryan (`pages/about.html`)
- **Personal Journey**: A heartfelt letter from founder Ryan detailing his upbringing in Brighton and his dream of opening community-focused coffee houses.
- **Direct Founder Contact Card**: Quick email and WhatsApp touchpoints for collaborative inquiries.

---

## 📞 Contact Details & Alternative Communication Channels

Morning Muse provides transparent, dedicated contact channels for everyday guests, bulk orders, event organizers, and urgent out-of-hours assistance:

| Channel Type | Department / Purpose | Contact Destination | Availability |
| :--- | :--- | :--- | :--- |
| **Primary Phone** | Central Desk & Reservations | [`+44 (0) 20 7946 0920`](tel:+442079460920) | Mon–Fri: 9:00 AM – 5:00 PM |
| **Primary Email** | General Inquiries & Customer Care | [`hello@morningmuse.co.uk`](mailto:hello@morningmuse.co.uk) | Response within 2 hours |
| **Alternative WhatsApp** | Instant Takeaway Orders & Fast Chat | [`+44 (0) 7700 900 842`](https://wa.me/447700900842) | Mon–Sun: 8:00 AM – 6:00 PM |
| **Alternative Email** | Pre-Orders, Receipts & Invoicing | [`orders@morningmuse.co.uk`](mailto:orders@morningmuse.co.uk) | Mon–Fri: 8:30 AM – 5:30 PM |
| **Alternative Events** | Private Café Hire & Event Catering | [`events@morningmuse.co.uk`](mailto:events@morningmuse.co.uk) | Mon–Fri: 9:00 AM – 5:00 PM |
| **Alternative Wholesale**| Roasted Bean Subscriptions & Machines | [`beans@morningmuse.co.uk`](mailto:beans@morningmuse.co.uk) | Mon–Fri: 9:00 AM – 5:00 PM |
| **Out-of-Hours Line** | Emergency, Logistics & Couriers | [`+44 (0) 800 048 7654`](tel:+448000487654) | 24 Hours / 7 Days |

---

## 📍 Branch Locations

### ☕ Brighton (Flagship & Roastery)
- **Address**: 42 Bond Street, North Laine, Brighton BN1 1RD, United Kingdom
- **Direct Telephone**: `+44 (0) 1273 800 912`
- **Branch Email**: `brighton@morningmuse.co.uk`
- **Features**: Outdoor street seating, live roasting demonstrations, and bean retail bar.

### ☕ London (West End Flagship)
- **Address**: 158 Oxford Street, West End, London W1D 1ND, United Kingdom
- **Direct Telephone**: `+44 (0) 20 7946 0920`
- **Branch Email**: `london@morningmuse.co.uk`
- **Features**: Two spacious floors, co-working tables with power outlets, and full artisan pastry counter.

### ☕ Manchester (Northern Hub)
- **Address**: 84 Oxford Road, Manchester M1 5WH, United Kingdom
- **Direct Telephone**: `+44 (0) 161 496 0341`
- **Branch Email**: `manchester@morningmuse.co.uk`
- **Features**: Lush indoor botanical garden, specialty cold brew tap, and quiet study alcoves.

---

## 🛠️ Technology Stack

- **Core Structure**: Semantic HTML5 with proper heading hierarchy, ARIA attributes, OpenGraph protocol, and Twitter Card metadata.
- **Styling Architecture**: Vanilla CSS3 utilizing:
  - Custom CSS properties (Design Tokens for brand colors, spacing, and typography)
  - CSS Grid and Flexbox for responsive layouts
  - Native Smooth Scrolling (`scroll-behavior: smooth`)
  - Automatic Dark Mode via `@media screen and (prefers-color-scheme: dark)`
  - Motion accessibility via `@media (prefers-reduced-motion: reduce)`
- **Typography**: Locally hosted `Josefin Sans` and `Poppins` fonts via modern WOFF2 format for zero external layout shifts.
- **Interactivity**: Pure JavaScript (ES6+):
  - Accessible mobile hamburger navigation drawer (`script.js`)
  - Double-click/double-tap image zoom modal with touch optimization (`scripts/gallery.js`)
- **PWA Ready**: Web App Manifest (`site.webmanifest`) with multi-size touch icons.

---

## 📁 Project Directory Structure

```text
Morning-Muse/
├── index.html                   # Landing homepage with hero banner and quick contact
├── site.webmanifest             # PWA web manifest with Morning Muse branding
├── style.css                    # Global styling & landing page styles
├── script.js                    # Mobile navigation toggle and drawer script
├── apple-touch-icon.png         # iOS icon
├── favicon.ico                  # Standard favicon
├── favicon-16x16.png            # 16x16 Favicon
├── favicon-32x32.png            # 32x32 Favicon
├── android-chrome-192x192.png   # Android launcher icon (192x192)
├── android-chrome-512x512.png   # Android launcher icon (512x512)
├── LICENSE                      # MIT Open Source License
├── README.md                    # Project documentation
│
├── pages/                       # Multi-page website views
│   ├── about.html               # Ryan's founder story and direct contact box
│   ├── gallery.html             # Interactive café & latte art photo gallery
│   ├── locations.html           # Branch locations, hours, and Contact Hub
│   └── menu.html                # Artisan beverages and bakery menu
│
├── css/                         # Page-specific modular stylesheets
│   ├── about.css                # Styles for about page layout and image container
│   ├── gallery.css              # Gallery grid and modal zoom styling
│   ├── locations.css            # Opening hours, branch cards, Contact Hub & footer
│   └── menu.css                 # Menu card grid, prices, and allergen badges
│
├── scripts/                     # Modular JavaScript
│   └── gallery.js               # Gallery image zoom & touch interactions
│
└── assets/                      # Media and typography assets
    ├── about/                   # High-res responsive founder imagery
    ├── fonts/                   # Locally hosted Josefin Sans & Poppins WOFF2 fonts
    ├── gallery/                 # Curated showcase photography
    ├── index/                   # Landing hero coffee & grinder graphic variants
    ├── locations/               # Branch photos (Brighton, London, Manchester) & SVGs
    ├── logo/                    # Vector / webp logo assets
    ├── menu/                    # Beverage & pastry product photography
    └── open_graph/              # Social media sharing preview images
```

---

## 🚀 Getting Started & Local Setup

The project runs 100% natively in any modern web browser without requiring complex build steps, compilers, or `node_modules`.

### 1. Clone or Download the Repository
```bash
git clone https://github.com/Roxaski/Coffee-Cup-Cafe.git Morning-Muse
cd Morning-Muse
```

### 2. View in Browser
- **Direct**: Double-click `index.html` to open it in your default web browser.
- **Local Server (Recommended)**: Run a lightweight HTTP server to test web manifests and relative paths:
  ```bash
  # Using Python 3
  python -m http.server 8000
  ```
  Then visit [http://localhost:8000](http://localhost:8000) in your browser.

  *Alternatively, using Node.js:*
  ```bash
  npx serve .
  ```

---

## ♿ Accessibility & Responsive Design

- **Semantic HTML**: Proper use of `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` elements.
- **Keyboard & Screen Reader Accessible**: Navigation links use ARIA states (`aria-expanded`, `aria-label`).
- **Dark Mode Support**: All pages automatically adapt to user system theme preferences via CSS `prefers-color-scheme: dark`.
- **Reduced Motion**: Respects users with vestibular motion sensitivities through `@media (prefers-reduced-motion: reduce)`.
- **Device Support**: Fully tested and optimized for mobile screens (320px+), tablets, laptops, and ultra-wide displays (up to 1920px).

---

## 🎨 Customization Guide

- **Brand Details**: Update the brand name across the `<title>` and `<p class="logo">` tags in `index.html` and `pages/*.html`.
- **Contact Details**: Update the primary desk or alternative communication numbers in `pages/locations.html` under the `#contact` section.
- **Color Palette**: Modify the CSS variables inside `:root` in `style.css` and `css/*.css`:
  ```css
  :root {
      --clr-white: #f7f4f4;
      --clr-blk: #212121;
      --clr-brown: #b27526;
      --clr-darkBrown: #865340;
  }
  ```

---

## 📜 Credits & License

- **Design & Code**: Originally created by [Roxaski](https://github.com/Roxaski).
- **Brand & Content Updates**: Rebranded to **Morning Muse** with expanded primary and alternative contact infrastructure.
- **Photography**: Unsplash, Pexels, and Pixabay creators.
- **License**: Released under the [MIT License](LICENSE).
