# AdvancedBotsLoadouts
Tired of duplicates scavs and raiders loots ? Here you go an advanced version of the bots loadouts.
Each of scavs and raiders have their own bunch of loadout, more than 6k exactly. Gears(except weapons), loots in pocket, vests, backpacks have been randomly generated from a script.

Every item of the game up to 12.2 can be found on the scavs as well as raiders. Note that this version of the mode aim to be like the official in term of gears, that mean you're not gonna find tactect on normal scavs. Every gears wich is not on a scav side, is on the other side (tactec is not in normal scav but on raiders one for exemple).

**How the loot have been generated ?**:

Every items of the game have been splitted up in a list of 8 tiers, from 0 for the most common item to 7 for the maximum rarity of items. Each tier have a specific chance of getting choose by the script. Armor durability is as well randomly generated.

**Will i still have duplicated stuffs ?**

You will, because it seems that the game select a bunch of presets at the beginning of a game wich are going to be the spawned scavs. But due to the larger amount of presets there wont be so much duplicate as the default one.

**Will the loot have the in raid state ?**

YES it will !! I managed to get most of the items to have the in raid state, except for weapons and some scopes. So have fun for the future quests ! :slight_smile:


**Where do i download this freaking amazing shit ?**

Here is the download link for the actual files : 
/!\ This is only supported for **12.2.x +** versions of the game. Don't use it for older versions you may have issues with it/!\

> https://github.com/KandaSoranyan/AdvancedBotsLoadouts/releases


**Will be other version of this mod ?**

YES there will. I will work on differents versions of the mod for differents purposes.
For exemple next work is to have a version that "emulate" PMC as scavs, and i will try to add them those freaking dogtags. I got a bunch of weapons presets specially made for this PMC version from @jessica_r#5493 and @Bear#7174 and i'm thanksfull for that it saved me a lot of time.

I will probably make an other version wich include absolutely every gear, and every items (the only ones missing are cases.) to the normal scavs.
So stay tuned about the mod ! and have fun using it ! :slight_smile:

**Actual plans for the mods**

There will be an upcoming version of the mod, the version 1.1.0 wich will handle all bosses and their followers. I already started to progressively update the mod, but note that it can take some time as theses loadouts or handmades, wich means i'm making them myself, so i need to think to wich items the boss will have on him, wich ammo and so on.

The version 2.0 of the mod will have a complete rework of scavs loadouts with a different way of generating them. I will include with this a rework of pmc's loadouts with more weapons presets, and maybe a new generation system too. I still don't know about scavs raiders, they seems fine as they are now.

*Actual progression :*
- [x] Bosses
- [ ] Bosses followers
- [ ] Scavs rework
- [ ] PMC's rework

*Note:*

You can send me other weapons presets if you wish ! For doing so, make your weapon preset in the in game editor, save it with this name : weaponName + PMC and send me over in PM the userbuild.json file located into /user/profile/id/

## Installation Guide

/!\ For now, only do what is stated in the TRHOUBLESHOOT section ! /!\

Here is how you install this mod, follow all steps and it's good !

	1. First is to download the last version of the mod here : https://github.com/KandaSoranyan/AdvancedBotsLoadouts/releases
	2. Drop the folder Sorata-AdvancedBotsLoadouts in *user/mods*.
	3. Add this code in the server.config.json in the "list" data.
	
```json
{
"name": "AdvancedBotsLoadouts",
"author": "Sorata",
"version": "1.0.8",
"enabled": true
}
```

	4. Restart the server.
	5. Go into a raid.
	
## Troubleshoot
Sometimes scavs spawnw without weapon wich make them to stand in a place without doing anything. If you encounter any, feel free to give me wich mags he got in his tactical vest to let me the possibility of investigate the weapon that cause this issue.

For PMC side, there's still a lot of them without weapons, as for now, i'm still investigating the issue and i'm working hard on it to fix it. Sorry for the inconvenience ! Stay tuned for updates ;)

For now bot modding is not available yet, if you want to get the mod working, make a backup of your db/bots folder, and replace it with the new db/bots folder in the archive !

Feel free to send me a DM on Discord if need helps #Sorata
