# Meph-lite

This is a vanilla-compatible release of Meph's 32x32 Tileset.  
The most notable difference between this release and the full  
version is that this release excludes the decorative workshops.  
If you would like to download the full version of Meph 32x with  
all the features, you can get it from its thread on bay12forums.

Meph's forum thread: www.bay12forums.com/smf/index.php?topic=161047.0

________________________________________
________________________________________

*Note: The following is a modified and*  
*updated version of Meph's original readme*  
*file from the v1.3 release of his tileset.*
________________________________________


Hello and thank you for downloading the Meph Tileset.

________________________________________
________________________________________
Index:
 * 1.0 - Installation and System Requirements
 * 1.1 - Seasonal Colors
 * 1.2 - Dfhack
 * 1.3 - TWBT
 * 1.4 - Screenshots
 * 1.5 - Credits
 * 1.6 - Patreon/Donations
________________________________________
________________________________________





________________________________________
1.0 - Installation and System Requirements:
________________________________________
This edition of Meph 32x is designed for use with Lazy Newb Packs. Simply drop the "Meph" folder into the /LNP/graphics/ folder of a compatible Lazy Newb Pack and use the PyLNP launcher to install.

The tileset is designed to be used with both dfhack and Text-will-be-text (TWBT) plugin. Although this tileset can be run without TWBT, it's going to be a greatly-diminished experience. If you still want to try without TWBT, you should probably install a 32x32 text-heavy tilesheet and switch the "GRAPHICS_FONT" to it from the "Customize" tab of the "Graphics" tab of the PyLNP launcher.

This tileset needs a minimum horizontal resolution of 2560 pixels and a minimum vertical resolution of 800 pixels. Any 1440p display will be able to properly show it in full size, although I do recommend a 4k display.


________________________________________
1.1 - Seasonal colors:
________________________________________
The graphic set also includes a custom dfhack script that switches color palettes each season. These are saved in your region-folders, so you can use different ones in different saves, if you like.  You find them in the "seasonal colors" folder.

They are named `colors_season.txt`. To use them, copy them into dwarffortress/raw and replace the 5 colors_*.txt in there. The first one is the default palette and will be used in the menu.

To get an idea of how they look, just open the Legend - Seasonal color schemes.png in the seasonal colors folder.

If you want to enabled this feature, open the `onLoad_gfx_Meph.init` file with a text editor and remove the 2 "#" signs from "#s#eason-palette start". Or if you don't want it to run automatically everytime, you can enter "season-palette start" into the DFHack Terminal window.


________________________________________
1.2 - DFHACK:
________________________________________
Dfhack is a DF utility that allows changes to be made that are otherwise impossible. It has many features, anything from cheats to bugfixes and ingame utilities.

You can read more about it on http://www.bay12forums.com/smf/index.php?topic=139553.0


________________________________________
________________________________________
1.3 - TWBT:
TWBT, or Text-Will-Be-Text, is a dfhack plugin that allows multiple graphical fixes. You can see several z-levels at once, you can use second tileset just for the font, and you can override single tiles with better replacements.

This is heavily used for this tileset, replacing several hundred tiles with unique sprites.

You can read more about it on http://www.bay12forums.com/smf/index.php?topic=138754.0

WARNING: 
TWBT might cause instability issues on some peoples machines. This is rare and usually only happens if either the GPU is very old, or if a lot of tiles are replaced at the same time. 

SOLUTIONS: 
- Try to stay away from ocean/beach embarks; the constant waves change a lot of tiles.

- Disable multilevel view by typing "multilevel 0" into the dfhack command window.

- Disable tile overrides by deleting/removing the overrides.txt in the data/init folder.

- Disable TWBT by deleting/removing the hack/plugins/twbt.dll file.


________________________________________
1.4 - Screenshots:
________________________________________
I plan to include cool screenshots from players into the download to showcaste the tileset. If you have nice pics, please send them to me. I'm Meph on Bay12, found here http://www.bay12forums.com/smf/index.php?action=profile;u=61165


________________________________________
1.5 - Credits:
________________________________________
I used Photoshop and MS Paint to make the tileset.
I used resources from Vordak, Dibujor, Obsidian Soul, Doren and Utkonos.

Dibujor: Thank you and best of luck with your (maybe) revived work. I used some of his furniture, wall and weapon ideas.

Obsidian Soul: Thank you and I hope you come back to DF some time. I used some of your abandoned 24/32x item sprites and based the civ-creatures of your design.

Doren: You are a genius for the way you designed the ballista! I used some of your 24x machinery upscaled/smoothed it for 32x.

Utkonos: Special thanks to you for allowing me to use your creature sprites. I based the map-tileset of your work and most monsters/animals in this set are upscaled/smoothed versions of your 24x creatures.

Thanks also to Toady One (for DF), Deon (for Genesis, my favoutire mod), Phoebus (for my favourite tileset) and everyone who gave me feedback and suggestions for the set. :)


________________________________________
1.6 - Patreon/Donations:
________________________________________
If you really like DF and/or this tileset and want to help out indy developers, consider making a small donations.

Tarn Adams aka Toady One, the developer of DF: https://www.patreon.com/bay12games
Patrick Martin aka Meph, the maker of this tileset and the MasterworkDF Mod: https://www.patreon.com/meph

Thank you!