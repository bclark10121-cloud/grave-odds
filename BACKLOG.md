# Gravehand: backlog

Updated 2026-11-21 (0.4.1). BC decides the order. Plan: `ideas/n65/PLAN.md` in game-studio.

## Done

- 0.4.1 The look, part 2 (2026-11-21): the map climbs from the bottom with stained glass room medallions and tap a room, Candlelight first, ten floor 2 and 3 monster portraits, a new fight layout that uses the screen (monster card, bigger portrait, damage panel), three floor backdrops, gear and charm icon slots, medallion icons on Play Hand, Discard, Sort and Menu.

- 0.4.0 The look, part 1 (2026-11-21): stained glass art from Nano Banana 2.1 (BC's pick after a side-by-side test). Five floor 1 monster portraits, twelve court cards, four Ace emblems, a new card back, a deck stack, a bigger sideways portrait. Readability first: corner rank and suit always on top.

- 0.3.0 Deeper (2026-11-21): floor 3 The Bell Vaults and the Carrion Clock, all twenty charms, the full gear list, Dread signature lines, the Dread pity rule, stars, daily goals, player level with table and card edge colors, Menu > Progress.

- 0.2.1 (2026-11-21): cards select by tap again (a tap counted twice and dropped the card), panels fit their buttons.

- 0.2.0 The run (2026-11-21): the dungeon map with fair routes, two floors (The Crypt, The Drowned Nave), Fight, Elite, Shrine, Treasure, Rest and Boss rooms, the Ossuary King and the Tollkeeper, gear in four slots and four tiers, ten charms with reorder, rites, three shrines, Tallowgate with the Smith, Mender, Curio Stall and Chapel, the Codex, the full ten achievements, whole-run saves.

- 0.1.0 Gray box fight (2026-11-21): the day one shell, three fights in a row in the Crypt (Crypt Rat, Bone Warden, Lantern Wight), poker hands scored as Force x Fury, damage preview, the monster's next strike shown, free discards, sort by rank or suit, heal 10 after a win, a lost fight ends the run, Candlelight, Dusk and Midnight, ten achievements and six stats, score and best, four-color deck, best hand hint, title font Grenze Gotisch, chant on the start screen and Crypt in fights, upright and sideways, Xbox controller, Android back button.

## Now

- BC plays 0.1 and sends notes on the feel and the difficulty.
- BC plays 0.2 and sends notes on the run, the loot and the difficulty.
- BC plays 0.4.1 on his tablet and phone and sends notes on the map, the fight layout and the slots.
- Next: 0.4.2 number cards. BC picked look C, dark Diablo cards. The Pro pictures are in `art_src/nb21/cards/`. First BC picks between face cards on bone and face cards on the dark gold frame.
- Then: the town art and the sound set (the rest of 0.4).

## Asked for by BC, not built yet

- 0.3 Deeper: floor 3 and the Carrion Clock, all twenty charms, all gear lines and Dread items, 1,000 bot runs per difficulty for balance, stars, daily goals, player level cosmetics.
- 0.4 Look and sound (the MVP), still to build: number cards (0.4.2), the town, the sound set, drag to reorder the hand. Card faces, the card back and floor 1 monsters shipped in 0.4.0. Floor 2 and 3 monsters, the map and the fight layout shipped in 0.4.1.
- 2026-11-21: "I want to improve the artwork of the front of the cards with the numbers ... should have more diablo design and flare to them". Look C picked. Comes in 0.4.2.
- 2026-11-21, 5:00 PM: "We need to add joker cards and images for each one. do 5 per release", with a list of about 55 Balatro jokers (common and uncommon). In Gravehand these are charms. BC, 5:14 PM: "Original names" and "if that is what the charms are for that is fine, just want to reuse the abilities". So: new charms with Gravehand names, stained glass medallion icons and the listed abilities in Gravehand's terms (Chips are Force, Mult is Fury, $ is gold). Five per release, each batch with a bot balance run. Suggested first five: the four suit charms and the Pair charm.
- Old saves in the test gate (G5.24): a `tests/saves/` folder with one save per save version. `release_check.py` fails on it today.
- A controller way to open a gear or charm slot in the fight (0.4.1 opens them by tap. Menu > Charms and gear shows the same text).
- Charm names beside the slots on a tablet held sideways (no room in 0.4.1).
- The look and sound decision page (G0.16). 0.1 used best judgement picks.

## Ideas to choose from (BC picks by number)

1. A daily seeded run everyone gets the same.
2. Town upgrades between runs (cosmetic only, G4.20).
3. Card etching: Honed, Bloodied and Shrouded cards.
4. A second hero with a different starting deck.
5. A Suno or Patch.gg boss track.

## Later

- More bosses: the Rust Abbot, the Magpie Queen, the Leech Count, the Shrouded One.
- Gear sets and an heirloom slot.

## Not planned (they break the pillars)

- Gore or jump scares.
- Betting, chips or a casino look.

## Decisions from BC

- 2026-11-21, 2:53 to 3:08 PM: a new AI Studio chat for the art, better map art for "the branch tree" and the "fight, treaure, elite, boss selections", "start at the bottom for the first levels and make our way up", "easy first" on the difficulty page, "better icons for the discard, sory and play hand" "and menu in top right", and "take advantage of screen space better for horizontal and vertical views. Maybe make the enemy bigger". Of six layout ideas: "do all 6", "do 4 last though".
- 2026-11-21, 4:22 to 4:50 PM: number cards need work. Samples first, then "C: dark diablo cards", then the model: "fast", then "sorry, pro".
- 2026-11-21, 4:52 PM: "approve route" (Gemini art from cloud chats through GitHub, G8.8) and "continue" (ship 0.4.1 now, cards next).
- 2026-11-21, 10:59 AM: "We need to add 2d monsters via gemini in the next release". 0.4 brings Gemini monster art.

- 2026-11-21, 8:18 AM: "a game the combines balatro in a diablo world". Picked card fights on a dungeon path, loot with rarity colors, a dark gothic mood, deeper floors with a town and bosses with twists. Plan home in game-studio.
- 2026-11-21, 8:59 AM: "Use your best judgement and move forward". Claude picked: the name Gravehand, all five override rows, one art set at three floor depths as one area, Trade Blows, 8 cards with 5 played and 3 discards, all charms open from run one, start 0.1 now, look B stained glass, Grenze Gotisch, Gregorian Chant and Crypt. Each can be reversed.
