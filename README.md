# Tsukiro - Boobies Bounce Thrice

If you're already experienced with downloading a Wabbajack modlist please head to the Quickstart located here: https://github.com/zhongjiedong/Tsukiro/wiki/1--Welcome-to-hell-Quickstart

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
    - [Graphical Settings](#graphical-settings)
    - [Getting an ENB](#getting-an-enb)
    - [Profiles](#Profiles)
- [Updating](#updating)
- [In Game MCM Options](#in-game-mcm-options)
- [How to start playing](#How-to-start-playing)
- [FAQ](#faq)
  - [Ultrawide Options](#ultrawide-options)
  - [Performance stuff](#Performance-stuff)
    - [Tweaking the ENB](#tweaking-the-enb)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)


## Installation
### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

## Steam Config

#### Steam Library

If you have your steam library in program files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

This entire Modlist is in English and I cannot offer support or troubleshooting to people who are not playing with the game set to English.

#### Clean Skyrim
If this is your first time installing a Wabbajack modlist please use the [Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133). This will provide you with a known state of the game which means troubleshooting issues is much easier.

## Start Skyrim

After you have done everything above and got a clean SSE installation ready, Launch Skyrim once through Steam and get to the main menu and quit. This sets up all the back end stuff that Wabbajack needs to read.

### Using Wabbajack

## Preparations

Download the release to a newly created folder (Name it Wabbajack for example). This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:\Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the new folder.
Wabbajack will not work with Windows 7, I will not offer any kind of support for users of that operating system.

## Graphical Settings

My PC specs:

Ryzen 7 5800x
Radeon RX 6800XT
32GB RAM
NVME SSD

I play at 1440p and it's mostly locked at 61 FPS in most areas apart from a few places like certain parts of Falkreath and JK's interiors like Dragonsreach and Blue Palace

At 1080p you can get away with far lower specs, for reference you'd likely only realistically need a GTX 1070 with a CPU at least as modern as an i5 6600k/Ryzen 1600

Initial loading times will be exceptionally long if you do not have this modlist installed on a SSD.

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## In-Game MCM Options
MCM options have been tweaked specifically for this list, do not modify anything unless you know what you're doing.

#### Game Difficulty

This modlist isn't easy, it's following the Soulsborne style of gaming philosophy. If you don't like it then don't play it. If you really still want to play it you can adjust MCM settings for Sekiro at your own discretion.

## FAQ

## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Ultrawide Options

Read [Here](https://docs.google.com/document/d/1D3Yapmu_IkTWSszJ4h9wpNxgNLCi46f7XiJknpdMb6E/edit?usp=sharing)

## I have a question/I have a bug

I reside here for any questions related to playing the modlist: https://discord.gg/VVRWPJmgf7

## I want to support your work!

I thank you for that thought but you should probably donate to Wabbajack first. Link [here](https://www.patreon.com/user/overview?u=11907933).

## Credits and Thanks

- Halgari and everyone in the WJ Team - goes without saying
- All the creators and devs in the WJ discord, I've leeched so much information from you all.

## Changelog

See [Changelog](https://github.com/SovnSkyrim/QWEST/blob/main/Changelog.md).
