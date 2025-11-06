# Resume Website — Christian Georgis

This is a responsive, multipage resume website built with Bootstrap.
It includes Home (index.html), About and Work pages, plus a downloadable PDF resume (resume.pdf).

## What is included
- index.html, about.html, work.html
- assets/css/style.css, assets/js/main.js
- resume.pdf (your downloadable resume) — if this is not a PDF convertable file, see notes below
- README.md (this file) and .gitignore

## How to use
1. Download the ZIP and extract the folder `resume-website`.
2. Replace `assets/images/hero.jpg` and other images with your own photos (keep same filenames) and optimise them for web (72–100ppi, compressed).
3. Open `index.html` locally to preview, or serve the folder using a simple HTTP server:

# Python 3
python -m http.server 8000
# then open http://localhost:8000

## Deploy to GitHub Pages (quick)
1. Create a repo on GitHub (e.g. `christian-georgis-resume`).
2. Upload all files (drag-and-drop) or push via git.
3. In repo Settings → Pages, choose branch `main` and folder `/ (root)` then Save.
4. Site will be available at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Notes about the PDF (resume.pdf)
- A resume.pdf file is included. If it isn't a proper PDF (text fallback), open `resume.pdf` in Word/Google Docs or your browser and export/print as PDF to generate a high-quality PDF for submission.
- The website links to `resume.pdf` from the navbar. Replace it with your final exported PDF if you make changes.

## Edit content
Open the HTML files and edit text directly. The files use standard Bootstrap classes to keep layout responsive.

