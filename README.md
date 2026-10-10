# Guanyu Hou's academic homepage

Personal academic website at https://orangestella.github.io/, based on [al-folio](https://github.com/Orangestella/al-folio).

## Edit content

- `_pages/about.md`: biography and academic service.
- `_bibliography/papers.bib`: publications and selected papers.
- `_data/cv.yml`: web CV.
- `assets/pdf/guanyu_hou_cv.pdf`: downloadable English CV.
- `_data/socials.yml`: contact links.

## Build and publish

GitHub Actions installs Ruby/Jekyll, formats checks, builds the site, and verifies generated pages.
Migration branches build without deployment. A passing build on `main` publishes to GitHub Pages.
The repository Pages source must be set to **GitHub Actions**.
Docker is optional for local development; the hosted website consists of static files.

The repository history preserves the previous homepage and its original CV URLs.
