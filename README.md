# Earth System Prediction Lab – Research Website

This is the GitHub Pages website for the **Earth System Prediction (ESP) Lab** at the University of Oklahoma, led by Dr. Kathy Pegion.

🌐 **Live site:** https://ou-esplab.github.io/Research_Website/

---

## Site Structure

```
Research_Website/
├── index.html            ← Home page
├── research/
│   └── index.html        ← Research page
├── people/
│   └── index.html        ← People page
├── assets/
│   ├── css/
│   │   └── style.css     ← Shared stylesheet
│   └── images/           ← Place lab photos and figures here
├── _config.yml           ← GitHub Pages / Jekyll configuration
└── README.md             ← This file
```

---

## Enabling GitHub Pages

1. Go to **Settings → Pages** in this repository.
2. Under **Source**, select **Deploy from a branch**.
3. Choose the **main** branch and **/ (root)** folder.
4. Click **Save**. Your site will be available at:
   `https://ou-esplab.github.io/Research_Website/`

---

## Adding Photos

### Lab member photos

1. Add the photo file to `assets/images/` (e.g., `KathyPegion.jpeg`).
2. Open `people/index.html` and find the relevant `<div class="person-card">` block.
3. Replace the placeholder `<div class="photo-placeholder">👤</div>` with:
   ```html
   <img class="photo" src="../assets/images/YourFileName.jpeg" alt="Your Name" />
   ```

### Research figures

1. Add the image to `assets/images/` (e.g., `NMME_forecast.png`).
2. In `research/index.html`, replace a `<div class="card-img-placeholder">` with:
   ```html
   <img src="../assets/images/NMME_forecast.png" alt="NMME forecast" />
   ```

---

## Updating Content

All pages are plain HTML files — open them in any text editor and update the text directly.

| Page | File |
|------|------|
| Home | `index.html` |
| Research | `research/index.html` |
| People | `people/index.html` |
| Styles | `assets/css/style.css` |

---

## Original WordPress Backup

The file `earthsystempredictionlab.WordPress.2025-12-08.xml` is the original WordPress export.
It contains media attachment metadata (image URLs from `kathypegion.com`).
The actual page and post content was not included in the export — if you have access to
the original WordPress admin panel or a full database backup, that content can be manually
added to the HTML pages above.

---

## Contact

For questions, contact [kpegion@ou.edu](mailto:kpegion@ou.edu).
