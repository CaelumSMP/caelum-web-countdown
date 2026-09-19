# caelum-web-countdown

Pre-launch countdown page for the CaelumSMP website. Static files, no build step, served by GitHub Pages at caelumsmp.com.

- `index.html`: countdown, Discord card, newsletter sign-up
- `confirmed.html`: where Kit sends people after they confirm their email
- `style.css`: shared styles

**Settings** (top of the `<script>` in `index.html`):
- `LAUNCH`: launch moment in UTC.
- `KIT_FORM_ID`: the Kit form the sign-up posts to (public ID, not a secret). Empty hides the sign-up card.

**Run locally:** `python -m http.server` in this folder, then open http://localhost:8000.
