# Niko Nikolic — Cash Offer Landing Page

Static, single-page site. No build step, no dependencies — plain HTML + CSS.
Content migrated from the Homebase-hosted page at `homebasemail.io/site/nemanja-nikolic`.

## Files

- `index.html` — the whole page
- `css/site.css` — all styles
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Before going live

The contact form sends submissions to `Berrystreetholdingsllc@gmail.com` through
[FormSubmit](https://formsubmit.co):

```html
<form action="https://formsubmit.co/Berrystreetholdingsllc@gmail.com" method="post" class="lead-form">
```

The first submission sends a confirmation link to that address — click it once to
activate delivery. Until then, nothing is delivered.

## Publishing on GitHub Pages

Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
The site goes live at `https://lm0323.github.io/NikoCashOffer/`.

For a custom domain, add a `CNAME` file containing the bare domain, then point four
A records at GitHub (`185.199.108-111.153`) and a `www` CNAME at `lm0323.github.io`.

## Design

| Token | Value |
| --- | --- |
| Primary green | `#15803d` |
| Dark panels | `#0f172a` |
| Mint sections | `#f0fdf4` |
| Body text | `#475569` |
| Font | Inter 400–900 |
