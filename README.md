# EquipViewer
EquipViewer is a plugin for Ashita4 that allows you to overlay your equipment menu anywhere on your screen allowing you to see what is equipped at any given time. 

###Commands
All commands should be prefixed with /equipviewer or /ev

**/ev pos[ition] x y**<br>
Changes the position of EquipViewer to the given position. 

**/ev scale number**<br>
Changes the scale (size) of EquipViewer. To make it twice as large, for example, you would set the size to 2.0. Default scale = 1.0.

**/ev opacity number**<br>
Changes the opacity of the on-screen textures and font objects. Should be between 0 (completely transparent) and 1.0 (completely opaque).

**/ev bgcolor a r g b**<br>
Changes the color of the background box to the specified argb value. Default: 64, 0, 0, 0

**/ev showammo**<br>
Toggles EquipViewer overlaying ammo count when stackable ammo is detected.

**/ev hideinchat**<br>
Toggles EquipViewer to automatically hide when viewing the expanded full chatlog. 

**/ev encumberance**<br>
Toggles EquipViewer to indicate an equip slot being encumbered with a red "X" on the bottom right of the slot.

**/ev help**<br>
Prints the above commands.