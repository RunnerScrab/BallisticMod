# BallisticMod
## Overview
A 7DTD modlet which attempts to make firearm ballistics/handling more realistic. (Does not add bullet drop.) Developed for A19.

* Crosshairs will not appear while aiming a weapon with sights or optics
* Shotguns are now more accurate (~3" diameter shot spread at 10 yards) and have much greater effective reach
* Blunderbusses still have limited range and a very wide spread, but slightly less so than before
* Handguns now have realistic range and accuracy (around 10 MOA) and remain extremely effective
* Rifles have much better range and accuracy than anything else, more so than before (though range is probably first limited by the game's max view distance)
* Handguns benefit least from being aimed, shotguns slightly more, and rifles the most
* Cyclic rate of fire for fully automatic weapons are now set to their real world counterparts'

The numbers I've used in my mod are calculated loosely based on what I could find in the way of the real world MOAs, shot spread, and effective ranges. Handling values (when shooting "from the hip" with crosshairs) are an arbitrary, eyeballed compromise roughly correlating to weapon lengths and sight radii. Weapons are between 2 to 20 times more accurate when aimed.

Effective ranges shown in game are in blocks, which by my estimation have a length of about 82% of a yard, and indicate the distance after which there is damage falloff.

Shotguns are peculiar in games like 7DTD because no distinction is made between shot spread and accuracy. Increasing spread decreases accuracy at long ranges, as with weapons which only fire a single projectile at a time, but doing so with shotguns also increases hit probability at close range regardless of where the weapon is pointed - a situation with no bearing in reality. As a compromise between accuracy and power when shooting from the hip, I've given shotguns similar handling characteristics to handguns. Not entirely realistic, but better than the alternatives.

## INSTALLATION:
1. Create a folder named "Mods" in your 7DTD directory if it doesn't not already exist (e.g: "C:\Program Files (x86)\Steam\steamapps\common\7 Days To Die\Mods\")
1. Place the BallisticMod folder in your 7 Days To Die mods folder
2. Start the game

## UNINSTALLATION
1. Remove/delete BallisticMod folder from the 7DTD Mods directory

