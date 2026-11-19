# Leyla Safiye Karatay | UX Research Portfolio

A minimal, responsive UX research portfolio intended for **leylasafiye.github.io**.

## What is included

- `index.html`: homepage with clear research positioning, one featured project, research approach and about section
- `projects/duolingo/index.html`: full HTML case study that can be read without opening a PDF
- `styles.css`: responsive design with accessible focus states and reduced-motion support
- `assets/duolingo-portfolio.pdf`: 13-slide visual case study
- `assets/duolingo-research-document.pdf`: detailed supporting research notes
- `assets/duolingo-cover.webp` and `assets/duolingo-concept.webp`: images derived from the case study PDF
- `assets/favicon.svg`: text-only favicon, no profile photograph
- `.nojekyll`: serve the project as a static GitHub Pages website

## How the website was organised

This portfolio is based on the principle that **a recruiter is also a user**. The homepage gives a clear research identity, a selected project, an explanation of method and a direct route to the full case study. Project pages distinguish published information, hypotheses and future testing. It is influenced by the portfolio-review advice from the *Ghosted: The UX Job Search* session (28 October 2026).

Professional portfolio guidance used to inform the structure:
- Nielsen Norman Group, [Portfolios for UX Researchers](https://www.nngroup.com/articles/ux-researcher-portfolio/)
- Nielsen Norman Group, [5 Steps to Creating a UX Design Portfolio](https://www.nngroup.com/articles/ux-design-portfolios/)

## Publish on your existing GitHub Pages repository

**Before replacing your old homepage, save a copy of its files.** This package is intended to replace the main site files. It does not automatically delete anything in GitHub.

1. Open `https://github.com/leylasafiye/leylasafiye.github.io` in GitHub.
2. Download or clone the current repository as a backup.
3. Extract this ZIP and keep the folder structure exactly as shown.
4. Replace the repository's website files with the files inside this package. Remove the old image references from any leftover pages you keep. The new files contain no personal photograph.
5. In the repository's **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/ (root)` if this is not already configured.
6. Open `https://leylasafiye.github.io` after GitHub Pages finishes deploying.

If using Git locally:

```bash
# Run these commands inside a local clone of the existing repository.
# Back up existing work before deleting or replacing files.
git add -A
git commit -m "Rebuild UX research portfolio"
git push origin main
```

These commands **only publish files you have already copied into the repository**. They do not download or arrange this package for you.

## Important checks before publishing

- Read the Duolingo project and PDFs carefully and confirm that the wording accurately reflects your personal contribution.
- The project is a desk-based concept study, **not** a completed participant study. It should not be presented as tested product research or as work undertaken for Duolingo.
- Keep the source links, limitations and assistance disclosure truthful.
- This package does not contain any personal profile photo.
- Confirm the repository address and links once the site is published.
- Update the GitHub profile link if your username is different.

## Local preview

Open `index.html` in a browser, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
