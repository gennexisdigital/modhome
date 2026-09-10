# modhome — website

Static, bilingual (EN / 中文) website for **modhome**, a luxury interior design studio.

- `index.html` — the whole site (HTML, CSS, JS in one file)
- `img/` — optimised WebP photography, 4 per project (38 projects)
- Deployed automatically to GitHub Pages on every push to `main` (see `.github/workflows/pages.yml`).

## Before going live
Search `index.html` for the placeholders and replace them:

| Placeholder | What to put |
|---|---|
| `[AWARD NAME]` / `[CATEGORY · YEAR]` (×3) and `[N]` | Award names, years, and the total count |
| `[DESIGNER NAME]` / `[设计师姓名]` | Lead designer |
| `6500000000` (in `wa.me/` links) | WhatsApp number, country code + number, digits only |
| `[+65 0000 0000]`, `[hello@modhome.design]`, `[WeChat ID]`, `[Studio address · City]` | Contact details |
| `[PASTE-WEB3FORMS-ACCESS-KEY]` | Free key from web3forms.com so the enquiry form emails you (until then it falls back to opening the visitor's mail client) |

## Local preview
Open `index.html` in a browser — no build step needed.
