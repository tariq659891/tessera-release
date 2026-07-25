# Tessera

Desktop release artifacts for Tessera. **Source code is private** — this repository
contains only built installers and the auto-update feed.

## Install (macOS)

Download the latest release below and pick the build for your Mac:

| Your Mac | File |
|---|---|
| Apple Silicon (M1/M2/M3/M4) | `Tessera-x.y.z-arm64.dmg` |
| Intel | `Tessera-x.y.z.dmg` |

Not sure which you have?  → Apple menu → About This Mac. "Apple M…" = Apple Silicon.

Open the `.dmg`, drag **Tessera** to your Applications folder, and launch it.

The app is **signed and notarized by Apple**, so it opens normally — no security
warnings and no right-click workaround. If macOS ever does warn you that the app is
damaged or from an unidentified developer, do not bypass it: that means the download
was corrupted or tampered with. Re-download from this page.

## Updates

Tessera checks this repository for updates on launch and every 6 hours. When a new
version is ready it downloads in the background and offers to restart — updates are
never installed without your consent.

## Windows and Linux

Not yet available. Both are built but not published, because neither is
code-signed yet and an unsigned installer would greet you with a security warning
we're not willing to ship.

## The `.zip` files

Each release includes `.zip` artifacts alongside the `.dmg`. Those are what the
auto-updater consumes — you don't need to download them. Use the `.dmg`.

## Support

Questions or problems: tessera@tesserra.app
