# Purser — landing page

Static waitlist landing page for **Purser** (AI fund operations for emerging VC managers), part of the Vela family.

## Before you go live — 3 swaps
1. **Domain:** find-and-replace `purser-domain.com` → your real domain in `index.html`, `robots.txt`, and `sitemap.xml`.
2. **Formspree:** create a dedicated form at formspree.io and replace the form ID `xlgyewva` in `index.html` (two `<form action=...>` tags). Until then, signups land in Vela's Formspree tagged `proposition: Purser — Fund Admin`.
3. **Email (optional):** `hello@fundvela.com` is used as the contact; swap for a Purser address if/when you set one up.

## Deploy (same as Vela)
1. Create a GitHub repo and push this folder.
2. In Vercel: **Add New → Project → Import Git Repository** → select the repo → confirm **Production Branch = main** → Deploy.
3. Buy/add the domain in **Vercel → Settings → Domains** (buying it in Vercel auto-configures DNS).
4. Enable **Vercel → Analytics** (the analytics script is already in the page).
