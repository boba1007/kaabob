# kaabob

Personal site for [Bob Le](https://kaabob.com) — built with Astro, styled in pure black and white, animated with GSAP.

## Stack

- [Astro 5](https://astro.build) — static site generation
- [Tailwind CSS v3](https://tailwindcss.com) — utility styling (black/white palette only)
- [GSAP + ScrollTrigger](https://gsap.com) — all animations
- [Cormorant Garamond + Inter](https://fonts.google.com) — display and body fonts

## Commands

```bash
npm install       # Install dependencies
npm run dev       # Start dev server at localhost:4321
npm run build     # Build for production → dist/
npm run preview   # Preview production build locally
npm run check     # Type-check all .astro files
```

## Deployment

Static output. Deploy the `dist/` folder to any static host.

The `public/_headers` file configures security headers for **Netlify**. For other platforms, adapt those headers to your host's config format (Vercel `vercel.json`, Cloudflare Pages `_headers`, etc.).

> Run Lighthouse against `npm run preview` (production build) for accurate scores — the dev server skips minification and optimization.
