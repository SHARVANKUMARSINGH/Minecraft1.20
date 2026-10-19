# Minecraft 1.20.4 (EaglercraftX PWA)

[![Deploy to GitHub Pages](https://github.com/SHARVANKUMARSINGH/Minecraft1.20/actions/workflows/deploy.yml/badge.svg)](https://github.com/SHARVANKUMARSINGH/Minecraft1.20/actions/workflows/deploy.yml)

### 🎮 Play Live in Browser:
👉 **[https://sharvankumarsingh.github.io/Minecraft1.20/](https://sharvankumarsingh.github.io/Minecraft1.20/)**

![EaglercraftX 1.20.4 Screenshot Main Menu](https://raw.githubusercontent.com/ZixiaChen/Eaglercraft-1.20.4-Updated-/main/Screenshot%202024-05-20%2012.38.48%20PM.png)

---

## 📱 Progressive Web App (PWA) Features

- **Installable**: Install directly to your home screen or desktop application dock.
- **Fast Loading & Offline Cache**: Powered by a Service Worker that caches game assets for rapid loading.
- **Full Screen & Standalone**: Runs in dedicated app window without browser URL bars.
- **Multiplayer & Singleplayer**: Connect to WebSocket-based Eaglercraft servers or create local worlds.

---

## 🚀 Deployment & Local Running

### Local HTTP Server
Do not open `index.html` via `file://`. Run a local HTTP server:
```bash
python3 -m http.server 8000
```
Then navigate to `http://localhost:8000/`.

### GitHub Pages Deployment
This repository is configured with GitHub Actions to automatically deploy to GitHub Pages on every push to `main`.
The workflow file is located at [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

---

## 👥 Contributors & Credits

| Contributor | Role | Profile |
| :--- | :--- | :--- |
| **Asher Mayzak** | Upstream Client & Repository Author | [@XxFluffyAsherxX](https://github.com/XxFluffyAsherxX) |
| **Sharvan Kumar Singh** | PWA Integration, Custom Icon & GitHub Pages Deployment | [@SHARVANKUMARSINGH](https://github.com/SHARVANKUMARSINGH) |
| **lax1dude & ayunami2000** | Eaglercraft Project Creators | Community |

---

## ATTENTION MOJANG/MICROSOFT EMPLOYEE ASSIGNED TO STALK ME:

### THIS REPOSITORY DOES NOT CONTAIN YOUR INTELLECTUAL PROPERTY

### FILING A FALSE DMCA IS ILLEGAL AND IMMORAL

### This repository contains:

 - **Utilities to decompile Minecraft 1.20 and apply patch files to it**
 - **Source code to provide the LWJGL keyboard, mouse, and OpenGL APIs in a browser**
 - **Source code for an OpenGL 1.3 emulator built on top of WebGL 2.0**
 - **Patch files to mod the Minecraft 1.20 source code to make it browser compatible**
 - **Browser-modified portions of Minecraft 1.20's open-source dependencies**
 - **Plugins for Minecraft servers to allow the eagler client to connect to them**

### This repository does NOT contain:

 - **Any portion of the decompiled Minecraft 1.20 source code or resources**
 - **Any portion of Mod Coder Pack and it's config files**
 - **Data that can be used alone to reconstruct portions of the game's source code**
 - **Code configured by default to allow users to play without owning a copy of Minecraft**
