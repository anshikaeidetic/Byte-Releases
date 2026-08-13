# Byte — Downloads

Installers and update manifests for **Byte**, the local-first Claude Code observability dashboard.

This repository holds **no source code**. It exists so that installed copies of Byte can reach their update feed, and so anyone with a licence can download a build, without the product's source repository being public.

## Downloads

Every build is on the [Releases](../../releases) page.

| Platform | File |
|---|---|
| Windows (installer) | `Byte-Setup-<version>-x64.exe` |
| Windows (no install) | `Byte-<version>-x64-portable.exe` |
| macOS (Apple silicon) | `Byte-<version>-arm64.dmg` |
| macOS (Intel) | `Byte-<version>-x64.dmg` |
| Linux (Debian/Ubuntu) | `ByteAgentMonitor-<version>-amd64.deb` |
| Linux (portable) | `ByteAgentMonitor-<version>-x86_64.AppImage` |
| Node, no install | `Byte-Runner-<version>-x64.zip` |

`latest.yml`, `latest-mac.yml` and `latest-linux.yml` are the update manifests. They are read by the app, not by you.

## Verifying a download

Each release carries `SHA256SUMS.txt`.

```powershell
Get-FileHash .\Byte-Setup-<version>-x64.exe -Algorithm SHA256
```

```bash
shasum -a 256 Byte-<version>-arm64.dmg
```

## Licence

Byte is proprietary software. Downloading a build does not grant a licence to use it.
