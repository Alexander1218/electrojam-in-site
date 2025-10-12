# electrojam-in-site
Electrojam.in Beta: no-framework static site for M8 livestream — hero, 16:9 player, Stripe “Buy Ticket”, and protected badge. Deployable on Cloudflare Pages.
# electrojam-in-site

Electrojam.in **Beta** landing page. Pure static HTML/CSS with:
- Hero logo + protection badge
- 16:9 Castr player embed
- **Join the Beta** button (Stripe Payment Link)
- No JS build tooling required; perfect for Cloudflare Pages

## Live structure
- `index.html` – single page layout
- `ASSETS/IMAGES/` – hero + badge
- `ASSETS/VIDEOS/` – (optional)
- `ASSETS/CSS/` – (optional; styles inline in `index.html` for now)

## Configure
- Update the iframe `src` with the current Castr URL
- Replace `STRIPE_PAYMENT_LINK` with your live Payment Link:
  `https://buy.stripe.com/...`

## Deploy (Cloudflare Pages)
- Project type: **Direct Upload / Connect to Git**
- Build command: **None**
- Output directory: **/**

## License
Private © Electrojam.in

