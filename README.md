# Mountain Blade
![4277-1665765591-334181290](https://user-images.githubusercontent.com/17627623/224583503-024f767d-d50b-47bd-ae4e-8702d521e420.jpeg)


---

## Table of Contents
- [Introduction](#Introduction)
   - [Information](#Information)
   - [Requirements & Installation](#requirements-and-installation)
   - [System Requirements](#system-requirements)
 - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Calradia Under Fire](#installing-calradia-under-fire)
      - [Installation Issues](#installation-issues)
      - [Nexus Premium vs Non-Premium](#nexus-premium-vs-nonpremium)
      - [Updating the list](#updating-the-list)
- [Post Installation Setup](#post-installation-setup)
   - [Playing Calradia Under Fire](#playing-calradia-under-fire)
- [FAQ](#faq)
- [Bugs](#bugs)
- [Thanks & Credits](#thanks--credits)

# Introduction

Mountain Blade is a work in progress modlist for Mount and Blade II: Bannerlord. I think it's going to be mostly vanilla.

## Information

This is where I should list the important mods and link a load order library, if it works. Something like that.

### Requirements & Installation

In order to play my modlist, you must meet these conditions:

- You must own a legitimate copy of Mount & Blade II: Bannerlord on Steam. Only the Steam version is supported, I do not care that you use or like GOG.
- Your copy of the game *must* be 100% unmodified. If you have been modding it directly, or have been fucking around with the workshop, this is where you ensure all mods are disabled, and or nuke your entire game directory and start over.
- You must have a Nexus Account and probably have Premium.
- Your Bannerlord version must be v1.2.12. In the launcher it should say v1.2.12.77991. Do the following:
   - Go to Properties > Beta and make sure [Beta Participation is set to None](https://i.imgur.com/IdTGKZS.png).
   - Make sure Language is set to [English](https://i.imgur.com/0aD9AhD.png)
   - There is no way to disable Automatic Updates, only to delay them. The best option is [Wait until I launch the game](https://i.imgur.com/ar0ImE3.png). Set that.
   - If the game updates, select v1.2.12 from the Betas, I'll have to look into it.

Additionally, if you do not have [.NET Desktop Runtime 6.0.14](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) - you need it. Novus Launcher won't work without it.

### System Requirements

- See the recommended specs from the Steam page. You don't need a 4090 but you are expected to have a decent PC in 2023, and are expected to have an SSD for games. I would actually hope you install this on an SSD.

- You need around X GB of free space for this modlist
   - X GB for the base game, already installed separately
   - X GB for the modlist (X GB downloads + X GB install)

## Wabbajack Installation

Download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases). Install in a folder such as `C:\Wabbajack`. Do not install it to any of your Steam Library directories nor your game root folder. Do not extract it to locations such as Program Files, or User Directories like Documents, Downloads and so forth.

### Downloading and Installing Calradia Under Fire

1. Open Wabbajack and click `Browse Modlists`
2. Tick on the `Show Unofficial lists` option in the top right corner of Wabbajack
3. Filter by Mount & Blade II: Bannerlord. Click the download button below the gallery image and wait for it to download.
4. Either select `Install From Disk` or wait for Wabbajack to automatically switch to the modlist installing tab.
5. You'll be prompted with a window to select where to install the modlist and its resource downloads, here is an example. I have it on my `F Drive` which is a separate NVME SSD.

![Wabbajack_YnKGZnRdGu](https://user-images.githubusercontent.com/17627623/224857931-cf99d6f9-585c-467f-8a52-8dcb3e643845.png)

- `Target Modlist` should be automated, based on if you installed from disk or installed from the gallery.
- `Modlist Installation Location` should be anywhere but your Steam Library, Program Files or User Directories like My Documents, Downloads etc
- `Modlist Resource Downloads` should follow the same rules but they do not have to be in the same folder. It's recommended you have your downloads on a fast drive.

Afterwards, hit the play button and wait. While waiting, you can read this readme.

### Installation Issues

You may run into some issues with Wabbajack, here are some common ones

- Could not download x: 
   - Large files can potentially fail due to connection issues. Re-run Wabbajack or download the file manually, but make sure you placed it in your downloads folder

- Wabbajack can't find the game folder
   - The only thing I can recommend is actually buying the game

- Not an issue but you're installing it on an HDD and it's awfully slow
   - Get an SSD

### Nexus Premium vs Non-Premium

If you have Premium, WJ will request a Nexus login and use the api to download all mods automatically. Without Premium, you'll be prompted to manually download all the mods. There are 126 mods to download, and while only a small number of them contribute to the total size (16GB), you still have over 80 mods that are incredibly small in size to manually download when prompted in Wabbajack. If you don't like this, get Nexus Premium I dunno.


## Updating the list

You can update the list the same way you install it, just be sure to check CHANGELOG LINK first. **DO NOT** manually update mods, unless you know what you're doing and you know how I made them, which you likely don't. I changed some mods around a little, so if you update them manually.. there could be an issue.

# Post Installation Setup 

### First Time Setups

Since I don't use the Stock Game folder, as it's not supported yet, paths aren't exactly saved from updates/compiles, so go do the following to quickly fix your paths. Do this first.

https://user-images.githubusercontent.com/17627623/225754253-6d9c6060-e11b-47ca-9b07-776252373dd6.mp4

------------------------------------------------------------------------------------------------------

- Go to where you installed the modlist and look for the folder `GAME FILES FOLDER`, find `Configs.7z`
- Use something like `7zip` to open it. You'll see two folders:
   - Copy `Configs` to your user documents eg `...\Documents\Mount and Blade II Bannerlord`
   - Copy `NovusLauncher` to your root game folder eg `...\SteamLibrary\steamapps\common\Mount & Blade II Bannerlord`


1. Using the video above, add `NovusLauncher.exe` as an executable (Use the plus sign, and navigiate to your root game folder where you extracted it, select the exe, hit apply)
2. Make sure your managed game under settings points to the base [TaleWorlds Launcher](https://i.imgur.com/F9vUdly.png) 
3. Additionally, if you **want** [Adonnay's really cool Exotic Weaponry](https://www.nexusmods.com/mountandblade2bannerlord/mods/2620) to be added to the tournament prize pool, please navigate to the incovenient location known as `C:\ProgramData\Mount & Blade II: Bannerlord\AEW` and modify `AEW.settings.xml`, so the values are *true* instead of *false*. If you don't see the folder, google "how 2 show hidden files, folders and drives".

### Launching Calradia Under Fire

You are generally ready to play, there are some extra instructions and things to be aware of.

- Launch `ModOrganizer.exe`
- Launch `Novus Launcher.exe` from the MO2 drop down
- Decide which preset you want to play


---

**CalradiaUnderFire-RBM**:

- Make sure only `Warlords Battlefield - RBM Version` is [enabled in MO2](https://i.imgur.com/KdC1a0g.png) before running `Novus Launcher`
- Make sure you have the **Combat Module** in the RBM options via main menu enabled 
- Double check for all armors, you have relevant RBM patches loaded after them (they should by default)

   
**CalradiaUnderFire-WBL**:

- Make sure only `Warlords Battlefield` is [enabled in MO2](https://i.imgur.com/ckirBse.png) before running `Novus Launcher`
- Make sure you have the **Combat Module** in the RBM options via main menu disabled
- Make sure you have no RBM patches accidentally on your load order, they will make everyone even stronger 
    
---

Adjust the following on every new game start:

- **Improved Garrisons**
   - Press Left Alt + G, go to `NPC Settings` and make sure it looks like [this](https://i.imgur.com/BkdUc12.jpeg). Do not enable food module(s)


*By the way, there reasons why some options are disabled in the MCM options of mods.*

- Realistic Battle Mod
   - **The Tournament Module** is disabled because to ensure compability with **Banner Kings**
   - **Troop Overhaul** is disabled because on both profiles because I use the troop overhaul **Warlords Battlefield**, which use their own non-RBM/RBM gear.
- Xorberax Legacy
   - **Deadly Combat** and **Deadly Horse Charge** are disabled because I'm not sure they are balanced..
   - **Friendly Fire** can be enabled/disabled, it's actually kinda funny
- Improved Garrisons
   - **Food Module(s)** in the Left Alt + G settings are supposed to be disabled to ensure compatibility with **Banner Kings**

The rest of the changes are a work in progress, untested or personal balance changes I felt were okay.

## FAQ

#### Q: What's this menu where I can choose my "start"? Banner Kings? What is this?
A: Banner Kings. Read all about it in-game or [here](https://github.com/R-Vaccari/bannerlord-banner-kings/wiki)

#### Q: Why do weapons feel so weak initially, why is the game harder on the RBM profile?
A: Let me introduce you to [Realistic Battle Mod](https://www.nexusmods.com/mountandblade2bannerlord/mods/791). It's kinda feature bloated but it overhauls damage calculation. You need to get good, literally - level up your skills more. Swords, Maces, Axes.. they act differently against different types of armor. Also, there are 8 types of defenses: Head, Face, Neck, Shoulder, Lower Shoulder, Chest, Abdomen, Arms, and Legs. Check the shield icon in your inventory, next to your gear.

#### Q: God, I hate Realistic Battle Mod (The Combat Module)
A: This isn't a question, but I'm also not really a fan of the Combat Module. I'm personally looking into disabling the Combat Module, which means disabling all the RBM patches, keeping the AI Module and adding [Warbandlord](https://www.nexusmods.com/mountandblade2bannerlord/mods/3961) 
A: Use the Warbandlord profile

#### Q: Help I'm getting my ass beat in Tournaments
A: This is a combined result of using a troop overhaul such as Warlords Battlefield, and using the combat module from RBM. You are fighting against random troops and lords who are using their innate gear and weapons, even if kills are non-lethal, it will naturally will be hard if you are low level with low skills. I might add the mod "Balanced Tournament Armor"  to potentially address this and return it to the classic style of tournaments being more fair.

#### Q: WOW, I seem to making fuckin cash from battle loot, don't you think this is too much?
A: This question was like a 5 minute observation, but incase people think they might be making too much dineros.. No. I feel it'll balance out in the long run, especially with Banner Kings, Royal Armory's admission costs and what not. I generally don't care if it seems like too much, though.

#### Q: Why do you use this mod over that mod? Why DON'T you use this or that mod?
A: Kinda hard to say, but if you must know a little about me: I'm someone who doesn't really care too much about balance and or restriction, I like power fantasy. For example, I like big dick troop trees, which is why I picked Warlords Battlefield. I don't care too much for lore friendly stuff. 

A: I can't tell you why I don't use mods, and the sort. It can be any reason, but I generally want to keep it simple, I've only tested so many mods.

#### Q: Can I enable the NSFW mods like Hot Butter? Captivity Events?
A: Sure. They work, I just don't know how well they work with this mod selection, eg Banner Kings. You're kinda on your own.

### Bugs

At the time of the writing, there's only real one known crash so far.. and it's a dreaded base game *Sandbox Core* crash that can happen when you approach a settlement. I have no real tips to avoid it, save your game somewhat often, and wait a bit before you head into a settlement.

### Thanks & Credits

- Bloc for making great mods, specifically Novus Launcher
- TW for making a great framework
- Bannerlord modding community for turning a framework into a damn house
- Halgari - for making Wabbajack. Wouldn't have been possible otherwise.
- You, made you look.
