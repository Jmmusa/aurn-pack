Folk of Aurn skins
==================
Drop 64x64 Minecraft skin PNGs into the folder of the people they belong to:

  assets/aurnfolk/textures/entity/folk/<folder>/<any name>.png

Folders: frostborne emberkin sylvani duskborn grokh nimtouched vigilborn unfallen thalassi
         screamborn endling divinity shadowlord citizen citizen/sazane citizen/aldergear merchant bandit
         pirate pirate/captain
         dreadknight cultist fallen reaver (warbands; their warlords use <race>/leader)

Each NPC picks one skin from its folder. As soon as a folder holds one of your skins,
the built-in placeholders for it stop being used. Then press F3+T in game (no restart).

Models: elves (sylvani, duskborn) use the slim Alex arms, everyone else uses Steve arms.
Put "_slim" or "_wide" in a file name to override that for one skin.
Emberkin are drawn at about 3/4 height, so any normal skin becomes a dwarf.

Ranks have their own sub-folders: <race>/knight, <race>/guard, <race>/noble, <race>/leader
(e.g. sylvani/noble, citizen/knight, citizen/aldergear/leader). An empty folder falls back to
its parent, so a knight without knight skins wears the people's ordinary skins.
Named nobles and leaders wear the file named in config/aurnfolk-spawns.json ("skin").
Skins on drive E: are sorted in by AURN_tools/modwork/import_skins.py.
