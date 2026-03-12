<div align="center">
  <h1 style="font-size: 3.5em; color: #39FF14; font-family: 'Courier New', monospace; text-shadow: 
    0 0 10px #39FF14,
    0 0 20px #39FF14,
    0 0 40px #39FF14,
    0 0 60px #FF00FF;">
    ⚡ PACKETTUNER ⚡
  </h1>
  <h2 style="color: #00FFFF; text-shadow: 
    0 0 10px #00FFFF,
    0 0 20px #00FFFF;
    font-family: 'Courier New', monospace;">
    🧠 AI‑Driven Network Tuning • Created by Olemec‑ip
  </h2>
  <p style="font-size: 1.4em; color: #FF00FF; text-shadow: 0 0 15px #FF00FF;">
    💡 Idea – human<br>
    🤖 Code – AI‑crafted<br>
    🔥 Result – zero lag, pure stability!
  </p>
  <img src="https://img.shields.io/badge/NEON%20EDITION-FF00FF?style=for-the-badge&logo=neon&logoColor=white" alt="Neon Edition">
  <br>
  <img src="https://img.shields.io/github/stars/Olemec-ip/PacketTuner?style=flat-square&color=00FF99&label=STARS" alt="Stars">
  <img src="https://img.shields.io/github/downloads/Olemec-ip/PacketTuner/total?style=flat-square&color=00FFFF" alt="Downloads">
  <img src="https://img.shields.io/github/license/Olemec-ip/PacketTuner?style=flat-square&color=39FF14" alt="License">
</div>

---

## 👾 The Story Behind PacketTuner

**Hello, world!** 👋

I'm **Olemec-ip** — a gamer who got tired of lag, a streamer fed up with packet loss, and living proof that in 2026 you **don’t need to be a coder** to build professional software.

I have **zero years** of manual coding experience. I never wrote a single algorithm by hand.  
Instead, I learned to **masterfully orchestrate AI** (Grok, Claude, ChatGPT) to turn ideas into reality.

**My formula:**
- 🔥 **Idea & architecture** – 100% mine, born from real gaming frustration
- 🤖 **Prompts, code, debugging** – handled by AI under my direction
- 🎨 **Design & UX** – I polish until it shines
- ✅ **Final product** – production‑ready and battle‑tested on my own connection

PacketTuner is the result: a **powerful, beautiful, and absolutely free** tool that proves you don't need a CS degree to create something valuable. You just need a clear vision and the right AI companions.

---

## 🚀 What Is PacketTuner?

<p align="center">
  <img src="assets/screenshots/tab_home.bmp" alt="PacketTuner Home Tab" width="45%">
  &nbsp;&nbsp;
  <img src="assets/screenshots/tab_tests.png" alt="PacketTuner Tests Tab" width="45%">
</p>

**PacketTuner** is a modern graphical interface for **fine‑tuning network traffic on Windows 10/11**. It gives you complete control over how your computer connects to games, streaming services, and websites — all through a sleek, neon‑styled dashboard.

### ✨ Key Features

|   | Feature | What It Does |
|---|---------|--------------|
| ⚙️ | **One‑Click Auto‑Tune** | Automatically tests hundreds of packet strategies to find the fastest, most stable connection for your network. |
| 🎮 | **Game Mode** | Measures and optimizes UDP traffic (jitter, packet loss) — essential for Discord, online gaming, and voice chat. |
| 📋 | **Live List Editor** | Edit domain/IP lists directly in the app. Add your own servers or exclude others with instant save. |
| 🌐 | **Hosts Manager** | Replace or restore your system `hosts` file with a click. Perfect for local routing adjustments. |
| 🔍 | **Deep Diagnostics** | Scans your system for conflicts (antivirus, other network tools), checks driver health, and fixes issues automatically. |
| 🧠 | **AI‑Designed UI** | Built with CustomTkinter — dark/light theme, smooth animations, and that unmistakable neon vibe. |

---

## 💻 For Users (Quick Start)

### 📦 Installation

**Option 1 – Installer (Recommended)**
1. Download the latest `PacketTuner_Setup_vX.X.X.exe` from [Releases](https://github.com/Olemec-ip/PacketTuner/releases).
2. Run the installer — it will place PacketTuner in `C:\Program Files\PacketTuner`.
3. Launch from desktop shortcut. **Always run as Administrator** (UAC shield).

**Option 2 – Portable**
1. Download `PacketTuner_Portable.zip`.
2. Extract anywhere (avoid spaces/Cyrillic, e.g., `C:\Tools\PacketTuner`).
3. Run `PacketTuner.exe` as Administrator.

### 🚦 Your First 3 Minutes

1. **Auto‑Tune**: Go to **Tests** → **Auto‑tune** → click **Start**. Wait 2–5 minutes.
2. **Apply Best**: After tests finish, click **Apply best**.
3. **Install Service**: Switch to **Home** → click **Install service**.

That's it. Your system now has optimized network parameters running as a Windows service.

### 🎛️ Daily Use

- **Home** tab: Start/stop the service, see real‑time status.
- **Lists** tab: Add your favorite game servers or streaming domains.
- **Settings** tab: Toggle game filter, choose theme, enable auto‑updates.
- **Updates** tab: Refresh IP lists or check for new versions.

---

## 🔧 For Developers (Build from Source)

Want to see how AI‑crafted code looks? Clone and explore:

```bash
git clone https://github.com/Olemec-ip/PacketTuner.git
cd PacketTuner
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python main.py   # must be run as admin
