# Best free CSGO cheats ![CS:GO]
[//]: <> (!![App menu]("link do screena samego menu"))

## Features

* **Glow** - render glow effect on entities
* **Misc** - miscellaneous features
* **Config** - JSON-based configuration system

<details>
<summary>Features in depth</summary>

* **Glow** - render glow effect on entities

    *Allies, Enemies, Planting (player planting bomb), Defusing (player defusing bomb), Local player, Weapons (dropped weapons), C4, Planted C4, Chickens* **/** *All, Visible, Occluded*

    * **Enabled** - on / off master switch
    * **Health based** - color is based on player's hp
    * **Rainbow** - change color frequently
    * **Thickness** - outline thickness
    * **Alpha** - outline alpha
    * **Style** - glow style [*0*-*3*]

* **Misc** - miscellaneous features
    * **Auto strafe** - automatically strafe in air following mouse movement
    * **Bunny hop** - automatically simulate space bar press / release while jump button is being held; increases movement speed
    * **Moonwalk** - break walking animation

* **Config** - JSON-based configuration system
    * **Create config** - create new configuration file
    * **Reset config** - restore default configuration settings (does not touch saved configuration)
    * **Load selected** - load selected configuration file
    * **Save selected** - save selected configuration file
    * **Delete selected** - delete selected configuration file
</details>

# Hooks
* **createmove**
* **reset**
* **lock cursor**
* **dme**
* **cl move**

# Comments navigation
* **@note:**
* **@ida:**
* **@xref:**
* **@credits:**
* **@fix-me:**

# Dependencies
 * **[imgui]**(https://github.com/ocornut/imgui)
 * **[minhook]**(https://github.com/TsudaKageyu/minhook)

### Cloning
The very first step in order to compile csgo_kns is to clone this repo from GitHub to your local computer. Git is required to step futher, if not installed download it [here](https://git-scm.com). Open git bash / git cmd / cmd and enter following command:
```
git clone https://github.com/
```
`csgo_kns` folder should have been succesfully created, containing all the source files.

