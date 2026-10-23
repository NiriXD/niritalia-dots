# 🍦 Niritalia

```text
  _   _ _     _ _        _ _       
 | \ | (_)_ _(_) |_ __ _| (_) __ _ 
 |  \| | | '_| |  _/ _` | | |/ _` |
 |_| \_|_|_| |_|\__\__,_|_|_|\__,_|
                                   
```

> A clean, minimalist cream-colored rice pairing the **Niri** scrollable-tiling window manager with the **Noctalia** shell environment on **CachyOS**. 
> 
> **Maintained & Cooked by:** `NiriXD`

---

## 📸 Gallery
I'm terribly sorry for the image quality.

Dark theme
<p align="center">
  <img src="https://files.catbox.moe/s44cul.jpeg" alt="Niritalia Desktop Screenshot" width="85%">
</p>

White Theme (Cream-like color)
<p align="center">
  <img src="https://files.catbox.moe/20dc28.jpeg" alt="Niritalia Desktop Screenshot" width="85%">
</p>

Wallpaper Carousel Showcase

https://github.com/user-attachments/assets/4d8c226d-dc62-4bd4-893b-57824a1eabca

---

## 📦 System Architecture

Here is exactly what gets tracked, packed, and deployed across the suite:

* 🪟 **Niri Window Manager:** Custom scrollable tiling layouts, hand-optimized animations, and fluid keybind mechanics (`~/.config/niri/config.kdl`).
* 🐚 **Noctalia Shell Environment:** Not much, waste of time.
(`~/.config/noctalia/`).
* 🔌 **Noctalia v5 Plugin Array:** Embedded workflow engine add-ons including the custom wallpaper carousel module (`~/.local/share/noctalia/plugins/`).
* 🎨 **Global Theme State:** Locked-in accent configurations and live system overrides managed by the UI (`~/.local/state/noctalia/settings.toml`).
* 🖼️ **Assets & Wallpapers:** Complete visual package dump matching the active aesthetic automatically synced to your `~/Pictures` path.

---

## 🚀 Quick Start

Grab your local terminal session, unpack the payload, and fire up the unified dashboard interface:

```bash
tar -xzf Niritalia.tar.gz
cd Niritalia
./manage.sh
```

---

## 🛠️ Unified Command Dashboard

Running `./manage.sh` fires up an interactive wizard handling the heavy lifting. Click the dropdowns below to see how each module acts behind the scenes:

<details>
<summary><b>1️⃣ Option 1: Full Automated Installation</b></summary>
<br>

* Automatically triggers database refreshes and checks system dependencies.
* Pulls core infrastructure blocks: `niri`, `waybar`, `rofi-wayland`, `swww`, `mako`, `foot`, and audio backends.
* Patches broken symbols instantly by bundling `ttf-jetbrains-mono-nerd` out of the box.
* Hot-swaps all configuration files securely into system paths.
</details>

<details>
<summary><b>2️⃣ Option 2: Interactive Pick-and-Choose Mode</b></summary>
<br>

* **Smart Defaulting:** Smashed the `Enter` key too fast? The script instantly assigns standard default choices **[Y/n]** instead of breaking or skipping steps.
* **Web Browser Selector:** Choose between `Helium-browser-bin`, `Firefox`, `Chromium`, or `Brave-bin`.
* **AUR Helper Fallback Engine:** The script actively runs checks for your system wrappers. It prioritizes executing packages via `paru`. If `paru` is missing, it automatically pipes the install over to `yay`. If neither AUR helper is present on the machine, it routes the package preference safely back down to official `pacman` binaries.
* **Component Level Toggles:** Isolate and select whether you want to deploy just configs, plugins, settings files, or target wallpapers individually.
</details>

<details>
<summary><b>3️⃣ Option 3: Emergency Restore Module</b></summary>
<br>

* **Warning Alert:** Enforces a strong manual confirmation step.
* **Nuclear Reset Option:** Intended for troubleshooting broken environments. Instantly wipes out active configuration workspaces (`~/.config/niri` and `~/.config/noctalia`) and overwrites the directories back to matching clean stock Niritalia snapshot states.
</details>

---

## 📋 Technical Prerequisites

* **Base Distribution:** Optimized directly for **CachyOS** configurations to align with upstream package structures.
* **Repository Validation:** Core components reference the official native Arch / CachyOS mirrorlist configurations.

---
Note: Source code wont be on Github, but you can download it in Releases and check codes and files etc in the folder you unzip
---
<p align="center">Made with ☕ and clean code by <b>NiriXD</b></p>
