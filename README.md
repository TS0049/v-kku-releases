# V-KKU releases

This repository holds only the update feed for V-KKU (a macOS dictation app):

- `appcast.xml` — the Sparkle 2 update feed, served by GitHub Pages at
  <https://ts0049.github.io/v-kku-releases/appcast.xml>
- Signed and notarized `V-KKU-vX.Y.Z.zip` files are attached to GitHub Releases.

The source code is not here. Every update is Developer ID–signed, notarized by Apple and
EdDSA-signed for Sparkle; the app refuses updates whose signature does not match.
