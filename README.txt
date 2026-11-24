MyAlternates - phone app (demo)
================================

Files
  index.html            the app (one file, works offline once opened)
  manifest.webmanifest  app name, colours and icons for "Add to Home Screen"
  sw.js                 offline cache (used only when the folder is served over https)
  icon-192.png, icon-512.png, apple-touch-icon.png   app icons

Option 1 - quick look on a phone
  Copy index.html to the phone and open it in Chrome (Android) or Files > Safari (iPhone).
  It opens full screen at the phone's size. Demo login: OTP 123456, then any 4-digit MPIN.

Option 2 - install like an app (recommended)
  1. Upload this whole folder to any https web host (GitHub Pages, Netlify, Vercel,
     Firebase Hosting, or your own company server).
  2. Open the https link on the phone.
     Android (Chrome): menu > "Install app" / "Add to Home screen".
     iPhone (Safari): Share > "Add to Home Screen".
  3. The MyAlternates icon appears on the home screen and opens full screen, without the
     browser bar, and keeps working offline.

Option 3 - Play Store / App Store
  The hosted link from option 2 can be wrapped into an Android APK / AAB with PWABuilder
  (pwabuilder.com) or into Android and iOS apps with Capacitor. Store publishing needs a
  Google Play developer account (Android) and an Apple developer account + a Mac (iOS).

Note: all figures in this demo are sample data.
