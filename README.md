<p align="center">
  <img src="https://i.imgur.com/qJyxGvd.png" width="800">
</p>

**Nebula UI** — is a visual redesign of the Garry's Mod main menu featuring a modern dark style, accent colors, animations, multi-resolution support, and an improved user interface.

---

## ✨ Preview

<p align="center">
  <img src="https://i.imgur.com/B5wAKIY.jpeg" width="800">
</p>

---

## 📸 Screenshots

### New Game Menu

<p align="center">
  <img src="https://i.imgur.com/yBJY0tG.jpeg" width="800">
</p>

### Server Browser

<p align="center">
  <img src="https://i.imgur.com/cKono6w.jpeg" width="800">
</p>

### Addons List

<p align="center">
  <img src="https://i.imgur.com/gBHMjy1.jpeg" width="800">
</p>

### Nebula UI Settings

<p align="center">
  <img src="https://i.imgur.com/ffPUKJh.jpeg" width="800">
</p>

---

## 🎨 Features

- Modern dark glass-style interface
- Custom navbar
- Color scheme selector
- Animated background support
- Optional performance mode
- Redesigned server browser
- Redesigned new game menu
- Redesigned language selector
- Responsive 720p / 1080p / 2K / 4K support
- Original Q-menu Saves/Dupes compatibility

---

# 📦 Installation

## Manual Installation

1. Download the latest release from the repository.

2. Extract the archive.

3. Move the folder:

```txt
GarrysMod/garrysmod/addons/
```

---

# ⚙️ Usage

Nebula UI includes a built-in settings panel that allows you to customize the interface directly inside the game.

To open Nebula UI settings:

```txt
Main Menu → Settings → Nebula UI
```

---

## 🎨 Accent Colors

Nebula UI supports multiple accent color presets.

Available options include:

- Blue
- Purple
- Red
- Orange
- Green
- Pink
- Custom RGB color

Changing the accent color updates:

- buttons;
- checkboxes;
- scrollbars;
- hover effects;
- server browser highlights;
- navigation elements.

---

## 🎥 Animated Background

Nebula UI supports animated video backgrounds.

Available options:

- Enable / disable animated background
- Restart background video

If performance mode is enabled, animated backgrounds become unavailable automatically.

---

## 🖼️ Custom Animated Background

You can replace the default Nebula UI animated background with your own video or GIF.

### Video Background

Replace:

```txt
html/media/backgrounds/menu_video.webm
```

with your own `.webm` video.

Recommended format:

```txt
Resolution: 1920x1080
Codec: VP9 / WEBM
FPS: 30/60
Length: 10-60 seconds or 10 minutes
```

For best performance, use a compressed looping video.

---

### GIF Background

Replace:

```txt
html/media/backgrounds/menu_background.gif
```

with your own animated GIF.

GIF background is used as:
- fallback background;
- low-performance alternative;
- backup when video playback fails.

---

## ⚠️ Notes

Very large videos may increase:
- menu loading time;
- VRAM usage;
- Chromium memory usage.

For low-end systems it is recommended to:
- disable animated backgrounds;
- or use lightweight WEBM files.

- The custom animated background must be named exactly:

```txt
menu_video.webm
```

Do not rename it to anything else, otherwise Nebula UI will not detect it.

---

## ⚡ Performance Mode

Performance mode disables heavy visual effects to improve FPS and reduce menu lag on weaker systems.

When enabled, Nebula UI disables:

- animated backgrounds;
- blur effects;
- expensive UI transitions;
- glow effects.

Recommended for:

- low-end PCs;
- integrated graphics;
- older Chromium builds.

---

## 🔄 Resetting Settings

Nebula UI settings are stored locally.

To reset all settings:

```txt
Nebula UI Settings → Reset Settings
```

or manually delete browser storage/cache.

---
