LUDORA ARCADE - install on your phone
=====================================
Files: index.html (the whole game), manifest.webmanifest, sw.js (offline support), icon-192/512/maskable PNGs.
Keep all files together in ONE folder.

OPTION A - Install as an app (free, no Play Store, works offline after first load)
1. Upload this whole folder to any free HTTPS host, e.g.:
   - Netlify Drop: go to app.netlify.com/drop and drag this folder in
   - or GitHub Pages / Cloudflare Pages / Vercel
2. Open the link on your phone in Chrome (Android) or Safari (iPhone).
3. Android Chrome: menu (3 dots) > "Install app" / "Add to Home screen".
   iPhone Safari: Share > "Add to Home Screen".
It then opens full-screen like a normal app with its own icon.
(Installing needs HTTPS. Opening index.html straight from the phone's files works for playing, but cannot be installed.)

OPTION B - Real Android APK
Upload the hosted link from Option A to pwabuilder.com and press "Package for Stores" > Android to get an APK/AAB.
