# 👋 Hey, I’m Ragex / Kippy!

I’m a Java developer focused primarily on **Minecraft Forge modding**, especially the **1.7.10 ecosystem**.

A lot of my work involves maintaining, modernizing, optimizing, and extending large legacy mods that were never designed to work together. I regularly work with old or undocumented codebases, renderer internals, networking, coremods, compatibility layers, server systems, and large modpack environments.

I maintain projects for **[Deadhour](https://github.com/mchelioverdrive/Ragexs-Nuclear-Tech-GIT)**, formerly known as **Ragecraft**, alongside several standalone forks, ports, fixes, and overhauls.

---

## 🔧 What I Work On

### 🚁 Vehicle & combat systems

I develop and maintain projects around **MCHeli Overdrive** and **Hand Made Guns Overdrive**.

My work includes:

* Vehicle combat and damage systems
* Weapon behavior and gun mechanics
* Vehicle interaction with blocks and the world
* Aircraft and vehicle networking
* Collision and damage logic
* Server-side restrictions and behavior
* Multiplayer fixes
* Integration with other combat systems

Projects:

* [MCHeli Overdrive / MCHO](https://github.com/RagexPrince683/MCHOrebase)
* [Hand Made Guns Overdrive](https://github.com/RagexPrince683/GvCEXOverdrive-HandMadeGunsOverdrive)

---

### 🎮 Multiplayer, factions & gamemodes

I develop **XenoFactions**, which started as a faction and territory-control system and has grown into a larger multiplayer framework.

Recent work includes:

* Factions and territory control
* Safezones and warzones
* Server-side rule enforcement
* TDM systems
* FFA / Deathmatch systems
* Bomb gamemodes
* Buy phases
* Separate kill, point, and purchase scoring
* Utility and killstreak systems
* Gamemode-specific loadouts
* Team-aware chat
* Server administration systems

Project:

* [XenoFactions](https://github.com/RagexPrince683/xenofactions)

---

### ⚙️ Legacy mod modernization

A large part of what I do now is keeping **Minecraft 1.7.10 software usable in modern large modpacks**.

That means taking old mods and fixing things such as:

* Broken or unnecessary dependencies
* Client/server classloading problems
* Dedicated-server crashes
* Excessive memory allocation
* Rendering performance problems
* OpenGL state leaks
* Tile entity performance
* Compatibility with modern 1.7.10 optimization mods
* Fragile coremods and ASM transformers
* Broken development environments
* Old build systems
* Mod interoperability

I often try to make forks **more standalone, easier to distribute, and less dependent on abandoned libraries**.

---

### 🚀 Performance & rendering work

I have been doing significantly more profiling and performance work across legacy mods.

Recent work includes:

* Reducing temporary render allocations
* Cleaning up retained OpenGL resources
* Fixing GL state leaks
* Reducing tile entity update overhead
* Removing redundant world updates
* Optimizing animated render paths
* Fixing recursive rendering and validation logic
* Improving large-scale block rendering
* Separating shared renderer state
* Tracking down memory leaks rather than only FPS problems

A major goal is making old mods behave properly inside **large Angelica-based Forge 1.7.10 modpacks**.

---

### 🧩 Compatibility & integration

I spend a lot of time making mods coexist when they really do not want to.

This includes:

* Angelica compatibility
* Renderer compatibility
* Coremod / ASM transformer isolation
* Client-only vs dedicated-server separation
* NEI integration
* Cross-mod recipe support
* Dependency removal
* Runtime classpath fixes
* Crash debugging
* Optional integrations
* Large-modpack compatibility

One thing I care about strongly is preventing mods from modifying unrelated mods or taking ownership of systems they should not touch.

---

## 🛠 Recent Projects

### 🌿 DHPsychedelicraft

A maintained fork of Psychedelicraft focused on **performance, compatibility, bug fixes, and expansion** for modern 1.7.10 modpacks.

Recent work includes:

* Angelica compatibility
* Restricting coremod transformations to intended Minecraft classes
* Preventing transformations of unrelated mods
* Dedicated-server startup fixes
* Render transformer fixes
* Reduced rendering allocations
* OpenGL resource cleanup
* NEI recipe integration
* Drying Table recipe support
* Development mod loading
* Entity spawning/configuration fixes
* New Grow Light mechanics
* General modpack-focused cleanup

Repository:

* [DHPsychedelicraft](https://github.com/RagexPrince683/TodoangelicafixPsychedelicraft-Legacy)

---

### 🚪 MalisisDoors fork

I maintain a heavily modified **MalisisDoors 1.7.10** fork focused on performance and compatibility.

Recent work includes:

* Angelica rendering compatibility
* Fence gate and trapdoor rendering optimization
* Reduced animation allocations
* Reduced tile entity updates
* OpenGL state cleanup
* Renderer state isolation
* Fence gate recursion fixes
* Garage door placement crash fixes
* Block Mixer GUI/render fixes

Repository:

* [MalisisDoors fork](https://github.com/RagexPrince683/MalisisDoorsragecraftver)

---

### 📐 Schematica Plus Reforged

A standalone Schematica Plus fork focused on removing unnecessary legacy dependencies.

Major work includes:

* Removing the **LunatriusCore** dependency
* Replacing required LunatriusCore functionality internally
* Restoring standalone compilation and runtime behavior
* Simplifying deployment in modern 1.7.10 modpacks

Repository:

* [Schematica Plus Reforged](https://github.com/RagexPrince683/Schematica-Plusohno)

---

### 🌐 Et Futurum Requiem Reforged

My fork of Et Futurum Requiem focuses heavily on **runtime independence, compatibility, stability, and continued 1.7.10 development**.

Work includes:

* Removing unnecessary runtime dependencies
* Removing FastUtil / GTNHLib dependencies where practical
* Replacing utility-library functionality locally
* Compatibility fixes
* Spectator-system fixes
* Crash fixes
* Runtime optimization

Repository:

* [Et Futurum Requiem Reforged](https://github.com/RagexPrince683/Et-Futurum-Requiem-Reforged)

---

### 🧰 Smaller ports, forks & fixes

I also maintain or experiment with a large number of smaller legacy projects.

These include:

* [ItemBlacklistUnfucked](https://github.com/RagexPrince683/ItemBlacklistUnfucked)
* [Shader Fixer](https://github.com/RagexPrince683/Shader-fixerrc)
* [ReplayMod 1.7.10](https://github.com/RagexPrince683/ReplayMod1.7.10TEST)
* [LootableBodies 1.7.10](https://github.com/RagexPrince683/LootableBodies1.7.10fix)
* [RecipeHandler RCEdition](https://github.com/RagexPrince683/RecipeHandlerRCEDition)
* [CustomNPC+ fork](https://github.com/RagexPrince683/CustomNPC-PlusRagecraftVer)
* [ServerUtilities fork](https://github.com/RagexPrince683/ServerUtilitiesRagecraft)
* [FarPlaneTwo 1.7.10](https://github.com/RagexPrince683/FarPlaneTwo1.7.10)
* [Aqua Acrobatics 1.7.10](https://github.com/RagexPrince683/aquaacrobatics)
* [Revive Me 1.7.10](https://github.com/RagexPrince683/Revive_Me1.7.10)
* [Controlled Burn 1.7.10](https://github.com/RagexPrince683/Controlled-Burn1.7.10)

Some are full forks, some are ports, and some exist because I needed one very specific thing fixed and nobody else was going to do it.

---

## ☢️ Technology, chemistry & nuclear systems

I also work with **HBM's Nuclear Tech** and related forks.

My work in this area focuses on:

* Nuclear reactor systems
* Materials and metallurgy
* Chemistry
* Industrial processing
* Fuels
* Large crafting chains
* Progression
* More grounded technical mechanics

**[Ragex's Nuclear Tech](https://github.com/mchelioverdrive/Ragexs-Nuclear-Tech-GIT)** is my broader overhaul/fork work in this area.

---

## 🌍 Deadhour

**Deadhour**, formerly **Ragecraft**, is the ecosystem that ties much of my work together.

It is a combined-arms Minecraft project built around:

* Infantry combat
* Vehicles
* Aircraft
* Weapons
* Team combat
* Factions
* Competitive gamemodes
* Server-side systems
* Large-scale mod integration

A lot of my forks exist because Deadhour pushes Minecraft 1.7.10 and its mods far beyond the environments they were originally designed for.

---

## 🧠 Technical Experience

My main areas of experience include:

* **Java**
* **Minecraft Forge 1.7.10**
* Large legacy Java codebases
* Forge events and hooks
* Client/server separation
* Networking and packets
* Tile entities
* NBT
* Rendering
* OpenGL debugging
* Performance profiling
* Memory/allocation debugging
* Coremods
* ASM / bytecode transformation debugging
* NEI integration
* Dependency removal
* Gradle / legacy build systems
* Reverse engineering undocumented behavior
* Mod compatibility
* Crash analysis
* Server-side game systems

I am especially comfortable entering large codebases with poor documentation and figuring out **why something behaves the way it does before changing it**.

---

## 🎯 What I Care About

I want to:

* Keep ambitious **Minecraft 1.7.10** development alive
* Make abandoned mods maintainable again
* Reduce unnecessary dependency chains
* Make large modpacks more stable
* Improve performance instead of accepting legacy overhead
* Build deeper multiplayer systems
* Push vehicle and firearm gameplay further
* Make old mods cooperate with modern optimization projects
* Build complete gameplay ecosystems instead of collections of unrelated mods

I would rather substantially overhaul an existing system than add another shallow feature that does not interact with anything else.

---

## 📌 Main Projects

| Project                                                                                            | Focus                                                    |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| [MCHeli Overdrive](https://github.com/RagexPrince683/MCHOrebase)                                   | Vehicles, aircraft, combat, networking                   |
| [Hand Made Guns Overdrive](https://github.com/RagexPrince683/GvCEXOverdrive-HandMadeGunsOverdrive) | Firearms and combat systems                              |
| [XenoFactions](https://github.com/RagexPrince683/xenofactions)                                     | Factions, TDM, FFA, Bomb, multiplayer systems            |
| [DHPsychedelicraft](https://github.com/RagexPrince683/TodoangelicafixPsychedelicraft-Legacy)       | Performance, Angelica compatibility, fixes and expansion |
| [Et Futurum Requiem Reforged](https://github.com/RagexPrince683/Et-Futurum-Requiem-Reforged)       | Modern Minecraft features for 1.7.10                     |
| [MalisisDoors fork](https://github.com/RagexPrince683/MalisisDoorsragecraftver)                    | Rendering, performance and compatibility                 |
| [Schematica Plus Reforged](https://github.com/RagexPrince683/Schematica-Plusohno)                  | Standalone Schematica Plus without LunatriusCore         |
| [Ragex's Nuclear Tech](https://github.com/mchelioverdrive/Ragexs-Nuclear-Tech-GIT)                 | Nuclear, chemistry and industrial systems                |
| **[Deadhour](https://www.curseforge.com/minecraft/modpacks/deadhour)**                             | Combined-arms modpack/server ecosystem                   |

---

## ☕ Support My Work

I spend a lot of time maintaining, fixing, and expanding legacy Minecraft mods, often working with abandoned codebases and complex compatibility issues.

If you enjoy my projects or have benefited from my work, consider supporting continued development through Ko-fi.

**[☕ Support me on Ko-fi](https://ko-fi.com/Y8Y5ZHL41)**

Donations are entirely optional. Every bit of support helps me dedicate more time to maintaining and expanding these projects.

## 📺 YouTube

I occasionally post development, Minecraft, installation, and other content on YouTube:

[https://www.youtube.com/@RagexPrince683](https://www.youtube.com/@RagexPrince683)

---

## 📫 Contact

**Discord:** `aanalystt`

You can also contact me through **GitHub Issues / Discussions** on the relevant project.

---

## ⚠️ A note about my projects

A lot of my work involves forcing old mods to behave in ways they were never designed for.

That can mean digging through undocumented systems, replacing abandoned dependencies, intercepting behavior, fixing bytecode transformers, rewriting integration layers, or tracking down problems that only appear when dozens or hundreds of mods are installed together.

If you want to contribute, feel free.

**Just keep it open source.**
