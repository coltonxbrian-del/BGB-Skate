# Street Legend Skate

An original, lightweight skateboarding browser game designed for phones. It is a fan-made project and is not affiliated with EA or the Skate franchise.

## Publish it with GitHub Pages

1. Sign in to GitHub and create a **new public repository** (for example, `street-legend-skate`).
2. Upload all files in this folder to the repository's root. Make sure `index.html` is at the root, not inside another folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then press **Save**.
6. Wait for GitHub Pages to publish. Your game URL will look like `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Add it to your iPhone Home Screen

1. Open the published GitHub Pages URL in **Safari** (not an in-app browser).
2. Tap the **Share** button.
3. Scroll and choose **Add to Home Screen**.
4. Keep the suggested name or rename it, then tap **Add**.
5. Launch **Street Skate** from the new Home Screen icon.

## Controls

- **PUSH**: hold to build speed.
- **BRAKE**: hold to slow down.
- **OLLIE**: jump.
- **FLIP**: perform a kickflip/heel-flip while airborne.
- **GRIND**: use near a rail.

The game is best played in landscape orientation. It stores your best score locally on your device.

## Files

- `index.html` — game and interface
- `manifest.webmanifest` — installable app metadata
- `sw.js` — offline caching service worker
- `icon.svg` — Home Screen/app icon

## Notes

GitHub Pages serves the site over HTTPS, which is required for service workers and PWA installation. If you update the game, refresh the site; the service worker cache may take a moment to update.
