# Harshith Ram — Portfolio

Static site, no build step. Everything needed to publish is in this `site/` folder.

```
site/
├── index.html        the portfolio
├── 404.html          "page not found" page
├── favicon.svg
├── robots.txt
└── assets/
    ├── harshith.jpg          photo (compressed)
    ├── og.jpg                link preview image (LinkedIn, WhatsApp, X)
    └── apple-touch-icon.png
```

## Publish it (pick one)

**Netlify Drop (easiest, no account setup beyond sign-in)**
1. Go to https://app.netlify.com/drop
2. Drag this whole `site` folder onto the page.
3. You get a live link like `https://something.netlify.app`. Rename it under Site settings.

**Vercel**
```bash
npx vercel deploy --prod
```
Run from inside `site/`.

**GitHub Pages**
Push the contents of `site/` to a repo named `<your-username>.github.io`, then enable Pages in the repo settings.

## After it's live

Link previews on LinkedIn and WhatsApp need full URLs. In `index.html`, replace these
with your real address (example uses `https://harshithram.netlify.app`):

- `og:image` and `twitter:image` → `https://harshithram.netlify.app/assets/og.jpg`
- `og:url` → `https://harshithram.netlify.app/`

## Editing content

All text lives in `index.html`. Search for the section label (e.g. `04 / Experience`) to find it.
Contact email is `ram.h@aptivacorp.ae`; it appears in the contact section, the mobile menu and the
structured data at the top of the file.
