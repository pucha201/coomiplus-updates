# CoomiPlus Update Channel

Installers are published as GitHub Releases (see the Releases tab).

- desktop-v* : Windows x64 installer, asset `CoomiPlus_{ver}_x64-setup.exe`
- mobile-v* : Android arm64-v8a APK, asset `coomi-app_{ver}_arm64-v8a.apk`

- SHA-256 of each asset is written in the release notes; the client verifies it after download.
- Old versions are never deleted (rollback support).
- Downloads prefer https://gh-proxy.com/ when direct GitHub is unreachable.
