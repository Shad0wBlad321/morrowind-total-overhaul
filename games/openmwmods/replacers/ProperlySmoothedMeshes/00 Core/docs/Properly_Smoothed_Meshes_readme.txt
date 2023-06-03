************************************************************************************************
Properly Smoothed Meshes
by Stuporstar

Version 1.03
Requires Morrowind

Contact: sarahdimento@gmail.com
@Stuporstar#1172 https://discord.me/mwmods
************************************************************************************************
This graphic replacer covers tons of misc items, furniture, lights, and some containers. They are manually smoothed vanilla meshes or remade from scratch, keeping the same UVs (with fixes) and footprint of the original meshes.
The default meshes are not reflection mapped, like they were in my older replacer MIO - those have been moved to an optional folder.

Optional Folders:

01 Optional Textures: includes a few hand-upscaled textures as well as normal and reflection maps for a few misc items
02 Flat Tables: included flat-topped versions of the smoothed de_p tables (may cause some clipping in-game, which is why they're optional)
03 Higher Poly Glowing Candles: comes with their own glowmaps, so Glowing Flames is not required, but recommended
04 Reflection Mapped: [OpenMW Users Do Not Use] [Requires Optional Textures] - adds reflection maps to some meshes for MGE XE users who'd like shiny ceramic and glassware
05 Beakers, Flasks - clear glass: reflection-mapped clear glassware like Qarl's
06 Inkwell - cut glass: my own alternate mesh and texture - shiny
07 Barrel - no rivets: replaces riveted hoops with plain vanilla metal strip texture, because rivets on barrels is stupid
08 Potted Plant - redware: changes plaster texture on plant pot for redware

All glassware have alpha properties. If you don't want transparent glass, use textures that don't have alpha channels (such as the original textures or Connary's).

************************************************************************************************
Installation & Load Order
************************************************************************************************
If using a BAIN-type installer, load the core mod and any options you prefer.
The reflection mapped folder requires the optional textures folder. They've been separated for OpenMW users.

Some meshes were never used in the game, such as the half barrels, but I included them anyway as modder resources.
Any mod that restores these items to the game will benefit from the upgraded meshes.

Load Before PSM
Correct Meshes: - https://www.nexusmods.com/morrowind/mods/39348
Tarius' Better Meshes: for some furniture done well enough I don't feel the need to redo them - https://www.nexusmods.com/morrowind/mods/38170
RR Better Meshes: for smoothed apparatus, potions, and any miscs I missed - https://www.nexusmods.com/morrowind/mods/43266
Glowing Flames: not required to use the glowing candles in this mod, but will fill out ones I haven't smoothed - https://www.nexusmods.com/morrowind/mods/46124

Load After PSM
Project Atlas: which I made smoothed urns and redware for - https://www.nexusmods.com/morrowind/mods/46124
Any replacers more HD than this one

Not Recommended:
Mesh Improvements or my old Mesh Improvements Optimized
Qarl's Bowls - all replaced by this mod now, and shiny versions are available in optional reflection-mapped folder
Qarl's Flasks - all replaced by this mod with more optimized versions
************************************************************************************************
Changelog
************************************************************************************************
Version 1.03
- Removed stray alpha property from blue ceramic bowl and pitcher
- Fixed pixelation on glowmaps in optional Glowing Higher Poly Candles folder

Version 1.02
- optional textures folder should now work properly with BAIN installers

Version 1.01
- removed crappy round dwemer coin because it's supposed to be octagonal and there's better replacers out there
- optimized collision on round cushions
- TR uses flat poor tables, so added them to core mod in TR folder to replace them with smoothed versions
- Also made sure flat tabletops match the height of the TR ones

************************************************************************************************
File List
************************************************************************************************
D/
ex_r_trapdoor_01.nif
in_r_trapdoor_01.nif (I only smoothed the door part, not the ladder)

F/
Flora_muckpod_01-05.nif
Flora_T_podbud_01-04.nif
Furn_Ashl_Bugbowl.nif
Furn_Ashl_Bugbowl_01.nif
Furn_Ashl_Bugbowl_02.nif
Furn_Ashl_Bugbowl_03.nif
furn_basket_01.nif (a rounder basket than the one in MOAR Meshes - added collision mesh as well, since this one's normally static)
furn_cart00.nif
furn_cushion_round_01.nif - furn_cushion_round_07.nif
furn_cushion_square_01.nif - furn_cushion_square_09.nif
furn_de_chair_01.nif
furn_de_chair_02.nif
furn_de_stool_02.nif
furn_de_table_01.nif
furn_de_table_02.nif
furn_de_table_03.nif
furn_de_table_04.nif
furn_de_table_05.nif
furn_de_table_06.nif (fixed missing underside on table top, which somehow went unnoticed for 15 years)
furn_de_table_07.nif
furn_de_table_08.nif
furn_de_table_09.nif
furn_halfbarrel_00.nif (not found in ESPs)
furn_halfbarrel_01.nif (not found in ESPs)
Furn_Planter_MH_01-05
furn_pottedplant.nif (redware version is in the Optional folder)
furn_spinningwheel_01.nif
furn_spinwheel00.nif
furn_stool_01.nif
furn_t_fireplace_01.nif (I made this when making new Telvanni fireplaces. It's made from scratch, not a smoothed mesh like Mechior Darhk's replacer, but the same fit as the original)
furn_table_01.nif

L/
Light_buglamp_01.nif (new texture included in Optional folder)
Light_Com_Candle_01.nif
Light_Com_Candle_02.nif (version in optional glowing candles has beveled base and tweaked UV maps)
Light_Com_Candle_04, 06, 07, 11, 13 (the squat candles without holders)
Light_Com_Candle_05.nif
Light_Com_Candle_09.nif (version in optional glowing candles has rounder base)
Light_Com_Candle_12.nif
Light_De_Candle_01-26.nif
Light_Redware_Lamp.nif (not found in game)
Light_Velothi_Brazier.nif (smoothed brazier bowl)

M/
misc_beaker_01.nif (uses peach glass like vanilla - clear version in optional folder, as well as flasks)
Misc_bowl_bugdesign_01.nif
misc_bowl_glass_peach_01.nif
misc_bowl_glass_yellow_01.nif
Misc_bowl_orange_green_01.nif
misc_bowl_redware_01.nif
misc_bowl_redware_02.nif
Misc_bowl_redware_03.nif
misc_bowl_white_01.nif
misc_com_bucket_01.nif
Misc_Com_Bucket_Metal.nif
Misc_Com_Iron_Ladle.nif
Misc_Com_Metal_Goblet_01.nif
Misc_Com_Metal_Goblet_02.nif
Misc_Com_Pitcher_Metal_01.nif
misc_com_wood_bowl_01.nif
misc_com_wood_bowl_02.nif
misc_com_wood_bowl_03.nif
misc_com_wood_bowl_04.nif
misc_com_wood_bowl_05.nif
misc_com_tankard_01.nif
misc_com_wood_cup_03.nif (not found in ESPs)
misc_com_wood_cup_04.nif (not found in ESPs)
misc_de_bowl_01
misc_de_pitcher_01
misc_de_tankard_01
misc_dwrv_artifact00
misc_dwrv_artifact50
misc_dwrv_artifact60
misc_dwrv_bowl00
misc_dwrv_coin00.nif
misc_dwrv_goblet00
misc_dwrv_goblet10
misc_dwrv_mug00
misc_dwrv_pitcher00
misc_flask_01.nif (not exactly like vanilla, since tx_item_pot_glass_peach_01.dds stretches horribly I replaced it with tx_item_pot_glass_peach_02.dds)
misc_flask_02.nif (see above)
misc_flask_03.nif (see above)
misc_flask_04.nif (see above)
misc_glass_green_01.nif (normal maps included in Optional folder)
misc_glass_yellow_01.nif (see above)
misc_inkwell.nif (cut glass version - only available in optional folder)
Misc_LW_Bowl.nif (normal maps included in Optional folder)
Misc_LW_Cup.nif (see above)
Misc_LW_Flask.nif (see above)
Misc_LW_Platter.nif (see above)
misc_portal_shard.nif
misc_pot_blue_01.nif	(only use one texture, with different alpha values, rather than the ugly original tops)
misc_pot_blue_02.nif	(this pot has an alpha property, like the blue ceramic, that will only show up if you use an alpha texture)
misc_pot_glass_peach_01.nif (new texture included in Optional folder)
misc_pot_glass_peach_02.nif (see above)
misc_pot_green_01.nif
misc_pot_mottled_01.nif (new texture included in Optional folder)
Misc_pot_redware_01.nif
Misc_pot_redware_02.nif
Misc_pot_redware_03.nif
misc_pot_redware_04.nif
misc_redware_bowl.nif
misc_redware_bowl_01.nif
misc_redware_cup.nif
misc_redware_flask.nif
misc_redware_lamp.nif (non-light version, not found in ESPs)
misc_redware_pitcher.nif
misc_redware_plate.nif
Misc_Redware_Platter.nif
Misc_Redware_Vase.nif
misc_portal_shard.nif
misc_spool_01.nif (more detailed than RR version, slightly less vanilla but the same size)

O/
contain_barrel_01.nif (new version found in the "Barrel - no rivets" folder only, because Tarius already replaced it in Better Meshes)
contain_com_basket_01
contain_dwrv_barrel00.nif
contain_dwrv_barrel10.nif
contain_couldron10.nif
contain_pot_01.nif
contain_urn_01-05.nif (similar to RR versions, but with collision meshes)

X/
ex_S_forge.nif (from Bloodmoon)

************************************************************************************************
Credits/Permissions
************************************************************************************************
Qarl's reflection maps are included in the Optional folder, as well as his glass texture in the Beaker and Flasks folder.
Connary's bug bowl texture is included in the optional folder to match the reflection map.
The rest have been upscaled or modified by me, using mostly vanilla textures.

The meshes and textures are free for use in any Morrowind project. Most meshes are made from scratch, but a few are original meshes smoothed.
No permission necessary. Feel free to redistribute in your own packages. Credit would be nice.