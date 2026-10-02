# Byte downloads

Installers and update manifests for **Byte**, the workspace for coding agents, tasks and evidence.

This repository contains release downloads. Byte's source repository remains private.

## Byte 2.4.0

Byte Solo preserves personal plans and data. Enterprise is a restricted administration preview. Identity-provider activation, company collection and managed execution remain held until their release gates pass.

Download the package for your platform from the [Byte 2.4.0 release](https://github.com/anshikaeidetic/Byte-Releases/releases/tag/v2.4.0).

| Platform | Package |
| --- | --- |
| Windows installer | `Byte-Setup-2.4.0-x64.exe` |
| Windows portable | `Byte-2.4.0-x64-portable.exe` |
| macOS Apple Silicon | `Byte-2.4.0-arm64.dmg` |
| macOS Intel | `Byte-2.4.0-x64.dmg` |
| Linux Debian/Ubuntu | `ByteAgentMonitor-2.4.0-amd64.deb` |
| Linux AppImage | `ByteAgentMonitor-2.4.0-x86_64.AppImage` |

The release includes `latest.yml`, `latest-mac.yml` and `latest-linux.yml`. Keep these manifests with the corresponding packages when mirroring a release.

The installed Windows app and Linux AppImage support automatic updates. To update macOS, download the matching DMG and replace Byte in Applications. Existing data and enrolment are preserved.

Windows and macOS packages are unsigned. Read the installation instructions in the release notes and verify the downloaded file before installation.

## Verify a download

Compare the result with the same release's `SHA256SUMS.txt`:

```powershell
Get-FileHash .\Byte-Setup-2.4.0-x64.exe -Algorithm SHA256
```

```bash
shasum -a 256 Byte-2.4.0-arm64.dmg
```

Previous versions remain on the [releases page](https://github.com/anshikaeidetic/Byte-Releases/releases).

## Licence

Byte is proprietary software. Downloading a build does not grant a licence to use it.
