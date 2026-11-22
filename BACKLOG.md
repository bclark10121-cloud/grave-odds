# Grave Odds (was Gravehand): backlog

Updated 2026-11-22 (0.4.5). BC decides the order. Plan: `ideas/n65/PLAN.md` in game-studio.

## Done

- 0.4.4 (2026-11-21): renamed Grave Odds with a new page link (the old one forwards). The scoring feel: a run score plate with the best beside it, the full count-up with rising notes, the stained glass fire kill flare, light hit weight, phone buzz on Android, game speed 1x to 4x starting at 2x and the glass shard loot reveal. The rose window start screen, the Crypt glass sound effects and a controller way into the gear and charm slots.

- 0.4.3 (2026-11-21): dark gold cards for the whole deck with gem pips and a corner plate (look C, "move to dark gold"), the hand kept in rank order after every draw, and a charm menu with pictures and descriptions for the reward, the Curio Stall and the swap.

- 0.4.2 (2026-11-21): a new app icon, the spade with the crowned skull on cobalt stained glass (BC picked option B of four). The Game Shelf card shows the same picture. Nothing in the game changed.

- 0.4.1 The look, part 2 (2026-11-21): the map climbs from the bottom with stained glass room medallions and tap a room, Candlelight first, ten floor 2 and 3 monster portraits, a new fight layout that uses the screen (monster card, bigger portrait, damage panel), three floor backdrops, gear and charm icon slots, medallion icons on Play Hand, Discard, Sort and Menu.

- 0.4.0 The look, part 1 (2026-11-21): stained glass art from Nano Banana 2.1 (BC's pick after a side-by-side test). Five floor 1 monster portraits, twelve court cards, four Ace emblems, a new card back, a deck stack, a bigger sideways portrait. Readability first: corner rank and suit always on top.

- 0.3.0 Deeper (2026-11-21): floor 3 The Bell Vaults and the Carrion Clock, all twenty charms, the full gear list, Dread signature lines, the Dread pity rule, stars, daily goals, player level with table and card edge colors, Menu > Progress.

- 0.2.1 (2026-11-21): cards select by tap again (a tap counted twice and dropped the card), panels fit their buttons.

- 0.2.0 The run (2026-11-21): the dungeon map with fair routes, two floors (The Crypt, The Drowned Nave), Fight, Elite, Shrine, Treasure, Rest and Boss rooms, the Ossuary King and the Tollkeeper, gear in four slots and four tiers, ten charms with reorder, rites, three shrines, Tallowgate with the Smith, Mender, Curio Stall and Chapel, the Codex, the full ten achievements, whole-run saves.

- 0.1.0 Gray box fight (2026-11-21): the day one shell, three fights in a row in the Crypt (Crypt Rat, Bone Warden, Lantern Wight), poker hands scored as Force x Fury, damage preview, the monster's next strike shown, free discards, sort by rank or suit, heal 10 after a win, a lost fight ends the run, Candlelight, Dusk and Midnight, ten achievements and six stats, score and best, four-color deck, best hand hint, title font Grenze Gotisch, chant on the start screen and Crypt in fights, upright and sideways, Xbox controller, Android back button.

## Now

- BC plays 0.4.4 on his tablet and phone and sends notes on the new name, the count-up, the kill flare, the loot shard, game speed and the rose window. Notes on earlier releases are still welcome.
- Next: 0.5, Tier 2 from the research, choices (boss omen, omen row, Culling Fire, Tithe box, Weigh scale, plus Curio packs and Waystone boons if BC picks them) and 10 new charms with stained glass images. Research: `docs/research/gravehand_fun_features_2026-11-21.md` in game-studio.
- Then: the town art (the rest of 0.4).
- Release plan (BC, 2026-11-21, 8:27 PM: "over the tier 2 and tier 3, tier 4 releases add 10 new charms and images each release"): 0.5 Tier 2 choices, 0.6 Tier 3 builds, 0.7 Tier 4 replay. Each of those releases adds 10 new charms with their stained glass images (Balatro joker abilities, Gravehand names), each batch with a bot balance run. This replaces the earlier 5 per release.

## Asked for by BC, not built yet

- 1,000 bot runs per difficulty for balance (the rest of 0.3 Deeper shipped in 0.3.0).
- 0.4 Look and sound (the MVP), still to build: the town and drag to reorder the hand. The sound set shipped in 0.4.4. Card faces, the card back and floor 1 monsters shipped in 0.4.0. Floor 2 and 3 monsters, the map and the fight layout shipped in 0.4.1.
- 2026-11-21: "I want to improve the artwork of the front of the cards with the numbers ... should have more diablo design and flare to them". Look C picked. Shipped in 0.4.3.
- 2026-11-21, 5:00 PM: "We need to add joker cards and images for each one. do 5 per release", with a list of about 55 Balatro jokers (common and uncommon). In Gravehand these are charms. BC, 5:14 PM: "Original names" and "if that is what the charms are for that is fine, just want to reuse the abilities". So: new charms with Gravehand names, stained glass medallion icons and the listed abilities in Gravehand's terms (Chips are Force, Mult is Fury, $ is gold). Five per release, each batch with a bot balance run. Suggested first five: the four suit charms and the Pair charm.
- 2026-11-22, 8:57 AM: "add to the backlog to redesign the number cards, the face cards look great, but not sure i love the numbered cards". Redesign the number cards (2 to 10). Keep the face cards and Aces as they are. BC picked Suit glass with tracery on the decision page (9:46 AM). Building in 0.4.5.
- Old saves in the test gate (G5.24): a `tests/saves/` folder with one save per save version. `release_check.py` fails on it today.
- Charm names beside the slots on a tablet held sideways (no room in 0.4.1).

- Small fixes seen in the 0.4.4 look check (not asked for yet, BC decides):
  - The New Rocker "0" on the score plate reads like a bar until the first score.
  - With motion on, the kill flare flames cover "Dusk Armor 1" and the bottom of the health bar for a moment.
  - On the start screen held upright, the kit's key hint line overlaps the altar cards (a kit change in `title_screen.gd`).
  - The browser test's own loot shard pictures catch the gear panel, since headless Chrome draws few frames. The checks still pass.
  - With Text size Large the card corner rank is no bigger on screen than at Normal, since the upright hand cards shrink (fresh review of the card corners, 2026-11-22). G5.26 asks for a quarter more.
  - The count-up row's small cards show the rank at about 12 px, under the 16 px floor (G5.26).
  - The gold card frame and gems still shimmer a little on the small count-up cards (their imports have mipmaps off, 0.4.5 turned them on for the new windows only).
  - The charm panels open with a first guess at their size and settle a few frames later, so a scroll bar can flicker for a moment on the tablet (seen in the 0.4.5 test).
  - Silver spades on silver glass have the least contrast of the four suits. Clubs read softer with red-green colorblindness.

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

- 2026-11-21, 10:37 PM: "the numbers on all the cards need to be smaller or redeigned ... covering the artwork". Held 0.4.4 for it ("Hold 0.4.4 for cards"). 10:47 PM, the card decision page: small corner index, plain bold rank. Built in 0.4.4.
- 2026-11-21, 7:31 PM, the look and sound decision page: icon B (now), start screen scene A the rose window, colors A (now), title font C New Rocker, Game Shelf card A a fight with a hand picked, start screen music A Gregorian Chant (now), fight music C Interloper, sound effects C Crypt glass, a lost fight ends the run (now), tap to pick (now), tagline B "Deal death, one hand at a time.", backup name B Crypt and Card, next A the picks from this page. Font, tagline, fight music and the Shelf card ship in 0.4.3. The rose window start screen and the Crypt glass sounds come in 0.4.4.
- 2026-11-21, 8:41 PM: "Grave Odds, update the game and github with the new name in the next release" (picked from 15 names, a quick web search found no game by that name). Then "New link + redirect": the page repo becomes `grave-odds`, a small `gravehand` repo forwards old links, the app ID (com.brianclark.gravehand) and the save files stay so phones update in place and keep progress. The private source folder stays `games/gravehand`. Ships in 0.4.4.
- 2026-11-21, 7:52 PM, the 0.4.4 decision page (scoring feel): big score A run score plate, count-up A full count, kill flare A stained glass fire, hit weight B light, phone buzz A on by default, game speed B start at 2x, loot reveal A glass shard, after 0.4.4 A Tier 2 choices.

- 2026-11-21, 6:12 PM: "move to dark gold". Face cards and Aces use the dark gold frame too. 6:14 PM: "the initial sort should be by card number and not a random order or by suit". 6:15 PM: "a new menu when choosing a charm to display the charm image and description instead of teh current menu". 6:31 PM: "the gameshelf image needs to be of the game, not the aplk icon" (override 6 ended, the card shows gameplay). All in 0.4.3.

- 2026-11-21, 5:38 PM: "make a new logo and apk for gravehand, dont like the curent one". Four stained glass options on Nano Banana Pro. 5:44 PM: "B for apk image" (the spade and skull). 5:45 PM: "use the same image on teh gameshelf". Shipped as 0.4.2.

- 2026-11-21, 2:53 to 3:08 PM: a new AI Studio chat for the art, better map art for "the branch tree" and the "fight, treaure, elite, boss selections", "start at the bottom for the first levels and make our way up", "easy first" on the difficulty page, "better icons for the discard, sory and play hand" "and menu in top right", and "take advantage of screen space better for horizontal and vertical views. Maybe make the enemy bigger". Of six layout ideas: "do all 6", "do 4 last though".
- 2026-11-21, 4:22 to 4:50 PM: number cards need work. Samples first, then "C: dark diablo cards", then the model: "fast", then "sorry, pro".
- 2026-11-21, 4:52 PM: "approve route" (Gemini art from cloud chats through GitHub, G8.8) and "continue" (ship 0.4.1 now, cards next).
- 2026-11-21, 10:59 AM: "We need to add 2d monsters via gemini in the next release". 0.4 brings Gemini monster art.

- 2026-11-21, 8:18 AM: "a game the combines balatro in a diablo world". Picked card fights on a dungeon path, loot with rarity colors, a dark gothic mood, deeper floors with a town and bosses with twists. Plan home in game-studio.
- 2026-11-21, 8:59 AM: "Use your best judgement and move forward". Claude picked: the name Gravehand, all five override rows, one art set at three floor depths as one area, Trade Blows, 8 cards with 5 played and 3 discards, all charms open from run one, start 0.1 now, look B stained glass, Grenze Gotisch, Gregorian Chant and Crypt. Each can be reversed.
