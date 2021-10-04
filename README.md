# Tsukiro - Boobies Bounce Thrice

If you're already experienced with downloading a Wabbajack modlist please head to the Quickstart located [here](https://github.com/zhongjiedong/Tsukiro/wiki/3---Quickstart)

- [Pre-requisites](#pre-requisites)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
  - [Steam Config](#steam-config)
    - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)
  - [Clean Skyrim](#clean-skyrim)
  - [Start Skyrim](#start-skyrim)
  - [Updating](#updating)
  - [In Game MCM Options](#in-game-mcm-options)
  - [Commonly failing downloads](#commonly-failing-downloads)
- [FAQ](#faq)
  - [Why can't I fast travel?](#why-cant-i-fast-travel)
  - [How do I start the main story quest?](#how-do-i-start-the-main-story-quest)
  - [Help! I can't jump anymore.](#help-i-cant-jump-anymore)
  - [Why do I have marks on my skin?](#why-do-i-have-marks-on-my-skin)
  - [Starting an alternate Character](#starting-an-alternate-character)
  - [Ultrawide Options](#ultrawide-options)
  - [Controller Support](#controller-support)
  - [Game Difficulty](#game-difficulty)
  - [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Changelog](#changelog)

### Pre-Requisites

These steps are only needed if you install this Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

## Steam Config

### Disable the Steam Overlay

Right click on Skyrim SE and click on properties, untick "Enable Steam Overlay while in-game"

#### Steam Library

If you have your steam library in program files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

This entire Modlist is in English and I cannot offer support or troubleshooting to people who are not playing with the game set to English.

#### Clean Skyrim
If this is your first time installing a Wabbajack modlist please use the [Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133). This will provide you with a known state of the game which means troubleshooting issues is much easier.

### Start Skyrim

After you have done everything above and got a clean SSE installation ready, Launch Skyrim once through Steam and get to the main menu and quit. This sets up all the back end stuff that Wabbajack needs to read.

## Graphical Settings

My PC specs:

Ryzen 7 5800x

Radeon RX 6800XT

32GB RAM

NVME SSD

I play at 1440p and it's mostly locked at 61 FPS in most areas apart from a few places like certain parts of Falkreath and JK's interiors like Dragonsreach and Blue Palace.

At 1080p you can get away with far lower specs, for reference you'd likely only realistically need a GTX 1070 with a CPU at least as modern as an i5 6600k/Ryzen 1600

Initial loading times will be exceptionally long if you do not have this modlist installed on a SSD.

## Updating

Major update means the first number changes (for example beta 27 to beta 30), these will not be save friendly. Minor update means the second number changes, these will be save friendly. If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

If you would like to add mods to the list and keep them rename the mod in MO2 with [NoDelete] in front of the name and do NOT tick overwrite when updating the list.

## In-Game MCM Options
MCM options have been tweaked specifically for this list, do not modify anything unless otherwise specified.

## Commonly failing downloads

Please refer to this page for links: https://github.com/zhongjiedong/Tsukiro/wiki/Commonly-failing-downloads

Download the files manually and place them unmodified into the folder with the rest of your downloads

# Next steps for installation

[![Foo](https://i.imgur.com/042G5it.png)](https://github.com/zhongjiedong/Tsukiro/wiki/1---Full-guide)

## FAQ

### Why can't I fast travel?

Fast travel is limited in this modlist, you can only travel from signposts on the road or craft a consumable item at a cooking pot.

### How do I start the main story quest? 

Don't worry about it, just go do other stuff. You'll get to it eventually

### Help! I can't jump anymore.

For some reason there's a rare bug where you stop being able to jump. So far disabling and enabling Engarde in the MCM seems to have a 100% success rate in fixing this:
![image](https://i.imgur.com/FjWPz9H.png)

Turn off Souls like stamina and also the toggleable power after re-enabling Engarde:

![image](https://i.imgur.com/keKcPDk.png)
![image](https://i.imgur.com/4H6HnEN.png)

### Why do I have marks on my skin?

![image](https://i.imgur.com/TlH9LVn.jpg)

Go into your lesser powers and use the "wash and rinse" power.

### Ultrawide Options

Read [Here](https://docs.google.com/document/d/1D3Yapmu_IkTWSszJ4h9wpNxgNLCi46f7XiJknpdMb6E/edit?usp=sharing)

### Controller support

See [Here](https://github.com/zhongjiedong/Tsukiro/wiki/Controller-support)

### Game Difficulty

This modlist isn't easy, it's following the Soulsborne style of gaming philosophy. If you don't like it then don't play it. If you really still want to play it you can adjust MCM settings for Inpa - Sekiro Combat at your own discretion.

### Starting an alternate Character

On the main menu, click on load and then "show all characters". Find the save named START and load that.

### Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

### I have a question/I have a bug

I reside here for any questions related to playing the modlist: https://discord.gg/VVRWPJmgf7

### I want to support your work!

I thank you for that thought but you should probably donate to Wabbajack first. Link [here](https://www.patreon.com/user/overview?u=11907933).

## Credits and Thanks

- Halgari and everyone in the WJ Team - goes without saying
- All the creators and devs in the WJ discord, I've leeched so much information from you all.
- No Copyright Music for the main menu music: https://www.youtube.com/watch?v=H31PRzqlj8s

## Changelog

See [Changelog](https://github.com/zhongjiedong/Tsukiro/releases).
