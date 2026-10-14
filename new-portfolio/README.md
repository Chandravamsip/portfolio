# Pulipati Chandra Vamsi — Portfolio

A single self-contained `index.html` (CSS, JS and photos embedded). No build step. Only Google Fonts load externally.

## Deploy

**Netlify** — drag this folder onto https://app.netlify.com/drop, or connect the repo (`netlify.toml` sets the publish directory to the root).

**Vercel** — run `npx vercel` in this folder, or import the repo at https://vercel.com/new. No framework preset needed (`vercel.json` is included).

**GitHub Pages** — push `index.html` to a repo, then Settings → Pages → Deploy from branch → `main` / root. The site appears at `https://<username>.github.io/<repo>/`.

## Notes

- Contact form: posts to FormSubmit by default (activate once via the email it sends you). For instant delivery with no activation, get a free key at web3forms.com and paste it into `W3F_KEY` near the bottom of index.html. If sending fails, a link opens Gmail compose with the message ready. Opening the file locally (file://) always uses that fallback.
- To change text, edit `index.html` directly. Photos are base64 `<img src>` values.
