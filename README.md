# Soviet Project

Static web build for the Soviet Project atlas. GitHub Pages deploys this folder on updates to `main`.

After publishing, set the app bundle's `SPRemoteURL` Info.plist value to the deployed HTTPS URL and rebuild the Mac app once. The app then checks the hosted page at launch and falls back to its bundled copy when offline.
