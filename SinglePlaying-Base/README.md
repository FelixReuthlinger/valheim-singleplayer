# Single Player Base

This mod pack does add some of the most basic mods that change playing the game:
1. Create Level and Loot Control (CLLC) -> adds harder creatures
2. Epic Loot (EL) -> enchanted loot
3. Dual Wield (DW) -> let's you use same weapons both handed
4. Regenerative Nature (RN) -> re-spawns trees and tin rocks
5. Better Wards -> to protect your warded bases better from creature attacks and enable unlimited fire sources

The configuration provided for these mods in this modpack remains pretty simple, the only bigger change is that
CLLC's item config is activated and item's configuration is slightly changed, like weight and items that are kept on death.

## Installation

Most of the installation works out-of-the-box using ThunderStore Mod Manager (TMM), but some mods don't clearly comply to loading config from config folder.

### Epic Loot manual steps

To actually make this mod pack work properly, you will need to do some manual steps, since Randy still didn't choose to make his loot mod to 
also support custom configs by reading file from config folder. You will need to go to the modpack folder (where TMM did install it into 
the profile) and copy around the custom configs to make them work. Starting the game without this step will load the default configs for 
EpicLoot, which screws up the game a lot, since the loot is way to powerful and the game gets boring by this - imho.

Steps:
1. go to TMM client
2. click "settings" button on the left
3. click "locations" tab on the top of the right selection menu
4. click "browse profile folder" -> a windows explorer should be opened
5. switch to the window of the windows explorer
6. navigate into folders "BepInEx\config\EpicLoot"
7. copy all files inside that folder
8. navigate into folder (again starting from profile folder) "BepInEx\plugins\RandyKnapp-EpicLoot"
9. paste all the files there and accept to overwrite any existing files

(if you wanna help to making this easier, I guess Randy will be happy to get that feedback on discord, maybe he changes his mind some time)

## Changelog

* 1.3.5 -> updated to most recent mod versions from game update on 25th Nov
* 1.3.4 -> extracted some mod configs to be re-used in other packs
* 1.3.3 -> added auto repair
* 1.3.2 -> dependency updates and minor fixes for EL configs
* 1.3.1 -> added StaminaRegenerationFromFood
* 1.3.0 -> added Better Wards with config protecting your buildings from monster attacks
* 1.2.0 -> added Dual Wield mod; added manually installed EL config (added H&H loot to loot tables, 
but removed tools and pickaxes from loot drops; dis-/enchanting and recipe changes, removed/modified 
enchants to let them make more sense)
* 1.1.1 -> more CLLC adjustments
* 1.1.0 -> enabled most basic settings in CLLC
* 1.0.0 -> first version, only changed CLLC item config

## Contact

* https://github.com/FelixReuthlinger/valheim-singleplayer
* Discord: Flux#0062 (you can find me around some of the Valheim modding discords, too)
