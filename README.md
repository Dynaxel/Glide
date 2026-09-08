# Glide 1.0 — Public Tester Pack

**Glide — Browse light. Stream smooth.**

Glide is a lightweight Windows browser built with gamers, streamers and content creators in mind. It uses Microsoft WebView2 for web rendering while Glide manages its own browser UI, tabs, streamer tools and resource-conscious behaviour.

This pack is for **public testing of Glide 1.0.0**.

## Downloads

Choose one:

- **Glide-1.0.0-Setup.exe** — recommended installer
- **Glide-1.0.0-win-x64-portable.zip** — portable Windows x64 build

## Important: Windows SmartScreen

Glide 1.0 is currently distributed as an **unsigned independent application**.

Because the installer is new and unsigned, Microsoft Defender SmartScreen may show an **"Windows protected your PC"** or **"Unknown publisher"** warning. This does not by itself mean the file is malicious; it means the app does not yet have established signing/reputation.

Only download Glide from the official GitHub release page and compare file hashes with `SHA256SUMS.txt` if you want to verify the download.

## What to test

Glide 1.0 includes:

- lightweight WebView2-based browsing
- logical tab system with bounded live-tab behaviour
- optional **Maximum live tabs** setting
- bookmarks and bookmark manager
- browsing history
- downloads manager
- privacy and site-data controls
- popup handling
- Twitch raid handling
- Stream Mode
- OBS Studio and Meld Studio detection
- Streamer Controls
- mute/unmute all Glide audio
- play/pause active media
- Panic Silence
- creator quick links
- settings export/import
- dark/light themes and accent choices
- default-browser registration
- single-instance external-link handling
- session restore
- optional performance diagnostics bar

## Recommended test setup

Glide 1.0 is intended for **Windows x64**.

For the best feedback, try Glide during the kind of workload it is designed for:

- gaming with a browser open on another monitor
- Twitch or YouTube playback while gaming
- OBS Studio or Meld Studio running
- several normal tabs plus 1–4 live tabs
- downloading files
- using Glide as the Windows default browser

## Getting started

### Installer

1. Run `Glide-1.0.0-Setup.exe`.
2. Follow the installer.
3. Launch Glide from the Start Menu.
4. Open **Settings** to review Stream Mode, themes and Maximum live tabs.
5. To make Glide your browser for web links, use **Set Glide as default browser...** from Glide and complete the choice in Windows Default Apps.

### Portable build

1. Extract `Glide-1.0.0-win-x64-portable.zip`.
2. Run `Glide.exe`.
3. Keep the extracted folder intact.

## Reporting problems

Please read `REPORT-A-BUG.md`.

Useful reports include:

- what you were doing
- what you expected
- what actually happened
- Windows version
- RAM / CPU / GPU
- whether OBS Studio or Meld Studio was open
- Maximum live tabs setting
- whether Stream Mode was active
- screenshots where useful

Crash logs are stored locally under:

`%LOCALAPPDATA%\Glide\Logs`

Please review any log before sharing it publicly.

## Privacy

See `PRIVACY.md`.

## Release status

This is the **Glide 1.0.0 public tester build**. Feedback, edge cases and bug reports are welcome.

Source code is **not included in this tester pack**.
