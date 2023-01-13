# Lalaland

![image](https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/AVOLogo.webp)

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/GitHub.png" width="72px" /></td>
<td><a href="https://discord.gg/DffHKcszfg">Support Discord</a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing AVO](#downloading-and-installing-avo)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [Reshade](#reshade)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
  - [Adding mods to AVO](#adding-mods-to-avo)  
  - [Updating AVO](#updating-the-modlist)
  - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble

Animonculory Visual Overhaul (AVO) is designed as a list to bring the vanilla game up to modern standards without changing the core vanilla feel and gameplay. Featuring graphical enhancements, mandatory bug fixes and tweaks and method patching, it is the perfect base to build upon. AVO is made for Skyrim Special Edition Version 1.6.343 and uses the .exe of that version as well. It **DOES NOT** require the paid update to the game. It uses [Rustic Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/8398) by default; however, it can support whichever weather mod you wish to use.

The full modlist can be viewed [here](https://loadorderlibrary.com/lists/animonculory-visual-overhaul), a selection of screenshots can be viewed [here](https://imgur.com/a/mcpBqFW) and a video showcase by DroppedIceCream of an older version can be viewed below.

[![AVO Showcase](https://img.youtube.com/vi/CXuDlNrPVoo/0.jpg)](https://www.youtube.com/watch?v=CXuDlNrPVoo)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

As of version 3, AVO has become much less taxing on the system. It is still, however, modded Skyrim. Therefore, a system similar to the following is recommended.

 - i5 7th Gen or 2nd Gen Ryzen 5
 - 16GB DDR4 RAM
 - GTX 1660ti / RX 5600xt

RX 500 series cards (580 or similar) are **not supported.**

### My specs

- R7 5800x
- 32GB DDR4 3600mhz
- NVME M.2 PCIE 3 SSD
- RTX 3090 FE

I average (locked) 116fps @ 1440p everywhere.

Space required: Approx 168GB (Downloads included)

## Installation

Installing AVO is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing AVO, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.

***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing AVO

Downloading and installing AVO can take a while depending on your internet connection and computer. To install AVO, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on AVO and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\AVO. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Game Folder

AVO uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called “Game Root”. You don’t need to copy anything at all.

***

### Reshade

Starting with version 3, AVO now comes with two Reshade presets that have been custom tweaked to fit the list. To swap between them, you will need to follow the steps below.

#### Change the Reshade

1. Launch Mod Organizer 2.
2. There will be a dropdown box on the top right and a big `Run` button next to it. 
3. Run the program named `Manage ENB/Reshade Presets` from Mod Organizer 2.

![image](https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/Select%20ER%20Manager.png)

If the image below comes up, simply press OK. It is nothing to be concerned about.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/Ignore%20Warning.png?raw=true)

Navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%203.png?raw=true)

Activate the Reshade you wish to use by pressing the slider. To deactivate it, simply press the slider.

![image](https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/Pick%20the%20Preset.webp)

For adding your own presets and more details, please follow the guide in [How to Modify AVO](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Adding%20mods%20to%20AVO.md).

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the `Run` button.

### In-Game MCM options
`AVO has no MCM options required, however you can load the SmoothCam preset if you wish.`

- This serves as a placeholder in case you want to use the Readme as some sort of template.

### Starting the Game

- Placeholder for your Readme. By default, AVO uses [Optional Quick Start](https://www.nexusmods.com/skyrimspecialedition/mods/63953).
	
## Adding mods to AVO

To safely add mods to AVO, please read [the guide](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Adding%20mods%20to%20AVO.md), which covers some of the details you need to know.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### I own the AE paid addon. How do I use it?

You will need to copy all of the CC content into the `Game Root` folder and then use the `Curation Club` tool in MO2 to manage it properly. **Note**: You will **need** to resolve conflicts in xEdit.

***

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- The Animonculory Team.
- Noggog for Mutagen.
- xSlim for Proofreaading documentation.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.

## Contact

Whilst I am available primarily on [my server](https://discord.gg/DffHKcszfg), please check the [issues](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/issues) tab on github first if you have any issues. DO NOT DM ME ON DISCORD.

You are welcome to [contribute](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Contributing.md) to the list, however please check the [changelog](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Changelog.md) before you do.

## The Animonculory Team
- Althro - Leader & Head of Development (Author of [ADT](https://github.com/The-Animonculory/ADT/blob/main/README.md), [AVO](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul) & Tinvaak)
- Styyx - Senior Management Team & Dev Team (Author of [Ruvaak](https://github.com/chri3i/Ruvaak-Readme))
- Chef/Para0x - Senior Management Team & Dev Team (Author of [Fahdon](https://github.com/Para0x/Fahdon-A-Skyrim-Together-Experience/blob/main/Readme.md))
- The Spaniard -Senior Management Team, Documentation & Dev Team
- GuitarBarbarian - Senior Management Team
- Abandoned by Arkay - Dev Team & Testing (Author of [DNGG](https://github.com/Arkay-1248/Do-Not-Go-Gentle))
- Astro - Dev Team & Testing
- DestinySlayer - Dev Team & Community Engagement (Author of [Krahven](https://sites.google.com/view/krahven/krahven-main-page))
