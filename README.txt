STEPS:
1. Is zip ko extract karo. Andar ye dikhna chahiye: app (folder), settings.gradle, build.gradle, gradle.properties, build.yml.txt
2. GitHub par new repository banao. "uploading an existing file" me ye sab (app folder samet) drag-drop karo. Commit karo.
3. Repo me: Add file > Create new file. Naam me exactly ye likho:  .github/workflows/build.yml
   (slash type karte hi folders ban jate hain). Content = build.yml.txt ka poora text paste karo. Commit karo.
4. Actions tab > "Build APK" > Run workflow (ya khud chal jayega). 3-6 min wait.
5. Run kholo > neeche Artifacts > LocalShare-APK > download > extract > app-debug.apk
