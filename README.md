# photography-portfolio-landing-or-fine-art-gallery-landing

Single-page landing site for a fine-art black-and-white photography portfolio — floating framed hero image, Explore Gallery CTA.

## Overview

A self-contained, mobile-first landing page presented as an online gallery for a
fictional photographer (**Mara Voss**). Modern, minimal, editorial — neutral
palette, true-black framing, generous negative space, and restrained motion.

Everything lives in a single file: **`index.html`** (HTML + CSS + a touch of
vanilla JS, no build step).

## Run

Open `index.html` in any modern browser, or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Features

- **Minimal fixed header** — small-caps logotype, sparse Work / About / Contact
  nav, blur-on-scroll, accessible mobile menu.
- **Asymmetric hero** — confident display headline + a single primary CTA
  (`EXPLORE GALLERY`) with a clean invert/slide hover.
- **Floating framed hero photo** — thin black modern frame, soft drop shadow,
  perpetual float plus pointer-tilt and scroll parallax.
- **Mini gallery strip** — staggered high-contrast monochrome plates.
- **Accessible & performant** — semantic HTML, alt text, visible focus states,
  skip link, lazy-loaded imagery, and full `prefers-reduced-motion` support.

## Swapping the hero / gallery images

Replace the `src` (and `alt`) of the `<img>` inside `.frame` for the hero, and
the `.plate` images in the gallery section. Placeholders use Unsplash URLs.
