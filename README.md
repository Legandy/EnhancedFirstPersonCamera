# Enhanced First Person Camera Mod

<p align="center"><img src="https://raw.githubusercontent.com/Legandy/EnhancedFirstPersonCamera/main/Pictures//Enhanced First Person_Modpage.png" width="512" height="288">

## For No Man's Sksy

## Downloads
[NexusMods](nm)


## Description
This mod modifies the FOV values (Foot/Ship) and Multitool position to be more like a standard FPS view.

I wanted to enhance the overall first person experience for more immersion, like the view and gunplay.
But I wasn't satisfied while changing the gunplay values (Recoil, Shake) so I separated these two.
The player FOV doesn't seem to apply, but the Ship FOV works. (set it manually in the TKGRAPHICSSETTINGS.MXML).


## The Enhanced First Person Camera (EXML & .lua):
I would highly suggest to make use of the .lua to adjust the mod to your preference, but if really needed I can make another variant.


### Changes in:
### GCCAMERAGLOBALS.GLOBAL.MBIN:
- FOV Settings for Character and Ship
- No free look smoothing while in Mech and Ship
- I excluded Exocraft because it gets replaced by many overhaul mods, but the settings are included in the .lua

### GCGAMEPLAYGLOBALS.GLOBAL.MBIN:
- Multitool & Staff Position
- I didn't adjust Staff Position because I don't have one, but the settings are included in the .lua


## Enhanced Gunplay (only .lua):
- I think I got the right properties but didn't test all.
- I tried a lot of values but I weren't satisfied, so I abandoned the idea for now.
- If you want to tinker with the settings yourself, I included the .lua. If you find nice settings, please share them with me.

### Changes in:
### GCCAMERAGLOBALS.GLOBAL.MBIN:
- Multitool/Gun Shake intensity
- GCPLAYERGLOBALS.GLOBAL.MBIN:
- Scope stronger zoom


## CONFLICTS:
- ✅ Patch mod - Likely to work well with other Patch and Replacement mods

## Bugs:
- The Player FOV doesn't seem to apply, but the Ship FOV works. Set it manually in the TKGRAPHICSSETTINGS.MXML located in No Man's Sky\Binaries\SETTINGS\

## INSTALLATION:
- Vortex should work
- For manual installation, extract the contents of the EnhancedFirstpersonCamera.zip file into your No Man's Sky\GAMEDATA\MODS
- [More details here][mg]

## Special thanks to:
- [AMUMSS][amuss-ref] for making the modding pretty easy

[nm]: https://www.nexusmods.com/nomanssky/mods/3901
[mg]: https://docs.google.com/document/d/18k5VfvzLXbpBrAGGO7LK30c2Ta_lWQ5F5YgEpuwKZ6M/edit?tab=t.0#heading=h.vm4bcr5uj28i
[amuss-ref]: https://www.nexusmods.com/nomanssky/mods/957