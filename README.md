# Paper Mario TOK Save Editor
A Save Editor for the recently released Paper Mario: The Origami King written in C#.

# Features
## Editors
* Stat Editor (HP, Max HP, Coins, Spent Coins, Confetti, Confetti Bag Capacity, and current Bibliofolds)
* Inventory Editor (Weapon and Item edits. Can change a weapon's used durability and chance of breaking on the next turn)
* Partner Editor (Can choose to have Folded Bowser, Bone Goomba, Sombrero Guy, Professor Toad, Green Toad, Luigi, Spike, Kamek, and Normal Bowser | Some partners may stay after removing them depending on your game progression)
* Play Time Editor (Game's internal timer)
* Gameover Count Editor
## Settings
* Automatically create save file backups in by enabling a setting
* Have the program remind you to create a save file backup on startup

# User Guide
## Prerequisites
* You must have a modded Switch in order to backup your saves and replace them with edited ones.
* If you have a modded Switch, you will need to install a save manager such as [Checkpoint](https://github.com/FlagBrew/Checkpoint/releases/tag/v3.7.4).
* Download and install the .NET Framework 4.7.2 Runtime.

## Steps
### Getting your Save Data
1. Use your Save Manager of choice and backup your save data for Paper Mario: The Origami King.
2. Locate your data00.bin file in your SD Card and make sure it's on your PC.
 a. Backup your data00.bin in case anything goes wrong during the editing process.
 
### Editing your Save File with the Tool
1. Download the latest version of the Paper Mario: The Origami King Save Editor from the [Releases page](https://github.com/zSupremoz/Paper-Mario-TOK-Save-Editor/releases)
2. Open the application.
 a. If you wish to enable automatic backups, go to File -> Settings, then click on Automatically Create Backups.
 b. You can also change the location where you want to store these backups at. By default, the program creates the backup at the same place your data00.bin is located.
3. Open the data00.bin with the application.
4. Start editing to your hearts content.
5. When you're done editing, click on File -> Save to save your edits. Then export your save file to your save manager.

# Credits
* [zSupremoz](https://twitter.com/zSupremoz) - Main developer
* [Blue](https://twitter.com/1mBlueDabadee) - Taught me how to recalculate the CRC32B hash
