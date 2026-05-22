╔══════════════════════════════════════════════════════════════╗
║         DNA DESIGNS — INVOICE STUDIO (PWA)                  ║
╚══════════════════════════════════════════════════════════════╝

HOW TO INSTALL AS A MOBILE APP
────────────────────────────────────────────────────────────────

BEST WAY — Host on Netlify (free, takes 2 minutes):
  1. Go to netlify.com → Log in → "Add new site" → "Deploy manually"
  2. Drag & drop this entire folder onto the Netlify drop zone
  3. You get a live URL like: https://dna-invoice.netlify.app
  4. Open that URL on your phone:
       • Android Chrome: tap menu (⋮) → "Add to Home Screen" / "Install app"
       • iPhone Safari:  tap Share (□↑) → "Add to Home Screen"
  5. App icon appears on your home screen. Done!

────────────────────────────────────────────────────────────────

LOCAL NETWORK (same WiFi, no internet needed):
  1. Open Terminal / Command Prompt in this folder
  2. Run:   python3 -m http.server 8080
  3. Find your PC's local IP (e.g. 192.168.1.5)
  4. On your phone open:  http://192.168.1.5:8080
  5. Add to home screen as above

NOTE: Service Worker (offline mode) only works on HTTPS or localhost.
      Netlify provides HTTPS automatically.

────────────────────────────────────────────────────────────────

FILES IN THIS FOLDER:
  index.html        Main app (self-contained React PWA)
  manifest.json     Web App Manifest (name, icons, colors)
  sw.js             Service Worker (offline caching)
  icons/            App icons in all required sizes
  README.txt        This file

