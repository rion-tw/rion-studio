# Rion Studio

English | [繁體中文](docs/README.zh-TW.md) | [简体中文](docs/README.zh-CN.md) | [日本語](docs/README.ja.md)

![Rion Studio banner showing isolated roles, browser workspaces, and assistive controls](.github/assets/rion-studio-github-preview-1280x640.jpg)

**A cross-platform login launcher and assistive workspace for web games.**

Rion Studio helps web game players keep every role, login session, and browser
layout organized in one desktop app. Create dedicated browser roles, sign in with
less friction, launch familiar window arrangements, and reduce repetitive manual
actions while you stay actively in control of play.

## Download

- [Download for macOS](https://github.com/rion-tw/rion-studio/releases/latest/download/Rion.Studio-mac.dmg)
- [Download for Windows](https://github.com/rion-tw/rion-studio/releases/latest/download/Rion.Studio-win.exe)

These links point to the installer assets attached to the latest GitHub release.
If a download returns 404, open the [latest release](https://github.com/rion-tw/rion-studio/releases/latest)
and confirm the release has finished uploading assets.

### macOS Installation

The macOS beta build uses an ad-hoc signature and is not notarized with Apple
Developer ID. Open the DMG, drag Rion Studio to Applications, and try to open it
once. If macOS blocks it, open **System Settings > Privacy & Security**, then
click **Open Anyway** for Rion Studio.

If **Open Anyway** is unavailable and you trust the download source, use this
one-time fallback in Terminal:

```bash
xattr -dr com.apple.quarantine "/Applications/Rion Studio.app"
```

This fallback removes quarantine only from Rion Studio. It does not notarize the
app or disable Gatekeeper system-wide.

## Why Rion Studio

Web games often make players juggle multiple accounts, browser windows, login
states, and repeated routine actions. Rion Studio turns that scattered workflow
into a focused control desk:

- Keep each game role in its own isolated browser session.
- Return to saved window layouts instead of rebuilding your setup every time.
- Complete sensitive sign-in flows in system Chrome when needed.
- Run small assistive macros for keys, clicks, delays, and loops under your
  supervision.
- Keep passwords out of the app. Rion Studio stores browser session data only.

## Features

### Isolated Role Browsers

Create a role for each game account, character, or task. Every role owns its own
browser directory, so sessions stay separate and can be launched independently.

### Smoother Login Flow

Some services block sign-in inside automation-controlled browsers. Rion Studio
can open the same role directory in system Chrome for login, then verify the
saved session before launching the normal bundled browser.

### Launch Workspaces

Group roles into a launch workspace and assign each one a window layout. Start a
single role or launch a full multi-role setup into the arrangement you already
prepared.

### China CDN Compatibility

Improve resource loading on networks where Google-hosted assets are unavailable.
The optional compatibility mode can automatically detect restricted access and
replace supported Google Fonts, hosted libraries, reCAPTCHA, Gravatar, Bootstrap,
and jQuery resource URLs with reachable alternatives in embedded and external
Chrome sessions. It is a targeted resource rewrite, not a VPN or proxy service.

### Human-Supervised Macros

Build compact assistive macros from key presses, clicks, delays, and repeat
intervals. Macros are designed to reduce repetitive manual input while you remain
present, supervising, and operating the game.

## Legal And Fair Use Notice

Rion Studio is an independent, general-purpose launcher and human-supervised
assistive utility. It is not affiliated with or endorsed by any game, identity
provider, Google, Chrome, Facebook, or other third-party platform. Always follow
the target service's rules and do not use Rion Studio for unattended botting,
anti-cheat evasion, exploits, disruption, or unlawful activity.

Review the complete, versioned documents before use:

- [Terms of Use](docs/legal/terms.en.md)
- [Privacy Notice](docs/legal/privacy.en.md)
- [Fair Use Rules](docs/legal/fair-use.en.md)
- [Third-Party Software Notices](docs/legal/THIRD_PARTY_NOTICES.md)
- [All supported languages](docs/legal/README.md)

## Support And Feedback

This repository is the public download and product-support home for Rion Studio.
Use [GitHub Issues](https://github.com/rion-tw/rion-studio/issues) for product bug
reports and feature requests. Source-code pull requests are not accepted; see
[SUPPORT.md](SUPPORT.md) and [SECURITY.md](SECURITY.md) for the appropriate channels.
