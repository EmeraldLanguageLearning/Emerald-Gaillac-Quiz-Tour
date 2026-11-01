# Gaillac History Tour – Android app

Emerald Language Learning's Gaillac History Tour quiz.

- **Website:** https://emeraldlanguagelearning.github.io/Emerald-Gaillac-Quiz-Tour/ (GitHub Pages, served from `index.html` at the top of the repo).
- **Android app:** a WebView around the same `index.html`, copied into the app when the APK is built.

- Every push builds the APK with GitHub Actions: **Actions → Build APK → latest run → Artifacts → GaillacTour-apk**.
- To publish a download link: **Actions → Publish APK release → Run workflow**, with the build run's ID and a tag such as `v1.0`.
- To update the quiz (website and app), replace `index.html` at the top of the repo and push.
