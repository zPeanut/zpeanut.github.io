# Changelog

All changes of Hydrogen are documented in this File
Hydrogen adheres to [Semantic Versioning].

## v1.9.1

released 6th Sep 2021

- added tooltips to clickgui
- fixed func_73734_a failed mixin apply on startup (thanks neyled!)
- fixed credits button in main menu being 1px longer

## v1.9

released 3rd Sep 2021

- added STap
- added BowAimbot
- added NoChatRect
- added autoclicker "type" mode (right click, left click)
- added autoclicker random ms option
- added unbind option to clickgui
- renamed "W-Tap" -> "WTap"
- renamed "aim assist" to "aimassist"
- moved WTap from movement to combat
- fixed nochatrect crashing sometimes
- mainmenu watermark is now drawn in ttf

## v1.8.3

released 27th July 2021

- fix update button not working when version is outdated

## v1.8.2

released 27th July 2021

- fix outdated check (update notification) for real now

## v1.8.1

released 27th July 2021

- fix chat dissapearing and chat history resetting when opening clickgui

## v1.8

released 26th July 2021

- add aim assist module
- add targets select module
- add fastbow module
- add hitbox module
- add reach module
- fix outdated check in main menu
- add setting to toggle font in clickgui (ttf / minecraft font)
- add color picker to gui
- main menu rect now has an outline
- outdated check now works on patch versions (1.8.**x**)
- fixed autoclicker clicking faster than intended
- added startup sound (toggleable)
- added credits screen to main menu
- settings with the same name dont overwrite themselves anymore due to settings now being saved to the module itself

## v1.7

released 14th July 2021

- added alt manager
- added alt manager button to main menu (seperate menu coming soon when more custom guis are coming)
- added thealtening support (in alt manager)
- errors are now showing up correctly in console log

## v1.6.3

released 11th July 2021

- add on click option to autoclicker
- remove custom blur on clickgui, uses minecraft default one now
- new default clickgui bind is now **LCONTROL**

## v1.6.2

released 17th May 2021

- move clickgui to hud category
- info (HUD) font is now drawn in correct SF UI font, instead of verdana

## v1.6.1

released 14th April 2021

- fix hotbar drawn incorrectly when opening debug (f3) mode
- fix crashing error ""ticksExisted" not located in target class" caused by wrong mixin
- fix crashing error ""func_183501_a" not located in target class" caused my wrong mixin
- correctly move clickgui to "hud / gui" category
- new symbol on "settings marker" in clickgui (now shows "v" when extended)

## v1.6

released 14th March 2021

- fix font issues in 1.5
- add command system
- add bind command
- add toggle command
- add help command
- the "H" on the new watermark is now lowercase
- hud hotbar is now blurred
- hotbar font has now been correctly fixed to SF_UI (previously verdana)
- more particles in main menu!

## v1.5

released 12th March 2021

- add custom main menu
- add toggleable option for custom main menu in hud category
- add rainbowsetting to main menu
- add outdated check
- add updater to main menu
- add nohurtcam
- fixed storageesp category
- add bedaura
- add bedesp
- remove velocity
- change font in hud from verdana -> SF-UI
- fix arraylist errors
- rename no-bob back to nobob
- add color and outline option to itemesp
- fix items drawing above nametags above yourself


## v1.4.2

released 26th February 2021

- fix several visual bugs

## v1.4.1

released 24th February 2021

- fix arraylist outline
- wtap now only happens when hitting near an enemy
- nobob has been renamed to "no-bob"

## v1.4

released 21st February 2021

- arraylist slide speed can now be changed
- custom hotbar added
- changed clickgui blur to overlap inventory and gui
- left aligned arraylist has been removed
- watermark background now has an outline
- eagle has been renamed to fastbridge
- airstrafe module has been added
- autoclicker now actually presses leftclick
- custom font has been added
- clickgui has now added ttf font setting
- the ingamehud is now drawn in ttf font (verdana)
- added toggleable 24/12h time format
- info alignment added (left or right)
- arraylist color now has a category specific option (i.e. combat is orange, player is yellow etc.)
- fixed drawrect bug in clickgui
- fixed crash bug when enabling fastbridge
- add antiafk module
- add velocity module
- add flight module
- add itemesp module

## v1.3

released 13th February 2021

- modules now stay enabled when closing and starting the game
- add nametags module
- add cheststealer module
- add inventorywalk module
- add clickgui module descriptions
- add nospeedfov module
- add trajectories module
- add nochatrect module
- add storageesp module
- setting values in clickgui now draw righthand sided
- keybind in clickgui now has a seperator to differienciate from other settings

## v1.2

released 8th February 2021

- fixed render bug caused by outlineesp
- add rainbow array list
- watermark now always stays on the left side
- coordinates, time and fps added to hud
- renamed to hydrogen
- add safewalk module
- add fullbright module
- made clickgui colors darker
- added blur option to clickgui
- added optional entity setting to outlineesp

## v1.1

released 6th February 2021

- added autoclicker cps support
- added triggerbot, with cps support
- hud no longer draws in array
- clickgui default key now lshift
- fixed outlineesp not drawing on players
- add nobob module

## v1.0

released 5th February 2021

- fixed game crash on startup
- fixed game crash when using sprint or eagle
- added chams module
- added autosprint
- added fastplace
- added clickgui
- added ingame hud
- added eagle module
- added saving clickgui values and binds

Client created on the 2nd February 2021.   
Original Client which Hydrogen is based off of *(Tephra for Minecraft 1.8.8)*, was released on the 22nd October 2017.





[Semantic Versioning]: http://semver.org/spec/v2.0.0.html
