# Maranatha Bhajana — GitHub Pages PWA

## Publish
1. Create a public GitHub repository named `maranatha-bhajana` (or another name).
2. Upload the **contents of this folder** to the repository root. `index.html`, `manifest.json`, `sw.js`, and `icons/` must be at the top level.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select branch `main` and folder `/(root)`, then Save.
5. Wait for GitHub Pages to finish publishing. The project URL usually looks like:
   `https://YOUR-USERNAME.github.io/maranatha-bhajana/`

## Install on iPhone/iPad
1. Open the published HTTPS URL in **Safari**.
2. Tap Share → **Add to Home Screen** → Add.
3. Launch it from the Home Screen.

## Install on Android
Open the HTTPS URL in Chrome, then use **Install app** or **Add to Home screen**.

## Important limitations
- This package provides PWA metadata, an app shell cache and install instructions. Offline behaviour should be tested on real devices after publishing.
- The supplied HTML itself labels audio playback and some settings as prototype/UI-only. The play button currently animates a progress bar; it does not stream actual bhajana audio. Real audio requires audio files or verified streaming URLs and playback code.
- Google Fonts and any externally hosted media may not be available offline unless separately cached/hosted.
- GitHub Pages deployment must be completed in your GitHub account; this package does not publish itself.
