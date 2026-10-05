# Luxora Jewelry – E-commerce Website

A modern, dark and gold jewelry store website built with pure **HTML, CSS and JavaScript**. It is a single file (`index.html`) with no frameworks and no build step.

**Created by Jagdish Maliwad**

---

## Features

- **Responsive layout** that works on desktop, tablet and mobile
- **Sticky header** with animated menu tabs (Shop, Collections, Best Sellers, New In, About, Journal)
- **Active tab highlighting** that follows the section you are viewing
- **Hero slider** with 3 slides, auto-rotation every 5 seconds, and a progress line
- **Shop by Collection**: click a category to filter products
- **Trending products** with ratings, wishlist hearts and add-to-cart
- **Search** with live results as you type
- **Wishlist drawer** with a live counter
- **Cart drawer** with quantity controls, total and a checkout demo
- **Sign-in panel** (demo)
- **Newsletter** with email validation
- **Sale banner** with a discount code message
- **Animations**: scroll reveal, hover effects, floating hero art, gold shimmer text, scroll progress bar
- Respects the `prefers-reduced-motion` setting

## Getting Started

1. Download `index.html`.
2. Open it in any modern browser (double-click the file).

To host it, upload `index.html` to any static host such as GitHub Pages, Netlify or Vercel.

## Project Structure

```
.
├── index.html   # Complete website (HTML + CSS + JS)
└── README.md    # Project documentation
```

## Customization

- **Products:** edit the `P` array in the `<script>` section (name, price, category, rating, type).
- **Colors:** change the CSS variables in `:root` (`--gold`, `--bg`, `--card`, `--line`).
- **Images:** the product art is generated as SVG. To use real photos, replace the `art()` output with `<img>` tags.
- **Fonts:** Cormorant Garamond and DM Sans are loaded from Google Fonts, which needs an internet connection.

## Notes

- Checkout, login and the discount code are front-end demos. There is no backend, payment or account system.
- Cart and wishlist data are kept in memory and reset when the page reloads.

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox, animations)
- Vanilla JavaScript (no libraries)

## Author

**Jagdish Maliwad**

## License

© 2024 Luxora Jewelry. All rights reserved. Created by Jagdish Maliwad.
