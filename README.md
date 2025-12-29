# Pan-American International Company Ltd. (台美洋行國際股份有限公司) — GitHub Pages Site

This repo is a fast, single-page bilingual (Traditional Chinese + English) marketing site for Taiwan SEO.

## Quick publish
1. Create a GitHub repository (public recommended for free Pages on some plans).
2. Upload all files from this folder to the repo root.
3. In GitHub: **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
4. Wait for the Pages URL to appear.

## Custom domain
- In **Settings → Pages → Custom domain**, add your domain (e.g., `www.example.com` or `example.com`).
- GitHub will create a `CNAME` file in the publishing branch.

## Contact form
This uses Formspree by default:
- Replace `https://formspree.io/f/yourFormID` in `index.html` with your real Formspree endpoint.

## Replace placeholders
Search and replace `https://example.com/` with your final domain:
- index.html (canonical + og tags)
- robots.txt
- sitemap.xml
