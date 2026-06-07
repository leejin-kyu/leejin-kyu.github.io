# Jinkyu Lee — Personal Website

Single-page academic / portfolio site (modern tech theme). Pure HTML/CSS/JS, no build step.

**Live URL (after deploy):** https://leejin-kyu.github.io/

## Edit your links
Open `index.html`, find the `LINKS` block near the bottom (`<script>`), and fill in:
```js
const LINKS = {
  cv:       "assets/Jinkyu_Lee_CV.pdf",
  linkedin: "https://www.linkedin.com/in/your-id",
  scholar:  "https://scholar.google.com/citations?user=XXXX"
};
```
Empty links are auto-dimmed until you set them.

## Add your CV
Drop your CV PDF into `assets/` named `Jinkyu_Lee_CV.pdf` (or change the path above).

## Deploy to GitHub Pages
1. Create a **public** repo named exactly `leejin-kyu.github.io` on GitHub.
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/leejin-kyu/leejin-kyu.github.io.git
   git push -u origin main
   ```
3. GitHub → repo → **Settings → Pages** → Source: `main` / root. Site goes live at https://leejin-kyu.github.io/ in ~1 minute.

## TODO before submitting to NVIDIA
- [ ] Add CV PDF to `assets/`
- [ ] Set LinkedIn + Google Scholar links
- [ ] Verify the book publication year (memo flagged 2015 — likely 2023)
- [ ] Optional: add a profile photo + DOI/links on publications
