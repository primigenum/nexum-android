# Nexum — Android APK distribution

Public release channel for the [Nexum](https://nexum.app) Android app.
APKs published here are built and signed by the same CI pipeline that
publishes to Google Play, so installs from this repo and from Play Store
are functionally equivalent.

## Install with Obtainium

[Obtainium](https://github.com/ImranR98/Obtainium) polls GitHub Releases
for new versions of an app.

1. Install Obtainium (F-Droid or GitHub releases).
2. Add app → paste: `https://github.com/primigenum/nexum-android`
3. Obtainium picks the latest tagged release. Tap Install. Future updates
   are one tap from inside Obtainium.

## Install manually (sideload)

1. Download the latest `.apk` from [Releases](https://github.com/primigenum/nexum-android/releases).
2. On your device, enable "Install unknown apps" for your file manager.
3. Open the APK to install.

## Verify the APK

Each release shows a SHA-256 checksum. Verify before installing:

```bash
sha256sum nexum-vX.Y.Z.apk
```

## Privacy

See [nexum.app/legal/privacy-policy](https://nexum.app/legal/privacy-policy)
for what data the app collects.

## Source code

Nexum is proprietary software. This repo distributes the official APK
builds only; it does not mirror the source code.

## Issues

For bugs or questions, open an issue in this repo's
[Issues](https://github.com/primigenum/nexum-android/issues) tab.
