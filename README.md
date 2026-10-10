# Nishaaj Alam — Developer Overworld

A Minecraft-inspired, pixel-art software developer portfolio. Pure HTML/CSS/JavaScript: no build tools or dependencies required. Responsive layout, interactive skill inventory, and handcrafted CSS blocky landscape.

## Preview locally

Open `index.html` in your browser, or run a local HTTP server:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy with GitHub Pages

1. Create a new **public** GitHub repository (e.g., `minecraft-portfolio`).
2. Upload `index.html`, `styles.css`, `script.js` to the **root** of the repository (not inside a subfolder). You can also upload this README.
3. In the repository, navigate to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**; select `main` and `/ (root)`, then **Save**.
5. Your site will appear at `https://YOUR_USERNAME.github.io/minecraft-portfolio/` after GitHub finishes publishing.

Or push from the terminal:

```bash
git init
git add .
git commit -m "Launch pixel portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/minecraft-portfolio.git
git push -u origin main
```

Then enable Pages in Settings.

## Before publishing

- Change the placeholder `https://github.com/` GitHub link in `index.html` to your real profile.
- Check the experience and project wording; remove or correct anything that doesn't match work you completed.
- Add actual repository and demo links to project cards as you publish them.
- Change the email address if needed.

This is an original block-game-inspired design using CSS pixel art; it does not bundle Minecraft game textures, characters, or trademarks.
