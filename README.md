# ORBIT — iPhone app package

This is a small installable Progressive Web App (PWA).

## Install on iPhone
1. Publish the contents of this folder to a static HTTPS host (GitHub Pages is a free option).
2. Open the published HTTPS address in Safari on your iPhone.
3. Tap Share → Add to Home Screen → Add.
4. Launch ORBIT from the new home-screen icon.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new public repository named `orbit-explorer`.
2. Upload all five files from this folder to the repository root.
3. Open repository Settings → Pages.
4. Under Build and deployment, select Deploy from a branch, choose `main` and `/ (root)`, then Save.
5. Wait for the Pages URL to appear. Open it in iPhone Safari and use Add to Home Screen.

The app works offline after its first successful load because the service worker caches the app files. The simulation is an educational 2D model, not a to-scale scientific visualization.

No Apple Developer account or App Store submission is needed for this home-screen web app. A native App Store app would require a separate iOS build and Apple signing/deployment.
