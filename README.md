# AHZA ASISTANT Download Website

Landing/download page with credit `LUA/AHZA` and TikTok `@luahub.kali`.

## GitHub Pages
1. Create a GitHub repository (e.g. `AHZA-ASISTANT-DOWNLOAD`).
2. Upload all files in this folder to repository root.
3. Ensure `AHZA-ASISTANT-FULL-SOURCE.zip` is included in the repository root (GitHub has file size limits; use a GitHub Release if it exceeds the limit).
4. Repository Settings → Pages → Deploy from branch → `main` → `/ (root)`.
5. Open the published Pages URL.

The download is source code, not a prebuilt APK/EXE. Build with Flutter:
`flutter pub get`, `flutter build apk --release`; Windows build on Windows: `flutter build windows --release`.
