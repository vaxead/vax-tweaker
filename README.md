<div align="center">

# ⚡ VAX TWEAKER

### Native Windows optimization suite for gamers, power users, and latency-sensitive setups

[![Version](https://img.shields.io/badge/version-2.3.1-00d4aa?style=for-the-badge)](https://github.com/vaxead/vax-tweaker/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078d4?style=for-the-badge&logo=windows)](https://github.com/vaxead/vax-tweaker)
[![Architecture](https://img.shields.io/badge/arch-x64-333333?style=for-the-badge)](https://github.com/vaxead/vax-tweaker)
[![License](https://img.shields.io/badge/license-Proprietary-ff4444?style=for-the-badge)](LICENSE)

**359 tweaks across 15 active modules, with one-click restore, hardware-aware safeguards, and official free + premium editions.**

<br>

<img src="assets/preview.png?v=2.3.1" alt="VAX TWEAKER v2.3.1 Preview" width="700">

<br>
<br>

[💎 Get Premium](https://vaxtweaker.com/) · [🆓 Free Edition](https://github.com/vaxead/vax-tweaker-free) · [💬 Discord](https://discord.com/invite/UsJRm6shZw) · [📋 Changelog](#changelog) · [🛡️ Safety](#safety--restore) · [❓ FAQ](#faq)

</div>

---

## 🎯 What is VAX TWEAKER?

VAX TWEAKER is a native C++ application that optimizes Windows 10/11 systems through carefully curated registry tweaks, service controls, driver-level settings, cleanup tools, and diagnostic utilities.

This public repository is used for official release visibility, screenshots, documentation, and issue tracking. The premium source code is not public.

Unlike disposable "optimizer" tools, VAX TWEAKER is built around control and recoverability:
- **Native C++** — no Electron, no Python runtime, no .NET dependency
- **Hardware-aware** — incompatible tweaks are hidden or warned before you apply them
- **Full revert path** — backups, restore flow, and reboot-aware safeguards are built in
- **Portable** — single executable, no installer, no background service
- **Focused on outcomes** — lower background overhead, cleaner systems, better frame pacing, and easier maintenance

---

## ✨ Release Snapshot — v2.3.1

- **359 total tweaks** across **15 active modules**
- **Expanded core coverage**: FPS & Rendering `57`, Gaming Performance `58`, Network `26`, Privacy `61`, Debloater `49`, Cleaner `39`, Service Manager `42`
- **Premium-only toolset** now includes **VAX Score**, **Gaming Mode**, **Diagnostics**, **Process Booster**, **Game Profiles**, and **System Monitor**
- **Drift Detection** alerts when Windows, drivers, or other software revert previously applied tweaks
- **Post-release hotfixes** harden restore-point validation against phantom entries and move active premium builds to a built-in one-file updater flow

---

## 💎 Premium vs Free

| Category | Free Edition | Premium Edition |
|---|---|---|
| Active modules | 3 | 15 |
| Optimization coverage | 75 entries | 359 tweaks |
| Included core modules | FPS & Rendering, Network & Latency, System Cleaner | All free coverage plus Gaming Performance, NVIDIA tuning, Privacy, Security, Debloater, Service Manager |
| Advanced tools | — | Diagnostics, Process Booster, VAX Score, Gaming Mode, Game Profiles, System Monitor |
| Best for | Baseline cleanup and starter optimization | Full competitive setup tuning, system maintenance, and deeper diagnostics |
| Release model | Maintenance updates | Full feature releases and premium-only modules |

> **Choose Free** if you want a lightweight baseline setup.  
> **Choose Premium** if you want the full optimization stack, exclusive tools, and the current flagship release.

---

## 📦 Core Optimization Modules — 359 Tweaks

| # | Module | Tweaks | Description |
|---|--------|:------:|-------------|
| ⚡ | **FPS & Rendering** | 57 | Display compositor tuning, GPU scheduling, overlays, timer distribution, power and latency related tweaks |
| 🎮 | **Gaming Performance** | 58 | CPU priority, timer controls, service tuning, startup control, memory and I/O optimization for game workloads |
| 🖥️ | **NVIDIA Inspector** | 14 | NVIDIA driver-level tuning for power, shader cache, threaded optimization, texture filtering, and related GPU behavior |
| 🌐 | **Network Optimization** | 26 | NIC tuning, TCP stack adjustments, DNS options, heuristics, QoS, latency-focused networking tweaks |
| 🔒 | **Privacy & Telemetry** | 61 | Windows telemetry controls, Recall/Copilot/Cortana related settings, activity sync, permissions, and third-party telemetry cleanup |
| 🛡️ | **Security Hardening** | 13 | Browser and OS hardening, credential and network security controls, legacy feature lockdown |
| 🧹 | **Windows Debloater** | 49 | Windows UI cleanup, scheduled task reduction, update noise reduction, experiment and consumer-feature cleanup |
| 🧽 | **System Cleaner** | 39 | Temp files, shader caches, browser/application residue, ghost devices, leftover registry cleanup, and RAM-oriented cleanup actions |
| ⚙️ | **Service Manager** | 42 | Toggle unnecessary services that impact background overhead, latency, telemetry, or system clutter |

### 🧰 Tools & Quick Actions

- **System Monitor** — live CPU, RAM, and disk activity dashboard
- **Game Profiles** — save and reload per-game optimization sets
- **Process Booster** — prioritize target processes and reduce background interference
- **Diagnostics** — inspect DPC latency, WHEA/TDR errors, and network jitter
- **VAX Score** — rate your current optimization level on a 0-100 scale
- **Gaming Mode** — one-click pre-game optimization workflow

---

## 🛡️ Safety & Restore

VAX TWEAKER is designed to let you tune aggressively without losing visibility or recovery options.

| Feature | Description |
|---------|-------------|
| 🔄 **Automatic Backup** | Registry targets are backed up before modification and persisted for restore |
| 💾 **Crash Recovery** | Backup state survives interrupted sessions and failed tweak batches |
| ⏪ **One-Click Restore** | Reverse changes from the app without manually hunting registry keys or services |
| ⚠️ **Risk Classification** | Every tweak is labeled `SAFE`, `MODERATE`, `ADVANCED`, or `RISKY` |
| ✅ **Confirmation Prompts** | Riskier actions surface confirmation text before execution |
| 🖥️ **System Restore Point** | Restore point creation is offered before applying large changes |
| 🔍 **Compatibility Engine** | Build, hardware, and platform checks prevent obviously incompatible tweaks from being applied |
| 📝 **Full Logging** | Operations are logged so you can review what changed |
| 🔔 **Drift Detection** | Reverted tweaks can be surfaced after updates, driver changes, or system maintenance |
| 🌐 **Official Distribution** | Download Premium from [vaxtweaker.com](https://vaxtweaker.com/) and Free from the official GitHub repository only |

> Some security products may flag system utilities that modify registry, services, or power settings. Download only from official channels and review changes before applying them.

---

## 💻 System Requirements

| Requirement | Minimum |
|-------------|---------|
| **OS** | Windows 10 / Windows 11 (x64) |
| **Privileges** | Administrator recommended for full system coverage |
| **Disk Space** | Small portable executable, no installer required |
| **Dependencies** | None — no external runtime needed |

---

## 🚀 Quick Start

1. **Choose your edition**: [Premium](https://vaxtweaker.com/) or [Free](https://github.com/vaxead/vax-tweaker-free)
2. **Download only from official sources**
3. **Run as Administrator** if you want full HKLM / service / power plan coverage
4. **Create a Restore Point** when prompted
5. **Apply module by module** instead of toggling everything blindly on a fresh system
6. **Reboot when requested** by a tweak or module

> **Recommendation:** Start with FPS, Network, and Cleaner on stable systems; move to deeper privacy, debloat, and service changes once you've reviewed the descriptions.

---

## 📸 Screenshot

<div align="center">
<img src="assets/preview.png?v=2.3.1" alt="VAX TWEAKER Main Menu" width="600">
<br>
<sub>VAX TWEAKER v2.3.1 — Premium build overview</sub>
</div>

---

## ❓ FAQ

<details>
<summary><b>Is it safe to use?</b></summary>
<br>
VAX TWEAKER operates through standard Windows interfaces such as registry, service, and power configuration APIs. It is built around backups, confirmation prompts, restore points, compatibility checks, and full revert workflows. As with any system utility, review the tweak descriptions and keep a restore path before applying broader changes.
</details>

<details>
<summary><b>Why might antivirus or SmartScreen flag it?</b></summary>
<br>
System optimization tools can trigger heuristic detections because they change services, registry values, startup behavior, power settings, or network-related configuration. That does not automatically mean a file is malicious, but it does mean you should download only from official channels and verify that the build came from VAX TWEAKER.
</details>

<details>
<summary><b>What is the difference between Free and Premium?</b></summary>
<br>
The Free Edition covers a lighter baseline setup with 3 active modules and 75 entries. Premium unlocks the full 15-module release, 359 tweaks, and the exclusive toolset around diagnostics, scoring, gaming mode, profiles, and deeper system coverage.
</details>

<details>
<summary><b>Will it increase FPS on every PC?</b></summary>
<br>
Not every machine will gain the same amount. The main goals are lower background overhead, cleaner frame pacing, reduced stutter sources, and easier maintenance. Results depend on your hardware, drivers, Windows build, and how optimized your system already is.
</details>

<details>
<summary><b>Do I need to install it?</b></summary>
<br>
No. VAX TWEAKER is distributed as a portable executable. Download it, run it, and use only the modules you actually want.
</details>

<details>
<summary><b>Can I undo everything?</b></summary>
<br>
Yes. Restore flows are built into the app and registry backups are created before changes are written. Restore points are also offered for broader recovery.
</details>

<details>
<summary><b>Is the source code available?</b></summary>
<br>
The Premium build is proprietary. This repository is used for official release visibility, documentation, and issue tracking around the product.
</details>

<details>
<summary><b>How is this different from disposable tweaker packs?</b></summary>
<br>

- **Native C++ application** instead of a bundle of loose scripts
- **Structured modules and metadata-driven tweaks** rather than opaque one-off commands
- **Compatibility-aware behavior** for hardware and OS build differences
- **Rollback-minded architecture** with backups, restore, and failure handling
- **Built-in diagnostics and maintenance tools** alongside the tweak library

</details>

---

## 📋 Changelog

### v2.3.1 — Global Release
- **359 total tweaks** across **15 active modules**
- **VAX Score** added for fast optimization scoring across performance, GPU, network, privacy, and system state
- **Gaming Mode** added for one-click pre-game preparation
- **Diagnostics Module** expanded around DPC latency, WHEA/TDR, and network jitter analysis
- **System Cleaner** expanded to **39 actions**
- **Service Manager** expanded to **42 targets**
- **Privacy & Telemetry** expanded to **61 tweaks**
- **Core framework** updated with safer background batch execution and rollback-aware processing
- **Store and licensing flow** refreshed for the current global release
- **Post-release hotfixes** improved restore-point confirmation and moved active premium builds to a built-in one-file updater flow

### v2.2.0 — Deep Optimization Update
- **296 total tweaks** across **12 modules**
- Drift Detection, Multi-GPU driver support, additional diagnostics coverage, and faster background status refresh
- FPS & Rendering, Gaming Performance, NVIDIA Inspector, Network, Service Manager, and Debloater all expanded

### v2.0.0 — Major Update
- **275 total tweaks** across **12 modules**
- Privacy, Security, Debloater, NVIDIA Inspector, Service Manager, System Monitor, and Game Profiles expanded or introduced
- Machine-bound licensing and full tweak revert/status detection added to the premium architecture

---

## ⚖️ License

**VAX TWEAKER** is proprietary software.  
Copyright © 2026 [Vaxead](https://github.com/vaxead). All rights reserved.

This software is provided "as is" without warranty of any kind. Use at your own risk.  
See [LICENSE](LICENSE) for full terms.

---

<div align="center">

**Built in C++ by [Vaxead](https://github.com/vaxead)**

⭐ Star this repo if you want to follow future releases

</div>
