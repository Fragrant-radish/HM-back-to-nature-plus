[README.md](https://github.com/user-attachments/files/33919903/README.md)
# Back to nature+

**A mod for Harvest Moon: Back to Nature (PS1, USA)**

Back to nature+ keeps the game you know and adds QOL improvements, a stronger tool tier, farm upgrades that automate tedious actions, coloured hens, new outfits, a new berry and faster boots. Everything uses the game's own art and style. I haven't added any new art into the game all changes where made using the original assests.



<!-- Screenshots: drag images into this file on GitHub's edit page and they appear here -->

## What's new

### Tools
- **Adamantite tier**, above Mythril. Order it from Saibara like the other upgrades.
  - Bigger work areas: hoe 3x6, sickle 7x7, hammer 3x3.
  - The watering can holds 30.
  - The axe gives 18 lumber per stump and uses less stamina.
- Adamantite shows on the Level page and in the farm score, which can now reach 100.

### Gotz's farm upgrades
Each one costs lumber and gold, takes 3 nights to build and a letter arrives in your mailbox when it's done.
- **Bulk shipping:** empty hands + X at a shipping bin ships everything you carry. It also works from the back of the grown horse when you press triangle
- **Reinforce hothouse:** storms and blizzards can't destroy it.
- **Hardwood fences:** lumber you place never rots.
- **Automatic feeders:** troughs for animals inside are filled each night from your fodder stock.
- **Build bridge:** a log bridge to the lake island mine, spring to fall, gone in winter.
- **Expand field:** 190 extra squares east of the stable, plus a water trough by the stable.
- **Enlarge hothouse:** a much deeper hothouse with four big plots.

### Animals
- **Miracle berry:** Won sells it for 10000G. Eat it and your animals stay happy in bad weather and stray dogs won't scare them.
- **Coloured hens:** when you buy a chicken from Lillia pick White, Brown, Lavender or Grey (same price).
  - Chicks grow up in the colour of a hen in your flock.
  - The colour shows everywhere: on the farm, when carried, in the start menu, in Lillia's sell list and in the chicken festival contest. Your rival in the contest is never your colour.
- Hens outside cluck once per visit instead of all the time.
- Best-herd and best-flock festival bonuses, four animals now get the gold badge if they meet the heart requirements. 

### Shopping and outfits
- **New outfits** at the blacksmith, 2000G each, with matching yarn balls: Red, Green, Purple, Black, Aqua, Pink, Yellow, Emerald, Teal and Dark blue, plus the original Overalls.
- **Running boots:** 7000G, help you sprint faster.
- Bulk food from the supermarket goes into the fridge.
- The cabinet is available earlier, the pile of boxes in the first house.

### Fixes to the original game
- Hothouse eggplant (and similar items) no longer show the wrong colours when held overhead.


## How to install

You need your own copy of the game: Harvest Moon: Back to Nature (USA), SLUS-01115, as a .bin/.cue. It must be the clean, unmodified disc:

| | |
|---|---|
| CRC32 | `B0E8F078` |
| SHA-1 | `cb26381fa1336bdd15f07469e59f1143ccf37b03` |

A .chd of the USA disc works too. Turn it back into .bin/.cue first with `chdman extractcd`.

1. Back up your original .bin.
2. Get Delta Patcher (or any xdelta3 patcher).
3. Original file = your clean .bin. Patch file = `Harvest Moon Back To Nature+.xdelta`.
4. Apply. Point your .cue at the new .bin (rename the .bin to match, or edit the .cue's first line).
5. Play on an emulator (DuckStation, ePSXe, etc.) or burn it.

If the patcher says the source file doesn't match, your disc isn't the clean USA version.

Old saves load fine, but keep a copy of your memory card before playing, just in case something breaks.


## Good to know
- The developer debug menu used while making the mod is switched off but it has been translated by me into english.

## Found a bug?
Open an issue in the Issues tab. Say what you were doing, the season and day and which upgrades you had. A screenshot helps a lot.

## Credits
- Mod by Fragrant-radish.
- Built on the Harvest Moon: Back to Nature decompilation by **coalslav** (hmbtn-decomp). Without it this mod would not exist.
- Harvest Moon: Back to Nature is by Victor Interactive Software / Natsume. This mod contains no game files.
