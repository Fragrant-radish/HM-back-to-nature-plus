# Back to nature+

**A mod for Harvest Moon: Back to Nature (PS1, USA)**

Back to nature+ keeps the game you know and adds QOL improvements, a stronger tool tier, farm upgrades that automate tedious actions, coloured hens, new outfits, a new berry and faster boots. Everything uses the game's own art and style. I haven't added any new art into the game all changes were made using the original assets.

**[Download the latest version](../../releases/latest)**

**[Back to nature+ v1.1.1 — patches and readmes](https://github.com/Fragrant-radish/HM-back-to-nature-plus/releases/tag/v1.1.1)**

## v1.1.1 hotfix (28 Oct 2026)
- Fixes the wife's name on the summary page (the Start menu). Since v1.0 it showed a wrong name (for example "JO") for anyone married and could potentially freeze the game. Nothing else is changed.
- Same patch, same install steps. If you already play v1.1, apply this one to your clean disc instead, your saves carry over.
- The stand-alone Farm score fix has the same correction in its new version.

## New in v1.1

### Rucksack stacks

- Open the **Options** window, its located at the bookshelf of your house. Pick **Rucksack**. It's a permanent choice for that save:
  - **Classic:** the original bag.
  - **Stacks:** 9 of a kind in a slot. Once you own the biggest rucksack, the supermarket sells the **Rucksack+** for 33333G, which raises it to 99.
  - **Stacks 99:** 99 of a kind in a slot from the start (no Rucksack+).

The entry disappears once you've chosen. Old saves also get a choice when you open options.
- What stacks: things of the same kind and quality. Crops, flowers, weeds, dishes, eggs, milk, wool, fish, ores, fodder. 
- Your hands always hold one item. **R2** with empty hands takes one from the first stack in the bag, if you put it back, it merges again and that stack moves to the end of the bag. This feels intuitive and works well for the game. Counts show on the menu screen, fridge, cabinet and kitchen. 
**Select** on a bag slot throws a whole stack away, it will ask you first. 
- Bulk shipping ships whole stacks. Events that take things from you (Ann's eggs and the mayors requests) take them from your stacks in any order.

### Text speed
- **Options > Text speed: Normal or Fast.** Fast makes the text about 6 times faster than the original while you hold x. Every box still waits for you to press X again, nothing is skipped.

### Farm score
- The farm score on the summary page can now reach **100** the way the game intended. Each Power Berry you eat counts 1 (there are 10) and the Mystic Berry counts as 2. In the original the berries were never added, so the score stopped at 88. In v1.0, I had made Adamantite/outfit bonus reach 100%; the score is the game's own formula again.
- If you only want this fix see **Farm score fix** below.




<!-- Screenshots: drag images into this file on GitHub's edit page and they appear here -->

## What's new

### Tools
- **Adamantite tier**, above Mythril. Order it from Saibara like the other upgrades.
  - Bigger work areas: hoe 3x6, sickle 7x7, hammer 3x3.
  - The Adamantite can waters 36 squares.
  - The axe gives 18 lumber per stump and uses less stamina.
  - The hammer patches 3x3 tilled fields.
- Adamantite shows on the Level page and in the farm score.

### Gotz's farm upgrades
Each one costs lumber and gold, takes 3 nights to build and a letter arrives in your mailbox when it's done.
- **Bulk shipping:** empty hands + X at a shipping bin ships everything you carry. It also works when you're on the back of a grown horse and press triangle
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
- Hothouse eggplant and similar items no longer show the wrong colours when carried overhead.
- The farm score can reach 100%. The original never added the power berries or the mystic berry to the score, so it stopped at 88%.

## How to install

You need your own copy of the game: Harvest Moon: Back to Nature (USA), SLUS-01115, as a .bin/.cue. It must be the clean, unmodified disc:

| | |
|---|---|
| CRC32 | `B0E8F078` |
| SHA-1 | `cb26381fa1336bdd15f07469e59f1143ccf37b03` |

A .chd of the USA disc works too. Turn it back into .bin/.cue first with `chdman extractcd`.

1. Back up your original .bin.
2. Get Delta Patcher (or any xdelta3 patcher).
3. Original file = your clean .bin. Patch file = `Harvest.Moon.Back.To.Nature.Plus.v1.1.1.xdelta`.
4. Apply. Point your .cue at the new .bin (rename the .bin to match, or edit the .cue's first line).
5. Play on an emulator (DuckStation, ePSXe, etc.) or burn it.

If the patcher says the source file doesn't match, your disc isn't the clean USA version.

Old saves load fine, but keep a copy of your memory card before playing, just in case something breaks.


## Farm score fix (stand-alone)

A separate one-change patch for people who want the **original game with only the farm score fixed**: Power berries count 1 each and the mystic berry 2, so a complete farm reads 100% instead of 88%. Nothing else is changed. It's applied to the clean disc the same way. Not needed with Back to nature+ v1.1, which already has the fix.


## Good to know
- The Rucksack choice is one per save. To try another mode, start a new game.
- The developer debug menu used while making the mod is switched off but it has been translated into english.

## Found a bug?
Open an issue in the Issues tab. Say what you were doing, the season and day and which upgrades you had. A screenshot helps a lot.

## Credits
- Mod by Fragrant-radish.
- Built on the Harvest Moon: Back to Nature decompilation by **coalslav** (hmbtn-decomp). Without it this mod would not exist.
- Harvest Moon: Back to Nature is by Victor Interactive Software / Natsume. This mod contains no game files.
