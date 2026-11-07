Digital Dukaan Hisab - branded deployment files
================================================

Upload ALL six files below into the ROOT of your GitHub repository, replacing index.html:
  index.html      Updated page with app branding and manifest links
  manifest.json   Web app manifest
  logo.png        Full logo artwork (available for future landing page use)
  icon-192.png    App icon
  icon-512.png    High-resolution app icon
  favicon.png     Browser tab icon

Important:
- This update only adds branding and app manifest metadata.
- Existing accounting, Receive Payment, Firebase, reports, and backup logic are retained.
- No service worker/offline caching was added, to avoid interfering with your working live app.
- Before replacing the live index.html, keep a copy of your current file and a JSON data backup.
- After upload, open the site and refresh. To install, use Chrome menu > Add to Home screen
  if the browser offers it. Full PWA installation/offline support may need a service worker later.
