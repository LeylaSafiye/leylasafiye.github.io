# Publishing checklist for leylasafiye.github.io

This is a **replacement design package** for the portfolio site, not an edit that has already been published to GitHub.

## Protect the old site before editing

Download a ZIP backup of the existing repository from GitHub (`Code → Download ZIP`). Keep it somewhere safe before replacing any files.

## The photo

The replacement homepage contains no profile photograph and does not reference one. If the previous repository contains `leyla.jpg`, `profile-photo.jpg` or another personal image file, delete that file in GitHub as well if you do not want the original publicly accessible. Removing a photo from the homepage does **not** automatically delete the underlying old file from a public repository or its commit history. To eliminate old images from Git history, additional Git history rewriting may be required.

## Replace the site

1. Sign in to GitHub and go to `https://github.com/leylasafiye/leylasafiye.github.io`.
2. Back up the existing repository.
3. Extract the downloaded site ZIP locally.
4. Copy the extracted contents **inside** the `leylasafiye-ux-portfolio` folder into the **root** of your existing repository. Keep the `assets` and `projects/duolingo` folders intact.
5. Remove or archive old pages that are no longer part of the new portfolio. Remove the old personal-photo files if desired. Do not remove the `.git` folder from a local clone.
6. Commit the changes. If GitHub Pages is already configured for branch `main`, GitHub will deploy the updated site. Otherwise go to `Settings → Pages` and choose the main branch at the root.
7. Open `https://leylasafiye.github.io` and check the homepage, case study and both PDF download links.

## Review the wording before making it public

Review the about section, research experience and case study carefully. The Duolingo project is an independent desk-research concept with AI-assisted writing and layout. It does not contain participant research or validated UX findings. Keep these limitations clear and do not claim results or work that did not take place.

## Contents

- Homepage: `index.html`
- Case study: `projects/duolingo/index.html`
- Styling: `styles.css`
- Portfolio PDF and detailed research PDF: `assets/`

If using GitHub's web interface rather than Git Desktop, create any missing folders by adding files with paths that include the folders. GitHub does not deploy the archive if you simply upload the ZIP itself.
