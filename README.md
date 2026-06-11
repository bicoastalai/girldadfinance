# Girl Dad Finance

**Raising Financially Fearless Daughters**

Coming-soon landing page for [girldadfinance.com](https://girldadfinance.com).

---

## Stack

- Plain HTML + CSS (no framework — intentionally simple while building out)
- Hosted on **Vercel** (auto-deploys on every push to `main`)
- Domain registered on **Namecheap**, DNS pointed to Vercel

## Project Structure

```
girldadfinance/
├── index.html        # Landing page
├── styles.css        # All styles, design tokens, responsive layout
└── assets/
    ├── logo-card.png # Brand card — hero image
    └── hero.png      # Original gym photo (kept for reference)
```

## Local Development

No build step needed. Open `index.html` directly in a browser, or use any static server:

```bash
npx serve .
```

## Deploying

Push to `main` — Vercel picks it up automatically.

```bash
git add .
git commit -m "feat: your change"
git push
```

## Brand Tokens

| Token | Value | Usage |
|-------|-------|-------|
| Forest Green | `#2d6a4f` | Primary accent, borders |
| Light Green | `#52b788` | Secondary accent, brand name |
| Gold | `#c9a84c` | Tagline, CTA button, gradient |
| Background | `#0d1a12` | Page background |
| Surface | `#132019` | Card background |

## Open TODOs

- [ ] Hook email form to Mailchimp or ConvertKit
- [ ] Add About section
- [ ] Add Blog/content section
- [ ] Consider migrating to Next.js when content grows
