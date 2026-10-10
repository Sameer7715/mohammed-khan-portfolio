# Mohammed Khan — New Repository Package

This is a static website (HTML/CSS/JavaScript) for GitHub Pages and Vercel. It requires no build command, install command, or environment variables.

## IMPORTANT: upload the CONTENTS of this folder

The files must be directly at the top level of the GitHub repository. Do not upload the outer folder as one nested folder.

```text
repository-root/
├── index.html
├── styles.css
├── script.js
└── assets/
    ├── logo.png
    ├── logo.svg
    ├── profile-photo.jpg
    └── profile-photo.png
```

## Create a new GitHub repository

1. Open https://github.com/new
2. Repository name: `mohammed-khan-portfolio`.
3. Choose **Public**. Leave the options to add a README, .gitignore, or license unchecked.
4. Click **Create repository**.
5. Click **Add file → Upload files**.
6. In File Explorer, open the extracted `Mohammed-Khan-New-Repository` folder. Select `index.html`, `styles.css`, `script.js`, and the `assets` folder, then drag them into GitHub's upload area.
7. Click **Commit changes**.
8. On the Code tab, verify that `index.html`, `styles.css`, `script.js`, and `assets` are all visible at the same level.

## Deploy on Vercel

1. Open https://vercel.com/new and import the new GitHub repository.
2. Framework Preset: **Other**.
3. Root Directory: `./` (repository root).
4. Build Command: leave blank. Install Command: leave blank.
5. Output Directory: leave blank if allowed; otherwise enter `.`.
6. No environment variables are needed for this static site.
7. Click **Deploy**.

## Enable GitHub Pages (optional)

Repository → **Settings → Pages** → **Deploy from a branch** → select `main` and `/(root)` → **Save**.

## Verify the hosted image files

After upload, replace `YOUR-USERNAME` and `YOUR-REPO` with your actual GitHub username and repository name and open these URLs:

- `https://YOUR-USERNAME.github.io/YOUR-REPO/assets/logo.png`
- `https://YOUR-USERNAME.github.io/YOUR-REPO/assets/profile-photo.jpg`

Each URL should display the image directly. GitHub filenames are case-sensitive. Keep names exactly as shown. The website uses relative `./assets/...` paths and image fallbacks, so it supports both a GitHub Pages project site and Vercel.
