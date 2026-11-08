# Pocket Friend releases

Public, release-only files for the Pocket Friend (Claude) app and BOBO (BF-01) software.
There is no source code here, and nothing secret.

- `app/PocketFriend.json`: latest app version. The app reads this to tell you an update is ready.
- `firmware/BF01-firmware.json`: latest BOBO software version (published only after it is built and checked).
- `app/PocketFriend.apk`: the app file itself (the JSON points to it). Firmware files will be attached to GitHub Releases.

The app checks the version and the file's SHA-256 before installing anything, and never installs by itself.
