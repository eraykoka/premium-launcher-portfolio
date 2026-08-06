<p align="center">
  <img src="assets/logo.png" alt="Premium Launcher" width="112" />
</p>

<h1 align="center">Premium Launcher</h1>

<p align="center">
  <strong>Modern, player-first Minecraft launcher for Windows</strong><br/>
  Isolated profiles · Skin Studio · Mod health · Secure updates · Premium desktop UX
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge" alt="Windows" />
  <img src="https://img.shields.io/badge/Status-Active-2ea44f?style=for-the-badge" alt="Active" />
  <img src="https://img.shields.io/badge/Source-Proprietary-c81e28?style=for-the-badge" alt="Proprietary" />
</p>

> **Public portfolio only.** Product source, build internals and first-party assets remain private. This repository presents the product without publishing its implementation.

## Product

Premium Launcher turns Minecraft setup into a clear three-step flow: connect an account, choose an isolated profile, and play. Advanced controls remain available without overwhelming new players.

## Current capabilities

| Area | Experience |
|---|---|
| Accounts | Microsoft and offline accounts with first-run account gate |
| Profiles | Isolated Vanilla, Fabric, Forge and NeoForge installations |
| Skin Studio | Automatic account skin, local PNG import, Classic/Slim choice and interactive 3D preview |
| Content | Modrinth discovery, mods, resource packs, shaders and worlds |
| Reliability | Mod-health checks, crash diagnostics, managed Java and repair actions |
| Servers | Saved servers and direct join |
| Desktop | Responsive Forgeboard shell, animated voxel hero, tray behavior and integrated titlebar |
| Updates | Dedicated release channel, SHA-256 verification and Defender release audit |

## Gallery

| Surface | Preview |
|---|---|
| Home | ![Home](images/gallery/01-home.png) |
| Profiles | ![Profiles](images/gallery/02-profiles.png) |
| Mods | ![Mods](images/gallery/03-mods.png) |
| Settings | ![Settings](images/gallery/04-settings.png) |
| Brand atmosphere | ![Hero](images/gallery/home-hero.png) |

More visuals: [Gallery](docs/gallery.md)

## Product principles

- Player-first hierarchy: account → profile → Play
- One coherent anthracite shell with crimson actions and restrained violet depth
- Clear status by exception; healthy states stay quiet
- Isolated data and reversible profile operations
- No hidden account tokens in the browser layer
- Release integrity independent from source visibility

## Technology overview

Windows desktop host · Python application core · embedded HTML/CSS/JavaScript interface · Minecraft runtime and loader integrations · local 3D skin rendering.

Implementation details, authentication internals and build pipelines are intentionally omitted.

## Distribution

Official installers and update artifacts are published through [premium-launcher-updates](https://github.com/eraykoka/premium-launcher-updates). The source repository is private.

## License

Portfolio text and media are provided for evaluation only. All rights reserved. See [LICENSE](LICENSE).

## Contact

GitHub: [@eraykoka](https://github.com/eraykoka)

<p align="center"><sub>Designed and developed by Eray Akbay.</sub></p>
