# Aurum — Luxury Restaurant Website

Multi-page website for a fictional fine dining restaurant. Built with pure HTML, CSS, and JavaScript — no frameworks, no npm, no build step. Ready to upload directly to Hostinger or any static host.

---

## Pages

| File | Page |
|---|---|
| `index.html` | Home — hero, signature dishes, gallery, experiences |
| `menu.html` | Menu — tabbed sections: tasting menus, à la carte, wines, desserts |
| `reservations.html` | Reservations — booking form, hours, FAQ accordion |
| `about.html` | About — chef story, team, philosophy, timeline |
| `contact.html` | Contact — contact form, map, getting here |

## Structure

```
aurum-restaurant/
├── index.html
├── menu.html
├── reservations.html
├── about.html
├── contact.html
├── css/
│   └── style.css       # Full design system + all components
└── js/
    └── main.js         # Nav, animations, tabs, forms, lazy-load
```

## Design

**Archetype 02 — Editorial Dark Warm**

- Background: deep warm brown `#1a1410`
- Accent: gold `#c9a84c`
- Headings: Cormorant Garamond (serif, via Google Fonts)
- Body: Jost (sans-serif, via Google Fonts)
- All images: Unsplash CDN — free, no attribution required

## Features

- Sticky nav with scroll-triggered background
- Mobile hamburger menu with full-screen overlay
- Scroll-triggered fade-in animations (IntersectionObserver)
- Tabbed menu switcher (no page reload)
- FAQ accordion
- Booking and contact forms with client-side validation
- Hero parallax background (desktop)
- Lazy-loaded images with fade-in
- Fully responsive down to 320px

## Deploy to Hostinger

1. Log in to Hostinger and open **File Manager**
2. Navigate to `public_html`
3. Upload the entire contents of `aurum-restaurant/` (not the folder itself, its contents)
4. Open your domain — done

No database, no server-side code, no configuration needed.
