RA MOVE PRACTICE COACH — ONLINE + OFFLINE IPHONE PACKAGE

WHAT THIS PACKAGE DOES
- Keeps the available original HTML page content, with minimal additions for install/offline support.
- Includes a web app manifest and service worker for caching the page after the first online visit.
- Does not automatically publish a website; publishing requires a hosting account.

PUBLISH ONLINE (GitHub Pages)
1. Extract this ZIP on your MacBook.
2. Sign in at https://github.com/ and create a new repository.
3. Upload index.html, manifest.webmanifest, and service-worker.js to the repository root.
4. Open repository Settings > Pages.
5. Select Deploy from a branch, choose main and /(root), then save.
6. Open the published HTTPS URL and wait for it to finish loading once.

USE ON IPHONE AND ENABLE OFFLINE
1. Open the published HTTPS website in Safari while online.
2. Tap Share > Add to Home Screen.
3. Launch MOVE Coach from the new Home Screen icon while still online once.
4. After it has loaded and cached, try airplane mode to check offline availability.

IMPORTANT
- iOS does not reliably run interactive local HTML files directly from the Files preview. The offline approach is to install the HTTPS website as a Home Screen web app first.
- This is a static PWA package. If the original coach relies on server-side features, those features may still require internet access.
- The source HTML was not verified against the live hosted site, so exact parity with every live feature cannot be guaranteed.
