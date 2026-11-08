# Ardenmark - downloads and updates

Download the latest **Ardenmark** installer from the
[Releases page](https://github.com/rokheine91-bot/ardenmark-updates/releases/latest): `Ardenmark-Setup.exe` (about 8 MB).

The setup downloads the game and installs it for your user account in `%LOCALAPPDATA%\Ardenmark` (no administrator
rights needed), with Start-menu and desktop shortcuts and an uninstaller in "Apps & features".

The game updates itself: when a new version is out, it asks "Update now / Later" at start-up.
Updates download only the files that changed and are signed (ed25519), so only genuine Ardenmark updates are installed.

`manifest.json` lists the current version, its notes and each file's size, SHA-256 and download link, with the signature.

This repository holds only release files; the game source is private.
