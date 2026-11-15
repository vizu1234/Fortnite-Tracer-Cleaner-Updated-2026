# 🎮 Fortnite Tracer Cleaner (Updated 2026 Edition)

<p align="center">
  <img src="https://img.shields.io/badge/OS-Windows%2010%20%2F%2011-blue?style=for-the-badge&logo=windows" alt="Windows">
  <img src="https://img.shields.io/badge/Status-Updated%202026-success?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Target-Telemetry%20%2F%20Logs-orange?style=for-the-badge" alt="Target">
</p>

---

## 📌 Overview

This repository hosts the updated **Fortnite Tracer Cleaner**, created by **vizu1234**. Designed for the current system environment, this utility automatically sweeps and purges residual tracking files, Unreal Engine telemetry logs, crash reports, and local cache artifacts left behind by Fortnite and the Epic Games Launcher.

> [!NOTE]
> This tool focuses exclusively on log files, telemetry traces, and local cache directories. It does not modify game core files, pak files, or system drivers.

---

## ✨ Key Features

* **🧹 Comprehensive Log Purging:** Automatically detects and clears `%localappdata%\FortniteGame` logs and temporary cache directories.
* **🔍 UE4/UE5 Trace Stripping:** Removes Unreal Engine crash dumps, session logs, and telemetry tracking files.
* **⚡ Fast Automated Execution:** Streamlined architecture designed for rapid execution before launching the game session.
* **🛡️ Safe & Non-Destructive:** Cleans only ephemeral user data and logs without touching essential game assets or installation files.

---

## 📋 System Requirements

| Component | Requirement |
| :--- | :--- |
| **Operating System** | Windows 10 / Windows 11 (`x64` architecture) |
| **Permissions** | Administrator privileges recommended for complete AppData access |

---

## 🚀 Usage Guide

> [!IMPORTANT]
> **Pre-requisite:** Ensure Fortnite and the Epic Games Launcher are completely closed before running the cleaner.

1. Download or clone the repository into your working directory.
2. Right-click the script or executable and select **Run as Administrator**.
3. Allow the automated scan to clear residual logs and telemetry traces.
4. Launch your game or custom client session cleanly.

---

## 🛠️ Troubleshooting & FAQ

* **Q: Do I need to run this every time I play?**
  * **A:** Running it before starting your session ensures that old telemetry logs and crash reports from previous sessions are completely wiped.
* **Q: Does this affect my in-game settings or account data?**
  * **A:** No. Configuration files and user profiles remain untouched; only temporary logs, caches, and crash dumps are targeted.

---

## ⚖️ Credits & Disclaimer

* **Developer:** [vizu1234 (GitHub)](https://github.com/vizu1234)
* **Disclaimer:** This software is shared for educational, informational, and archival research purposes only. The user assumes full responsibility for any consequences arising from its usage.
