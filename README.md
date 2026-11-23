# Bakery Stall

A one-page website for a bakery stall: menu with prices in PKR, a prices list, contact section, and a daily sales counter.

## Files

- `index.html`: page structure
- `styles.css`: all styling
- `script.js`: menu, sales counter, undo and reset logic
- `.gitignore`: files Git should ignore

No build step or dependencies are needed. It's plain HTML, CSS, and JavaScript.

## Run locally

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Put it on GitHub

```bash
git init
git add .
git commit -m "Initial bakery stall site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/bakery-stall.git
git push -u origin main
```

Create the empty `bakery-stall` repository on GitHub first, then replace `YOUR-USERNAME`.

## Publish with GitHub Pages

1. Open the repository on GitHub and go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose branch `main` and folder `/ (root)`, then save.
4. After a minute, the site is live at `https://YOUR-USERNAME.github.io/bakery-stall/`.

## Before going live

- Replace the placeholders in the **Contact Us** section in `index.html` (phone, WhatsApp, address, hours).
- Sales data is stored in the browser's `localStorage`, so it stays on each device and is not shared between devices.
