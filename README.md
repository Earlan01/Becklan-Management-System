
# Becklan Forms Hub (Static PWA)

A lightweight, mobile-first hub that links to Google Forms used by Becklan Drugstore.

## Pages
- `index.html` – Hub with buttons for: Medications, Sales, Purchases, Patients, Services
- One page per form with:
  - Header with Becklan logo
  - Open Form button
  - Share via Email (to: drugstore@wellbodifoundation.org, amarababadee13@gmail.com, rekabba@yahoo.com, allan@avwilliams.com)
  - Share via WhatsApp (+13014128793, +12408935099, +23276586152)
  - Embedded form preview (iframe)

## Deploy to GitHub Pages
1. Create a repository (e.g. `Becklan-Forms-App`).
2. Upload all files in this ZIP to the repo **root**.
3. GitHub → Settings → Pages → Source: **Deploy from a branch** → Branch: `main` → Folder: `/ (root)`.
4. Open: `https://<your-username>.github.io/<repo>/`

## Change form links
Edit `FORMS` list in `index.html` links (the individual pages are static; to change URLs, update each `*.html`).

## PWA
This site includes a minimal `manifest.json` and `service-worker.js` so staff can **Add to Home Screen**.
