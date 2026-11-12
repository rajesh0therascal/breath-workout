Breathing practice - installable offline app

1. Upload every file in this folder to any https static host
   (GitHub Pages, Netlify Drop, Cloudflare Pages, your own site).
2. Open the link once while online. The app saves itself to the phone.
3. Install:
   - Android (Chrome): menu > Install app (or Add to Home screen).
   - iPhone / iPad (Safari): Share > Add to Home Screen.
4. It then opens full screen and works with no internet.

For spoken counts offline on Android, install the voice data once:
Settings > Languages > Text-to-speech output > Install voice data.

When you change index.html, change CACHE = 'breathing-v1' in sw.js
(for example to 'breathing-v2') so phones pick up the update.
