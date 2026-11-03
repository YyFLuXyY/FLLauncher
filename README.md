# FLLauncher

Independent Minecraft launcher and modpack manager for Windows x64.

**[Project website](https://yyfluxyy.github.io/FLLauncher/) · [Compiled Windows release](https://github.com/YyFLuXyY/FLLauncher/releases/tag/v0.5.1)**

This public repository contains the project website and release information. The launcher source code is not published.

## Features

- Separate Java instances, Minecraft version and mod-loader selection, and automatic Java runtime installation.
- Modrinth catalog, modpack import, installed-mod search and enable/disable controls.
- A visual mod dependency map and optional AI assistance for questions and crash logs.
- Drag-and-drop modpack/JAR import and MRPACK/ZIP export. Streaming ZIP64 supports archives up to 64 GiB without loading entire packs into memory.
- Manual system memory cleanup with synchronized live counters.
- Optional Discord Rich Presence: FLLauncher, its icon, project link and a fixed description.
- Windows Bedrock installation and launch through official Microsoft Store services, subject to platform and ownership requirements.

- One-click installation with a separate Version selector for mods, modpacks, resource packs and shaders; automatic compatible release selection.
- Skin-head avatars beside the account nickname.
- Current Microsoft profile skins, immediate Slim/Classic preview and model saving.
- Faster repeated EXE starts: application files are expanded once and reused.
- Launcher update notifications and a dedicated Settings → Updates page: one click checks and downloads a new release, then a separate button installs and restarts the app.
- Selected-mod update checks, Ctrl+A selection and pinned mod/resource-pack/shader releases.
- Instance change history with rollback, readable instance folders and a local screenshot gallery.

- Eight color themes in Settings → Appearance, with matching launcher/window/desktop-shortcut icons and automatic saving.

- Friends by launcher nickname, with accepted requests and Java Vanilla/Fabric worlds hosted on the player’s PC. Both launchers must be online for discovery.
- Automatic offline PNG and Classic/Slim synchronization through CustomSkinLoader in compatible modified Java clients.

## Current Microsoft authentication status

FLLauncher uses its own Microsoft application registration, approved for the Minecraft API allow list on October 23, 2026. Microsoft sign-in verifies Minecraft Java ownership. Minecraft is not included in the download.

## Download

Download **FLLauncher-0.5.1-Windows.exe** from [Releases](https://github.com/YyFLuXyY/FLLauncher/releases/tag/v0.5.1). This is a portable Windows x64 application. No source build or Node.js installation is needed.

SHA-256: `cede335fac32a0fbaf6f6b72af2a0b81c2e16c240c51df3222f2d6e362776324`

## Website

The [feature overview](https://yyfluxyy.github.io/FLLauncher/#functions) includes eight additional application screenshots, feature descriptions and a keyboard-accessible full-size viewer. The original mod-management and dependency-map previews are also available.

The static site is in `index.html` with embedded styles, scripts and images. GitHub Pages publishes the `main` branch, `/ (root)` directory. No third-party scripts, analytics or sign-in are required to read the project page.

## Rights

Copyright (c) 2026 FLLauncher. **All rights reserved.** Original launcher code, branding and website content are proprietary. Compiled releases may be used personally and non-commercially under [LICENSE](LICENSE). Third-party components retain their respective licenses; see [notices](THIRD_PARTY_NOTICES.txt).

FLLauncher is an independent project and is not affiliated with or endorsed by Mojang or Microsoft. Minecraft and related trademarks belong to their respective owners.
