# Pip — Cold-Pressed Juice Co.

Marketing site for **Pip**, a small-batch cold-pressed juice brand. Static
HTML/CSS/JS, no build step, no dependencies.

## Structure

```
index.html       one-page site: hero, menu, about, visit, footer
css/style.css    design tokens + all styles
js/main.js       mobile nav toggle + scroll-reveal animation
assets/          favicon
```

## Run it locally

Any static server works. From this folder:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Before you launch

This is a first draft with **placeholder content** — swap in the real details:

- Address, hours, phone, and email in the "Visit" section (`index.html`)
- Juice names, ingredients, and prices in the "Menu" section
- Social links in the footer (currently `#`)
- Brand name / copy, if "Pip" isn't the final name

## Deploy

It's plain static files, so any of these work with zero config:

- **Netlify** — drag the folder into the Netlify dashboard, or `netlify deploy`
- **Vercel** — `vercel` from this folder
- **GitHub Pages** — push to a repo, enable Pages on the `main` branch

## Design notes

Visual system is built around vintage citrus-crate-label art: bold
color-blocked sections (ink / cream / orange / lime / pink), thick ink
outlines, sunburst illustrations, and stamped badges — instead of stock
photography. Fonts: Fraunces (display), Inter (body), Space Mono (labels/
prices), loaded from Google Fonts.
