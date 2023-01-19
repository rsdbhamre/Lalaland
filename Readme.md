# Lalaland

![image](https://raw.githubusercontent.com/rsdbhamre/Lalaland/main/Lalaland.webp)

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://raw.githubusercontent.com/rsdbhamre/Lalaland/main/Requiem.png" width="72px" /></td>
<td><a href="https://discord.gg/fthGXJbY">Support Discord</a></td>
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
      - [Downloading and Installing LL](#downloading-and-installing-ll)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)  
  - [Updating LLL](#updating-the-modlist)
  - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble

LalaLand (LL) is a 3tweaks (A Requiem overhaul) based modlist. It aims to provide a fair and challenging combat/gameplay, while keeping up with modern graphical standards with heavy emphasis on performance and consistency. It is built from [Animonculory Visual Overhaul](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Readme.md) v2.3 and graphically further tweaked to increase the performance of an already very well optimised base. Gameplay inspiration was drawn from [Arkay's Commandment](https://github.com/Fornication/Arkays-Commandment), another 3tweaks list, and as such plays similar but not identical to it. Many thanks to Althro and Fornication for their work!

LL is made for Skyrim Special Edition Version 1.6.640 and uses the .exe of that version as well. It **DOES NOT** require the paid update to the game.

The full modlist can be viewed here, [ENB](https://https://loadorderlibrary.com/lists/lalaland-enb), [Non-ENB](https://loadorderlibrary.com/lists/lalaland-non-enb).
A selection of screenshots can be viewed here, [ENB](https://imgur.com/gallery/NshVBZy), [Non-ENB](https://imgur.com/gallery/L07SGCh).

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

As mentioned earlier, LL has a focus on performance and IMO has an excellent graphics to performance ratio. If you can't run the ENB version, the non ENB profile has got you covered. Just for reference though, here's the recommended specs-

 - i5 7th Gen or 2nd Gen Ryzen 5
 - 16GB DDR4 RAM
 - GTX 1660ti / RX 5600xt

RX 500 series cards (580 or similar) are **not supported.**

Space required: Approx 152GB (Downloads included)

## Installation

Installing LL is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing LL, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.

***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing LL

Downloading and installing AVO can take a while depending on your internet connection and computer. To install LL, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Check the 'Show unofficial lists' box on the top right.
3. Press the download button on LL and wait for it to download.
4. Set the installation folder to be somewhere like C:\Games\Lalaland. **Do not install it to your desktop or downloads folder.**
5. The download location does not need to be on a SSD but it makes installing a bit faster
6. Press the play button to begin.
7. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
8. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

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

LL uses an isolated copy of your Skyrim to keep your Steam installation clean. All the files that you need to run the list are in a folder called “Game Root”. You don’t need to copy anything at all.

***

### ENB

LL comes with ENB installed in the Game Root folder mentioned earlier. ENB GUI is opened by pressing f11.

If you wish to play the non ENB profile, you need to hide/disable these two files
-d3d11.dll
-d3dcompiler_46e.dll
Then, you have to switch to the 'Lalaland Non-ENB' profile in MO2.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`.

Please go through the left pane of MO2, I have left notes on several mods explaining what I have edited/deleted, to give you a better understanding of my list.
There are two Major Seperators in the list, highlited in green. The 'Requiem' Seperator contains all the requiem and addon mods that constitute the majority of the gameplay changes. The other seperator 'Lalaland Additions' are the other additions I've made to AVO, ranging from graphics to gameplay mods and everything in between.

Now to start the game, make sure the dropdown box on the right is set to `SKSE` and press the `Run` button.

### In-Game MCM options
LL has no MCM options required, however you can load the SmoothCam preset if you wish.

### Starting the Game

LL uses [Alternate Start](https://www.nexusmods.com/skyrimspecialedition/mods/272) and [Requiem-Starting Choices](https://www.nexusmods.com/skyrimspecialedition/mods/62901). Press 'New Game' and complete your character creation in the LAL starting cell and wait 10 seconds to let scripts initialize. LL has automated MCM settings, [MCM recorder](https://www.nexusmods.com/skyrimspecialedition/mods/61719) will let you know once the default settings are applied. Then you can choose your start and spawn in the selected path, Requiem-Starting Choices will trigger where you can select your starting items.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### I own the AE paid addon. How do I use it?

You should not use the AE addons, let alone the 4 free ones, with LL. 3tweaks isn't -and probably won't be for a long time- patched for the CC stuff.

### How do I remove the black bars on the top and bottom of my screen?

It's called a letterboxe effect and can be disabled in the ENB GUI. Navigate to the shader window, drop down the postpass table and uncheck the letterbox option

### How do I increase the interior/night brightness?

For ENB users - open ENB GUI, got to the shader window and drop down the enbeffect table. At the top of the table you'll find settings for interior/night brightness, tune them to your liking. You can also head on the [Quick Light](https://www.nexusmods.com/skyrimspecialedition/mods/12633) MCM and configure your lantern to have a larger radius

For Non-ENB users - Unfortunately, no easy way for you to increase brightness like the ENB option, unless you want to deep dive edit alot in xEdit. At the very least you can configure your Quick Light as stated above.

### How do I start xEdit?

Create a mod called 'xEdit Cache' and enable it in MO2.

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
- Althro and Styyx for AVO
- Fornication for AC and continuation of 3tweaks with his own addon - [Ftweaks](https://www.nexusmods.com/skyrimspecialedition/mods/44044)
- The 3tweaks community for being awesome. Seriously, 3tweaks made me revive my requiem spark because of you guys.

## Contact

Take the 'Lalaland' role in this discord [Requiem - Wabbajack](https://discord.gg/fthGXJbY)
