# OTS iPhone Scanner — GitHub Pages Folder

This `docs/` folder contains the complete, self-contained **OTS iPhone Attendance Scanner** web app for deployment to **GitHub Pages**.

---

### Folder Contents

| File | Purpose |
|---|---|
| [`index.html`](index.html) | Primary entry point (loads the mobile scanner immediately on your GitHub Pages URL) |
| [`iphone_scanner.html`](iphone_scanner.html) | Standalone iPhone/mobile attendance scanner with live camera, QR scanning, and HUD |
| [`ots_cloud_data.json`](ots_cloud_data.json) | Synchronized plant roster & dynamic `.env` authorization password (`Bharat`) |
| [`waaree-logo.png`](waaree-logo.png) | Corporate Waaree Solar logo & iOS Home Screen touch icon |
| [`favicon.ico`](favicon.ico) | Browser tab favicon |
| [`.nojekyll`](.nojekyll) | Tells GitHub Pages to serve all JSON data, fonts, and assets directly |

---

### GitHub Pages Settings

In your GitHub repository:
1. Go to **Settings** ➔ **Pages**
2. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`)
   - **Folder**: `/docs`
3. Click **Save**.

Your scanner URL will be:
`https://<username>.github.io/<repo>/`
