# macadmin / winadmin downloads

Terminal apps that list a computer's apps, services, packages, local AI models, network and system
details, with update checks.

| | Program | Runs on |
|---|---|---|
| 🍎 | **macadmin** | macOS 27 or newer, Apple Silicon (arm64) |
| 🪟 | **winadmin** | Windows 11, 64-bit (x86-64) |

This repository only hosts the programs; the source code isn't published.

## Download

Open the [latest release](../../releases/latest) and pick the zip for your computer under **Assets**:

- `macadmin-<version>-macos-arm64.zip`
- `winadmin-<version>-windows-x86_64.zip`

Each zip holds the program and a `README.txt` with the install steps. GitHub shows each file's SHA-256 next to it.
The programs aren't code-signed, so macOS (Gatekeeper) and Windows (SmartScreen) ask once before the first start;
the README explains what to click.

## macadmin quick start

```bash
cd ~/Downloads/macadmin-<version>-macos-arm64
./macadmin init      # checks, settings (models folder, internet access), security
./macadmin           # the app; last tab = Settings, q = quit
./macadmin update    # newer version? shows the changes and asks before downloading
```

## Versions

Versions are the build date and a build id, for example `2026.10.22-908c835`. Every release lists its changes.
