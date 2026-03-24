# Client Setup

One-command installer for your development environment. Installs 15 tools including Node.js, Python, Git, Pandoc, Claude Code, and more.

## Quick Start

### macOS / Linux

Open Terminal and paste:

```bash
curl -fsSL https://raw.githubusercontent.com/lorecraft-io/client-setup/main/script-0-install.sh | bash
```

### Windows

Open PowerShell and paste:

```powershell
irm https://raw.githubusercontent.com/lorecraft-io/client-setup/main/script-0-install.ps1 | iex
```

## What Gets Installed

| Tool | Purpose |
|------|---------|
| Homebrew (Mac) / winget (Win) | Package manager |
| Git | Version control |
| Node.js (v18+ via nvm) | JavaScript runtime |
| Python 3 + pip | Python runtime |
| Pandoc | Document conversion (docx, pptx → markdown) |
| xlsx2csv | Spreadsheet conversion (xlsx → csv) |
| pdftotext | PDF text extraction |
| jq | JSON processing |
| ripgrep | Fast code search |
| GitHub CLI (gh) | GitHub from the terminal |
| tree | Directory visualization |
| fzf | Fuzzy finder |
| wget | File downloads |
| Claude Code | AI-powered coding assistant |

## After Install

The script will prompt you to log in to Claude Code:

```bash
claude auth login
```

This opens a browser window — sign in with your Anthropic account and you're set.

## Requirements

- **macOS** 11+ (Big Sur or later)
- **Linux** Ubuntu 20.04+ / Debian 11+ / Fedora 36+
- **Windows** 10 (1709+) or 11
- Internet connection
- Do **not** run as root/admin
