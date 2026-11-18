<p align="center">
  <img src="docs/art/banner.svg" width="100%" alt="Rust Server Control: install, run and manage a Rust server on Windows">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=2600&pause=1400&color=64D2FF&center=true&vCenter=true&width=640&lines=Installing+Rust+Dedicated+through+SteamCMD.;Console+live.+Filters+on.+Search+ready.;Plugin+reloaded.+The+compiler+is+happy%2C+for+once.;Wipe+scheduled.+Backup+written.;RCON+on+127.0.0.1%2C+where+it+belongs." alt="">
</p>

<p align="center">
  <a href="https://github.com/Yanoee/RustServerControl/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/Yanoee/RustServerControl?style=for-the-badge&label=version&color=0A84FF&labelColor=1c1c22"></a>
  <img alt="Windows 10 and 11" src="https://img.shields.io/badge/Windows-10%20%7C%2011-5E5CE6?style=for-the-badge&logo=windows11&logoColor=white&labelColor=1c1c22">
  <img alt="Native AOT, one exe" src="https://img.shields.io/badge/Native%20AOT-one%20exe-BF5AF2?style=for-the-badge&labelColor=1c1c22">
  <img alt="Free" src="https://img.shields.io/badge/price-free-30D158?style=for-the-badge&labelColor=1c1c22">
</p>

<p align="center">
  <a href="https://github.com/Yanoee/RustServerControl/releases/latest/download/RustServerControl-win-x64.zip"><img alt="Download RustServerControl-win-x64.zip" height="44" src="https://img.shields.io/badge/Download-RustServerControl--win--x64.zip-0A84FF?style=for-the-badge&logo=windows&logoColor=white"></a>
  <a href="https://yanoee.github.io/RustServerControl/"><img alt="Website" height="44" src="https://img.shields.io/badge/Website-yanoee.github.io-5E5CE6?style=for-the-badge&logo=githubpages&logoColor=white"></a>
</p>

<p align="center">
  <img src="docs/media/overview.png" width="100%" alt="Overview page with a running server">
</p>

## What it is

A Windows app that installs, runs and manages a Rust dedicated server. One exe, no installer, no .NET to hunt down.

Hosting Rust on Windows usually means a SteamCMD window, a batch file, an RCON tool, a text file full of convars and a backup folder you meant to keep up to date. This puts all of that in one window. It does not play Rust for you. That part is still your job.

## What it does

| | |
|---|---|
| **Install and update** | Rust Dedicated, Carbon or Oxide through SteamCMD, with branch selection. |
| **Live console** | Server output with filters, search and command autocomplete. |
| **Players** | Players, chat and bans over RCON. |
| **Plugins** | Add, reload, read compiler errors, browse uMod. |
| **Server settings** | Search, presets and a check of the final launch line. |
| **Server identity** | Name, description, logo and banner, with a live server browser preview. |
| **Backups and wipes** | Backups, scheduled wipes and automation tasks. |
| **Stats** | CPU, memory, FPS and player graphs, plus a kill/death leaderboard. |
| **Languages** | English and Turkish. |

<p align="center">
  <img src="docs/art/console.svg" width="49%" alt="Illustration: console with autocomplete">
  <img src="docs/art/plugins.svg" width="49%" alt="Illustration: plugin pieces snapping into place">
</p>

## Quick start

**1. Download and run.** Extract the zip into an empty folder, for example `D:\RustServer`, and run `RustServerControl.exe`. Servers, SteamCMD, backups and settings live in that folder. Move the folder and everything moves with it.

**2. Create a server.** Click **Create server**. Pick a name, a folder, a framework (Vanilla, Carbon or Oxide) and the ports.

<p align="center"><img src="docs/media/create.webp" alt="Creating a server" width="88%"></p>

**3. Install.** Click **Install Rust server**. SteamCMD downloads the server (about 6 GB) and the framework. This is the slow part. Make a tea.

<p align="center"><img src="docs/media/install.webp" alt="Installing the server" width="88%"></p>

**4. Start.** Press **Start**. The console, players and plugins are live once the server is online.

<p align="center"><img src="docs/media/console.webp" alt="Starting the server and using the console" width="88%"></p>

## Screenshots

| Players | Plugins |
|---|---|
| ![Players](docs/media/players.png) | ![Plugins](docs/media/plugins.png) |
| **Server settings** | **Backups** |
| ![Server settings](docs/media/settings.png) | ![Backups](docs/media/backups.png) |
| **Server identity** | **Stats** |
| ![Server identity](docs/media/identity.png) | ![Stats](docs/media/stats.png) |

## Requirements

- Windows 10 or 11, 64-bit.
- About 12 GB free disk space per server.

That is the list.

## Good to know

- Everything is stored in the exe's folder.
- RCON listens on 127.0.0.1 by default, so only this PC can connect.
- Players cannot join? Open the game port (UDP 28015 by default) and the query port in your router and Windows Firewall.

<p align="center">
  <img src="docs/art/wipe.svg" width="32%" alt="Illustration: wipe calendar and clock">
  <img src="docs/art/radar.svg" width="32%" alt="Illustration: players radar">
  <img src="docs/art/vault.svg" width="32%" alt="Illustration: backup vault">
</p>

## Licence

Free to use, for private and commercial hosting. Not for resale or redistribution. See [LICENSE](LICENSE).

Unofficial tool. Not affiliated with or endorsed by Facepunch Studios. Rust is a trademark of Facepunch Studios.

<p align="center">
  <img src="docs/art/footer.svg" width="100%" alt="">
</p>
