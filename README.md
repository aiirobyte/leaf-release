# Leaf releases

Release artifacts for the Leaf CLI.

Source code lives in [aiirobyte/leaf](https://github.com/aiirobyte/leaf).

## Install

```bash
curl -fsSL https://leaf.rowan.today/install.sh | sh
```

On Windows:

```powershell
irm https://leaf.rowan.today/install.ps1 | iex
```

After installation, upgrade with:

```bash
leaf upgrade
```

## Assets

Each `v<version>` release contains:

- `leaf-darwin-arm64.gz`
- `leaf-darwin-x64.gz`
- `leaf-linux-x64.gz`
- `leaf-windows-x64.js.gz`
- `bun-windows-x64.exe.gz`
- `latest.json`
- `SHASUMS256.txt`

All downloads are checksummed by the installer and the CLI updater. The
primary download origin is `https://releases.rowan.today`; GitHub Releases is
the archival mirror.
