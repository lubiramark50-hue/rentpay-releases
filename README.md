# rentpay-releases

Public test channel for the RentPay Android app. Contains no source code.

- Branch `latest` holds the newest signed test APK and `manifest.json`. It is force-pushed by CI on every build, so it always has exactly one commit.
- The app checks `manifest.json` on launch and offers the update. Android always asks you to confirm the install.
- Builds here use a TEST signing key. They are not the Google Play release.
