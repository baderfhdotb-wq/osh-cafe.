# OSH ATELIER V4 — MULTIPAGE

A polished, static, responsive Arabic OSH coffee brand prototype, based on the original user-provided website.

## Pages
- `index.html` — premium homepage with central coffee-bean animation (CSS; no 3D models)
- `menu.html` — photo-based menu; search, filters, sorting, favorites, product customization
- `story.html` — story, identity, brand values
- `journey.html` — 11-second cinematic journey from Cairo to Kuwait, five chapters, **no bottom timeline**
- `gallery.html` — separate photo gallery
- `contact.html` — official contact page waiting for verified business details

## Demo commerce workflow
- Add products to a persistent `localStorage` demo cart.
- Choose size, milk and sugar. Large size adds 0.300 KWD; plant milks add 0.200 KWD (placeholder modifiers).
- Change quantity, remove products, clear the cart.
- Preview cart summary; copy the summary. No real order, payment, delivery, checkout, server or customer data capture.
- No official menu or prices have been provided; all examples must be reviewed and approved by OSH.

## Run
Open `index.html` directly in Chrome/Edge or host the `site` files in a static server. We recommend using HTTPS static hosting (GitHub Pages, Vercel, cPanel) because fonts, photos and future integrations rely on the internet.

## Photos and branding
- External Unsplash photographs are real editorial reference photographs, **not pictures of OSH products**. See `PHOTO_SOURCES.md`. Images need internet; SVG fallback displays if blocked.
- Transparent OSH SVG logo is a newly recreated vector interpretation based on the supplied brand-reference screenshot; request the official vector logo from the brand before commercial launch. It has **no dark background** and reads **OSH**, not OUSH.
- The trip map is an artistic concept, not precise GIS or 3D terrain; its 11-second interaction is real.

## Commercial launch checklist
- Receive OSH official logo, product list and prices, product photography, branch address and hours, social accounts.
- Connect a secure back end, real checkout, payments (e.g. KNET via a licensed PSP), delivery, order tracking and admin panel.
- Security review, payment/webhook validation, accessibility, image licenses, performance tests and phone/browser QA.

## Heritage
`legacy/coffee-single (3)(2)-original.html` = original intact user source.
`legacy/OSH_PREVIOUS_MULTIPAGE.zip` = unchanged copy of preceding multipage site (without nested legacy).
