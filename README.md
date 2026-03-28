# chalice-products-fix

> A drop-in replacement for [chalice.ai/products](https://www.chalice.ai/products) — which currently 404s.

Built in ~10 minutes because someone had to.

## The Problem

`https://www.chalice.ai/products` returns a 404. For an AI company selling advertising products, this is... a choice.

## The Fix

A clean, modern products page built from Chalice's own homepage content:

- ✅ All three products (CurateAI, Custom AI Models, AI Audiences)
- ✅ Real stats from their homepage (1.5pts sell-through, +6% lift, 28% CPA reduction)
- ✅ Real case study links (DocSend)
- ✅ Mobile responsive
- ✅ Zero dependencies (pure HTML/CSS)
- ✅ A polite "you're welcome" banner

## Deploy

### Option A — GitHub Pages (30 seconds)
1. Fork this repo
2. Go to Settings → Pages → Source: `main` branch, `/ (root)` folder
3. Done. Your products page lives again.

### Option B — Netlify Drop
Drag `index.html` to [netlify.com/drop](https://app.netlify.com/drop). Live in 10 seconds.

### Option C — Squarespace (where it should've been)
1. Add a new page called "Products" at the `/products` URL
2. Use the "Code Block" element
3. Paste the `index.html` contents

### Option D — Vercel
```bash
npx vercel --prod
```

## Built With

- HTML + CSS (no frameworks, no JS)
- Claude Code (because irony is a powerful motivator)
- Mild exasperation

---

*Made by someone who clicked on a /products link and got a 404 instead.*
