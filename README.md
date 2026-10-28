# Veya: Learning that stays

Landing page for Veya. One static file, no build step.

- `index.html`: the whole page. CSS (design tokens in `:root` at the top) and JavaScript are inline.
- `veya_logo_clean.png`: logo.

Fonts load from Fontshare (Satoshi) and Google Fonts (Inter).

Waitlist forms open the visitor's email app (mailto). Swap in a form backend (Formspree, Tally, etc.) to collect sign-ups directly.

## Hosting
Works on GitHub Pages, Vercel or Netlify as-is. For GitHub Pages: Settings > Pages > Deploy from branch > `main` / root.
