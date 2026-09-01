# 592 Compass — Windows Releases

**592 Compass** is a desktop app for turning your GitHub activity into clear monthly and yearly work reports — with AI summaries, submission templates, evidence packs, and local task tracking.

![592 Compass — submission reports dashboard](assets/app-screenshot.png)

This repository contains **official Windows builds only**. Source code lives in the main [592-compass](https://github.com/Taekondainc/592-compass) repo.

---

## Latest version

| | |
|---|---|
| **Release** | **592 Compass Beta 1.9.0** |
| **Date** | September 2026 |
| **Recommended** | [592-Compass-Beta-1.9.0-Setup.exe](releases/592-Compass-Beta-1.9.0-Setup.exe) (installer) |
| **Portable** | [592-Compass-Beta-1.9.0-Portable.exe](releases/592-Compass-Beta-1.9.0-Portable.exe) (no install) |

> **Beta** includes chunked AI summaries, submission templates, plan-vs-shipped tracking, evidence pack export, and the updated blue UI.

---

## Install

### Option A — Installer (recommended)

1. Download **`592-Compass-Beta-1.9.0-Setup.exe`** from the [releases folder](releases/).
2. Run the installer and follow the prompts.
3. Launch **592 Compass Beta** from the Start menu or desktop shortcut.

### Option B — Portable

1. Download **`592-Compass-Beta-1.9.0-Portable.exe`**.
2. Move it anywhere you like (e.g. `Downloads` or a USB drive).
3. Double-click to run — nothing is written to Program Files.

Windows may show SmartScreen on first run because the app is not code-signed. Click **More info → Run anyway** if you trust this download.

---

## How to use

### 1. Sign in

- Open the app and sign in with your **GitHub username** and a **Personal Access Token** ([create one here](https://github.com/settings/tokens) with `repo` scope).
- Optional: add a **Groq API key** in Settings (`gsk_…`) for free AI summaries — [console.groq.com/keys](https://console.groq.com/keys).

### 2. Browse your year

- Pick a **year** and **repository** (or *All repositories*).
- Click any **month** to open a detailed report: merged PRs, open/closed PRs, commits, and a narrative summary.

### 3. Generate & submit reports

- **Copy / Save / Share** — export as Markdown, PDF, Word, or plain text.
- **Submission templates** — Standard, Performance, Client, Contractor, or Manager formats.
- **Detailed AI summary** — opt-in table with one AI-written line per PR/commit (batches automatically for busy months).
- **Evidence pack** — zip with report, links, and metadata for audits or clients.
- **Plan vs shipped** — compare local tasks to what actually merged.

### 4. Tasks

- Use the **Tasks** tab to track planned work locally and link it to branches/repos in your reports.

### 5. Year report

- Click **Year report** for a full-year rollup with the same export and share options.

---

## All releases

| Version | Installer | Portable |
|---------|-----------|----------|
| **Beta 1.9.0** (latest) | [Setup](releases/592-Compass-Beta-1.9.0-Setup.exe) | [Portable](releases/592-Compass-Beta-1.9.0-Portable.exe) |
| 1.9.0 | [Setup](releases/592-Compass-1.9.0-Setup.exe) | [Portable](releases/592-Compass-1.9.0-Portable.exe) |
| 1.8.0 | [Setup](releases/592-Compass-1.8.0-Setup.exe) | [Portable](releases/592-Compass-1.8.0-Portable.exe) |
| 1.7.0 | [Setup](releases/592-Compass-1.7.0-Setup.exe) | [Portable](releases/592-Compass-1.7.0-Portable.exe) |
| 1.6.0 | [Setup](releases/592-Compass-1.6.0-Setup.exe) | [Portable](releases/592-Compass-1.6.0-Portable.exe) |
| 1.5.0 | [Setup](releases/592-Compass-1.5.0-Setup.exe) | [Portable](releases/592-Compass-1.5.0-Portable.exe) |

---

## Requirements

- **Windows 10/11** (64-bit)
- **GitHub account** with a Personal Access Token
- **Internet** for GitHub API and optional AI features

---

## Support

- **Source & issues:** [github.com/Taekondainc/592-compass](https://github.com/Taekondainc/592-compass)
- **Releases:** [github.com/Taekondainc/compass_592-releases](https://github.com/Taekondainc/compass_592-releases)

Built by Triston Carter · Taekonda
