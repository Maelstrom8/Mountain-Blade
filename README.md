# Calradia Under Fire

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
- [Thanks and Credits](#thanks-and-credits)

# Introduction

Calradia Under Fire is a dual purpose modlist for the v1.1.1 version of Mount & Blade II: Bannerlord. Calradia Under Fire makes use of a mod launcher called [Novus Launcher](https://www.nexusmods.com/mountandblade2bannerlord/mods/4924?tab=description), which allows users to make and customize load order presets for mods. This is basically what MO2 is for Bethesda games. Bannerlord has a basic MO2 plugin, and allows you to make profile presets, but because of how the game is built, MO2 can only really operate as a virtual file system. You need an additional tool such as Novus Launcher or BUTRLoader to then organize the load order of the mods.

Calradia Under Fire ships with two Noxus Launcher presets. One is meant to be the main modlist, which is meant to be played (almost) out of the box. It consists of 60 mods. The other preset is advanced users, or for those who want to build their own or test mods. That's where the real fun is. In all honesty you can make changes to either, but you should only touching the main one if you know what you're doing.

(This has nothing to do with the game Kingdoms: Under Fire)

## Information

`ModlistProfile` is the main profile, the modlist itself, which consists of about 60 mods and is what the standard user should select. It is focused around Realistic Battle Mod & Banner Kings. Features include the troop overhaul Warlords Battlefield, armors such as Open Source Armory, Swadian Armory, Vaegir Armory and many other QoL mods.

- Here is a small list of the more important mods I use, feel free to look up on them
   - [Realistic Battle Mod](https://www.nexusmods.com/mountandblade2bannerlord/mods/791) is the method of choice (for now) for overhauling the combat, specifically weapon and armor calculation.
   - [Banner Kings](https://github.com/R-Vaccari/bannerlord-banner-kings/wiki) is a core overhaul heavily inspired by Crusader Kings, lots of useful additions and changes
   - [Open Source Armory](https://www.nexusmods.com/mountandblade2bannerlord/mods/2829) is one of the largest armor collections to date on Nexus, and kinda a little bloated but it has overall good armor in it.
   - [Neated's NPC Upgrade Equipment](https://www.nexusmods.com/mountandblade2bannerlord/mods/4516) is a nice little mod that makes use of the armory mods I have. 
   - [Warlords Battlefield](https://www.nexusmods.com/mountandblade2bannerlord/mods/4277) is the troop overhaul of my pick. I really do not like the virgin troop trees of vanilla game.
   - [Dismemberment Plus](https://www.nexusmods.com/mountandblade2bannerlord/mods/2190) should be self explanatory
   - [Xorberax's Legacy](https://www.nexusmods.com/mountandblade2bannerlord/mods/3462) has mini-modules in it, but I mostly use it for the ability to enable weapons to cut through everyone
   - [Novus Launcher](https://www.nexusmods.com/mountandblade2bannerlord/mods/4924) well.. self explanatory

`BasicEssentials` is where the second purpose of the modlist comes in. Contains the bare minimum mods such as Harmony and what not. This is for advanced users to make their own load order based off the mods provided within MO2, or to mess around and test mods without affecting the main one.

If you would like to get a bit deeper into modifications - head on over to the [Modding Documentation](https://github.com/Maelstrom8/CalradiaUnderFire/blob/main/Documentation/Modding%20Documentation.md)

### Requirements & Installation

- A unmodified copy of Mount & Blade II: Bannerlord through Steam (I do not support anything else)
- A Nexus account (you don't need Premium but everyone should have an account)
- Your Bannerlord version must be v1.1.1
   - The "beta" is actually a hotfix and doesn't break my mods. Go to Properties > Beta and make sure it looks like [this](https://i.imgur.com/Sx5Z4K2.png)
   - Make sure Language is set to [English](https://i.imgur.com/2OKEBEl.png)
   - They really don't have any way to stop updates, so your best option is putting it so it [only updates when you launch it](https://i.imgur.com/T2h2pxF.png). Set that.
   - If the game updates, switch back to v1.1.1 (I'll likely ultilize stock game feature if it becomes available)

Additionally, if you do not have [.NET Desktop Runtime 6.0.14](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) - you need it. Novus Launcher won't work without it.

### System Requirements

- See the recommended specs from the Steam page. You don't need a 4090 but you are expected to have a decent PC in 2023, and are expected to have an SSD for games. I would actually hope you install this on an SSD.
- You need 99GB of free space. Base game (47GB) + the downloads (16GB) + the install (36GB)

## Wabbajack Installation

Download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases). Place it in a folder such as `C:\Wabbajack`. Do not extract it to any of your Steam Library directories nor your game root folder. Do not extract it to locations such as Program Files, or User Directories like Documents, Downloads and so forth.

### Downloading and Installing Calradia Under Fire

1. Open Wabbajack and click `Browse Modlists`
2. Tick on the `Show Unofficial lists` option in the top right corner of Wabbajack
3. Filter by Mount & Blade II: Bannerlord. Click the download button below the gallery image and wait for it to download.
4. Set the installation folder, following the directory rules above. For example, I have an NVME drive, and I have my Wabbajack installation on it, then separate from it I have another folder called "Wabbajack lists" which is where I install modlists
5. Press the play button to begin.
6. In the small time it takes to install, I recommend you spend your time reading this readme - as it's more important than your average readme
7. ???
8. Profit

### Installation Issues

You may run into some issues with Wabbajack, here are some common ones

- Could not download x: 
   - Large files can potentially fail due to connection issues. Re-run Wabbajack or download the file manually, but make sure you placed it in your downloads folder

- Wabbajack can't find the game folder
   - The only thing I can recommend is actually buying the game

- Not an issue but you're installing it on an HDD and it's awfully slow
   - Get an SSD

### Nexus Premium vs Non-Premium

If you have Premium, WJ will request a Nexus login and use the api to download all mods automatically. Without Premium, you'll be prompted to manually download the mods. Who are you kidding, it's like 16GB, you don't need it homie.



## Updating the list

You can update the list the same way you install it, just be sure to check [the changelog](https://github.com/Maelstrom8/CalradiaUnderFire/blob/main/Changelog.md) first. **DO NOT** manually update mods, unless you know what you're doing and you know how I made them, which you likely don't. I changed some mods around a little, so if you update them manually.. there could be an issue (eg. the RBM patches section)


# Post Installation Setup 

#### Novus Launcher and MCM Configs 

Go to where you installed the list, and open the folder labelled **GAME FILES FOLDER** 

1. Take `NovusLauncher` and copy it into your root game folder eg "F:\SteamLibrary\steamapps\common\Mount & Blade II Bannerlord" - [example](https://i.imgur.com/R4HCPAh.png)
2. Take `Configs` and copy it into your user documents eg ".\Documents\Mount and Blade II Bannerlord" - [example](https://i.imgur.com/xgL062d.png)
3. Open `ModOrganizer2.exe` within the list's directory and navigate to the drop down menu on the top right, hit the arrow and hit `<Edit...>`
4. All the way to the left next to "Executables" is a plus sign, click it and select "add from file"
5. Navigate to the `NovusLauncher.exe` you moved over to your Bannerlord folder, hit apply
6. PS make sure your managed game under settings points to the base TaleWorlds launcher - [example](https://i.imgur.com/F9vUdly.png)

You are generally ready to play, but there are one or two configs that aren't saved globally and have to be set every time you start a new game, but that's for another section. 


#### Playing Calradia Under Fire

1. Navigate to your installed modlist folder and double-click on `ModOrganizer2.exe`
2. Make sure Novus Launcher is selected as the launcher and hit run - [example](https://i.imgur.com/6dW3cwd.png)
3. Make sure `ModlistProfile` is selected under Novus Launcher if you want to play the main one - [example](https://i.imgur.com/clS9och.png)

If you're using the main profile, there are some **important** additional steps you need to take, because some configs are only saved on a per save basis.

- Upon a new save, hit left alt + G, go to NPC Settings and make sure it looks like [this](https://i.imgur.com/BkdUc12.jpeg) - do not enable food modules
- Make sure `AI Clan Governers Handles Issues` is enabled under the mod `Governers Handle Issues` - this can be done from the main menu or ESC > Options > Mod Options

**By the way, there reasons why some options are disabled in the MCM options of mods. Do not enable them.**

- Realistic Battle Mod
   - **The Tournament Module** is disabled because I use a Troop Overhaul such as **Warlords Battlefield**
- Xorberax Legacy
   - **Deadly Combat**, **Deadly Horse Charge** and **Friendly Fire** are disabled to ensure compatibility with **Banner Kings**
- Improved Garrisons
   - **Food Module(s)** in the LAlt + G settings are supposed to be disabled to ensure compatibility with **Banner Kings**

The rest of the changes are a work in progress, untested or personal balance changes I felt were okay.

## FAQ

#### Q: What's this menu where I can choose my "start"? Banner Kings? What is this?
A: Banner Kings. Read all about it in-game or [here](https://github.com/R-Vaccari/bannerlord-banner-kings/wiki)

#### Q: Why do weapons feel so weak initially, why is the game harder?
A: Let me introduce you to [Realistic Battle Mod](https://www.nexusmods.com/mountandblade2bannerlord/mods/791). It's kinda feature bloated but it overhauls damage calculation. You need to get good, literally - level up your skills more. Swords, Maces, Axes.. they act differently against different types of armor. Also, there are 8 types of defenses: Head, Face, Neck, Shoulder, Lower Shoulder, Chest, Abdomen, Arms, and Legs. Check the shield icon in your inventory, next to your gear.

#### Q: God, I hate Realistic Battle Mod (The Combat Module)
A: This isn't a question, but I'm also not really a fan of the Combat Module. I'm personally looking into disabling the Combat Module, which means disabling all the RBM patches, keeping the AI Module and adding [Warbandlord](https://www.nexusmods.com/mountandblade2bannerlord/mods/3961) 

#### Q: Help I'm getting my ass beat in Tournaments
A: This is a combined result of using a troop overhaul such as Warlords Battlefield, and using the combat module from RBM. You are fighting against random troops and lords who are using their innate gear and weapons, even if kills are non-lethal, it will naturally will be hard if you are low level with low skills. I might add the mod "Balanced Tournament Armor"  to potentially address this and return it to the classic style of tournaments being more fair.

#### Q: WOW, I seem to making fuckin cash from battle loot, don't you think this is too much?
A: This question was like a 5 minute observation, but incase people think they might be making too much dineros.. No. I feel it'll balance out in the long run, especially with Banner Kings, Royal Armory's admission costs and what not. I generally don't care if it seems like too much, though.

#### Q: Why do you use this mod over that mod? Why DON'T you use this or that mod?
A: Kinda hard to say, but if you must know a little about me: I'm someone who doesn't really care too much about balance and or restriction, I like power fantasy. For example, I like big dick troop trees, which is why I picked Warlords Battlefield. I don't care too much for lore friendly stuff. There is a reason why I included the Bannerlord Cheats mod :D

A: I can't tell you why I don't use mods, and the sort. It can be any reason, but I generally want to keep it simple, I've only tested so many mods.

#### Q: Can I enable the NSFW mods like Hot Butter?
A: Sure. They work, I just don't know if how well they work with this mod selection. You're on your own.

### Bugs

wip

### Thanks and Credits

- Bloc for making great mods, specifically Novus Launcher
- TW for making a great framework
- Bannerlord modding community for turning a framework into a damn house
- Halgari - for making Wabbajack. Wouldn't have been possible otherwise.
- You, made you look.
