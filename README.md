# Walkin'Life — Travel Agency Landing Page (Capstone)

**Theme:** Travel Agency — Walkin'Life  
**Files:** `index.html`, `style.css`, `images/` (placeholders), `README.md`

## Summary
A single-page responsive landing page for a travel agency, built with only HTML5 and CSS3. It showcases destinations, curated packages, "how it works", testimonials, stats, blog previews, newsletter signup and a contact form.

## Features implemented
- Full-width hero with dark overlay and CTA
- Transparent top nav over hero + solid sticky nav after hero (CSS-only approach)
- Popular Destinations (rounded image cards with hover lift)
- Tour Packages (earthy card style, durations & prices)
- How It Works (3-step rounded cards)
- Testimonials (minimal quote style)
- Stats (big bold numbers)
- Blog previews (earthy card style)
- Newsletter (minimal inline form)
- Contact form inside an earthy rounded card + contact info mock/map
- Minimal footer with centered copyright and social icons

## Design & Tech
- Only HTML5 and CSS3 (Flexbox and Grid used)
- CSS variables for palette and spacing
- Google Fonts: Montserrat & Inter
- Subtle hover transitions and a simple hero animation
- Semantic structure: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- Accessibility touches: `alt` attributes, labels on form fields, skip link

## Breakpoints
- Desktop ≥ 1024px — multiple grid columns (4 / 3 / 3)
- Tablet ≈ 768px — falls back to 2 columns for grids
- Mobile ≤ 480–600px — single-column stacks, compact hero

## How to run
1. Create a project folder, copy `index.html` and `style.css` into it.
2. Add an `images/` folder with images named used in the HTML (or update `index.html` to your own filenames).
   - Suggested files: `hero.jpg`, `dest1.jpg`, `dest2.jpg`, `dest3.jpg`, `dest4.jpg`, `pkg1.jpg`, `pkg2.jpg`, `pkg3.jpg`, `avatar1.jpg`, `avatar2.jpg`, `blog1.jpg`, `blog2.jpg`, `blog3.jpg`, `map-mock.jpg`, `logo.svg`.
3. Open `index.html` in any modern browser to view locally.
4. (Optional) Push the folder to GitHub and enable GitHub Pages to host.

## Notes / Customization
- Replace placeholder images in `/images` with optimized photos (unsplash is a good source).
- The sticky-nav technique uses two header bars: a transparent one overlaying the hero and a solid sticky header placed after the hero — no JavaScript required for the visual effect.
- A very small JS snippet sets the year in the footer — remove it if you want zero-JS.

---

**Good luck with submission.** If you want, I can:
- Replace placeholder images with Unsplash links (I can give direct image suggestions).
- Export the project as a zip you can download.
- Add screenshots (desktop & mobile) for the repo.
