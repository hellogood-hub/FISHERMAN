<p align="center">
  <img src="https://github.com/hellogood-hub/FISHERMAN/blob/main/icon.png" width="128" height="128" />
</p>

# FisherMan 🎣
**Your Personal Fishing Assistant for Minecraft Fabric 1.21.1**

FisherMan is a feature-rich utility mod designed to automate and enhance your fishing experience. Whether you're AFK fishing or just want a helper, FisherMan has you covered with customizable alerts, safety features, and a built-in stopwatch.

## ✨ Features

### 🤖 Auto-Fishing
- **Auto-Cast & Reel**: Automatically detects bites, reels in, and recasts.
- **Reaction Time**: Randomised reaction times (human-like behavior) to avoid detection.
- **Fail-Safes**: automatically stops if rod breaks or inventory fills up.

### ⏱️ FisherMan's Watch (Stopwatch)
- **Track Time**: Set a specific duration for your fishing session (e.g., 10 minutes).
- **Smart Alerts**: Get notified at 25%, 50%, and 75% completion, and during the final countdown.
- **Auto-Stop**: The mod automatically disables itself when the time is up.

### 🔊 Sound System (New in v1.2.6)
- **Custom Alearts**: Configure specific sounds for:
  - **Inventory Full**
  - **No Rod Equipped**
  - **Stopwatch Finished**
- **Modes**:
  - **Default**: Plays a subtle "Advancement Unlock" sound.
  - **Custom**: Play your own `.wav` files from your computer.
- **Volume Control**: Individual volume sliders for each alert type.

### 🎨 Fully Configurable
- **In-Game Config**: integrated with ModMenu and Cloth Config.
- **Custom Messages**: Change the text and color of every alert (Start, Stop, Warning).
- **Safety Toggles**: Enable/Disable specific safety checks.

## 📥 Installation for Minecraft 1.21.1.

1.  Install **Fabric Loader** for Minecraft 1.21.1.
2.  Download **FisherMan**.
3.  Install **Fabric API** and **Cloth Config API**.
4.  Install **Mod Menu** (for in-game config access).
5.  Place the `.jar` files into your `.minecraft/mods` folder.

## ⚙️ Configuration Guide

Access the settings via the **Mods** button in the ESC menu.

### General
- **Safety Timers**: Keep enabled to prevent server timeouts.
- **Welcome Message**: Toggle the join message.

### Time
- **Stopwatch**: Enable and set duration (HH:MM:SS).
- **Reaction Time**: Adjust min/max ms delay for catching fish.

### Sound (Advanced)
- **Inventory / No Rod / Stopwatch**:
    - **Play Alert**: Master toggle for this specific event.
    - **Volume**: 0-100%.
    - **Sound Mode**:
        - `DEFAULT`: Plays in-game sound.
        - `CUSTOM`: Plays local file.
    - **Custom Path**: Absolute path to your `.wav` file (e.g., `C:/Sounds/alert.wav`). Set to `None` to mute custom sounds.

## 👨‍💻 Credits
- **Author**: BOB THE EDITOR
- **Version**: 1.2.6

## 📜 License
This project is licensed under the **GNU General Public License v3.0 (GPLv3)**.
See the `LICENSE` file for more details.
