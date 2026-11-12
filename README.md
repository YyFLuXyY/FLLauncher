# FLLauncher

Independent Minecraft launcher and modpack manager for Windows x64.

**[Project website](https://yyfluxyy.github.io/FLLauncher/) · [Compiled Windows release](https://github.com/YyFLuXyY/FLLauncher/releases/tag/v0.5.5)**

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
- Searchable instance library with per-instance settings, cloning, and world backups.

- Nine color themes in Settings → Appearance, including the warm orange Claude theme. The window icon, the desktop shortcut and a pinned taskbar button follow the selected color; the choice is saved automatically.

- Friends by launcher nickname, with accepted requests and Java Vanilla/Fabric worlds hosted on the player’s PC. Both launchers must be online for discovery.
- Copyable local world addresses and configurable local host ports. Multiplayer uses verified Microsoft Minecraft Java accounts and compatible clients.
- Automatic offline PNG and Classic/Slim synchronization through CustomSkinLoader in compatible modified Java clients.

## Current Microsoft authentication status

FLLauncher uses its own Microsoft application registration, approved for the Minecraft API allow list on October 23, 2026. Microsoft sign-in verifies Minecraft Java ownership. Minecraft is not included in the download.

## Download

Download **FLLauncher-0.5.5-Windows.exe** from [Releases](https://github.com/YyFLuXyY/FLLauncher/releases/tag/v0.5.5). This is a portable Windows x64 application. No source build or Node.js installation is needed.

SHA-256: `68387577517dae09b67138dab3be744a9103d7d2a6af29baa6452117647a8995`

## Website

The [feature overview](https://yyfluxyy.github.io/FLLauncher/#functions) includes ten application screenshots, feature descriptions and a keyboard-accessible full-size viewer. Mod management, the dependency map and world backups are shown in a tabbed preview. A color picker at the top of the page switches the page accent and the main screenshot between the nine launcher themes.

The static site is `index.html` with inline styles and scripts. Screenshots are in `assets/img/`; the two self-hosted fonts, Onest and JetBrains Mono (SIL Open Font License 1.1, license texts included), are in `assets/fonts/`. GitHub Pages publishes the `main` branch, `/ (root)` directory. No third-party scripts, fonts, analytics or sign-in are required to read the project page.

## Rights

Copyright (c) 2026 FLLauncher. **All rights reserved.** Original launcher code, branding and website content are proprietary. Compiled releases may be used personally and non-commercially under [LICENSE](LICENSE). Third-party components retain their respective licenses; see [notices](THIRD_PARTY_NOTICES.txt).

FLLauncher is an independent project and is not affiliated with or endorsed by Mojang or Microsoft. Minecraft and related trademarks belong to their respective owners.
