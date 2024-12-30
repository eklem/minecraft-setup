# minecraft-setup
Just making local Minecraft machine setup easier. Mac mini and playit.gg.


## Setup of Mac Mini + connecting

* **Server:** System Preferences / Sharing / Remote Management -> on
* **Laptop:** Finder, choose Go / Connect to server and type vnc://minicraft

### On server:

* Safari: open [playit.gg](https://playit.gg/), log in and download plugin.
  Or download on laptop and scp as described further down.
* Minecraft server fork and version: Spigot v1.21.3

### Mods/plugins:

* [Playit.gg](https://playit.gg/) - You need to log in to download it.
* [ClickVillagers - Files - Minecraft Mods - CurseForge](https://www.curseforge.com/minecraft/mc-mods/clickvillagers/files/all?page=1&pageSize=20&version=1.21.1)
* [GappleOptions - Files - Minecraft Bukkit Plugins - CurseForge](https://www.curseforge.com/minecraft/bukkit-plugins/gapple-options/files/4598440)
* [Craftable Cobweb - The Craftables Series - Files - Minecraft Mods - CurseForge](https://www.curseforge.com/minecraft/mc-mods/craftable-cobweb-the-craftables-series/files/all?page=1&pageSize=20&version=1.21.1)
* [Bliss SMP Plugin | Spigot/Paper | SpigotMC - High Performance Minecraft](https://www.spigotmc.org/resources/bliss-smp-plugin-spigot-paper.113775/)
* A dependency of Bliss SMP Plugin is [Executable Items Premium](https://www.spigotmc.org/resources/5-custom-items-plugin-executable-items-add-infinite-abilities-to-your-items.83070/)

Plugins that needs to be downloaded when logged in needs to be scp'ed over to the server. Like this:

```console
scp ./playit-minecraft-plugin.jar eklem@minicraft:/Users/eklem/minecraft/plugins/
```
