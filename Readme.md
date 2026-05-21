# Titan Quest Giants Mod

A setup for playing as an overpowered giant with a custom world full of prey (WIP).

## How to Install Mod Source

You should be able to install the mod source for opening in the game's toolkit by copying the Working folder to the Working folder in your My Games directory. For example:

``.\Documents\My Games\Titan Quest - Immortal Throne\Working\CustomMaps\TQgiants\``

For the time being, the toolkit will need to be set up and used to build the mod. Refer to the game directory's toolset guide for info on setting up the working directories.

Change which giant to play as by renaming them in ``.\database\records\xpack\creatures\pc\``. Use the ArtManager.exe to see short descriptions for the files and of course to build the mod.

Unfortunately, actually getting **working textures** is a bit obtuse. You will need to copy the newly built database ARZ file into TheBouncer's database folder (create the folder) and rename the ARZ file to ``TheBouncer.arz``. Then, load into the game, play TheBouncer's custom "bounce" map with any character, then BACK OUT of the character select after the bounce messagebox, go to the Custom Quest character selector, and finally create a new character for your monster. If you don't do this, the monster models will have their textures overwritten by the player textures. One last thing, close and restart the game; trying to load a mod again at this point will just crash the game since it can't unload the mod from the bounce.

You can also use the "bounce" to load into the standard campaigns as the giant, though full compatibility with DLCs is not tested and may not allow using some weapon types.


