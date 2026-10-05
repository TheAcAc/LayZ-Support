# LayZ Support landing page

Static GitHub Pages site for the LayZ by Princess project. It is intentionally separate from the private releases repository so the project details can be publicly reviewed during payment-provider account setup.

The intended GitHub Pages URL is <https://theacac.github.io/LayZ-Support/>.

## Before enabling checkout

1. Create a Stripe Payment Link for voluntary, one-time support.
2. Replace `YOUR_STRIPE_LINK` in `config.js` with the real `https://buy.stripe.com/...` URL.
3. Add a support email address to the payment-help FAQ in `index.html`.
4. Confirm the wording and Stripe account details match the actual offering and your local requirements.

GitHub Pages is configured to deploy from the `main` branch root. Changes pushed to `main` will publish automatically.

Without a configured Stripe URL, the page keeps checkout disabled and says that the link is being set up.

## Local preview

Open `index.html` directly in a browser. No build step or dependencies are needed.

