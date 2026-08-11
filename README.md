# Astha Wagle — Quarto academic website

A research-first academic website built with Quarto.

## Files

- `index.qmd` — homepage
- `research.qmd` — research themes and projects
- `publications.qmd` — publications and reports
- `about.qmd` — education, research experience, leadership, skills
- `cv.qmd` — embedded/downloadable CV
- `css/styles.css` — visual styling
- `files/Astha-Wagle-CV.pdf` — current CV supplied for the site
- `_quarto.yml` — Quarto website configuration

## Run locally

Install Quarto from https://quarto.org/docs/get-started/ and then, from this folder:

```bash
quarto preview
```

## Build the website

```bash
quarto render
```

The generated site is in `_site/`.

## Publish with GitHub Pages

Create a GitHub repository, push this folder to it, and then use Quarto's GitHub Pages publishing workflow. The simplest route is:

```bash
quarto publish gh-pages
```

Before publishing, change the placeholder `site-url` in `_quarto.yml` to your real domain or GitHub Pages URL.

## Before going live

1. Add your preferred public email address.
2. Add confirmed links for Google Scholar, ORCID, GitHub, and LinkedIn.
3. Replace the monogram circle on the homepage with a professional photo if desired.
4. Add DOI/publisher/repository links to the publication entries.
5. Update the CV PDF in `files/` whenever the CV changes.
6. Connect a custom domain after the GitHub Pages version is working.
