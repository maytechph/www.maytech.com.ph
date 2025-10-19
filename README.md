
# Maytech - Ready-to-deploy Website

This folder contains a simple, mobile-first HTML/CSS/JS website for *Maytech*.
It includes:
- index.html, about.html, products.html, contact.html
- styles.css, script.js
- /assets (sample placeholder images)

**Order form**
- The site uses a mailto-based order/contact flow (no server required). Clicking "Order" will open the user's email client prefilled.
- Later you can replace `sales@maytech.example` in the JavaScript files with your real email.

**How to preview locally**
1. Unzip the archive.
2. Open `index.html` in a browser (double-click). For full JS behavior, use a local server (optional):
   ```
   python -m http.server 8000
   ```
   then open http://localhost:8000

**Hosting**
- GitHub Pages: push this folder to a repository and enable Pages.
- Netlify / Vercel: drag & drop the folder or connect a Git repo.
- Need step-by-step hosting instructions? Ask me which provider and I'll give exact steps.

**Next steps I can do for you (pick any):**
- Replace placeholder images with your real images.
- Replace placeholder email/phone/location with real contact details.
- Add an actual serverless form (Formspree, Netlify Forms) so submissions are stored.
- Create a WordPress theme or convert to a CMS.
- Optimize SEO and write product descriptions for 10 products.

