# ATTIRE — Modern Clothing

A clean, minimal single-page clothing store website built with pure HTML and CSS. No frameworks, no build tools — just fast, lightweight front-end code.

## Features

- Fixed navbar with smooth-scroll navigation
- Full-viewport hero section
- Responsive product grid (4 columns → 2 → 1 on smaller screens)
- 8 featured products with Add to Cart buttons
- Footer with quick links and social media
- Google Fonts (Inter) for clean typography
- Mobile-first responsive design

## Structure

```
Website/
└── index.html   # Entire site — HTML, CSS, and content in one file
```

## Running Locally

No build step needed. Just open `index.html` in your browser:

```bash
open index.html
```

Or serve it with any static file server:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## Deployment

This site is a single static HTML file and can be deployed to any static host:

- **GitHub Pages** — push to `main` and enable Pages in repo settings
- **Netlify** — drag and drop the folder onto netlify.com/drop
- **Vercel** — `vercel --prod` from this directory

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox, custom properties)
- Google Fonts — Inter

---

&copy; 2026 Attire. All rights reserved.
