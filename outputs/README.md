# DigiMart

DigiMart is a single-page static storefront for premium digital subscriptions and digital products. It presents entertainment, productivity, AI tools, and VPN products in a clean marketplace-style homepage.

## Overview

This project is built as one static HTML page with embedded CSS and JavaScript. It does not require a backend, database, build tool, login system, checkout flow, or external app framework.

## Features

- Minimal premium storefront design
- Compact navbar, hero, category strip, filter bar, product grid, and footer
- Product-first homepage layout
- 21 sample digital subscription products
- Category-aware generated product thumbnails
- Interactive client-side filters
- Responsive layout for desktop, tablet, and mobile
- No authentication, dashboard, checkout, or backend logic

## Product Categories

- Entertainment
- Productivity
- AI Tools
- VPN

## Files

```text
index.html
```

The complete website is contained in `index.html`.

## How to Run

Open `index.html` directly in a browser.

If you prefer running it through a local server:

```bash
python -m http.server 4173
```

Then open:

```text
http://127.0.0.1:4173/index.html
```

## Customization

Products are defined inside the JavaScript section of `index.html`. You can edit product names, categories, prices, durations, warranty labels, and thumbnail color tones from the `products` array.

## Tech Stack

- HTML
- CSS
- JavaScript
- Plus Jakarta Sans
- Inline SVG icons and generated SVG thumbnails

## License

This project is for personal or portfolio use. Add your preferred license before publishing publicly.
