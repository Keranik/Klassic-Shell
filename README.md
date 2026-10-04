# Klassic Shell

Klassic Shell is a continuation of [Open-Shell-Menu](https://github.com/Open-Shell/Open-Shell-Menu), which continues [Classic Shell](http://www.classicshell.net) by [Ivo Beltchev](https://sourceforge.net/u/ibeltchev/profile/). It is maintained by [Keranik](https://github.com/Keranik).

Open-Shell is not taking Windows 11 taskbar changes. This repository keeps that work on top of upstream Open-Shell.

### What changed

- The Windows 11 taskbar can be fully transparent again. The existing opaque and glass looks apply to the XAML taskbar.
- A taskbar texture replaces the Windows background instead of being drawn on top of it.
- A custom start-button image replaces the Windows logo, including on other monitors that show their own taskbar.
- The custom image is centered in the Windows 11 start-button slot. The original Start button no longer stays clickable underneath it.

The program name and installer are still Open-Shell. Build from this repository to get the taskbar fix.

Later Open-Shell updates can be merged from `upstream` (`https://github.com/Open-Shell/Open-Shell-Menu.git`) into `main` with `git fetch upstream` and `git merge upstream/master`.

----

<a href="#"><img src=/Src/Setup/OpenShell.ico width="80" align="left"/></a>


# Open-Shell

A collection of utilities bringing back classic features to Windows.

*Originally* **[Classic Shell](http://www.classicshell.net)** *by [Ivo Beltchev](https://sourceforge.net/u/ibeltchev/profile/)*

[![GitHub Release](https://img.shields.io/github/release/Open-Shell/Open-Shell-Menu.svg?style=flat-square)](https://github.com/Open-Shell/Open-Shell-Menu/releases/latest)&nbsp;&nbsp;[![GitHub Pre-Release](https://img.shields.io/github/release/Open-Shell/Open-Shell-Menu/all.svg?style=flat-square)](https://github.com/Open-Shell/Open-Shell-Menu/releases)&nbsp;&nbsp;[![Build](https://github.com/Open-Shell/Open-Shell-Menu/actions/workflows/build.yml/badge.svg)](https://github.com/Open-Shell/Open-Shell-Menu/actions/workflows/build.yml)&nbsp;&nbsp;[![Build status](https://img.shields.io/appveyor/build/passionate-coder/Open-Shell-Menu?logo=appveyor&style=flat-square)](https://ci.appveyor.com/project/passionate-coder/open-shell-menu/branch/master)&nbsp;&nbsp;[![GitQ](https://img.shields.io/badge/gitq-discussions-1577fa?style=flat-square)](https://gitq.com/passionate-coder/Classic-Start)&nbsp;&nbsp;[![Gitter chat](https://img.shields.io/gitter/room/badges/shields.svg?color=lightseagreen&logo=gitter&style=flat-square)](https://gitter.im/open-shell/Lobby)&nbsp;&nbsp;[![Discord](https://img.shields.io/discord/757701054782636082?color=mediumslateblue&label=Discord&logo=discord&logoColor=white&style=flat-square)](https://discord.gg/7H6arr5)

[Open-Shell Homepage](https://open-shell.github.io/Open-Shell-Menu)  

### Features
- Classic style Start menu for Windows 7, 8, 8.1, 10, and 11
- Toolbar for Windows Explorer
- Explorer status bar with file size and disk space
- Classic copy UI (Windows 7 only)
- Title bar and status bar for Internet Explorer

### Download
You can find the latest stable version here:

[![GitHub All Releases](https://img.shields.io/github/downloads/Open-Shell/Open-Shell-Menu/total?style=for-the-badge&color=4bc2ee&logo=github)](https://github.com/Open-Shell/Open-Shell-Menu/releases/latest)

> [!IMPORTANT]
> #### Windows for ARM compatibility
> Open-Shell is compatible with Windows for ARM since version [4.4.196](https://github.com/Open-Shell/Open-Shell-Menu/releases/tag/v4.4.196).
>
> If you install older one on a Windows for ARM installation (ex. using Parallels Desktop on an Apple Silicon Mac), you will no longer be able to log into your account the next time you reboot. Please refrain from installing Open-Shell on Windows for ARM.

### Code signing
Free code signing provided by [SignPath.io](https://about.signpath.io/), certificate by [SignPath Foundation](https://signpath.org/)

### Temporary Translation/Language Solution
1. Download [language DLL](https://coddec.github.io/Classic-Shell/www.classicshell.net/translations/index.html)  
2. Place it either in the Open-Shell's __install folder__ or in the `%ALLUSERSPROFILE%\OpenShell\Languages` folder

----

*For archival reasons, we have a mirror of `www.classicshell.net` [here](https://coddec.github.io/Classic-Shell/www.classicshell.net/).*

[How To Skin a Start Menu](https://coddec.github.io/Classic-Shell/www.classicshell.net/tutorials/skintutorial.html)  
[Classic Shell: Custom Start Buttons](https://coddec.github.io/Classic-Shell/www.classicshell.net/tutorials/buttontutorial.html)  
[Questions? Ask on the Discussions section](https://github.com/Open-Shell/Open-Shell-Menu/discussions) or on [Discord](https://discord.gg/7H6arr5)  
[Submit a bug report/feature request](https://github.com/Open-Shell/Open-Shell-Menu/issues)
