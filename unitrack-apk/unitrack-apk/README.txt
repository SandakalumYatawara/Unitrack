UniTrack APK builder

1. Create a free account at github.com, then click New repository (name: unitrack, Public) and Create.
2. Upload ALL files from this folder (including the hidden .github folder) to the repository.
   If .github does not upload: Add file > Create new file, type  .github/workflows/build-apk.yml
   as the name, and paste the contents of that file.
3. Open the Actions tab. The "Build APK" run starts by itself (about 4-6 minutes).
   If it does not, click Build APK > Run workflow.
4. When it shows a green tick, open the run and download "UniTrack-apk" under Artifacts. Unzip it.
5. Send app-debug.apk to your phone, tap it, allow "Install unknown apps" when asked, then Install.

To update the app later: replace www/index.html in the repository and commit. A new APK builds automatically.
