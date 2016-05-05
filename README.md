# BC7MOD

Trainer for Grand Theft Auto San Andreas


This is the decompiled source code of the latest -not released- BC7MOD (version 5).
Unfortunately the original source code with all the comments and segement explanation was lost, therefore a decompiled version is available.

The code is somewhat buggy and crashes can randomly occur.


===Plugins===
Requirements:

- IniFiles.cleo
	Used for reading and writing to ini files.

- GxtHook.cleo
	Used for displaying text using the GXT file in the CLEO_TEXT directory.

Optional:

- BC7ModExtra.cleo
	Addition to the BC7MOD which fix the well known mouse bug on Windows Vista and above and and toggable option to skip the intro movies.	
	Unfortunately the source code is also lost, however the use of this plugin is optional.

IniFiles.cleo and GxtHook.cleo can be found in the CLEO SDK. 
BC7ModExtra.cleo is included, but does not have to be used.

===Contents===

- bc7mod.txt
  CLEO_TEXT
	- BC7MOD.fxt
- 
- vehicles.ini

- Wearable.ini
- BC7ModExtra.cleo

Note: after first time use a BC7MOD_config.ini will be created in the CLEO root directory.

===changelog===

- Fully rewritten from scratch.
- One easy to use menu structure design.
- Change Hair (new)
- Change clothes (new)
- Change accessoiries (new)
- Change tattoos (new)
- Change statistics (new)
- Option to save teleport locatons and give them their own name (new)
- Launch the nearest person in the air (ped menu) (new)
- Option to drive on water (vehicle menu) (new)
- Option to flip the vehicle automaticly when it is up side down. (new)
- Option to change the handling of the vehicle that you are driving (highly experimental) (new)
- Option for unlimited ammo (new)
- Editable hotkey to open the menu (can be changed ingame) (new)
- Windows Vista and above mouse fix (BC7ModExtra.cleo required) (new)
- Option to skip the intro when starting the game (BC7ModExtra.cleo required) (new)
- Godmode for player and vehicle are now seperate (modified)
- New menu to edit the time (modified)
- Gravity can now be changed through a menu (modified)
- People menu (in earlier version ped menu) is now integrated in the main mod menu (modified)
- Vehicle menu is integrated in the main mod menu (modified)
- Vehicle customisation options are now divided into more logic categories. (modified)
- Some functions that where barely used are removed (removed)