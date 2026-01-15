# Frisson

A minimalist binaural beats meditation app.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g., `frisson`)

2. Clone and add these files:
   ```bash
   git clone https://github.com/YOUR_USERNAME/frisson.git
   cd frisson
   # Copy all files from this folder into the repo
   ```

3. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial Frisson PWA"
   git push origin main
   ```

4. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / `root`
   - Save

5. Your app will be live at: `https://YOUR_USERNAME.github.io/frisson/`

## Install on iPhone

1. Open Safari on your iPhone
2. Navigate to your GitHub Pages URL
3. Tap the Share button (square with arrow)
4. Scroll down and tap "Add to Home Screen"
5. Name it "Frisson" and tap Add

The app will now appear on your home screen and launch in standalone mode.

## Files

- `index.html` - Main app
- `manifest.json` - PWA configuration
- `sw.js` - Service worker for offline support
- `icons/` - App icons for home screen
