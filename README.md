<div align="center">

# ⚡ VAX TWEAKER

### Ultimate Windows System Optimizer

[![Version](https://img.shields.io/badge/version-1.0.0-00d4aa?style=for-the-badge)](https://github.com/vaxead/vax-tweaker/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078d4?style=for-the-badge&logo=windows)](https://github.com/vaxead/vax-tweaker)
[![Architecture](https://img.shields.io/badge/arch-x64-333333?style=for-the-badge)](https://github.com/vaxead/vax-tweaker)
[![License](https://img.shields.io/badge/license-Proprietary-ff4444?style=for-the-badge)](LICENSE)

**A professional-grade system optimization suite built in C++.**
Designed for gamers, power users, and IT professionals who demand peak performance.

<br>

<img src="assets/preview.png" alt="VAX TWEAKER Preview" width="700">

<br>
<br>

[📥 Download Latest Release](https://github.com/vaxead/vax-tweaker/releases) · [📋 Changelog](#changelog) · [🛡️ Safety](#safety--restore) · [❓ FAQ](#faq)

</div>

---

## 🎯 What is VAX TWEAKER?

VAX TWEAKER is a lightweight, native C++ application that optimizes Windows 10/11 systems through carefully curated registry tweaks, service management, and system configuration adjustments.

Unlike bloated "optimizer" software, VAX TWEAKER:
- **Runs entirely offline** — no telemetry, no accounts, no internet required
- **Modifies only what you approve** — every tweak requires explicit confirmation
- **Backs up everything automatically** — every change can be reverted instantly
- **Is a single portable executable** — no installation, no dependencies

---

## 📦 Modules

| # | Module | Description |
|---|--------|-------------|
| ⚡ | **FPS & Rendering** | Fullscreen optimizations, GPU scheduling, visual effects, Game Bar, DWM tuning, power plans |
| 🔒 | **Privacy & Telemetry** | 34 tweaks across telemetry, Cortana, Copilot, Recall, activity tracking, device permissions |
| 🎮 | **Gaming Performance** | CPU priority, system timers, HPET, MMCSS, service optimization, memory management |
| 🌐 | **Network Optimization** | Nagle's algorithm, TCP tuning, DNS configuration, NIC adapter settings, latency reduction |
| 🧹 | **Windows Debloater** | Remove bloatware, disable widgets, tips, suggestions, pre-installed apps |
| 🧽 | **System Cleaner** | 25 cleaning targets — temp files, caches, logs, crash dumps, browser data, Steam cache |
| 🛡️ | **Security Hardening** | Disable RDP, SMBv1, admin shares, harden UAC, disable PowerShell v2 engine |
| 📊 | **System Analysis** | Full hardware/software diagnostic scan with GPU, driver, runtime, and network details |
| 🚀 | **Startup Manager** | Enumerate, inspect, enable/disable startup programs across HKCU and HKLM |

---

## 🛡️ Safety & Restore

VAX TWEAKER is engineered with safety as the top priority:

| Feature | Description |
|---------|-------------|
| 🔄 **Automatic Backup** | Every registry change is backed up before modification — stored in `%APPDATA%\VaxTweaker` |
| 💾 **Crash Recovery** | Backup file persisted to disk after each operation with CRC32 integrity verification |
| ⏪ **One-Click Restore** | Restore all changes at any time from the main menu — reverse order, atomic operations |
| ⚠️ **Risk Classification** | Every tweak is labeled: `SAFE` · `MODERATE` · `ADVANCED` · `RISKY` |
| ✅ **Confirmation Prompts** | Detailed warning shown before every operation — name, description, risk level, reboot notice |
| 🖥️ **System Restore Point** | Offered at startup before any modifications — with automatic System Protection enablement |
| 🔍 **Compatibility Engine** | Detects laptop/desktop, Modern Standby, OS build, GPU driver — warns about risky combinations |
| 📝 **Full Logging** | Every operation is timestamped and logged — exportable crash log on fatal errors |

---

## 💻 System Requirements

| Requirement | Minimum |
|-------------|---------|
| **OS** | Windows 10 (build 10240+) or Windows 11 |
| **Architecture** | x64 |
| **Privileges** | Administrator recommended (required for HKLM tweaks) |
| **Disk Space** | < 2 MB |
| **Dependencies** | None — single portable `.exe` |

---

## 🚀 Quick Start

1. **Download** `VaxTweaker.exe` from [https://vaxead.gumroad.com/l/vax-tweaker]
2. **Right-click → Run as Administrator** for full functionality
3. **Accept the disclaimer** (shown only on first launch)
4. **Create a System Restore Point** when prompted
5. **Select a module** and start optimizing

> **Tip:** You can run without admin — HKCU tweaks will work, but HKLM tweaks will be skipped with a clear warning.

---

## 📸 Screenshots

<div align="center">
<img src="assets/preview.png" alt="VAX TWEAKER Main Menu" width="600">
<br>
<sub>Main menu — Admin mode, Windows 11 (Build 26200)</sub>
</div>

---

## ❓ FAQ

<details>
<summary><b>Is this safe? Can it cause a Blue Screen?</b></summary>
<br>
No. VAX TWEAKER operates entirely in user-mode — it modifies registry values, services, and power configurations through standard Windows APIs. It cannot cause a BSOD. Every change is backed up and can be restored with one click.
</details>

<details>
<summary><b>Do I need to install it?</b></summary>
<br>
No. VAX TWEAKER is a single portable executable. Download it, run it, done. No installation, no registry pollution from the app itself.
</details>

<details>
<summary><b>What if I want to undo everything?</b></summary>
<br>
Press <code>[R] Restore All Changes</code> from the main menu. Every modification made during any session is tracked and can be reversed in one step. The backup file survives crashes and reboots.
</details>

<details>
<summary><b>Does it work on Windows 10?</b></summary>
<br>
Yes. VAX TWEAKER supports both Windows 10 and 11. The compatibility engine automatically detects your OS build and warns if a tweak targets features not available on your version.
</details>

<details>
<summary><b>Is the source code available?</b></summary>
<br>
VAX TWEAKER is proprietary software. The source code is not publicly available. This repository serves as the official distribution channel for releases, documentation, and issue tracking.
</details>

<details>
<summary><b>How is this different from other tweakers?</b></summary>
<br>

- **Native C++** — no .NET runtime, no Python, no Electron. Sub-second startup.
- **Data-driven architecture** — tweaks are declared as metadata, not hardcoded logic. This makes them auditable and consistent.
- **Automatic backup with integrity verification** — CRC32-protected backup files with atomic writes.
- **Compatibility engine** — proactive warnings based on your actual hardware and OS.
- **No telemetry** — zero network calls. Ever.

</details>

---

## 📋 Changelog

### v1.0.0 — Initial Release
- 9 optimization modules with 100+ tweaks
- Automatic registry backup with CRC32 integrity verification
- System Restore Point integration
- Compatibility engine with laptop/Modern Standby detection
- Startup Manager with enable/disable toggle
- System Cleaner with 25 cleaning targets
- Security Hardening module

---

## ⚖️ License

**VAX TWEAKER** is proprietary software.
Copyright © 2025 [Vaxead](https://github.com/vaxead). All rights reserved.

This software is provided "as is" without warranty of any kind. Use entirely at your own risk.
See [LICENSE](LICENSE) for full terms.

---

<div align="center">

**Built with ❤️ and C++ by [Vaxead](https://github.com/vaxead)**

⭐ Star this repo if you find VAX TWEAKER useful

</div>
