# Nazia Zarin — Academic Portfolio

Personal academic website for MS/PhD and Erasmus Mundus funding applications. A single static page (`index.html`) with no build step — ready for GitHub Pages.

## Deploy to GitHub Pages

1. Create a GitHub repository named **`<username>.github.io`** (e.g. `naziazarin.github.io`) for the site to live at the root URL, or any repo name for `https://<username>.github.io/<repo>/`.
2. Push this folder:
   ```bash
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin master
   ```
3. On GitHub: **Settings → Pages → Source: Deploy from a branch → `master` / root → Save.**
4. The site is live in ~1 minute at the URL shown on that page.

## Before going live — personalize

- **Google Scholar**: create a profile and add a button next to ResearchGate.
- **Photo**: an optional professional headshot can go in the hero (`assets/photo.jpg`).
- **Conference photos**: drop images at `assets/photos/iybc-2026.jpg`, `icles-2025.jpg`, `icls-2025.jpg`, `ruec-2025.jpg`, then replace each placeholder `<div class="ph">…</div>` in `index.html` with `<img src="assets/photos/….jpg" alt="Nazia presenting her poster at …">`.
- **Artwork**: drop scans at `assets/art/01.jpg` … `03.jpg` and swap the placeholders the same way.
- **Bookshelf**: the "Beyond the lab" section has a placeholder note — add her favorite titles when she picks them.
- **CV**: replace `assets/Nazia-Zarin-CV.pdf` whenever the CV is updated.

## Updating content

Everything is in `index.html`:

| Section | What to update |
|---|---|
| Hero stats | Counts of publications / posters |
| Publications | Add new `<article class="pub">` blocks, newest first |
| Conferences | Add new `<li>` to the timeline, newest first |
| Footer | "Last updated" date |

## Structure

```
index.html              — the whole site (HTML + CSS, no JS needed)
assets/Nazia-Zarin-CV.pdf — downloadable Europass CV
```
