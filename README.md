# Trattoria Lucia

A one-page restaurant website for a fictional Italian trattoria, built with **Bootstrap 5** using Bootstrap's utility and component classes in place of custom CSS.

## What's on the page

- **Navbar** — a dark navbar that sticks to the top and collapses into a hamburger menu on mobile
- **Hero** — a full-width photo with a dark overlay, a headline, and buttons that link to the menu and visit sections
- **About** — three feature boxes laid out on the Bootstrap grid
- **Menu** — Starters / Mains / Desserts tabs (Bootstrap nav pills) showing **cards** with photos, prices, and dietary badges
- **Visit** — opening hours in a table inside a card, plus call and directions buttons
- **Footer** — copyright line and a nav with social icons

## Technologies

- Bootstrap 5.3 and Bootstrap Icons, loaded from the jsDelivr CDN
- Plain HTML with no build step
- Netlify Image CDN (`/.netlify/images`), which resizes the food photos and serves them as WebP

## Run locally

Any static server works, for example:

```bash
npx serve .
```

To load images through the Image CDN locally, use `netlify dev` instead.
