FRESHCHECK PWA STARTER PACKAGE

Files:
- index.html: FreshCheck app
- manifest.json: installable app metadata
- sw.js: basic offline shell cache
- icon-192.svg and icon-512.svg: app icons

DEPLOY TO YOUR EXISTING GITHUB PAGES REPOSITORY
1. Open https://github.com/anitameena4365-debug/Fresh-check (sign in to the account that owns the repository).
2. Choose Add file > Upload files.
3. Upload the FOUR files above (index.html, manifest.json, sw.js, icon-192.svg, icon-512.svg) to the repository root. If index.html already exists, replace it with this version.
4. Commit the changes to the branch/folder used by GitHub Pages (usually main / root).
5. In repository Settings > Pages, confirm GitHub Pages is enabled for that branch/folder.
6. After deployment, open https://anitameena4365-debug.github.io/Fresh-check/ in Chrome. If the page looks old, refresh or clear the site's cache.
7. On Android Chrome, use the browser menu and choose Install app or Add to Home screen if available.

IMPORTANT LIMITATIONS
- This package is a first PWA-ready website, not yet a Play Store or Apple App Store release.
- Food items and history are stored locally in the browser on that device. They do not sync across devices/users and clearing browser data may remove them. There is no account or cloud database yet.
- Offline support is a basic app-shell cache. Test it on the hosted HTTPS website before public launch.
- App store publication requires additional packaging, testing, developer accounts, privacy information, and store review.
