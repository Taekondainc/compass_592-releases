# 592 Compass — Desktop Releases

**592 Compass** is a desktop app for turning your GitHub activity into clear monthly and yearly work reports — with AI summaries, submission templates, evidence packs, and local task tracking.

![592 Compass — submission reports dashboard](assets/app-screenshot.png)

Official builds for **Windows**, **macOS**, and **Linux**. Source code: [592-compass](https://github.com/tristoncarter34/592-compass) (private).

---

## Latest version — Beta 2.1.0

| Platform | Download |
|----------|----------|
| **Windows** (installer) | [592-Compass-Beta-2.1.0-Windows-Setup.exe](releases/592-Compass-Beta-2.1.0-Windows-Setup.exe) |
| **Windows** (portable) | [592-Compass-Beta-2.1.0-Windows-Portable.exe](releases/592-Compass-Beta-2.1.0-Windows-Portable.exe) |
| **macOS** (Apple Silicon) | [DMG](releases/592-Compass-Beta-2.1.0-macOS-AppleSilicon.dmg) · [ZIP](releases/592-Compass-Beta-2.1.0-macOS-AppleSilicon.zip) |
| **macOS** (Intel) | [DMG](releases/592-Compass-Beta-2.1.0-macOS-Intel.dmg) · [ZIP](releases/592-Compass-Beta-2.1.0-macOS-Intel.zip) |
| **Linux** | [AppImage](releases/592-Compass-Beta-2.1.0-Linux.AppImage) · [DEB](releases/592-Compass-Beta-2.1.0-Linux.deb) |

> **2.1.0** — GitHub OAuth sign-in, instant cached month reports, PR diff–aware AI summaries, cancel button, styled Pro PDF exports, faster AI batching.

---

## Install

### Windows

1. Download **Setup** (recommended) or **Portable**.
2. Run the installer, or double-click the portable `.exe`.
3. If SmartScreen appears: **More info → Run anyway** (app is not code-signed).

### macOS

1. Download the **DMG** for your Mac (Apple Silicon or Intel).
2. Open the DMG and drag **592 Compass Beta** to Applications.
3. First launch: **System Settings → Privacy & Security → Open Anyway** if macOS blocks an unsigned app.

### Linux

**AppImage (recommended):**
```bash
chmod +x 592-Compass-Beta-2.1.0-Linux.AppImage
./592-Compass-Beta-2.1.0-Linux.AppImage
```

**Debian/Ubuntu:**
```bash
sudo dpkg -i 592-Compass-Beta-2.1.0-Linux.deb
```

---

## How to use

1. **Sign in** — click **Continue with GitHub** (browser OAuth) or use a [Personal Access Token](https://github.com/settings/tokens) (`repo` scope).
2. **AI reports** — Groq is bundled in official builds; optional Pro license unlocks styled PDF exports in Settings.
3. Pick a **year** and **month**, open a report (cached instantly, refreshes in background), export with templates.
4. Use **Tasks** for local plan-vs-shipped tracking.

---

## All Windows releases

| Version | Installer | Portable |
|---------|-----------|----------|
| **2.1.0** (latest) | [Setup](releases/592-Compass-Beta-2.1.0-Windows-Setup.exe) | [Portable](releases/592-Compass-Beta-2.1.0-Windows-Portable.exe) |
| 2.0.0 | [Setup](releases/592-Compass-Beta-2.0.0-Windows-Setup.exe) | [Portable](releases/592-Compass-Beta-2.0.0-Windows-Portable.exe) |
| 1.9.1 | [Setup](releases/592-Compass-Beta-1.9.1-Setup.exe) | [Portable](releases/592-Compass-Beta-1.9.1-Portable.exe) |
| 1.9.0 | [Setup](releases/592-Compass-1.9.0-Setup.exe) | [Portable](releases/592-Compass-1.9.0-Portable.exe) |

---

## Requirements

- **Windows 10/11**, **macOS 11+**, or **Ubuntu 20.04+** / Debian-based Linux (64-bit)
- GitHub account
- Internet for GitHub API and optional AI features

---

## Support

- **Releases:** [github.com/Taekondainc/compass_592-releases](https://github.com/Taekondainc/compass_592-releases)

Built by Triston Carter · Taekonda
