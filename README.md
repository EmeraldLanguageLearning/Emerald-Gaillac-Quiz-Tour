# Gaillac History Tour – Android app

Emerald Language Learning's Gaillac History Tour quiz, packaged as an Android app (a WebView around `app/src/main/assets/index.html`).

- Every push builds the APK with GitHub Actions: **Actions → Build APK → latest run → Artifacts → GaillacTour-apk**.
- To publish a download link: **Actions → Publish APK release → Run workflow**, with the build run's ID and a tag such as `v1.0`.
- To update the quiz, replace `app/src/main/assets/index.html` with the new HTML and push.
