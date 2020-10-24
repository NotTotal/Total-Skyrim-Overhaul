# Total-Skyrim-Overhaul

- [Introduction](#Introduction)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
    - [Start Skyrim](#start-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
- [Updating](#updating)
- [Gameplay Guide](#gameplay-guide)
- [In-Game MCM Options](#in-game-mcm-options)
- [FAQ](#faq)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

# Introduction
Total Skyrim Overhaul is a requiem based modlist, this means it is difficult. If you are looking for a gameplay experience that does not require careful planning I suggest playing Keizaal, The Phoenix Flavor, or Lexy’s instead. 

I will not provide support on how to add or change any mods beyond what is already provided. Do not ask me for help if you changed things. If you do not have experience modding requiem on SSE and patching with xedit I suggest you do not even think of changing anything.

If a question is sufficiently answered in this readme I will not respond to support requests relating to it. Please read the readme, I wrote it for a reason. If your question is not in the readme I will answer it to the degree possible.

NSFW Warning: This list contains nude models for female and males. To mostly remove nudity follow this guide.
## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/`.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1. Click on _High_
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _Off_
4. Check _Windowed Mode_ and _Borderless_

Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations


Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in X:\Wabbajack

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Load the Modlist from Disk
3. Set TSO to install to X:\Total Skyrim Overhaul and download to X:\Total Skyrim Overhaul\Downloads. Your downloads folder can be on a separate drive to save space but wabbajack's install speed will be limited to your slowest drive. 
4. Click the Go/Begin button
5. Wait for Wabbajack to finish

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

#### Copy Game Folder Files

Download the latest ENB Series from [here](http://enbdev.com/download_mod_tesskyrimse.htm) and copy `d3d11.dll` and `d3dcompiler_46e.dll` to your game folder.

Copy the all of the files from the `MO2/Game Folder Files` directory into your game folder.

#### Starting the Game

Head over to the installation folder and locate an executable named ModOrganizer.exe and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

# Gameplay Guide

GAMEPLAY QUESTIONS WILL NOT BE ANSWERED IN #TSO-SUPPORT, GO TO #GAMEPLAY-SPOILERS ON THE [TSO DEV SERVER](https://discord.gg/ueJH6Jz)

This section will be expanded as v3 gets closer to the end of alpha

## Religion

TSO uses SNBCJ’s excellent Immersive Divine Blessings as a core religious system as a replacement for AZ Tweak’s religious system. Daedra worship is managed by AZ Tweaks Daedric Worship. Reading both mod pages is a good idea in planning out the available buffs to your character. Consider your actions carefully as the gods shall judge you.



## In-Game MCM Options

Notes indicate settings to change, if not specified leave as default. 
- X = Enable 
- O = Disable
**Immediately after creating your character open your inventory and close it.**

## Requiem
To disable the annoying warning message on load in go to Compability & Debug and tick Disable Non-critical Warnings



## FAQ

Why is there a lantern always attached to my character?  Why am I always casting light?
- This is provided by a mod called quick light.  Holding E will toggle a light on and off to help brighten darker areas


How do I update to a later version?
- All you have to do is rerun wabbajack with the new version of the installer. If you have the downloads wabbajack will hash everything, download any new mods, and make the necessary changes in your install folder. You do not need to recopy the game folder files unless they have changed.

How do I use High Poly Head?
- In racemenu search for “face part” and move the slider. HPH will work on any pre existing presets that you have, but you will need to use HPH's eyebrows.

How do I set skyrim to borderless windowed mode?
- Change the settings in the SSE Display Tweaks INI in MO2

I have an ultrawide monitor (21:9), how do I fix the aspect ratios?
- Install the following mods: Complete Widescreen Fix, Extended UI - Widescreen fix, Wider MCM menu for Skyui Widescreen Fix, SkyUI SE - Flashing Savegames fix - Widescreen Fix, Better MessageBox Controls Widescreen fix, Better Dialogue Control Widescreenfix

I have an 60+ Hz screen (100hz, 144hz). What should I do?
- Edit the SSE Display Tweaks ini to properly support your monitor.

Is [insert mod name here] part of the list?
- Check the modlist manifest. If there is something you want that is not in the list, I highly suggest you do not add it unless you know what you’re doing.

Will you add x mod to the list?
- I only take suggestions I did not ask for from people who send me a save of them legitimately killing alduin.

How do I prevent my headgear from being unequiped out of combat?
- Modify the Dynamic Equipment Manager JSON

I think I found a bug! Here are some things that are not bugs:
- Blue swirling effect around some NPCs
- Red effect around vampires/werewolves
- Vampires/werewolves rapidly dying from nothing
- Being permanently out of stamina/magicka
- Any other persistent effect on your character
- Armors that are invisible on male characters
- Unable to allocate the first magick/crafting skill point
- Honed metal is weak
- The game yells that I fucked up when I die
- Unable to drop or deposit gold

## Performance

My Setup:

- Ryzen 2600x
- AMD 5700
- 32GB DDR4
- Game and MO2 running on a m2 drive

I get a consistent 55-60 fps in game. If you get bad frames I suggset swapping the enb to a lighter enb like The Truth or a performance preset of a fireamanaf enb for Obsidian. You may also want to adjust the ini settings to be lower via bethini. 

## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks
Total Skyrim Overhaul made by
- Total
Contributors
- JustThatKing
- NotSandwich
- Shelb
- Nathan
- Jdsmith2816
- OM3N1R
Halgari & Wabbjack Team
-For creating Wabbajack

Special Thanks
- MDC and Vaderade for the original readme template
- Erri for the base of the readme that was forked into elder souls from which this readme is forked
- DarkLadyLexy - Her list taught me how to mod properly and many choices were taken or inspired by it.
- Evertio - ENB light settings inspired by his LOTD+ guide
- The Wabbajack Team - For enduring months of hearing about this list before it was released

Mod Authors
- And of course, where would we be without Skyrim’s awesome mod authors? Thank you all for releasing the quality content that you guys do. PLEASE DO NOT FORGET TO ENDORSE THE AUTHORS!

Invisible Entity tier
- Moggi
- Dispo
            
Dremora tier

Churl Tier
- LanHsah


## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the [Issues](https://github.com/NotTotal/Total-Skyrim-Overhaul/issues) (open **and** closed ones) on GitHub first if you have any problems. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS**.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
