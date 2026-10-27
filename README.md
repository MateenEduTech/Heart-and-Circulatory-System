# The Human Heart & Blood Circulation: 3D PWA
Developed by Mateen Yousuf, Teacher. For Classes 5–6. No backend, no API key, works offline.

## Files
index.html (all content, CSS, JS) · three.min.js (local Three.js r149) · manifest.json · service-worker.js · offline.html · icons/

## Run / test
Service workers need **HTTPS or localhost** (opening index.html with file:// shows the app but not offline/install).
    cd heart_pwa && python3 -m http.server 8080   # then open http://localhost:8080

## Deploy
Upload the whole folder to any static HTTPS host (GitHub Pages, Netlify, Cloudflare Pages, school server). Keep the files together.

## Install on Android
Open the URL in Chrome while online → tap **Install App** (or menu ⋮ → Install app). On iPhone/iPad Safari: Share → Add to Home Screen.

## Verify offline
Open once online, reload once, then turn on airplane mode (or DevTools → Network → Offline) and reload: the app still loads. The chip at top shows Online/Offline.

## Updating
Change `VERSION` in service-worker.js after editing any file. Users see an "update available" toast.

## Notes
Blue/red = relatively low/high oxygen (teaching convention). Heart-rate numbers are illustrative; not medical advice.
