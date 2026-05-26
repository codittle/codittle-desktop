# Codittle Desktop

Native desktop app for **[Codittle](https://codittle.com)** — Codittle Code,
Canvas, and Origins in one local workspace, running on your own machine.

This repository is the **release channel** for Codittle Desktop: it hosts the
installers and the auto-updater manifest. There's no product source here — the
app is the same Codittle Studio you get at
[codittle.com](https://codittle.com), in a native window.

## Download

Grab the latest build from the
[**Releases page**](https://github.com/codittle/codittle-desktop/releases/latest).

| Platform | File | Notes |
|----------|------|-------|
| Windows 10/11 · x64 | `Codittle_<version>_x64-setup.exe` | **Recommended** — standard per-user installer |
| Windows 10/11 · x64 | `Codittle_<version>_x64_portable.zip` | Portable — unzip anywhere and run, no installation |
| Windows 10/11 · x64 | `Codittle_<version>_x64_en-US.msi`  | Managed / enterprise deploy (Intune, GPO) |
| macOS               | —                                   | Coming soon |
| Linux               | —                                   | Coming soon |

Installed builds keep themselves up to date.

## What's inside

One local workspace bringing together:

- **Codittle Code** — jBASE / Transact routine development: browse, edit, and
  SSH-deploy routines to a live server, with an embedded terminal.
- **OFS Playground** — compose and send OFS messages.
- **Port Checker** — probe services over SSH.
- **Claude Code terminal** — embedded AI coding assistant.
- **Canvas** and **Code Origins** — visual flow building and living software.

## Install — Windows

1. Download `Codittle_<version>_x64-setup.exe` from the latest release.
2. Run it. The installer is **per-user** — no administrator rights needed.
3. Launch **Codittle**.

**Prefer no installation?** Grab `Codittle_<version>_x64_portable.zip`, unzip it
anywhere, and run `codittle-desktop.exe` — no installer, no admin rights. For
managed / silent deployment, use the `.msi` (Intune or Group Policy).

## Versioning

Releases are tagged `vMAJOR.MINOR.PATCH` (semantic versioning). Each build also
carries a monotonic **build number**, shown in the app under **Settings → About**
alongside the version and commit — handy when reporting an issue.

## Links

- **Web app** — [codittle.com](https://codittle.com)
- **Support** — [support@codittle.com](mailto:support@codittle.com)

---

<sub>Codittle Desktop is built with [Tauri](https://tauri.app). Reporting an
issue with a specific build? Include the version and build number from
**Settings → About**.</sub>
