# Mutant Skinning Loot Chance Configuration Options (MCM)

This mod allows you to have more control over mutant loot chances. This mod was created for the GAMMA Modpack for S.T.A.L.K.E.R. Anomaly, but it should work with base Anomaly and other modpacks (see "Incompatibilities" for more info).

**Mod Features:**
- Multiply the base drop chance of mutant parts, mutant meat, and/or mutant pelts (up to a 5x multiplier)
- Multiply the base drop chance of miscellaneous mutant loot (up to 3x multiplier to avoid loot overload)
- Guaranteed drops of mutant parts, mutant meat, and/or mutant pelts
- Guarantee a random item from the mutant's loot table if said mutant would've had no loot on it
- *Includes compatibility with any changes any mod makes to mutant loot tables*
- *Includes compatibility for the* `Hunting Backpacks_DLTX` *module for those who installed the DLTX MiniMod Pack separately to ensure the correct bonus part chance is calculated (hide or delete the file* `zz_ui_mutant_loot_hunter_backpacks.script` *from the module)*


**Installation and Setup:**
(1) Download the mod
(2) Install the mod via MO2 and make sure it wins all file conflicts (or simply move it to the very bottom of your load order)
(3) Launch the game
(4) Go into the MCM and look for `Mutant Loot`
(5) Adjust your settings to your liking
- *Make sure to tick the* `Enable Mod?` *option in order for your settings to take effect*
- *Make sure to hover over the options for their descriptions if you are confused*

**Incompatibilities:**
o Any non-GAMMA mod that edits the `ui_mutant_loot.script` file
- *Feel free to create patches for any various mods that touch this script and share them here*
- *DO NOT file crash reports if you are using any of the patches not created by me*
- *As of Update 1, this mod is monkeypatched and no longer overrides the* `ui_mutant_loot.script` *file - however, this will override any changes made to the file's* `loot_mutant(..)` *and* `UIMutantLoot:Loot(...)` *functions*

Feel free to report any bugs or crashes that may occur. **Always include your crash log file when reporting a crash.**
