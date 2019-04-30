# Concept for MegaMod, created for Beta 1.7.3 Minecraft
###### Everything that's not made by me will have ***(Credit: person)*** as a tag next to the idea
##### ? = _Idea, possibly will do?_
##### ! = _Finished, already done_
___

## GUI Work
#### Main Menu
* **!** New main menu ***(Credit: Logan)***
* * Includes panorama background
* **?** Mod Info / Credits button
#### In-Game
###### F3 Menu
* **!** Show direction player is facing ***(Credit: portalsam)***
#### Controls GUI ***(NEW)***
* **!** Changing controls
* **!** Scrolling down because of lots of controls
* **!** More default controls from mod such as flying, sprinting
#### Mod Settings GUI ***(NEW)***
* **!** Fly settings
* **!** FoV slider
* **!** Double Tap Forward Run toggle
* **!** Double Tap Jump Fly Toggle
#### Sound Settings GUI ***(NEW)***
* **!** Master Sound
* **!** Music Volume
* **!** Animals Volume
* **!** Weather Volume
* **?** Main Menu Music Volume
#### Chat Settings GUI ***(NEW) (DEBUG)***
* **!** Chat Window Size
* **!** Chat Colors Toggle
* **!** Hide towny in chat toggle
* **?** Hide join/leave messages toggle
#### Controls GUI ***(NEW)***
* **!** New added default controls
* 1. Fly control
* 2. Sprint control
* 3. Zoom control
* **!** Set keybind like in 1.13
* * **?** Possible *settings* option for that control?
#### Video Settings GUI
* **!** Larger render distance
* **!** Sky Settings
* * **!** Rain toggle
* * **!** Fog toggle ***(DEBUG)***
* * **!** Sky toggle
* * **!** Cloud height slider
* * **!** Enable/Disable clouds
* * **!** Force time of day
#### Multiplayer GUI
* **!** Adding a new server
* **!** Editing an existing server
* **!** Deleting an existing server
* **!** Direct Connect
* **!** Setting a custom name
* * Custom names are also auto-saved
* **?** Showing if an existing server is up or not
#### Player-List GUI
* **?** Relying on custom packets (see Custom Server Packets)
* **?** Button can be changed in options. Default: TAB

___

## Global Stuff:
* **!** Update Checker upon starting game
* **!** Skins showing/working ***(Credit: Johnanater)***

#### Custom Server Packets
* **!** Servers with Custom Packets will rely on a custom plugin via Bukkit
* **!** Ability for server to know if you're using this mod
* **?** Server sending you all the players names

___



___

## Mods (Codename MegaMods)
* **!** Mods auto load from resources/mods/* ***(JavaScript)***
* **!** Console logging, warnings, and errors
* **!** Mod should be able to create a new control and wait for user input
* **!** Mod should be able to refresh itself (for developers)
* **?** Drawing things on screen
* **?** Interacting with LWJGL to change anything, such as the render engine
* **?** Grabbing current GUI and interacting with it
* **?** Possiblity to watch tick, so we can have a fake while loop
* **?** Full TypeScript definition files so that intellisense can be a thing
* **?** Ease of access of the Minecraft class so devs can see entities and stuff
* **?** Java mods
* * Loading mod via jar similar to forge
* * Java should be able to do everything JS does
* * API so developers know where to look

___

## In-Game:
* **!** Texture Packs button in-game
* **!** Sprint w/ keybind (see Controls GUI)
* **!** 3rd person view like modern
* **!** fly; toggleable, speed options and smoothness option
* * Also has fixed footstep sounds when landing
* **!** Better chat; Resizeable, fixed lines
* **?** GUI layout editor
