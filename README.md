# Polish Crew — Accounting (PWA)

Installable, offline-ready web app for Polish Crew Mobile Detailing.

## Quick Deploy (GitHub Pages)

1. Create a new repo on GitHub named **polishcrew** under **polishcrewmobiledetail**.
2. Upload all files from this folder to the repo root:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon-192.png`
   - `icon-512.png`
   - `.nojekyll`
3. Commit the files.
4. Go to **Settings → Pages**:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` (or `master`) / `/ (root)`
   - Save.
5. Wait for Pages to build (usually under a minute). Your app will be live at:

```
https://polishcrewmobiledetail.github.io/polishcrew/
```

## Install on your phone

- **Android (Chrome):** open the URL → ⋮ → **Add to Home screen** → Install.
- **iPhone (Safari):** open the URL → Share icon → **Add to Home Screen**.

The app works **offline** and keeps your data on the device. Use **Export JSON** to back up.

## Notes

- If you rename the repo, your URL will change to `https://polishcrewmobiledetail.github.io/<new-name>/`.
- To force an update for phones that already installed:
  - Edit and re-commit `service-worker.js` (even a version number change) to refresh the cache.
- Data is stored locally per device. Export your JSON regularly.
