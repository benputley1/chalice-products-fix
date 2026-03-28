# chalice-products-fix

A drop-in replacement products page for [chalice.ai/products](https://www.chalice.ai/products), which currently returns a 404.

Built to match Chalice's existing design system — Poppins + Manrope fonts, their actual colour palette, and layout consistent with the rest of their site.

## What's included

- All three products (CurateAI, Custom AI Models, AI Audiences)
- Real stats from their homepage (1.5pts sell-through, +6% lift, 28% CPA reduction)
- Real case study links (DocSend)
- Mobile responsive
- Zero dependencies (pure HTML/CSS)

## Deploy

### Option A — GitHub Pages (30 seconds)
1. Fork this repo
2. Go to Settings → Pages → Source: `main` branch, `/ (root)` folder
3. Done.

### Option B — Netlify Drop
Drag `index.html` to [netlify.com/drop](https://app.netlify.com/drop). Live in seconds.

### Option C — Squarespace
1. Add a new page at the `/products` URL
2. Use a Code Block element
3. Paste the contents of `index.html`

### Option D — Vercel
```bash
npx vercel --prod
```
