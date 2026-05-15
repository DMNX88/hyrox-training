HYROX Peak Training - iPhone access pack

Files:
- index.html: mobile web app
- manifest.webmanifest and icon.svg: home screen metadata
- service-worker.js: offline cache for hosted PWA

Option A - pure offline file:
Open hyrox_iphone_offline.html from Files/iCloud Drive on iPhone. This is the simplest path.

Option B - app-like Home Screen icon:
Upload this folder to any HTTPS static host such as GitHub Pages, Netlify, Cloudflare Pages, or your own web server. Open the URL in Safari on iPhone, Share, Add to Home Screen, Open as Web App. Open it once while online so the cache is created.

Option C - Notion:
Import the CSV files into Notion from desktop/browser first. Then open the page in Notion iOS and mark it Available offline.
