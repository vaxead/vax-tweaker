<div align="center">

# ⚡ VAX TWEAKER

### Ultimate Windows System Optimizer

[![Version](https://img.shields.io/badge/version-2.3.0-00d4aa?style=for-the-badge)](https://github.com/vaxead/vax-tweaker/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078d4?style=for-the-badge&logo=windows)](https://github.com/vaxead/vax-tweaker)
[![Architecture](https://img.shields.io/badge/arch-x64-333333?style=for-the-badge)](https://github.com/vaxead/vax-tweaker)
[![License](https://img.shields.io/badge/license-Proprietary-ff4444?style=for-the-badge)](LICENSE)

**A professional-grade system optimization suite built in C++.**
Designed for gamers, power users, and IT professionals who demand peak performance.

<br>

<img src="assets/preview.png?v=2.3.0b" alt="VAX TWEAKER v2.3.0 Preview" width="700">

<br>
<br>

[📥 Download](https://whop.com/vaxtweaker-2412/vax-tweaker/) · [💬 Discord](https://discord.gg/9Wu2EYPxrw) · [📋 Changelog](#changelog) · [🛡️ Safety](#safety--restore) · [❓ FAQ](#faq)

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

## ✨ What's New in v2.3.0

- **Whop licensing** — migrated license verification from Gumroad to Whop API v2
- **Simplified machine binding** — HWID stored as metadata on the Whop membership (no more uses counter)
- **330 total tweaks** across 13 modules

---

## 📦 Modules — 330 Tweaks

| # | Module | Tweaks | Description |
|---|--------|:------:|-------------|
| ⚡ | **FPS & Rendering** | 52 | Fullscreen optimizations, GPU scheduling, visual effects, Game Bar/DVR, DWM compositor, MPO, transparency, power plans, Intel/AMD/NVIDIA driver-level tweaks, PCIe ASPM, MSI Mode, coalescence timer, worker threads |
| 🎮 | **Gaming Performance** | 54 | CPU priority, system timers, HPET/TSC/Platform Tick, MMCSS, network throttling, prefetch, WER, service management, memory optimization, I/O system tuning, startup apps control |
| 🖥️ | **NVIDIA Inspector** | 14 | GPU driver-level optimizations — shader cache, power management, threaded optimization, texture filtering, CUDA, display power, PCIe link state, GR535, tray icon |
| 🌐 | **Network Optimization** | 23 | Nagle's algorithm, TCP tuning, DNS config, NIC adapter, AFD socket tuning, TCP advanced parameters, QoS bandwidth limit, timestamps, heuristics, ECN |
| 🔒 | **Privacy & Telemetry** | 62 | 10 groups — telemetry, Cortana/Copilot/Recall, activity sync, device permissions, app data access, sensors, NVIDIA/VS/Edge/Office telemetry |
| 🛡️ | **Security Hardening** | 13 | RDP, SMBv1, admin shares, UAC, WDigest, AutoRun, PowerShell v2, Edge/Chrome/Firefox browser security policies |
| 🧹 | **Windows Debloater** | 47 | 7 groups — taskbar UI, Start tips, UWP removal, scheduled tasks, Windows Update controls, Insider/experiments, compatibility |
| 🧽 | **System Cleaner** | 33 | Temp files, prefetch, thumbnails, browser caches (Chrome/Edge/Firefox), Steam, NVIDIA/AMD, Office, Teams, Discord, DNS flush |
| ⚙️ | **Service Manager** | 32 | Disable unnecessary Windows services — Xbox, Maps, Retail Demo, Contact Data, diagnostics, update, telemetry, geolocation, print spooler, and more |
| 📊 | **System Analysis** | — | Full hardware/software diagnostic scan — CPU, GPU, RAM, drivers, runtimes, disk health, power plan, event log errors, services audit |
| 📈 | **System Monitor** | — | Real-time CPU, RAM, and disk usage monitoring with live-updating console dashboard |
| 🎯 | **Game Profiles** | — | Save and load per-game optimization profiles — apply/revert tweak sets with one click |
| 🚀 | **Process Booster** | — | View running processes and change their priority class (e.g., High, Above Normal) for real-time performance tuning |

---

## 🔍 Drift Detection

VAX TWEAKER now saves a snapshot of your applied tweaks after each session. On the next launch, it compares the snapshot against the live system state and warns you if Windows updates, driver installations, or other software reverted any of your optimizations — with the exact list of drifted settings.

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
| 🖥️ **System Restore Point** | Offered at startup — automatic System Protection detection and enablement before creation |
| 🔍 **Compatibility Engine** | Detects laptop/desktop, Modern Standby, OS build, GPU vendor/driver — warns about risky combinations |
| 📝 **Full Logging** | Every operation is timestamped and logged — session log auto-exported on exit |
| 🔔 **Drift Detection** | Compares tweak snapshots across sessions — alerts if Windows or other software reverted your changes |

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

1. **Download** `VaxTweaker.exe` from [Whop](https://whop.com/vaxtweaker-2412/vax-tweaker/)
2. **Right-click → Run as Administrator** for full functionality
3. **Accept the disclaimer** (shown only on first launch)
4. **Create a System Restore Point** when prompted
5. **Select a module** and start optimizing

> **Tip:** You can run without admin — HKCU tweaks will work, but HKLM tweaks will be skipped with a clear warning.

---

## 📸 Screenshots

<div align="center">
<img src="assets/preview.png?v=2.3.0b" alt="VAX TWEAKER Main Menu" width="600">
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
- **Drift detection** — knows when Windows reverts your tweaks and warns you.
- **No telemetry**

</details>

---

## 📋 Changelog

### v2.3.0 — Expansion Update + Whop Licensing
- **34 new tweaks** — 330 total tweaks across 13 modules
- **FPS & Rendering** (47 → 52): 5 new driver-level and compositor tweaks
- **Gaming Performance** (44 → 54): 10 new system-level optimizations
- **Network Optimization** (17 → 23): 6 new protocol and adapter tweaks
- **Windows Debloater** (34 → 47): 13 additional bloatware and telemetry removal targets
- **New module: Process Booster** — view running processes and change priority class for performance tuning
- **Licensing backend migrated** from Gumroad to Whop API v2
- **Simplified machine binding** — HWID stored as Whop membership metadata instead of Gumroad uses counter
- **Updated purchase links** — download now available at [whop.com/vaxtweaker-2412/vax-tweaker](https://whop.com/vaxtweaker-2412/vax-tweaker/)

### v2.2.0 — Deep Optimization Update
- **22 new tweaks** — 296 total tweaks across 12 modules
- **FPS & Rendering** (40 → 47): Intel GPU Optimization, Power Latency Tuning, Connected Standby Disable, GPU Scheduler Optimization, Coalescence Timer Disable, Worker Thread Optimization, DWM Advanced Compositor tweaks
- **Gaming Performance** (38 → 44): I/O System Tuning, Disable All Startup Apps, and additional system-level optimizations
- **NVIDIA Inspector** (9 → 14): Display Power Management, PCIe Link State Override, GR535 Driver Optimization, Tray Icon Control, additional driver-level tweaks
- **Network Optimization** (13 → 17): AFD Socket Tuning, TCP Advanced Parameters, QoS Bandwidth Limit, additional protocol optimizations
- **Service Manager** (18 → 32): 14 additional toggleable Windows services — expanded coverage for telemetry, update, geolocation, print spooler, and diagnostic services
- **Debloater** (31 → 34): additional bloatware removal targets
- **New: Drift Detection** — background system that saves tweak snapshots and detects when Windows updates or other software reverts applied settings; warning displayed on startup with the list of drifted tweaks
- **New: Multi-GPU driver support**
- **New: PCIe ASPM disable** — powercfg-based Active State Power Management control for maximum GPU/NIC throughput
- **New: MSI Mode** — Message Signaled Interrupts for GPU, reducing interrupt latency
- **Restore Point refactored** — automatic System Protection detection and enablement before creation; COM-based retry logic
- **Console improvements** — custom font setup with automatic cleanup on exit; improved UTF-8 rendering
- **Diagnostics expanded** — disk health (SMART), services audit, recent system errors, 3rd-party driver checker, network latency test (ping), memory breakdown
- **Background scanning** — module status refresh runs on a detached thread so the main menu appears instantly
- **Session log auto-export** — session log automatically saved to disk on exit
- **StartupModule removed** — startup app management consolidated into Gaming Performance module

### v2.1.0 — Performance Parity Update
- **New tweak**: Force Platform Clock (`useplatformtick`) — bcdedit-based, full Apply/Revert/Status with laptop compatibility warnings
- **New tweak**: Disable Prefetch — stops Windows Prefetcher and Superfetch via registry (complements SysMain disable)
- **New tweak**: Disable Windows Error Reporting — stops WerSvc and blocks crash report uploads
- **New tweak**: Disable Connected User Experiences — stops dmwappushservice (DiagTrack companion)
- **Critical fix**: Added `NetworkThrottlingIndex = 0xFFFFFFFF` to MMCSS optimization — disables the default 10 Mbit/s network throttling during multimedia playback
- **Fix**: MMCSS description now correctly states 0% background CPU reservation (was showing 10%)
- **Fix**: Platform Tick now included in Compatibility Engine power/thermal warnings for laptops
- **Fix**: Service Host Split and Prefetch now properly listed in Memory & Storage group
- Updated group definitions for Services & Background and Memory & Storage
- **280+ total tweaks** across 12 modules

### v2.0.0 — Major Update
- **275 total tweaks** across **12 modules** (+30 new tweaks, +3 new modules)
- **Privacy**: 62 tweaks in 10 groups — new Extended Telemetry Controls, Sensor & Location, Third-Party Telemetry (NVIDIA, VS, Edge, Office)
- **Privacy**: Full ConsentStore coverage — Videos, Email, Tasks, Messaging, Broad Filesystem, Motion Data
- **Debloater**: 31 tweaks in 7 groups — new Windows Update Controls, Insider/Experiments, Compatibility & Diagnostics
- **Security**: 13 tweaks in 3 groups — new Browser Security group (Edge hardening, Chrome Reporter, Firefox Agent)
- **New module**: NVIDIA Inspector — 9 GPU driver-level tweaks via registry
- **New module**: Service Manager — 18 toggleable Windows services
- **New module**: System Monitor — real-time CPU/RAM/Disk dashboard
- **New module**: Game Profiles — per-game tweak presets
- **Machine-bound licensing** — HWID + DPAPI + Whop metadata binding (1 key = 1 device)
- All tweaks fully reversible with data-driven apply/revert/status detection

### v1.0.0 — Initial Release
- 9 optimization modules with 200+ tweaks
- Automatic registry backup with CRC32 integrity verification
- System Restore Point integration
- Compatibility engine with laptop/Modern Standby detection
- System Cleaner with 33 cleaning targets
- Security Hardening module
- Full System Analysis diagnostic scanner

---

## ⚖️ License

**VAX TWEAKER** is proprietary software.
Copyright © 2025 [Vaxead](https://github.com/vaxead). All rights reserved.

This software is provided "as is" without warranty of any kind. Use entirely at your own risk.
See [LICENSE](LICENSE) for full terms.

---

<div align="center">

**Built with ❤️ and C++ by [Vaxead](https://github.com/vaxead)**

[💬 Join our Discord](https://discord.gg/9Wu2EYPxrw)

⭐ Star this repo if you find VAX TWEAKER useful

</div>
