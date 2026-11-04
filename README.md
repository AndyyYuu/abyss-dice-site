# 深渊三骰 · Three Dice Deep

A dice-driven dungeon board game. Open `index.html` in a browser, or host this folder as a static site.

## Deploy to GitHub Pages
1. Create a repo and upload everything in this folder (`index.html`, `a/`, this README) to the repo root.
2. Repo Settings → Pages → Source: "Deploy from a branch" → branch `main`, folder `/ (root)` → Save.
3. After a minute the game is live at `https://<your-username>.github.io/<repo-name>/`.

- Language toggle: top-left button (中文 / English). Default is Chinese; the choice is remembered.
- Saves are stored in the browser (localStorage). Use the Save button to copy a save code.
- `a/` holds all 116 images (WebP). Keep the folder name, the page references it by relative path.
- Movement uses the map's independent six-sided die (1–6). Character dice remain exclusive to event checks.
- Each stop resolves one event. Story cards occupy event spaces; an interception replaces that stop's tile event.
- Event text appears one sentence at a time. Use Next line or Show all; read the outcome before continuing.
