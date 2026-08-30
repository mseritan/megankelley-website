# megankelley.space

Source code for my personal website — CV, portfolio, and (eventually) a blog.

**Live site:** https://megankelley.space

## Built with
- [Astro](https://astro.build) — static site generator
- Plain HTML/CSS (no JS framework)
- Hosted on [Netlify](https://netlify.com), auto-deployed from the `main` branch on every push
- Domain registered through Namecheap

## Project structure
```
src/
├── layouts/
│   └── Layout.astro          # shared <head>, nav bar, global styles
├── pages/
│   ├── index.astro           # homepage
│   ├── cv.astro              # CV
│   └── portfolio/
│       ├── index.astro       # portfolio grid (all categories)
│       └── [category].astro  # dynamic route — one auto-generated page per category
├── data/
│   └── portfolio.js          # portfolio category data (titles, cover images, descriptions)
└── assets/
    └── portfolio/            # all portfolio images, organized by supercategory/category
public/
├── profile-photo.png
└── favicon.png
```
