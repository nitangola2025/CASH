HOW TO MAKE THE APK (free, no programming)
1. Make a free account at github.com and press "New repository" (name: cashflow, Public or Private).
2. Press "uploading an existing file", then drag ALL the files and folders of this unzipped project
   (www, .github, package.json, capacitor.config.json, .gitignore). Press "Commit changes".
   Important: the folder ".github" must go in too (on Windows it can be hidden: turn on "Hidden items").
3. Open the "Actions" tab. If asked, press "I understand, enable workflows".
   Choose "Build Android APK" and press "Run workflow". Wait about 5 to 10 minutes until it is green.
4. Open that finished run, go down to "Artifacts" and download "CashFlow-apk" (a zip containing app-debug.apk).
5. Unzip it, send app-debug.apk to the phone (USB, WhatsApp as a document, email or Drive) and open it.
   Android will ask to allow installing from this source: allow it. Then install.
If the run shows a red X, open it, copy the error text and send it to Claude.
