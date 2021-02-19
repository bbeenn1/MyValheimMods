SkToolbox - Valheim
AUTHOR: Skrip (https://steamcommunity.com/id/Skrip037/)
Toolbox Version: 1.3
Valheim at time of release: 0.145.6

SkToolbox is a fully clientside utility meant for improving the gameplay experience, by enabling the player to modify their character or the environment to their liking. The mod enables features that could allow a player to drastically change their character or others.

It is recommended that you use discretion when using these commands in Multiplayer, as this will affect the gameplay experience of others.

:: REQUIREMENTS ::
None

:: FEATURES ::
• This mod works by extending the functionality of the console and chat commands. Most of the commands shown below are usable in both the console and via chat. Most commands work both via console or chat.
• Please see NexusMods page for most up to date feature list.

:: HOW TO INSTALL ::
• Method 1 (recommended):
	• Simply open the zip file and extract all contents to the game's root directory (You'll see valheim.exe and UnityPlayer.dll in this folder).
After extraction, in the game root folder, you should see the Valheim.exe file, and the BepInEx folder in the same folder. (https://i.imgur.com/QKx9yxU.png)
	• Run the game and enjoy.

• Method 2:
• If you use a standalone injector, here is the necessary injection information. Injecting from the main menu is the optimal place to inject, as if you wait until in-game, this can sometimes cause a crash.
	• Namespace: SkToolbox
	• Class: SkLoader
	• Method: Init

• I just need to update! What do I do?
	• Extract the .dll file to the plugins folder, run the game.

:: HOW TO USE ::
• Complete one of the two installation methods, then simply run the game and open the console.
	• Type help or /?
	• (/? also works as a chat command)

:: CHANGELOG ::
• Version 1.3
  !![NEW] Modified the console so you can now press the up arrow to get as many previous commands as you've entered.
  !![NEW] On-Screen Controls!
	[NEW] Teleport to Mouse
	[NEW] /set difficulty [Player Count] - Set the difficulty (default is number of connected players)
	[NEW] /set exploreradius [Radius] - Set the explore radius (default = 100f)
	[NEW] /set jumpforce [Force] - Set jump force (default 10). Careful if you fall too far!
	[NEW] /set pickup [Range] - Auto pickup radius can now be set (default 2)
	[NEW] /set speed [Speed Type] [Speed] - Speed Types: crouch (def: 2), run (def: 120), swim (def: 2)
	[NEW] /clearinventory - Clears the player inventory
	[FIX] Infinite stamina no longer causes lag, and is actually infinite now.
	[CHG] /listitems no longer requires caps
	[FIX] Backend changes. Performance increasecis.
	[CHG] /? is now organized by pages. Ex. /? 1
	[REM] /seed removed until it is properly working
	[REM] /findtrader removed until it is properly working
	[REM] /itp removed until it is properly working
	[REM] /ttp removed until it is properly working
	[CGH] Changes to give command. It now can be used with different parameters: /give [Item] [Qty=1], OR /give [Item] [Qty=1] [Player] [Level=1]
• Version 1.2
	[UPD] Updated BepInEx Version
	[NEW] /listskills will list all possible skills
• Version 1.1
	[CHG] /detect now has a range variable. /detect 50 (/detect performs a default of 20)
	[NEW] /imacheater now enables standard in-game cheats on any server (for you only)
	[FIX] /heal [Player=local] now properly heals other plyers
	[NEW] /set skill [Skill] [Level]
	[NEW] /seed - Display the world seed
	[FIX] /coords now show correctly
	[FIX] /tp now works correctly
	[CHG] /? now has pages. /? 1 or /? 2
	[NEW] /stopevent has been added
	[REM] /imaxstacks has been removed until properly working

:: KNOWN ISSUES ::

:: CREDITS ::
♦ This mod was produced exclusively by Skrip.
♦ ♦ ♦ https://steamcommunity.com/id/Skrip037/

♦ Thank you to the Harmony team for their patcher.
♦ ♦ https://harmony.pardeike.net 

♦ Thank you to the Doorstop team for their injector.
♦ ♦ https://github.com/NeighTools/UnityDoorstop

♦ Thank you to the BepInEx team for their injector.
♦ ♦ https://github.com/BepInEx/BepInEx