# AGENTS.md

## Architecture
A static single-page site with no build step. Netlify publishes the repository root (see `netlify.toml`).

- `index.html` — the whole site: navbar, hero, about, menu tabs with cards, visit section, footer
- `img/` — the original AI-generated PNG photos

## Conventions
- **Bootstrap classes only.** The goal of this project is to show off Bootstrap 5, so don't add a `<style>` block or a custom stylesheet. Build layouts from grid, spacing, color, and utility classes such as `object-fit-cover`, `ratio`, `bg-opacity-*`, and `position-*`.
- Load Bootstrap 5.3.3 and Bootstrap Icons from the jsDelivr CDN. The JS bundle runs the navbar collapse and the menu tabs.
- Always reference images through the Netlify Image CDN, e.g. `/.netlify/images?url=/img/pizza.png&w=600&fm=webp`, and never link the full-size PNGs directly.
- A menu item is a `.col > .card` inside a tab pane's `row-cols-*` grid. To add a dish, copy an existing card.
