# LASO releases

Installers and update files for the LASO desktop app. The app checks this repo for updates.

Download the latest version from [Releases](https://github.com/mmalko/laso-releases/releases/latest):

- Windows: `LASO-Setup-<version>.exe`
- macOS (Apple Silicon): `LASO-<version>-arm64.dmg`
- Linux:
  - `LASO-<version>.AppImage` runs on most distributions and updates itself. Make it executable, then open it.
  - `laso_<version>_amd64.deb` installs on Debian and Ubuntu with `sudo apt install ./laso_<version>_amd64.deb`. Updates ask for your password.

Builds aren't code signed yet. Windows shows a SmartScreen warning on first install: choose **More info**, then **Run anyway**.
