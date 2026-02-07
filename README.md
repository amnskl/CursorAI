# Cursor Agent – Static Landing Page
A simple static landing page built with **HTML + CSS**.

## Pages
- `cursor.html` — main landing page
- `features.html` — features page

## Tech stack
- HTML5
- CSS3 (`styles.css`)
- Assets in `images/`

## Project structure
- `cursor.html`
- `features.html`
- `styles.css`
- `images/`

## Run locally
### Option A: open the file directly
1. Open `cursor.html` in your browser (double-click it).
2. Make sure the `images/` folder stays in the same directory so images load correctly.

### Option B: use a local web server (recommended)
Serving the folder avoids path issues and better matches how it will behave when deployed.

#### Using Node (if installed)
```powershell path=null start=null
npx serve .
```
Then open the URL shown in the terminal.

#### Using Python (if installed)
```powershell path=null start=null
python -m http.server 5500
```
Then open:
- `http://localhost:5500/cursor.html`

## Customize
- **Content:** edit text/sections in `cursor.html` and `features.html`
- **Styling:** update colors, spacing, and layout in `styles.css`
- **Images:** replace files in `images/` (keep filenames the same, or update the `<img src="...">` paths)

## Deploy (GitHub Pages)
1. Push this folder to a GitHub repo.
2. In GitHub: **Settings → Pages**.
3. Set **Source** to `main` branch and **/ (root)**.
4. Your site will be available at the Pages URL; open `cursor.html` (or rename it to `index.html` if you want it to load by default).

## Disclaimer
This project appears to be inspired by the Cursor website and is intended for learning/practice. All third‑party logos/trademarks belong to their respective owners. Not affiliated with or endorsed by Cursor.