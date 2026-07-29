# Tandem Search Partners — website

Rebranded marketing site: retained executive search positioned for C-suite buyers
(CFOs first), emphasizing the pairing of veteran search partners with **Meridian™**,
the firm's proprietary talent-intelligence platform.

Static site — no build step, no dependencies. Open `index.html` in a browser, or
serve the folder from any static host (GitHub Pages, Netlify, S3, etc.).

## Structure

```
index.html          Single-page site (hero, stakes, method, platform, practices,
                    process, FAQ, contact)
css/styles.css      Monochrome design system (ink #0c0c0b on paper #fbfaf7)
js/main.js          Nav, scroll reveal, stat count-up, form handling
assets/logo.svg     Interlocked-strand mark + wordmark
assets/favicon.svg  Mark on black tile
```

## Brand system

- **Name:** Tandem Search Partners — "in tandem": human judgment and machine
  precision working as two strands of one method.
- **Mark:** two interlocked rings woven over-and-under; the interweave motif
  recurs as braid graphics in the hero and Method section (`#braid` SVG symbol
  in `index.html`).
- **Palette:** strictly black and white — ink `#0c0c0b`, paper `#fbfaf7`,
  tint `#f2f1ec`, hairlines `#e0dfd9` / `#2c2c2a`. No accent color; hierarchy
  comes from scale, weight, and inversion (dark sections).
- **Type:** Fraunces (display serif) + Inter (text), loaded from Google Fonts
  with system fallbacks.

## Placeholders to replace before launch

- **Statistics** in the hero stat bar (94% retention, 28-day shortlist, 68%
  passive, 400+ searches) are illustrative — replace with the firm's real,
  defensible numbers.
- **Replacement assurance / fee language** in the FAQ — confirm against actual
  engagement-letter terms.
- **Contact details** — `searches@tandemsearchpartners.com` and
  `+1 (713) 555-0147` are placeholders (555 number is fictional).
- **Contact form** is client-side only; wire it to a form service (Formspree,
  Basin) or CRM endpoint in `js/main.js` / the form `action`.
- **Meridian panel** figures (search 24-117) are illustrative.
