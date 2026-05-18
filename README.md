# 6sMaker — Website

The marketing and portfolio site for 6sMaker, a design-first creative studio. Built with Astro.

## Stack

- **[Astro](https://astro.build)** — static site generator
- **Cloudinary** — video hosting (hero + hype reel)
- No JavaScript frameworks — all interactions are vanilla JS

## Project Structure

```
src/
├── layouts/
│   └── Layout.astro   # Shared layout: nav, footer, global styles
└── pages/
    ├── index.astro
    ├── about.astro
    ├── contact.astro
    ├── confidentiality.astro
    ├── portfolio.astro
    └── portfolio/     # Individual case study pages
```

## Commands

| Command           | Action                               |
| :---------------- | :----------------------------------- |
| `npm install`     | Install dependencies                 |
| `npm run dev`     | Start dev server at `localhost:4321` |
| `npm run build`   | Build to `./dist/`                   |
| `npm run preview` | Preview the production build locally |
