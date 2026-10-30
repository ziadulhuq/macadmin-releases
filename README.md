# macadmin / winadmin downloads

Desktop apps (with a terminal mode) that list a computer's apps, services, packages, local AI models,
network and system details, with update checks.

**Latest: [v1.3.0](../../releases/tag/v1.3.0)**

| | Program | Runs on |
|---|---|---|
| 🍎 | **macadmin** | macOS 27 or newer, Apple Silicon (arm64) |
| 🪟 | **winadmin** | Windows 11, 64-bit (x86-64) |

This repository only hosts the programs; the source code isn't published.

## Install

**macOS** (Homebrew):

```bash
brew install ziadulhuq/tap/macadmin
macadmin init        # once: checks, settings, security; adds macadmin.app for Spotlight / Alfred / Finder
macadmin             # the terminal app; macadmin --gui (or macadmin.app) for the window
brew upgrade macadmin    # update (or: macadmin update)
brew uninstall macadmin  # remove
```

Without Homebrew: download `macadmin-<version>.aarch64.tar.gz` from the newest
[release](../../releases) that has one; its `README.txt` has the steps.

**Windows**: download `winadmin-<version>.x86_64.msi` from the newest [release](../../releases)
that has one and open it, then run `winadmin init` once. The Start menu opens the window;
`winadmin` typed in a terminal opens the terminal app (`--gui` / `--tui` choose). The user guide
(`winadmin-guide.pdf`) is next to the installer and in the Start menu. Uninstall from Settings > Apps.

A release can hold only the macOS or only the Windows file, when only that program changed.

GitHub shows each file's SHA-256 next to it. The programs aren't code-signed, so Windows (SmartScreen)
asks once before the first start, and so does macOS when you install without Homebrew.

## Versions

The last digit goes up for fixes (1.2.0 → 1.2.1), the middle one when features are added (1.2.1 → 1.3.0).
Every release lists its changes.
