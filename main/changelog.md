# Changelog

All changes of Tephra will be documented in this file.  
Since v23, the versioning adheres to [Semantic Versioning]

## v24.1 (27.01.2021)
### Added

- Trajectories Module
- Boxes to sliders in ClickGUI

## v24.0 (25.01.2021)
### Added

- added ItemPhysics Module
- added NoHurtCam Module
- Customizations to ArrayList (e.g. Rainbow Speed)
- added a Loading Screen bar to visualize progress
- added Chams Customizations (Players, Mobs)
- added a ToolTip to every Module in the ClickGUI
- add OldAnimations mod (e.g. old Blockhit, old Item Render etc.)
- added Lines to particles in the Main Menu

### Fixed

- Fixed Entities Setting in ESP Module
- Fixed small visual Updates in the Main Menu
- Fixed Items not drawing behind Walls while NameTags is enabled
- Change AutoClicker to use CPS instead of milliseconds
- Fixed ArrayList crash when enabling / disabling Modules too fast

### Changed

- The Client now runs on Minecraft version 1.8.8
- Modules are now alphabetically sorted in the ClickGUI
- ClickGUI Settings and main Panels now have an outline

### Removed

- Parkour Module due to not having a purpose and not bypassing common AntiCheats anymore
- OldItemRender module, now merged into OldAnimations module
- XRay Module for complications with new 1.8.8 render engine, will be readded with customizations later on
- Removed AltManager due to causing Session Issues
- Removed Ingame Changelog for better transparency (moved to GitHub)



## v23.1 (07.01.2021)

### Fixed

- Game crashing bug on startup
- Bossbar not displayed correctly

## v23.0 (06.01.2021)

### Added

- Added an Ingame Changelog screen
- Added saving ClickGUI values
- Added indication in ClickGUI whether Module has settings or not
- Added AltManager in menu tab
- Added ChestESP options to now include Hoppers, Dispensers etc.

### Fixed

- Fixed ClickGUI settings Tab overlapping
- Fixed Hungerbar randomly dissapearing
- Fixed being Stuck in Air while SafeWalk is enabled

## v22 (01.01.2021)

### Added

- Added NoChatRect module
- Added a rainbow ArrayList option

### Fixed

- Fixed the FileSystem sometimes not saving values correctly


## v21 (31.12.2021)

### Added

- Added a custom Loading Screen
- Added new Menu Settings: GitHub, and a future AltManager

### Fixed

- Menu Screens not resetting panorama when entered / exited

### Changed

- UpdateManager for better visual clarity

## v20 (29.12.2020)

### Fixed

- Game crashing bug in HUD when entering Nether

## v19 (29.12.2020)

### Added

- Added DiscordRPC Compatibility

### Removed

- HUD Themes: Beta, Simple for internal rewrite

## v18 (27.12.2020)

### Fixed

- Various UI Bugs and misalignments

### Changed

- Chams to now being Player only - customization soon
- ArrayList now being on the left side

## v17 (17.12.2020)

### Added

- Added a sliding ArrayList to simple Theme

### Fixed

- Watermark in Simple Theme being off by 2px

## v16 (15.12.2020)

###  Added

- Added new Player Category
- Added AutoRespawn Module
- Added BedAura Module
- Added a built in Update System
- Added an Update Manager to download new versions
- new HUD Themes: Beta and Simple

### Changed

- Previous HUD Theme now called: Tephra
- Default HUD Theme now: Tephra
- InventoryWalk moved to Player Caategory
- ChestStealer moved to Player Category

### Removed

- Changelog System for being slow and inefficient
- TabGUI for not serving the purpose i wanted to fullfil with it

## v15 (09.07.2019)

### Fixed

- Game crashing bug at startup

## v14 (09.07.2019)

### Fixed

- Various UI bugs

### Changed

- how the IngameHUD works for better performance

## v13 (01.06.2019)

### Added

- a Changelog for better update transparency

### Fixed

- fixed Main menu displaying wrong version
- fixed Performance Issues when opening ClickGUI

## v12 (12.05.2019)

### Added

- added new Main menu, replacing the default one
- added XRay Module

### Changed

- changed the ingame HUD, Watermark now being smaller and on the top left
- changed Module colors to category specific ones

## v11 (16.04.2019)

### Added

- added Parkour Module
- added AirStrafe Module

## v10 (03.03.2019)

### Added

- added NoBob module

## v9 (04.02.2019)

### Added

- Added ItemESP module

### Fixed

- Fixed ESP not drawing correctly

## v8 (22.12.2018)

### Fixed

- Fixed visual TabGUI bugs

## v7 (20.12.2018)

### Fixed

- Fixed TabGUI not drawing Modules correctly
- Fixed TabGUI switching Module places
- Fixed TabGUI inconsistently toggling modules

## v6 (19.12.2018)

### Added

- added ClickGUI values (e.g. GuiRed, GuiBlue etc.)
- added TabGUI for better access to modules

## v5 (4.08.2018)

### Fixed

- fixed NameTags not drawing Armor correctly sometimes

## v4 (12.05.2018)

### Added

- Added NameTags module

## v3 (26.03.2018)

### Added

- added ChestESP Module

## v2.1 (16.01.2018)

### Fixed

- fixed ClickGUI crashing when opened in other dimensions

## v2 (12.01.2018)

### Added

- added NameTags module

### Changed

- Updated ClickGUI for better visual clarity
- now runs on Minecraft 1.8
- complete internal Rewrite

### Removed

- removed LabyMod as dependency

## v1 (22.10.2017 - Initial Release)

Tephra v1, a ghost client for LabyMod v2.7.75 for Minecraft 1.8.9

### Added

- Added AutoClicker module
- Added Sprint module
- Added SafeWalk module
- Added Eagle module
- Added Chams module
- Added ESP module
- Added basic HUD implementation, containing Coordinates and FPS
- Added basic ClickGUI implementation






[Semantic Versioning]: http://semver.org/spec/v2.0.0.html
