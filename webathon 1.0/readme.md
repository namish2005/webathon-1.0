# Webathon 1.0

A simple static website built for the Webathon project. This repository contains a minimal HTML/CSS/JavaScript site intended as a starting point for small demos, prototypes, or hackathon entries.

## Quick preview

Open `index.html` in your browser, or run a tiny local server to preview the site (recommended).

### Try it (PowerShell)

```powershell
# From the project root (where index.html lives)
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

If you don't have Python installed, you can use the included `package.json` start script which uses `npx http-server`:

```powershell
npm start
# then open http://localhost:8000
```

## What’s included

- `index.html` — the main HTML page
- `style.css` — stylesheet with site styles
- `script.js` — client-side JavaScript
- `readme.md` — this file

## Features

- Lightweight static site — no build step required
- Easy to customize layout, styles, and scripts

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript

## Local development

1. Clone or copy the project to your machine.
2. Start a local server from the project folder (recommended) and open the site in the browser.

Examples:

- Python (built-in):

```powershell
python -m http.server 8000
```

- Node (npm start uses npx http-server):

```powershell
npm start
```

Open (https://webathon-24-10.netlify.app/)

## File structure

```
index.html
style.css
script.js
readme.md
```

## Contract (small)

- Input: User opens `index.html` or visits a served file URL.
- Output: Browser renders the page using `style.css` and executes `script.js`.
- Error modes: Missing files — browser will show 404 from server or fail to load resources; JavaScript errors are visible in DevTools console.

## Edge cases and notes

- If JavaScript fails to load, site should still present basic content from `index.html`.
- Test with no-JS browsers to verify progressive enhancement (if applicable).
- Mobile responsiveness depends on CSS; review `style.css` and add media queries if needed.

## Deployment suggestions

- Static hosting is ideal: GitHub Pages, Netlify, Vercel, or any static file host.
- For GitHub Pages: push to a repo and enable Pages from the `main` or `gh-pages` branch.

## Contributing

Small changes are welcome. Suggested workflow:

1. Fork / copy the project
2. Make edits to `index.html`, `style.css`, or `script.js`
3. Open a pull request or send your changes

Keep changes small and focused. If you plan a larger refactor, open an issue first to discuss.

## License

This project is provided under the MIT License. See the `LICENSE` file included in the repo.

## Added files

- `LICENSE` — MIT license file
- `assets/screenshot.svg` — placeholder image you can replace with a real screenshot (recommended name: `assets/screenshot.png`)
- `package.json` — includes a `start` script which runs `npx http-server -p 8000` for easy local serving

## Contact

If you'd like help customizing this site or deploying it, add a short message in an issue or contact the project owner.

---

If you'd like, I can also:

- Create a `CHANGELOG.md` or `CONTRIBUTING.md` template
- Add a tiny GitHub Actions workflow to deploy to GitHub Pages automatically
- Replace the SVG placeholder with a real PNG screenshot if you upload one now

Tell me which of those you'd like next and I'll implement it.

