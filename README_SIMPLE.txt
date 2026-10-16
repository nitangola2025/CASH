APK BUILD - SIMPLE STEPS
This package needs only TWO things in your GitHub repository (CASH-FLOW):
  1) index.html          (in the main list of files, NOT inside a folder)
  2) the build file at   .github/workflows/main.yml

HOW:
A. Unzip this zip.
B. In the repository: Add file > Upload files > drag ONLY index.html > Commit changes.
C. Open the file main.yml.txt with Notepad and copy ALL the text.
D. In the repository: Add file > Create new file.
   In the name box type exactly:  .github/workflows/main.yml
   (when you type each "/" a folder is made). Paste the text. Commit changes.
   If main.yml already exists, open it, press the pencil, delete everything, paste this text, commit.
E. Actions tab > Build Android APK > Run workflow. Wait 5-10 minutes for the green tick.
F. Open the finished run (click its name), scroll to the bottom: Artifacts > CashFlow-apk.
G. Unzip it: app-debug.apk is the Android app. Send it to the phone and install it.
