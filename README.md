# The Best Performance (and Quality-of-Life) Mods for Minecraft 1.21
This is the most up-to-date list of the mods that I personally use while playing Minecraft. From tripling performance to revamped menus, these mods improve your gameplay experience without changing vanilla gameplay.

If you see an ❌ next to a version (eg: "1.21.5 ❌"), that means that the mod is not updated for that version (as far as I know). If there is a ✔, it is updated. Sometimes, mods work for new versions but don't say it on the Modrinth page. If so, check my list to see if I tested it.

Want my mod configs? [Here you go](https://drive.google.com/file/d/1amMFKcRSWMBUf3ZmyKpcby5JMFJUhL8b/view)

## You must install [Fabric](https://fabricmc.net) to run these mods
Don't know how? Watch [my tutorial](https://www.youtube.com/watch?v=O7V7jBo5-6k&t=26s).

# FAQ
### Why can't I download these all in one folder? Why do I have to download them all individually?
* Not every mod is legally allowed to be distributed in modpacks. Some mods' license agreements say you can't include their mod in a modpack without explicit permission, and meticulously creating agreements really isn't worth it here. Plus, mods get outdated quickly, and, unlike in a standard modpack, it's important to keep all of these mods updated. So, I don't want to make a legally questionable ZIP file full of mods that will be outdated by the next day. Downloading each mod individually is the best way to have the best in-game experience.
### Will you make a Forge/NeoForge version?
* No. This isn't a personal vendetta, I just have no interest.
### Is this mod updated for the newest version?
* Some mods will work on new versions, but won't necessarily tell you on the download page yet. Refer to my guides below to see if mods are updated.
### My game is crashing any time I load a world/server, what's going on?
* If you get a crash any time you load a world or join a server, remove the Chat Patches mod. If that fixes it, add the mod back and then delete the file "chatlog.json" file in *.minecraft\logs*. This will reset your chat history and fix the crash.
### Will these mods affect my builds/redstone/farms?
* In theory, no. I made this list with the goal of staying true to vanilla while also improving the experience. If you notice an issue with your world, slowly remove mods from your mods folder until you figure out which mod is causing an issue, and report the issue to the mod developers (or check if it has already been reported/fixed). It could also be a setting within the mod that should have been toggled, and was unintentionally impeding your experience. To avoid this, use my mod configs, linked above.

# Mods
* [Concurrent Chunk Management Engine](https://modrinth.com/mod/c2me-fabric) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Performance mod**
  * Improves the efficiency of chunk generation
* [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Performance mod**
  * Reduces your game's frame rate while you aren't focused on the window to save power and increase the performance of the rest of your computer
  * **Requires Fabric API**
* [Enhanced Block Entities](https://modrinth.com/mod/ebe) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ❌
  * **Performance mod**
  * Changes blocks like chests and beds to use block models instead of entity models, which increases performance, but also allows for better custom textures and allows them to have smooth lighting
  * **Requires Fabric API**
* [Entity Culling](https://modrinth.com/mod/entityculling) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Performance mod**
  * Makes the game not render entites you can't see to improve FPS
  * **Requires Fabric API**
* [FerriteCore](https://modrinth.com/mod/ferrite-core) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Performance mod**
  * Reduces the game's memory usage
* [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Performance mod**
  * Makes the game's FPS higher
* [Iris Shaders](https://modrinth.com/mod/iris) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Quality-of-life mod**
  * Adds support for shader packs, just like OptiFine
  * **Requires Sodium**
* [Krypton](https://modrinth.com/mod/krypton) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Performance mod**
  * Improves performance internally in [magical ways](https://github.com/astei/krypton/wiki)
* [Lithium](https://modrinth.com/mod/lithium) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Performance mod**
  * Improves performance of features like mob AI, game physics, and more internal stuff without changing vanilla gameplay
* [Memory Leak Fix](https://modrinth.com/mod/memoryleakfix) - 1.20.6 ✔ **(not needed in 1.21+ anymore)**
  * **Performance mod**
  * Fixes memory leaks that can cause the game to lag/crash
* [ModernFix](https://modrinth.com/mod/modernfix) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ❌
  * **Performance mod**
  * Fixes bugs and mproves the resource usaage and framerate of the game in many ways
* [More Culling](https://modrinth.com/mod/moreculling) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Performance mod**
  * Adds more culling to the Entity Culling mod
  * **FPS testing in my 1.21 mods video was done without this mod installed as it wasn't updated yet**
* [Nvidum](https://modrinth.com/mod/nvidium) - 1.20.6 ✔ 1.21.4 ❌ 1.21.5 ❌ ([unofficial 1.21.5 version available here](https://github.com/drouarb/nvidium/releases)]
  * **Performance mod**
  * Uses "NVIDIA OpenGL extensions" to drastically increase the performance of the game. **Only works on NVIDIA 16xx, 20xx series and higher GPUs, the mod will auto-disable if you don't have the right GPU**
  * **Requires Sodium**
* [Sodium](https://modrinth.com/mod/sodium) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Performance mod**
  * Improves your game's FPS by an order of magnitude

## Dependency Mods (you need these too)
* [Fabric API](https://modrinth.com/mod/fabric-api) - 1.20.6 ✔ 1.21.4 ✔ 1.21.5 ✔
  * **Dependency mod**
  * Necessary for almost all Fabric mods to work
## Different Types of Mods
* Performance
  * Performance mods make your game run better and smoother like increasing your frame rate or making chunks load faster
* Quality-of-life
  * Quality-of-life mods make the Minecraft experience better overall, like always displaying coordinates in game or copying screenshots to your computer's clipboard for easy access
* Dependency
  * Dependency mods are mods that are really only used to make other mods work, like how most mods require Fabric API to run, even though the mod doesn't do anything to the game on its own


