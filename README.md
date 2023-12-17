# Total-Skyrim-Overhaul

- [Introduction](#Introduction)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
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
Total Skyrim Overhaul is a requiem based modlist, this means it is difficult. If you are looking for a gameplay experience that does not require careful planning I suggest playing Keizaal, The Phoenix Flavor, or Living Skyrim instead. If you have never played requiem before I strongly reccomend you start with Do Not Go Gentle first.

I will not provide support on how to add or change any mods beyond what is already provided. Do not ask me for help if you changed things. If you do not have experience modding requiem on SSE and patching with xedit I suggest you do not even think of changing anything.

If a question is sufficiently answered in this readme I will not respond to support requests relating to it. Please read the readme, I wrote it for a reason. If your question is not in the readme I will answer it to the degree possible.

Support is only available in the [Requiem Wabbajack Discord](https://discord.gg/WCbdB9TYbj)

NSFW Warning: This list contains nude models for female and males.
## Installation

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

You must do this for wabbajack to work. If your game was previously set to non-english make sure to verify your files on steam after fixing it. There is no support for non-english skyrim.

Open the Steam Properties window, navigate to the Language tab and select English from the dropdown menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in X:\Wabbajack

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD. You can have the TSO and downloads folder be on separate drives without issue, aside from being limited by the slowest drive during wabbajack installation.

1. Open Wabbajack
2. Load the Modlist from Disk
3. Set TSO to install to X:\Total Skyrim Overhaul and download to X:\Total Skyrim Overhaul\Downloads. Your downloads folder can be on a separate drive to save space but wabbajack's install speed will be limited to your slowest drive. 
4. Click the Go/Begin button
5. Wait for Wabbajack to finish

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. If you do not see an installation failed warning do not worry about it. If you feel like wabbajack is stuck or a download is hanging just restart wabbajack, it will pick up from exactly where you left off.  Please rerun wabbajack at least twice and try to manually download the file from nexus/ll first before posting about a failed download.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

#### Starting the Game

Head over to the installation folder and locate an executable named ModOrganizer.exe and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

# Gameplay Guide

GAMEPLAY QUESTIONS WILL NOT BE ANSWERED IN #TSO-SUPPORT, GO TO #GAMEPLAY-SPOILERS ON THE [Requiem Wabbajack Server](https://discord.gg/JycmyqzZz7)

## 3bfTweaks

TSO now features 3bftweaks, a comprehensive overhaul of requiem designed to eliminate many of the meta gaming strategies people have developed over time and force you to actually play the game to progress. **The only way to gain skill levels is by potions of insight which you earn from end chests of locations or by fighting powerful enemies**. Additionally, the economy has been drastically rebalanced so you can no longer abuse alchemy or sell junk gear to vendors to become rich. 3bfTweaks has many other significant changes to the ways that requiem works, which you will have to find out by playing.

## Perks

Requiem is an extremely perk focused mod. Every skill requires the initial perk to be usable. For example, you will not be able to pick any locks without the first perk in lockpicking, if you don’t have any perks in one handed you will struggle to even swing a sword. Requiem grants you three perk points at level one. Choose wisely.

As standard in requiem each smithing tier will require the respective book before you can spend a perk point. These books are scattered throughout the world in places where they logically belong. You will have to earn them.

## Saving
 
TSO features sleep to save. There are only two ways to save, either when you sleep at a bed, or once every 15 minutes with the item in your inventory called "Elder Scroll (Break)." No, there is no way to turn this off. 

## Religion

You can worship a god to gain extra power. You'll have to figure out how to do this.

## Equipment Durability

TSO features Equipment Durability. Items will degrade over time as you use them. This will be displayed with the name of the item being modified to show its degredation status. Items can be repaired by tempering

## Character Customization

TSO has two MCMs related to character customization that are easy to miss. Racemenu animated overlays will allow you to determine when overlays appear during combat. Skyrim outfit system allows you to set visual only outfits for various situations and locations. It's effectively transmog in skyrim, finally.

If you spent a long time making your character I highly suggest either finding a way to save quickly or making it a preset. Death is likely early on.

## In-Game MCM Options

All MCM options have been preconfigured

## FAQ

SKSE instantly crashes when I try to start the game
- Please ensure you have .NET v5.0 installed. Download and install both Console Apps x64 AND Desktop Apps x64 versions from Microsoft:
https://dotnet.microsoft.com/download/dotnet/5.0/runtime

I'm playing on a resolution above 1080p and my game resolution is messed up when I start the game!
- First, open up MO2, open up MO2's ini editor, and make sure the resolution in the skyrimprefs ini **in mo2** is set to the correct resolution. If this does not solve your problem open up SSE Display Tweaks in mo2, open up its ini and edit it to fit your resolution or just turn it to fullscreen. Finally if you still have a problem check windows scaling settings for skyrim.

Why is there a lantern always attached to my character?  Why am I always casting light?
- This is provided by a mod called quick light.  Holding E will toggle a light on and off to help brighten darker areas

How do I update to a later version?
- All you have to do is rerun wabbajack with the new version of the installer. If you have the downloads wabbajack will hash everything, download any new mods, and make the necessary changes in your install folder. You do not need to recopy the game folder files unless they have changed.

A bunch of armor files failed to download
- Links are here: https://github.com/NotTotal/Total-Skyrim-Overhaul/blob/master/Armorlinks.md

NPCs keep dropping Lusty Argonian Maid books
- Each maid that drops is an insight potion that could have dropped, but dropped as a maid instead.

How does this compare to other 3BFTweaks lists?
- TSO is slower, the enemies are more numerous and harder, and some other changes to make the game harder.

My character's hair/eyebrows/beard has weird texture issues
- You need to use High Poly Head and non-vanilla hair/eyebrows/beard (HPH has duplicates made for HPH)

How do I use High Poly Head?
- In racemenu search for “face part” and move the slider. HPH will work on any pre existing presets that you have, but you will need to use HPH's eyebrows.

Loverslab downloads keep failing!
- First make sure you verified your LL account and then restart WJ. If that doesn't work log in and out of LL in the WJ UI. If that doesn't work, grab the failing links from the WJ log, download the files manually, and put them in your downloads folder.

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

I think I found a bug! Here are some things that are not bugs:
- Blue swirling effect around some NPCs
- Unable to gain skill levels
- Red effect around vampires/werewolves
- Vampires/werewolves rapidly dying from nothing
- Being permanently out of stamina/magicka
- Any other persistent effect on your character
- Armors that are invisible on male characters
- Unable to allocate the first crafting skill point
- Inigo won't speak to me
- I can't recruit modded followers

## Performance

My Setup:

- Intel i13900k
- RTX 4090
- 64GB DDR5
- Game and MO2 running on a m2 drive

I get a consistent 120+ fps in game at 1440p. If you get bad frames I suggest not wearing any SMP items or figuring out how to use a lower NAT enb preset. I don't provide support for making your fps better so please do not ask me.

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

## Contact

While I'm always available on the [Requiem Wabbajack Discord](https://discord.gg/WCbdB9TYbj), I would advise checking the [Issues](https://github.com/NotTotal/Total-Skyrim-Overhaul/issues) (open **and** closed ones) on GitHub first if you have any problems. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS**.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
