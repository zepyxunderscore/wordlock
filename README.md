# Wordlock APK project
Your HTML lives at app/src/main/assets/index.html (edit it, rebuild, done).

## Option A: GitHub (no installs)
1. Create a new GitHub repo, upload this whole folder (keep .github/).
2. Open the Actions tab -> "Build APK" -> wait ~3 min.
3. Download the "Wordlock-apk" artifact, unzip, install app-release.apk.

## Option B: Android Studio
Open this folder, then Build > Build APK(s). Output: app/build/outputs/apk/release/.

The APK is debug-key signed, which is fine for sideloading.
Allow "Install unknown apps" on your phone when prompted.
