<div align="center">
    <img src="2022-03-17_03.29.56.png"/>
</div>


# Minecraft Dekhere Server by Nineria

Author: `Nineria` 

## Requirements
### Resource Pack
- Excalibur 1.18.1: [Download](https://www.mediafire.com/file/zin3cz824v8g55e/Excalibur_V1.18.1.zip/file
)

### Shader (Optional)
- OptiFine 1.18.2: [Download](http://adfoc.us/serve/sitelinks/?id=475250&url=http://optifine.net/adloadx?f=preview_OptiFine_1.18.2_HD_U_H6_pre1.jar&x=ec24)
- SEUS-Renewed: [Download](https://sonicether.com/shaders/download/renewed-v1-0-1/)

## How to play?
1. Install `Excalibur` Resource Packs
    - Download [Excalibur](https://www.mediafire.com/file/zin3cz824v8g55e/Excalibur_V1.18.1.zip/file
) ResourcePack File.
    - First Method (Recommended): Install Resource Packs while in game.
      - In game start menu
      - Click `Options...`.
      - Click `Resource Packs...`.
      - Click `Open Pack Folder`.
      - Copy `Excalibur_V1.18.1.zip` file and put it in the folder.
    - Second Method: Install Resource Packs in `AppData\Roaming\.minecraft`.
      - Go to `C:\Users\<username>\AppData\Roaming\.minecraft\resourcepacks`.
      - Copy `Excalibur_V1.18.1.zip` file and put it in the folder.

2. Install OptiFine 1.18.2 (Optional)
    - Download [OptiFine](http://adfoc.us/serve/sitelinks/?id=475250&url=http://optifine.net/adloadx?f=preview_OptiFine_1.18.2_HD_U_H6_pre1.jar&x=ec24)
    - Install OptiFine by double click on `OptiFine_1.18.2_HD_U_H6.jar`.
    - Click `Install` wait till finish and done.

3. Install `SEUS-Renewed` Shader (Optional)
    - Download [SEUS-Renewed](https://sonicether.com/shaders/download/renewed-v1-0-1/)
    - First Method (Recommended): Install Shader while in game
      - In game start menu
      - Click `Options...`
      - Click `Video Setting...`
      - Click `Shaders...`
      - Click `Shaders folder`
      - Copy `SEUS-Renewed-v1.0.1.zip` file and put it in the folder.
    - Second Method: Install Shader in `AppData\Roaming\.minecraft`.
      - Go to `C:\Users\<username>\AppData\Roaming\.minecraft\shaderpacks`.
      - Copy `SEUS-Renewed-v1.0.1.zip` file and put it in the folder.

## How to install mods?
### Recommended mods
- [3dskinlayers-fabric-1.4.2-mc1.18.2](https://www.curseforge.com/minecraft/mc-mods/skin-layers-3d/download/3672241).
- [appleskin-fabric-mc1.18.2-2.4.0](https://www.curseforge.com/minecraft/mc-mods/appleskin/download/3686478).
- [Autofish-0.9.4-fabric-mc1.18](https://www.curseforge.com/minecraft/mc-mods/autofish/download/3586323).
- [eating-animation-1.5](https://www.curseforge.com/minecraft/mc-mods/eating-animation-fabric/download/3651790).
- [fabric-api-0.48.0+1.18.2](https://www.curseforge.com/minecraft/mc-mods/fabric-api/download/3689020).
- [iris-mc1.18.2-1.2.2-build.32 (Optional for shader only)](https://www.curseforge.com/minecraft/mc-mods/irisshaders/download/3687476).
- [lambdynamiclights-2.1.0+1.17](https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights/download/3541670).
- [OptiFine_1.18.2_HD_U_H6 (Optional for shader only)](http://adfoc.us/serve/sitelinks/?id=475250&url=http://optifine.net/adloadx?f=OptiFine_1.18.2_HD_U_H6.jar&x=2bc6).
- [sodium-fabric-mc1.18.2-0.4.1+build.15 (Recommended)](https://www.curseforge.com/minecraft/mc-mods/sodium/download/3669187).

### Installation
1. Download the Fabric installer from [fabric-installer-0.10.2](https://maven.fabricmc.net/net/fabricmc/fabric-installer/0.10.2/fabric-installer-0.10.2.exe).
2. Download the IRIS INSTALLER from [Download Universal JAR](https://github.com/IrisShaders/Iris-Installer/releases/download/2.0.3/Iris-Installer-2.0.3.jar). (Optional for shader only)
   1. Open the `Iris-Installer-2.0.3.jar` file 
   2. Check on `Install as Fabric Mod` box. After that click `Install`
3. Open the `fabric-installer-0.10.2.jar` file and press `Install`. A new game version and profile will be created in the launcher's menu, which you can now use to launch `Fabric`.
4. Download all the `Recommended mods` above.
5. Go to `C:\Users\<username>\AppData\Roaming\.minecraft\mods`.
6. Copy all the Mods and put it in `mods` folder. 
7. launch the game.
  
## Install and setup Server
### How to install and setup minecraft server?
- search on the internet.

### Minecraft Server 1.18.2
- Download [minecraft_server.1.18.2.jar](https://launcher.mojang.com/v1/objects/c8f83c5655308435b3dcf03c06d9fe8740a77469/server.jar).

### Spigot 1.18.2
- Download [Spigot](https://download.getbukkit.org/spigot/spigot-1.18.2.jar).

### Plugin
- AureliumSkills-Beta1.2.10
- BetterSleeping
- ChestSort-13.0.2
- DeathDrops
- EliteMobs
- ExecutableItems-4.1.5.6
- GSit-1.0.7
- LevelledMobs-3.3.3_b604
- LPC
- LuckPerms-Bukkit-5.4.9
- OtherDrops3.2.6
- PlaceholderAPI-2.11.1
- ProtocolLib
- ServerListPlus-3.4.8-Universal
- SetHome-5.1.2
- SkinsRestorer
- TitleManager-2.3.6
- TreeCapitator-1.0-RELEASE
- worldedit-bukkit-7.2.9
- worldguard-bukkit-7.0.7-dist

## Command
1. Start Minecraft server:

        java -Xms2G -Xmx2G -jar .\spigot-1.18.2.jar nogui

2. Start ngrok tunnel:
    - Download [ngrok](https://ngrok.com/download)
    - Copy `ngrok.exe` file and put it in mincraft server directory
    - Add authtoken 
    
            ngrok.exe authtoken <token>
    
    - Start a tunnel
    
            ./ngrok.exe tcp 25565 --region ap

## Server IP address and Port (Example)
 
    0.tcp.ap.ngrok.io:19688



