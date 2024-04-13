[![](https://www.bisecthosting.com/images/CF/ATF5/BH_NU_PROMO.webp)](https://bisecthosting.com/AMPZ?r=modrinth_ATF5)

# All The Fabric 5 | Patch Notes
### Be sure to review these changes carefully before updating your world(s).

---

## Version: 5.6

_Minecraft 1.20.1_ | _Fabric Loader 0.15.9_

### Updated:
- Applied Energistics 2 (15.0.20 → 15.1.0)
- Ad-Astra: Giselle Addon (6.1 → 6.5) 
- Architectury API (9.1.12 → 9.2.14)
- Balm (7.2.1 → 7.2.2)
- Bookshelf (20.1.8 → 20.1.9)
- Botarium (2.3.2 → 2.3.3)
- Bewitchment (1.20-7 → 1.20.8)
- BetterTrims (2.2.3 → 2.3.0)
- CC: Tweaked (1.109.5 → 1.110.2)
- Chisel Reborn (1.6.0 → 1.6.1)
- Cooking for Blockheads (16.0.1 → 16.0.3)
- Controlify (2.0.0-beta.1 → 2.0.0-beta.2)
- DrippyLoadingScreen (3.0.1 → 3.0.2)
- Dungeons and Taverns (3.0.3 → 3.0.3.fix)
- Elytra Trims (2.0.0-beta.4 → 2.1.1)
- Fabric API (0.91.1 → 0.92.1)
- Fabric Language Kotlin (1.10.17 → 1.10.19)
- FancyMenu (3.1.0 → 3.1.4)
- Flan (1.9.0 → 1.9.1)
- Jade (11.7.0 → 11.8.0)
- JourneyMap (5.9.18 → 5.9.20)
- Konkrete (1.8.0 → 1.8.1)
- Lootr (0.7.29.75 → 0.7.30.77)
- Melody (1.0.1 → 1.0.4)
- Macaw's Bridges (2.1.0 → 3.0.0)
- Puzzles Lib (v8.1.16 → v8.1.17)
- Tips (12.0.4 → 12.0.5)
- Trample No More (13.0.2 → 13.0.3)
- Polymorph (0.49.1 → 0.49.3)
- Roughly Enough Items (12.0.684 → 12.0.697)

### Changed/Fixed
- Due to changes in Macaw's Bridges v3.0.0, bridges may appear distorted. To fix this, place a block above or next to the affected bridge or stairs, or break and replace them to trigger an update for neighboring bridges.
- Added new types of bridge:
  - Bridge Torch & Lantern
  - Bridge Piers
  - Red Asian Bridge + Stairs
  - Glass Bridge + Stairs
- Added [ComputerCraft Create](https://modrinth.com/resourcepack/ccc) resource pack by default.
- Fixed void/dupe when cell is removed from ME chest while the menu is open.
- Fixed text alignment for loading screen text.
- Fixed "Empty or non-existent pool: Minecraft:witch_hut/foundation" error.
- Fixed some UI assets not displaying on Linux devices.
- Fixed DualSense left_stick_up icon being broken.
- Fixed JourneyMap not updating properly for some users.
- Made the title screen splash.txt behave like it does for vanilla Minecraft.
- Improved bridge memory usage around 80-90%.
- Enhanced the visibility of the pack version button to clearly indicate its clickable nature.

### Added:
- Create
- Create Air Fabric
- Create: Steam 'n' Rails
- Create: Diesel Generators
- Create Slice & Dice
- Blur
- Concurrent Chunk Management Engine

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Fabric-5)

---

## Version: 5.5

_Minecraft 1.20.1_ | _Fabric Loader 0.15.7_

### Updated:
- Applied Energistics 2 (15.0.20 → 15.0.21)
- Ad Astra (1.15.16 → 1.15.18)
- Botarium (2.3.1 → 2.3.2)
- BetterTrims (2.0.5 → 2.2.3)
- Drippy Loading Screen (2.2.5 → 3.0.1)
- Elytra Trims (1.4.4 → 2.0.0-beta.4)
- FancyMenu (2.14.10-2 → 3.1.0)
- Fabric API (0.9.1.0 → 0.9.1.1)
- Flan (1.8.8 → 1.9.0)
- Iris Shaders (1.6.11 → 1.6.17)
- Iron Chests (2.0.0 → 2.0.2)
- Indium (1.0.27 → 1.0.30)
- Konkrete (1.7.0 → 1.8.0) 
- Macaw's Furniture (3.2.1 → 3.2.2)
- Puzzles Lib (8.1.11 → 8.1.16)
- Resourceful Lib (2.1.20 → 2.1.23)
- Reese's Sodium Options (1.6.5 → 1.7.2)
- Sodium (0.5.3 → 0.5.8)
- Sodium Extra (0.5.1 → 0.5.4)

### Changed/Fixed
- Please note this update will break the following items from the Ad Astra, you will need to replace them back after updating to this build:
  - Sliding Doors
  - Launch Pads
  - Cables/Fluid Pipes
  - All machines will lose their items, energy, and fluid contents.
- Addressed the issue with the Tech Reborn Elevator block preventing upward movement ([#2](https://github.com/AMPZNetwork/All-The-Fabric-5/issues/2)).
- Fixed energy cells keeping chunks loaded forever.
- Corrected the application of Iron Mining Speed to all tools on all blocks.
- Resolved a crash related to the Fire Charge effect.
- Prevented game server crashes caused by placing CC blocks on the location of removed Furniture blocks.
- Rectified display inconsistencies with the title bar pack icon, particularly on MacOS.
- Added a convenient "continue" button to the main menu for quick access to the last saved game or server.
- Included a Discord button on the main menu for easier access.
- Certain items from the ad astra collection may need replacement after this update due to underlying changes.
- Updated the server IP from `atfabric5.ampznetwork.com` to `atfb.ampznetwork.com`.
- Implemented a news/update section within the main menu for important announcements and updates.

### Added:
- Fabricae Ex Nihilo
- Industrial ReZolution
- Emojuful
- Continue
- NetherPortalFix
- Extreme Sound Muffler

### Removed:
- Industrial Revolution
- Searchables
- BackSlot

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Fabric-5)

---

## Version: 5.4 (HotFix)

_Minecraft 1.20.1_ | _Fabric Loader 0.14.25_

### Updated:
- Ad Astra (1.15.9 → 1.15.16)
- CC: Tweaked (1.109.3 → 1.109.5)

### Changed/Fixed
- Addressed an issue with keybinds displaying as `C+Keybind` when attempting to modify them.
- Rectified an issue with REI occasionally failing to display ingredients for the Ad Astra mod.
- Resolved a server-side crash occurring with Ad Astra.

### Removed:
- Controlling

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Fabric-5)

---

## Version: 1.3.1

_Minecraft 1.20.1_ | _Fabric Loader 0.14.25_

### Updated:
- Applied Energistics 2 (15.0.18 → 15.0.20)
- Ad Astra (1.15.5 → 1.15.9)
- Bewitchment (1.20-6 → 1.20.7)
- Botarium (2.2.1 → 2.3.1)
- Resourceful Config (2.1.1 → 2.1.2)

### Changed/Fixed
- Resolved the infinite update loop in the quantum bridge.
- Addressed a server crash associated with the poppet shelf.
- Rectified an issue causing ATLauncher server files to fail during launch.
- Corrected the phenomenon of lava transforming into ice in outer space.
- Updated the Modrinth button URL to direct users to our recently established Modrinth Organization page.

### Added:
- Ad-Astra: Giselle Addon

### Removed:
- Pack/Rule Menus
- ImmediatelyFast
- Statement
- Lanterns Belong on Walls

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Fabric-5)

---

## Version: 1.3

_Minecraft 1.20.1_ | _Fabric Loader 0.14.25_

### Updated:
- Applied Energistics 2 (15.0.15 → 15.0.18)
- Applied Energistics 2 Wireless Terminals (15.1.5 → 15.2.1)
- Balm (7.1.4 → 7.2.1)
- Better Advancements (0.3.2.161 → 0.3.2.162)
- Bookshelf (20.1.6 → 20.1.8)
- CC: Tweaked (1.109.0 → 1.109.3)
- Cinderscapes (4.0.9 → 4.0.10)
- Cloth Config API (11.1.106 → 11.1.118)
- CraterLib (1.0.2 → 1.1.1)
- Datapack/Gamerule Menus (1.0.1 → 1.1.0)
- Fabric Language Kotlin (1.10.16 → 1.10.17)
- Fabric Waystones (3.3.1 → 3.3.2)
- Farmer's Delight (1.4.2 → 1.4.3)
- Iris Shaders (1.6.10 → 1.6.11)
- Jade (11.6.2 → 11.7.0)
- NetherPortalFix (13.0.0 → 13.0.1)
- Oxidizing Lightning Rods (1.20.1-6 → 1.20.1-7)
- Patchouli (83 → 84)
- Pehkui (3.7.11 → 3.7.12) 
- Resourceful Config (2.1.0 → 2.1.1)
- Resourceful Lib (2.1.19 → 2.1.20)
- Roughly Enough Items (12.0.674 → 12.0.684)
- Statement (4.2.8 → 4.2.9)
- Terrestria (6.0.12 → 6.0.13)
- Traveler's Backpack (9.1.8 → 9.1.9)
- Traverse (7.0.10 → 7.0.11)
- Entity Model Features (1.1.0 → 1.2.1)
- Entity Texture Features (4.6.1 → 5.1.2)

### Changed/Fixed
- Fixed an issue where graves failed to retain inventory properly upon death in modded dimensions.
- Addressed a crash during world creation when used alongside essentials mod.
- Solved the problem of crops breaking on non-watered farmland.
- Cleaned up inconsistencies in server data.
- Potentially resolved a startup crash.
- Corrected portal linkage issues, preventing them from staying connected to return portal positions after destruction.
- Eliminated the invisible backpack bug on the server.
- Adjusted the behavior of throwing items when clicking on buttons.
- Resolved a crash triggered by holding **G** to bring up a guide on certain AE2 blocks, as reported [here](https://discord.com/channels/495506209881849856/1191719680197529600).
- REI will now default to displaying entries in name [Ascending] instead of registry [Descending] making it faster to find items.
- General performance improvements.

### Added:
- Very Many Players
- Animatica
- ImmediatelyFast

### Removed:
- Starlight

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Fabric-5)

---

## Version: 1.2

_Minecraft 1.20.1_ | _Fabric Loader 0.14.25_

#### Final Update for This Pack Until 2024, Unless a major issue arises.

### Updated:
- Ad Astra (1.15.4 → 1.15.5)
- Applied Energistics 2 (15.0.14 → 15.0.15)
- Applied Energistics 2 Wireless Terminals (15.1.3 → 15.1.5)
- BetterTrims (2.0.4 → 2.0.5)
- CC: Tweaked (1.108.4 → 1.109.0)
- ClearDespawn (1.1.13 → 1.1.15)
- Elytra Trims (1.4.1 → 1.4.4)
- Emerald Equipment (1.0.8 → 1.1.0)
- Fabric Language Kotlin (1.10.13 → 1.10.16)
- Fabric API (0.90.7 → 0.91.0)
- JourneyMap (5.9.16 → 5.9.18)
- Iron Chests (2.0.1 → 2.0.0)
- Patchouli (81 → 83)
- Puzzles Lib (8.1.8 → 8.1.11)
- Resourceful Lib (2.1.16 → 2.1.19)

### Changed/Fixed
- Fixed an issue with blocks not mining when using iron trim.
- Fixed launchpad breaking from liquids.
- Fixed launchpad being pushed by pistons.
- Fixed Netherite chest particles not showing.
- Fixed a crash when doing a resource reload.

### Added:
- Quarry Reborn
- Polymorphic Energistic

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Fabric-5)

---

## Version: 1.1

_Minecraft 1.20.1_ | _Fabric Loader 0.14.24_

### Updated:
- Applied Energistics 2 Wireless Terminals (15.1.2 → 15.1.3)
- Cinderscapes (v4.0.8 → v4.0.9)
- Fabric Waystones (3.1.3 → 3.3.1)
- Jade Addons (5.2.2 → 5.2.3)
- JourneyMap (5.9.15 → 5.9.16)
- Puzzles Lib (v8.1.8 → v8.1.5)
- Resourceful Lib (2.1.13 → 2.1.16)
- Terrestria (v6.0.11 → v6.0.12)
- Tips (12.0.3 → 12.0.4)
- Traverse (v7.0.9 → v7.0.10)
- Entity Model Features (1.0.2 → 1.1.0)
- Entity Texture Features (4.6 → 4.6.1)

### Changed/Fixed
- Added missing Flan mod.
- Fixed Official Server badge clashing with No Chat Report.
- Fixed a dupe bug with farmers delight.
- Fixed Fullscreen map issues on Mac Retina displays.
- Fixed a Server disconnect when packet is sent too early.
- Fixed a rare screen crash when the game is opened using a controller.
- Improved the server renting experience when using our partner's in-game service: Modpack detection is now automated during checkout.
- Improved PS4 and PS5 controller imput.

### Added
- Macaw's Furniture

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Fabric-5)

---

## Version: 1.0

_Minecraft 1.20.1_ | _Fabric Loader 0.14.24_

- Initial Release.

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Fabric-5)

---
