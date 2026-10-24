# macadmin / winadmin downloads

Terminal apps that list a computer's apps, services, packages, local AI models, network and system
details, with update checks.

| | Program | Runs on |
|---|---|---|
| 🍎 | **macadmin** | macOS 27 or newer, Apple Silicon (arm64) |
| 🪟 | **winadmin** | Windows 11, 64-bit (x86-64) |

This repository only hosts the programs; the source code isn't published.

## Install

**macOS** (Homebrew):

```bash
brew install ziadulhuq/tap/macadmin
macadmin init        # once: checks, settings (models folder, internet access), security
macadmin             # the app; last tab = Settings, q = quit
brew upgrade macadmin    # update (or: macadmin update)
brew uninstall macadmin  # remove
```

Without Homebrew: download `macadmin-<version>.aarch64.tar.gz` from the
[latest release](../../releases/latest); its `README.txt` has the steps.

**Windows**: download `winadmin-<version>.x86_64.msi` from the [latest release](../../releases/latest)
and open it, then run `winadmin init` once. Uninstall from Settings > Apps.

GitHub shows each file's SHA-256 next to it. The programs aren't code-signed, so Windows (SmartScreen)
asks once before the first start, and so does macOS when you install without Homebrew.

## Versions

`v1.0.0` → `v1.0.1` for fixes, `v1.0.1` → `v1.1.0` when features are added. Every release lists its changes.
