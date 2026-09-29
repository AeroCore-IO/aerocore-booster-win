# AeroCore Booster for Windows

Public **GitHub Release** artifacts for the Windows desktop client.

This repository is not the application source. Source lives in [`AeroCore-IO/instruments-desktop`](https://github.com/AeroCore-IO/instruments-desktop). The installed app checks `GET /repos/AeroCore-IO/aerocore-booster-win/releases/latest` via `https://api.mirror.aerocore.com.cn` and downloads:

- `AeroCore_<version>_x86_64.exe`
- `AeroCore_<version>_x86_64.exe.sha256`

Do not commit Setup binaries here. `instruments-desktop` CI builds the installer and uploads it to a Release on this repo.

Linux Booster installers stay on [`AeroCore-IO/booster-installer`](https://github.com/AeroCore-IO/booster-installer). Windows versions are independent.
