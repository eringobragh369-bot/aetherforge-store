# AetherForge Revenue Engine (GitHub Pages)

Live storefront + automatic post-payment download page.

## Structure

- `index.html` — Main store (all live Stripe buttons)
- `success.html` — Post-payment download page
- `products/` — All deliverable files

## After Payment Flow

1. Customer pays via Stripe Payment Link
2. Stripe redirects them to `success.html` on this site
3. Customer downloads the product file directly

## Stripe Setup (Required)

For each Payment Link in Stripe Dashboard:

1. Open the Payment Link
2. Edit → After payment → Redirect to a page
3. Enter your success URL:
   `https://eringobragh369-bot.github.io/aetherforge-store/success.html`
4. Save

Do this for all five products.

## Live URL

https://eringobragh369-bot.github.io/aetherforge-store/
