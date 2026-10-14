# Growth Vistara website

Static site (HTML/CSS/JS, no build step).

## Deploy on GitHub Pages
1. Create a repo and upload everything in this folder (index.html, assets/, .nojekyll).
2. Repo > Settings > Pages > Source: "Deploy from a branch" > Branch: main, folder: / (root) > Save.
3. Your site goes live at https://<username>.github.io/<repo>/ in about a minute.

## Before launch
- Enquiry form: set CONFIG.FORM_ENDPOINT near the bottom of index.html (Formspree / Web3Forms). Until then the form shows a "not connected" message and sends nothing.
- Footer: add verified email, phone and social links.
- Replace the Privacy Policy and Terms placeholders with reviewed text.
- Replace the "[Project title]" cards with real projects.
