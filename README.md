# Vanya Valindria Academic Website

Static website for GitHub Pages. No installation, npm, Jekyll, or build step is required.

## Publish on GitHub Pages
1. Create a GitHub account if needed.
2. Click **New repository**.
3. Name it exactly: `YOUR-GITHUB-USERNAME.github.io`
4. Set it to **Public**.
5. Create the repository.
6. Extract `vanya-academic-website-final.zip`.
7. Upload **all files and folders inside the extracted folder** to the repository root. Do not upload the ZIP itself.
8. Commit the files to the `main` branch.
9. Open **Settings → Pages**.
10. Under **Build and deployment**, select **Deploy from a branch**.
11. Branch: `main`; Folder: `/(root)`; click **Save**.
12. Wait a few minutes, then visit `https://YOUR-GITHUB-USERNAME.github.io/`.

## Before publishing
- Replace the `PROFILE PHOTO` placeholder in `index.html` if desired.
- Add team photos by replacing the avatar placeholders in `assets/js/main.js` or adapting the team renderer.
- The second forthcoming entry is deliberately labelled **title to be confirmed**, because the exact MICCAI workshop title was not provided in the material available in this chat. Replace it once the exact title is confirmed.
- Publication data is in `data/publications.json`; forthcoming/accepted work is in `data/forthcoming.json`.

## Editing
You can edit the `.json` files directly on GitHub later without touching the HTML layout.
