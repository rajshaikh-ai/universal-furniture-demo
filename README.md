# Universal Furniture, Jalandhar – demo website

Client preview of the Universal Furniture website. Plain static HTML/CSS/JS: no framework, no build step, no backend.

Live preview (GitHub Pages): https://rajshaikh-ai.github.io/universal-furniture-demo/

## Structure
- `index.html` – the whole site (styles and script inline).
- `assets/img/` – optimized WebP + JPEG photos, logo mark and favicon.
- `.github/workflows/pages.yml` – deploys the repository root to GitHub Pages on every push to `main`.

All asset paths are relative, so the site works under the `/universal-furniture-demo/` subpath and later on a custom domain.

## Run locally
```
python3 -m http.server 8000
```
then open http://localhost:8000.

## Notes
- The demo has `noindex` set so search engines don't list it before launch. Remove that meta tag and update the canonical / og:url when the real domain is connected.
- Enquiry buttons open WhatsApp (wa.me/919872990970) with a prefilled message; nothing is sent automatically.
