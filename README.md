# FurEngine Releases

This public repository is the **binary-only Windows update channel** for FurEngine.

Updates are produced by GitHub Actions from the private source repository (`furkhans4o4-create/furbyte-web`) and uploaded here as versioned GitHub Releases. This repository does **not** host game projects or application source code.

Each update release should contain:

- `FurEngine-Setup-<version>-x64.exe`
- `FurEngine-Setup-<version>-x64.exe.blockmap`
- `latest.yml`

FurEngine uses Electron's GitHub update provider to check this repository. Initial installation uses the installer; subsequent releases can be downloaded from within the app.

Do not commit access tokens or secrets here.
