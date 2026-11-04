# Gaillac History Tour – Android app

Emerald Language Learning's Gaillac History Tour quiz.

- **Website:** https://emeraldlanguagelearning.github.io/Emerald-Gaillac-Quiz-Tour/ (GitHub Pages, served from `index.html` at the top of the repo).
- **Android app:** a WebView around the same `index.html`, copied into the app when the APK is built.

- Every push builds the APK with GitHub Actions: **Actions → Build APK → latest run → Artifacts → GaillacTour-apk**.
- To publish a download link: **Actions → Publish APK release → Run workflow**, with the build run's ID and a tag such as `v1.0`.
- To update the quiz (website and app), replace `index.html` at the top of the repo and push.

## Licence

© 2026 Emerald Language Learning. Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (see [LICENSE](LICENSE)): you may copy, fork and adapt it for individual, non-commercial use with credit, but **commercial use is not allowed** without written permission. Third-party material (photos, icons, map or dictionary data) keeps its own licence.
