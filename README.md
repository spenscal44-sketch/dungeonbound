# Dungeonbound 3D

A Chromebook-friendly browser prototype. Hosted using GitHub Pages.

## Publish
1. Create a **public** repository named `dungeonbound` on GitHub.
2. Upload `index.html`, `.nojekyll`, and `README.md` to the root of its `main` branch.
3. Open repository **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then **main** and **/(root)**. Save.
4. After GitHub Pages finishes deploying, visit `https://YOUR-USERNAME.github.io/dungeonbound/`.

## Updates
Replace `index.html` with the new version and commit the change. Refresh the website (hard refresh if needed).

## Saves
Saves live in the browser's local storage on the specific website/origin, not in GitHub. Use **Export Save** regularly to keep a backup. On the website's opening screen, choose **Import Save File** to restore.

To migrate an existing local v0.9.1 save, open `Dungeonbound_Save_Exporter.html` from the same local-file origin where the old game was played, load your save, choose **Export Save**, then import the JSON file on the website. Chrome may isolate local files, so the exporter might not see the old save. If so, do not overwrite or delete your original game.

This is a prototype. GitHub Pages is public and the Three.js module is loaded from a CDN, so the game requires network access.
