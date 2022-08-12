# Tsukiro - Boobies Bounce Thrice

## THIS IS NOT OPTIONAL, YOU MUST READ THIS THOROUGHLY AND DO THE STEPS OR THE MODLIST WILL NOT FUNCTION

- [Pre-requisites](#pre-requisites)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Installing .NET Runtime 5](#installing-net-runtime-5)
    - [Pagefile configuration](#pagefile-configuration)
  - [Steam Config](#steam-config)
    - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)
  - [Start Skyrim](#start-skyrim)
  - [System Requirements](#system-requirements)
  - [Updating](#updating)
- [Credits and Thanks](#credits-and-thanks)
- [Changelog](#changelog)

### Pre-Requisites

You MUST have these installed for the modlist to function.

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Installing .net Runtime 5 - DO NOT ASSUME YOU ALREADY HAVE THIS, DOWNLOAD AND INSTALL ANYWAY

https://download.visualstudio.microsoft.com/download/pr/28b0479a-2ca7-4441-97f2-64a3d64b2ea4/9995401dac4787a2d1104c73c4356f4d/dotnet-runtime-5.0.12-win-x64.exe

https://download.visualstudio.microsoft.com/download/pr/1daf85dc-291b-4bb8-812e-a0df5cdb6701/85455a4a851347de26e2901e043b81e1/windowsdesktop-runtime-5.0.12-win-x64.exe

Download and install both files.

#### Pagefile configuration

1. Press Windows + R on your keyboard and enter sysdm.cpl ,3
2. Under the Performance section, press 'Settings'
3. Go to the Advanced tab at the top, and at the Virtual memory section press 'Change...'
4. Disable 'Automatically manage paging file size for all drives'
5. Set a custom size for the drive Skyrim is installed on with a mininum of at least 20480MB

AGAIN THIS IS NOT OPTIONAL, JUST BECAUSE YOU HAVE 6MILLION GB OF RAM DOES NOT MEAN YOU CAN SKIP THIS STEP, JUST DO IT.

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

### Start Skyrim

After you have done everything above, Launch Skyrim once through Steam and get to the main menu and quit. This sets up all the back end stuff that Wabbajack needs to read.

THIS LIST REQUIRES AN UP TO DATE SKYRIM SE *INSTALL*, MAKE SURE IN STEAM IT'S NOT PENDING AN UPDATE. DO NOT USE THE DOWNGRADE PATCHER.

# Next steps for installation - CLICK THE BOOBIES BELOW

[![Foo](https://i.imgur.com/042G5it.png)](https://github.com/zhongjiedong/Tsukiro/wiki/Full-guide)

## System Requirements

My PC specs:

Ryzen 7 5800x

Radeon RX 6800XT

32GB RAM

NVME SSD

Minimum Recommended specs for 1080p:

i5 10400/Ryzen 5 3600

GTX 2070 8GB/RX5600XT 8GB

16GB RAM

SSD

I play at 1440p and it's mostly locked at 61 FPS in most areas apart from a few places like certain parts of Falkreath and Solitude.

Initial loading times will be exceptionally long if you do not have this modlist installed on a SSD.

## Updating

Major update means any of the first 2 numbers changing (for example beta 1.1.5 to beta 1.2.0), these will not be save friendly. Minor update means the last number changes (for example 1.1.5 to 1.1.6), these will be save friendly. If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

If you would like to add mods to the list and keep them rename the mod in MO2 with [NoDelete] in front of the name and do NOT tick overwrite when updating the list.

If your game crashes when loading a save after an update, please refer to the following article: https://github.com/zhongjiedong/Tsukiro/wiki/Crash-on-load---SchlongsOfSkyrim.dll

## Credits and Thanks

- Halgari and everyone in the WJ Team - goes without saying
- All the creators and devs in the WJ discord, I've leeched so much information from you all.
- No Copyright Music for the main menu music: https://www.youtube.com/watch?v=H31PRzqlj8s

## Changelog

See [Changelog](https://github.com/zhongjiedong/Tsukiro/releases).
