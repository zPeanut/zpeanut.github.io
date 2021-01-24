# Changelog

All changes of Tephra will be documented in this file.  
Since v24, the versioning adheres to [Semantic Versioning]


## 24.0.0  
28th January 2021
### Added  

- added ItemPhysics Module
- added NoHurtCam Module
- Customizations to ArrayList (e.g. Rainbow Speed)
- added a Loading Screen bar to visualize progress
- added Chams Customizations (Players, Mobs)
- added a ToolTip to every Module in the ClickGUI
- add OldAnimations mod (e.g. old Blockhit, old Item Render etc.)
- added Lines to particles in the Main Menu


### Changed 

- The Client now runs on Minecraft version 1.8.8
- Modules are now alphabetically sorted in the ClickGUI
- ClickGUI Settings and main Panels now have an outline

### Removed

- Parkour Module due to not having a purpose and not bypassing common AntiCheats anymore
- OldItemRender module, now merged into OldAnimations module
- XRay Module for complications with new 1.8.8 render engine, will be readded with customizations later on

### Fixed

- Fixed Entities Setting in ESP Module
- Fixed small visual Updates in the Main Menu
- Fixed Items not drawing behind Walls while NameTags is enabled
- Change AutoClicker to use CPS instead of milliseconds
- Fixed ArrayList crash when enabling / disabling Modules too fast


[Semantic Versioning]: http://semver.org/spec/v2.0.0.html
