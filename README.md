# Gold Trading Plan Dashboard - PWA

This is a Progressive Web App (PWA) version of the Gold Trading Plan Dashboard that can be installed on mobile devices.

## Installation Instructions

### For Mobile Devices:
1. Open the website in your mobile browser (Chrome, Safari, Firefox, etc.)
2. Look for the "Add to Home Screen" or "Install App" option in your browser menu
3. Follow the prompts to install the app

### For Desktop:
1. Open the website in Chrome or Edge
2. Click the install icon in the address bar (looks like a computer with a down arrow)
3. Or use the browser menu to install the PWA

## Features
- Installable as a native app on phones and desktops
- Works offline (basic functionality)
- Fast loading with service worker caching
- Responsive design optimized for mobile

## Development
To test locally:
1. Run `python -m http.server 8000`
2. Open `http://localhost:8000` in your browser
3. Test the installation prompt

## Requirements for PWA
- Served over HTTPS (required for production)
- Web App Manifest (manifest.json)
- Service Worker (sw.js)
- Responsive design

Note: For production deployment, ensure the site is served over HTTPS as PWAs require secure contexts.