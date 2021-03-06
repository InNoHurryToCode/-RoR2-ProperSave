# Description
Saves your progress at the start of each stage. You can leave run as soon as the stage started.
Only 1 save file for each profile for a singleplayer. If you die, the save will be deleted.

# Multiplayer support
Only the host must have this mod for it to work.
A `Load` button will be active if you are host and was found suitable save file (if save file has the same set of players as in the current lobby).

# Game modes support
Each game mode (for now `Classic` and `Eclipse`) has it's own save files, so that you can switch between game modes and not losing your progress.

# Installation
- Install dependencies.
- Put `ProperSave` folder into `plugins` folder.

# Known issues
I tried to save all necessary data so that when you load the game would continue as it should have been without saving.

- Minions would respawn at different positions each time you load the same save file. It's not big of an issue, and there is nothing I can do about it.
- I've not tested this mod much with achievements unlocking, but for most, if not all cases, it should be working as intended. 

# Changelog

**2.2.2**

* Fixed `Load` button being active when returned to lobby after death.

**2.2.1**

* Updated langauge stuff

**2.2.0**

* Updated for `RoR2` release.
* Removed `Continue` button from the main menu (for game modes support).
* Game modes support.

**2.1.1**

* Fixed a bug: when entering the lobby when using a gamepad is causing the lobby glitches.

**2.1.0**

* Added `StartingItemGUI` support. (Items adding disabled while loading the game). Requested by `Thunderer1101` on GitHub.

**2.0.0**

* Changed save files structure, because of that, old version saves would be ignored, so consider end saved runs before updating.
* Added multiplayer support.
* Fixed an issue with `lockbox` from `Rusted key` not spawned when loading game.
* Saving some artifacts info for consistent gameplay.
* Fixed an issue for characters added by mods, when their loadouts weren't saved.
* Some minor fixes

**1.1.0**

* Added TemporaryLunarCoins mod support. When loading game lunar coins will be restored.

**1.0.1**

* Fixed crash when the mod was installed using mod managers.
* Saving lunar coins drop chance.

**1.0.0**

* Mod release.