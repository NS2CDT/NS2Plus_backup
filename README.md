﻿Custom HUD
==========

This mod for Natural Selection 2 allows the players to customize a number of settings of their HUD and game behavior (sounds, visuals).

If the server allows mods that use the entry system, you can use it as it's 100% client-side, otherwise you need the server to be running it.

You can type "chud" in console to see all available options or set them directly in your options menu.

Latest changes
==============
- 22/03/2014 (Build 264):
	- Expanded marine upgrade icons option to include the NS2 Beta icons.
	- Enabled game timer to Commanders.

- 21/03/2014 (Build 264):
	- Fixed bug where the CHUD Options menu was being recreated every time it opened.
	- Overhead spectators now get the player name in yellow if the player is parasited.
	- Made ammo bars for Marine Commanders colored depending on primary weapon, like in spectator view.
	- Redid the way Minimal GUI affects the Armory and Prototype Lab buy menus.
	
- 19/03/2014 (Build 264):
	- Reworked options system (internal). Console commands have changed. This has exposed some options that used to be only console commands. Type chud in console for help.
	- You can now toggle map particles separate from minimal particles.
	- Added new menu entry "Custom HUD" for the mod options, it has 3 tabs, Visual, HUD, Map.
	- The changelog is always available in the new Custom HUD menu option on the bottom left.
	- Reenabled Hive stats for servers that only run CHUD but not [Shine] NS2Stats.
	- Updated Veil low lights file. Also updated the rest to make sure they are up to date.

- 14/03/2014 (Build 263):
	- Fixed bug where Minimap locations wouldn't apply transparency on init

- 12/03/2014 (Build 263):
	- Added Alien Vision State option (chud_avstate) to set if you want to automatically turn on the AV on respawn.
	- Added location name transparency (chud_locationalpha) to set the transparency of the location name text on the minimap.
	- Added minimap transparency (chud_minimapalpha) to set the transparency of the minimap.

- 09/03/2014 (Build 263):
	- Server browser is now able to filter servers running CHUD, but can only do so ingame. To be able to search outside of a game use [CHUD Browser](http://steamcommunity.com/sharedfiles/filedetails/?id=236685163).

Credits/Thanks to
=================
- **Unknown Worlds Entertainment** for creating Natural Selection 2. This is a classic in mod credits.
- **Dragon** for rewriting my horrible light switching code (which I've stolen back from the NSL mod) and answering my stupid questions.
- **bawNg** for his awesome injection code (from SparkMod: https://github.com/SparkMod/SparkMod). Tip: Never mention CS:GO to him.
- **lwf** for the tracer code from Better NS2 (http://steamcommunity.com/sharedfiles/filedetails/?id=113116595)
- **Ghoul** (https://github.com/BrightPaul)
- **Sewlek**
- **Person8880** (https://github.com/Person8880) GetGamemode function to reenable Hive stats.