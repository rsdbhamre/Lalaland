# Lalaland: A 3BFTweaks Modlist

![Lalaland Logo](https://github.com/rsdbhamre/Lalaland/blob/730137f745bcd8eeb33f5f95aac7be08191f86aa/Resources/Lalaland%20WJ%20Image.png)

A beautiful yet performant 3BFTweaks experience in a refined Skyrim without too many additions. Using Community Shaders

**Links**: [Nexus Page](https://www.nexusmods.com/skyrimspecialedition/mods/149981?tab=description) | [Changelog](https://github.com/rsdbhamre/Lalaland/blob/main/changelog.md) | [Load Order](https://modlistgrimoire.com/modlists/lalaland) | [Discord](https://discord.gg/mJDkWtmt53)

---

**Requirements**:
- Skyrim SE version 1.6.1170 (latest Steam update).
- Four free Anniversary Edition mods: Fishing, Rare Curios, Survival Mode, Saints and Seducers (included in the November 2021 update).
- Does **not** require full Anniversary Edition DLC.

---

## Contents
- [Introduction](#introduction)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Post-Installation](#post-installation)
- [Playing the Game](#playing-the-game)
- [Updating](#updating)
- [Uninstalling](#uninstalling)
- [Troubleshooting](#troubleshooting)
- [Credits](#credits)

---

## Introduction
**Lalaland** is a gameplay and graphiical overhaul for Skyrim SE (1.6.1170), using [Community Shaders](https://www.nexusmods.com/skyrimspecialedition/mods/86492). Core gameplay is built around the awesome [3BFTweaks](https://www.nexusmods.com/skyrimspecialedition/mods/44044).

I have several Dead is Dead playthroughs with this list on my [Youtube Channel](https://www.youtube.com/@rsdbhamre_Lala)

Licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## System Requirements
- **OS**: Windows 10 or 11 (no LTSC or modified versions; Linux not supported).
- **Storage**: SSD required.
- **Download Size**: ~61 GB.
- **Install Size**: ~91 GB.
- **Total Space Needed**: ~153 GB.

| Component | Recommended (1080p) | My Specs (1440p) |
|-----------|---------------------|------------------|
| CPU       | i5 13600k or similar | 7800x3d      |
| GPU       | RTX 3060 or similar | RTX 4080        |
| RAM       | 16GB or more        | 32GB            |
| Storage   | SATA SSD            | NVMe SSD        |

---

## Installation

### Pre-Installation
1. **Install Dependencies**:
   - [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe).
   - [.NET Runtime 8.x.x Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.15-windows-x64-installer).
   - [.NET Runtime 6.0.0 Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.30-windows-x64-installer).
   - If Visual C++ is installed, use the `Repair` option.

2. **Steam Setup**:
   - Disable [auto-updates for Skyrim SE](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
   - Run Skyrim SE once for graphics check.
   - Install [Creation Kit](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/) on the same drive as Skyrim SE.
   - Run Creation Kit once, select `Yes` to unpack scripts.

### Wabbajack Installation
1. **Install Wabbajack**:
   - Create a folder (e.g., `C:\Wabbajack`) on your drive’s root (not in Program Files, Desktop, etc.).
   - Download [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) and place it in the folder.
   - Run `Wabbajack.exe` (requires version 4.0.0.0 or later).

2. **Install Lalaland**:
   - Open Wabbajack, select Skyrim SE, tick Non-featured, find Lalaland , and click “Download and Install.”
   - Set Installation Location (e.g., `C:\Lalaland`) and Downloads Location (avoid Program Files, Desktop, etc.).
   - Click Install.
   - Nexus Premium automates downloads; without it, manually click “Slow Download” for each mod.
   - If successful, proceed to [Post-Installation](#post-installation). If not, check [Troubleshooting](#troubleshooting).

---

## Post-Installation

### Antivirus Exceptions
- Add exceptions in Windows Defender for the Lalaland folder and `ModOrganizer.exe` to avoid crashes.
- Steps: Windows Security > Virus & Threat Protection > Manage Settings > Exclusions > Add Folder > Select Lalaland folder.

---

### Modlist At A Glance
I have thoroughly documented all the customizations, if any, of the installed mods and have tagged mods with keywords in the notes tab of mo2 left pane. The keywords being:
- Information - These are notes for mods that may need further customization depending on the user hardware and software environment or simply user preferance. The modlist is plug and play and the game will run just fine even if you don't bother reading this, but for the discerning fellow, it may be a good idea to read up on the info provided for such mods
- Post Installation - This is just for reference of what edits I have done to the mod after it's installation, like any changes to ini files or other assets
- Manual Installation - When mods have been installed manually, like changing folder structure during the installation, this is a reference for how it was done.
- FOMOD - This tag is to identify mods that have FOMODs. When reinstalling a mod that has FOMOD, the choices previously made will be highlighted.
- GUI key - keys for various utility mods like CS, dMenu etc. You can also check the hotkeys IN-GAME through SKSE menu framework in the Execute Hotkeys tab

To search mods tagged with the above keywords, you can use the filter in the left pane of mo2. Also, always check the OPTIONALS separator for optional mods according to your preference.

---

## Playing the Game
- Launch Skyrim SE through Mod Organizer 2 (MO2) in the Lalaland folder.
- Enjoy the enhanced visuals and gameplay!

---

## Updating
1. Open Wabbajack, find Lalaland, and click “Download and Install.”
2. Use the same Installation and Downloads folders.
3. Backup custom mods or settings (prefix added mods with **[NoDelete]** in MO2).
4. Check [Changelog](https://github.com/rsdbhamre/Lalaland/blob/main/changelog.md) for reference.

---

## Uninstalling
- Delete the Lalaland folder.

---

## Troubleshooting
- **Installation Issues**:
  - Missing files? Manually download and place them in the Downloads folder.
  - Game folder not found? Ensure Skyrim SE is installed and follow [Pre-Installation](#pre-installation).
  - Antivirus flagging? Add exceptions or uninstall aggressive third-party AV (e.g., Norton).

- **Post-Installation Issues**:
  - Form 43/DLL errors? Reinstall with “Overwrite Installation” checked in Wabbajack.
  - Crashing on startup? Reinstall or seek help on [Discord](https://discord.gg/mJDkWtmt53) with crash logs.

- Join [Requiem Discord](https://discord.gg/mJDkWtmt53) for support.

---

## Credits
- [Halgari](https://www.nexusmods.com/skyrimspecialedition/users/17252164) & Wabbajack team.
- [Bottle](https://github.com/InTheBottle) for his excellet modlist [CSVO](https://github.com/InTheBottle/CSVO) that I have referred for building a PBR graphical setup
- [DBF](https://dragonbornsfate.moddinglinked.com/) team for their modding guide
- All mod authors and the Skyrim modding community.
