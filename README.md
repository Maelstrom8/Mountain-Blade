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
- [Thanks & Credits](#thanks--credits)

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
   - [RTS Camera + Command System](https://github.com/Norbivar/RTSCamera) are two mods that allow better camera control and features in battle such as controlling troops after death, commanding your troops to attack formations, slow motion, etc
   - [Dismemberment Plus](https://www.nexusmods.com/mountandblade2bannerlord/mods/2190) should be self explanatory
   - [Xorberax's Legacy](https://www.nexusmods.com/mountandblade2bannerlord/mods/3462) has mini-modules in it, but I mostly use it for the ability to enable weapons to cut through everyone
   - [Novus Launcher](https://www.nexusmods.com/mountandblade2bannerlord/mods/4924) well.. self explanatory

`BasicEssentials` is where the second purpose of the modlist comes in. Contains the bare minimum mods such as Harmony and what not. This is for advanced users to make their own load order based off the mods provided within MO2, or to mess around and test mods without affecting the main one.

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

- You need around 91GB of free space for this modlist
   - 47GB for the base game, already installed separately
   - 44GB for the modlist (16GB downloads + 28GB install)

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

**OFFICIAL SUPPORT** IS PROVIDED OVER AT THE [WAKING DREAMS](https://discord.gg/wakingdreams) DISCORD

### Nexus Premium vs Non-Premium

If you have Premium, WJ will request a Nexus login and use the api to download all mods automatically. Without Premium, you'll be prompted to manually download all the mods. There are 126 mods to download, and while only a small number of them contribute to the total size (16GB), you still have over 80 mods that are incredibly small in size to manually download when prompted in Wabbajack. If you don't like this, get Nexus Premium I dunno.


## Updating the list

You can update the list the same way you install it, just be sure to check [the changelog](https://github.com/Maelstrom8/CalradiaUnderFire/blob/main/Changelog.md) first. **DO NOT** manually update mods, unless you know what you're doing and you know how I made them, which you likely don't. I changed some mods around a little, so if you update them manually.. there could be an issue (eg. the RBM patches section)

Also, until Stock Game is available, every update you will have to change the MO2 paths, mainly for Novus Launcher.


# Post Installation Setup 

### First Time Setups

If you haven't done these steps, do them. Go to where you installed the list, and find the folder named **GAME FILES FOLDER** - open them up, you will see two folders, `Configs` and `NovusLauncher`

- Copy the **NovusLauncher** folder into the game's [Root Game Directory](https://i.imgur.com/R4HCPAh.png). Example provided.
- Copy the **Configs** folder into the game's [User Documents Directory](https://i.imgur.com/xgL062d.png). Example provided.

Since I don't use the Stock Game folder, as it's not supported yet, paths aren't exactly saved from updates/compiles, so go do the following to quickly fix your paths:

https://user-images.githubusercontent.com/17627623/225754253-6d9c6060-e11b-47ca-9b07-776252373dd6.mp4



------------------------------------------------------------------------------------------------------
1. Using the video above, add `NovusLauncher.exe` as an executable (Use the plus sign, and navigiate to your root game folder where you extracted it, select the exe, hit apply)
2. Make sure your managed game under settings points to the base [TaleWorlds Launcher](https://i.imgur.com/F9vUdly.png) 
3. Additionally, if you **want** [Adonnay's really cool Exotic Weaponry](https://www.nexusmods.com/mountandblade2bannerlord/mods/2620) to be added to the tournament prize pool, please navigate to the incovenient location known as `C:\ProgramData\Mount & Blade II: Bannerlord\AEW` and modify `AEW.settings.xml`, so the values are *true* instead of *false*. If you don't see the folder, google "how 2 show hidden files, folders and drives".

You are generally ready to play, but there are one or two configs that aren't saved globally and have to be set every time you start a new game.

1. Launch the game by running Novus Launcher through MO2
2. Make sure `ModlistProfile` is selected under at the top of the Novus Launcher and then hit the green Play button.
3. Adjust the following:

- **Improved Garrisons**
   - Press Left Alt + G, go to `NPC Settings` and make sure it looks like [this](https://i.imgur.com/BkdUc12.jpeg). Do not enable food module(s)
- **Governors Handle Issues**
   - Make sure `AI Clan Governors Handles Issues` is enabled under the mod's MCM options.

*By the way, there reasons why some options are disabled in the MCM options of mods. Do not enable them.*

- Realistic Battle Mod
   - **The Tournament Module** is disabled because to ensure compability with **Banner Kings**
   - **Troop Overhaul** is disabled because I use the troop overhaul **Warlords Battlefield**, which use their own RBM gear.
- Xorberax Legacy
   - **Deadly Combat**, **Deadly Horse Charge** and **Friendly Fire** are disabled to ensure compatibility with **Realistic Battle Mod**
   - Also **Friendly Fire** doesn't even work
- Improved Garrisons
   - **Food Module(s)** in the Left Alt + G settings are supposed to be disabled to ensure compatibility with **Banner Kings**

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
A: Kinda hard to say, but if you must know a little about me: I'm someone who doesn't really care too much about balance and or restriction, I like power fantasy. For example, I like big dick troop trees, which is why I picked Warlords Battlefield. I don't care too much for lore friendly stuff. 

A: I can't tell you why I don't use mods, and the sort. It can be any reason, but I generally want to keep it simple, I've only tested so many mods.

#### Q: Can I enable the NSFW mods like Hot Butter? Captivity Events?
A: Sure. They work, I just don't know how well they work with this mod selection, eg Banner Kings. You're kinda your own.

#### Q: Why is my game crashing? 
A: I dunno. Do you have a Butterlib Log? Join the [Waking Dreams](https://discord.gg/wakingdreams) server, and post in the support channel. I don't do support on my readme.

### Bugs

At the time of the writing, there's only a few things to keep note of:

- Campaign AI might have some trouble with navigation, but Bannerlord is also known for being unfinish- I mean AI being brain-dead.
- I'm not sure if it's affected by my troop overhaul, but some quests that require you to go after Deserters may not show up because of it.. still testing

It's honestly hard to get a list of bugs because Bannerlord is built different, they'll come only when you play more and I haven't really.. played a lot, but if you'd like to experiment to see if you will crash, I'd appreciate people doing the following:

- Spam/use the fuck out of RTS Camera in combat, use slow motion, control your troops after death, change teams, all that
- Adjust Realistic Weather so the weather is rougher
- Adjust the Better Smithing MCM (untested)
- Dismember your enemies, go hard
- Use everything in the town menu(s) (eg tavern, trade, etc)
- Use Fourburie stuff in towns (eg the Scam button, etc)
- Try to trade and go into the smithy constantly, make stuff, make a living

Lastly.. If you run into any crashes, make sure you can reproduce it at least 3 times, click the dialog that says something like "show in Butterlib", and then hit `Upload Report as a Permalink`, copy it, join [Waking Dreams Discord Server](https://discord.gg/wakingdreams) and post in the respective support channel.

### Thanks & Credits

- Bloc for making great mods, specifically Novus Launcher
- TW for making a great framework
- Bannerlord modding community for turning a framework into a damn house
- Halgari - for making Wabbajack. Wouldn't have been possible otherwise.
- You, made you look.
