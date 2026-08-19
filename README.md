# AgriEstate / SM Properties & Livestock Brokers

Static HTML/CSS/JavaScript marketplace prepared for GitHub Pages.

## Pages
- `index.html` — Home
- `properties.html` — Property listings
- `livestock.html` — Cattle listings
- `sell.html` — Seller submission form
- `admin.html` — Local admin listing manager
- `about.html` — About
- `contact.html` — Contact

## Deployment
This version does **not** require npm, Node.js, Vite, or a package-lock file. GitHub Actions publishes the repository root directly to GitHub Pages.

Listings created through `admin.html` are stored in the browser's localStorage, so they appear on the same browser/device and same site origin. This is suitable for a prototype; a real multi-user marketplace should later use a database/backend.
