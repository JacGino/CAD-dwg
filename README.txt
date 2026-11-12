AUTOCAD 2D MOBILE - home-screen app pack
=========================================

Files: index.html (the app), manifest.webmanifest, sw.js (offline), 3 icons.
Keep all files together in one folder.

1) Put the folder online (free, pick one)
   - Netlify Drop: open app.netlify.com/drop and drag this whole folder onto the page.
   - GitHub Pages: upload the files to a new repository, then Settings > Pages.
   - Cloudflare Pages: Create project > Upload assets > drag the folder.
   You get an https address, for example https://yourname.netlify.app

2) Install on iPhone / iPad
   - Open that address in Safari (not inside another app).
   - Tap Share > Add to Home Screen > Add.
   - Open it once while online. After that it also works offline.

3) iCloud Drive / OneDrive
   - Save: menu > Save as... > pick a format. The iOS share sheet opens.
     Choose "Save to Files", then iCloud Drive or OneDrive.
     (OneDrive appears in Files only if the OneDrive app is installed.)
   - Open: menu > Open... > the Files picker shows iCloud Drive and OneDrive.
   It is manual saving, not automatic sync.

4) Updating later
   Replace the files online. The app updates next time it is opened with internet.
   Your drawings stay saved on the device.

4) OneDrive direct link (optional, free, one-time setup)
   - Open portal.azure.com > Microsoft Entra ID > App registrations > New registration.
   - Name: CAD 2D. Supported accounts: "Personal Microsoft accounts and accounts in any organizational directory".
   - Redirect URI: platform "Single-page application (SPA)", value exactly https://jacgino.github.io/CAD/
   - Register, then copy the "Application (client) ID".
   - In the app: menu > OneDrive... > Sign in. Paste the client ID once. Sign in with Microsoft.
   - Drawings are saved in OneDrive > Apps > (your app name) as .draft.json. Use Open there to load them.

5) iCloud Drive
   - Apple has no direct web link for iCloud. Use menu > "Save to iCloud / Files..." > Save to Files > iCloud Drive.
   - To open: menu > Open... and pick the file from Files > iCloud Drive.
