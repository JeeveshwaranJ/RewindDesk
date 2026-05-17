# 🖥️ RewindDesk

A local-first, lightweight background activity tracker designed with a gorgeous, nostalgic **"Potato PC" retro-classic clean & minimal UI**. 

RewindDesk silently runs in your system tray, building a high-performance timeline of your productive workflow sessions without ever uploading a single byte to the cloud.

---

## 🛡️ Core Principles (Zero Spyware)

RewindDesk is **not** employee monitoring software, **not** a keylogger, and **not** spyware. It is built strictly for personal productivity and self-reflection under absolute privacy.

* **🚫 NO Screenshots or Video**: Never captures your screen, camera, or visual inputs.
* **🚫 NO Keystroke Logging**: Never records what you type, preventing passwords or inputs from being intercepted.
* **🚫 NO Microphone Access**: Never listens to your audio.
* **🚫 NO Cloud Syncing**: There is **no database server and no cloud**. 100% of your data remains inside your own physical hard drive.
* **⚡ Ultra-Lightweight**: Optimised — it polls efficiently in the background using minimal CPU cycles and RAM.

---

## ⚙️ How It Works

1. **Active Window Polling**: Every 3 seconds, a native polling thread identifies your active window title, application name, executable path, and duration.
2. **Incognito & Sensitive Filtering**: Automatically ignores browser windows containing private/incognito tags and filters out any executable you add to the exclusion list (e.g., password managers).
3. **Local SQLite Vault**: Saves all logs securely inside a local SQLite database file located in your user directory.
4. **Heuristics Session Grouping**: Automatically parses sequential focus switches and groups them into logical, cohesive **Workflow Sessions** (e.g., *"Software Development Session"* or *"Research Session"*).
5. **Observed Analytics**: Provides a high-contrast console style distribution index showing where your time goes, without gamification or stress-inducing productivity "scores".

---

## 🎮 Retro "Potato PC" UI Aesthetic

Inspired by the clean, dense, grid-based layouts of late 90s operating systems (like Windows 95/98), RewindDesk brings back nostalgic physical interfaces combined with a premium dark slate color palette:

* **3D Bevel Outsets & Insets**: Strict square borders (`border-radius: 0px`) and mechanical sunken wells for logs.
* **Tactile Mechanical Buttons**: Titlebar window buttons (`_`, `□`, `×`) physically shift down and right by 1px on click (`active`), simulating spring-loaded clicks.
* **Checkered Pixel Scrollbars**: Retro checkered background track details with sliding mechanical thumbs.
* **Console Charts**: Focused application indices rendered as ASCII progress bars (`[ ██████████░░░░░ ] 67%`).

---

## 📥 How to Install (From GitHub Releases)

Getting RewindDesk up and running takes less than 30 seconds:

1. Navigate to the **[Releases](https://github.com/)** section of this GitHub repository.
2. Under the latest release, download the Windows setup executable: **`rewinddesk-v1.0.0-setup.exe`**.
3. Open and run the installer.
4. The application will immediately install itself, launch the main dashboard, and register a silent tray icon in the bottom right corner of your Windows Taskbar.
5. **Auto-Start**: By default, RewindDesk registers itself to start silently when Windows boots up so you never have to remember to log your hours manually. You can disable this anytime in the **PRIVACY** settings panel.

---

## 📂 Data Location & Privacy Controls

* **Local Database Path**: `C:\Users\<YourUsername>\AppData\Roaming\rewinddesk\rewinddesk.db`
* **Exclusion List**: Navigate to the **PRIVACY** tab inside the app to block tracking for specific apps (e.g., `discord.exe`, `bitwarden.exe`).
* **Wiping Data**: Click **`[FORMAT VAULT]`** inside the Privacy settings to immediately wipe and format your local SQLite tables permanently.

---
