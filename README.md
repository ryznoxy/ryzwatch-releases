# RyzWatch Releases

APK builds for RyzWatch. The application source is private.

The app's built-in updater reads `releases/latest` here, compares the tag with its own version,
downloads the newest `.apk` asset and hands it to Android's package installer.

Publish a new build with:

```bash
gh release create v<versi> ryzwatch-<versi>-arm64.apk \
  -R ryznoxy/ryzwatch-releases \
  --title "RyzWatch v<versi>" --notes "..."
```
