# Nawanan Khaunsamakhom — Portfolio

A single-page bilingual (EN/TH) portfolio website covering four disciplines:
Game Design, UX/UI Design, Graphic Design, and Project Manager.

## Structure

```
portfolio/
├── index.html      ← the whole site (HTML + CSS + JS in one file)
├── images/          ← all project screenshots + profile photo
└── README.md
```

## How to use / edit

- Open `index.html` in a browser to preview locally.
- Text content is bilingual: every piece of copy has an `<span class="en">…</span>`
  and a matching `<span class="th">…</span>`. The language toggle button (EN / TH)
  in the top-right of the nav bar switches which one is visible — edit both spans
  if you change the wording.
- Project images live in `images/`. To swap a project screenshot, replace the file
  with the same name, or update the `src` / `data-full` attributes in `index.html`.
- Click any project image on the live site to open it full-size in a lightbox.

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `portfolio`).
2. Push this folder's contents to the repo's `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. In the repo settings → **Pages**, set the source branch to `main` and the folder to `/ (root)`.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Notes

- Fonts are loaded from Google Fonts (Inter + Noto Sans Thai) via CDN — an internet
  connection is required for the fonts to load with full fidelity, but the site
  still works fine offline using fallback system fonts.
- All project descriptions were written based on the four portfolio PDFs provided
  (Game Design / UX-UI / Graphic Designer / Business Analyst → renamed to
  **Project Manager** per request). Feel free to edit any copy directly in
  `index.html`.
