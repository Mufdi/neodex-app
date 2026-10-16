# NEODEX for Android

Free companion app for [PokeMMO](https://pokemmo.com): analysis, calculators, breeding planner,
zone encounters and more. The same tools as [neodex.tools](https://neodex.tools), on your phone.
The game data ships with the app; **100% offline mode** in the menu also downloads the images and
cries, so the app works without a network.

This repository only hosts the app's releases. NEODEX is a fan project, not affiliated with
PokeMMO, Nintendo, Game Freak or The Pokémon Company.

## Features

**Home**
- In-game clock, day phase and season, with the changes coming in the next cycles.
- Roaming legendaries of the month, where they are and the upcoming rotations.
- Live alpha spawns, encounters by season, official events and forum news.

**Dex**
- **Mondex**: analysis of every species: stats, types, abilities, moves, evolutions and locations.
- **Itemdex**: every item, what it does and who holds it.
- **Movedex**: every move with power, accuracy, PP and type, and who learns it by each method.
- **Abilitydex**: every ability and the species that have it, regular and hidden.
- **Advanced search**: combine filters across combat (types, abilities, moves by learn method and kind, role, tier, held items), stats (ranges), biology (egg groups, gender, alpha) and location (region, zone, encounter type, rarity, season, time, hordes).
- **Compare**: up to 10 Pokémon side by side.

**Encounters**
- Interactive map of every zone: encounters by location, season, time of day and method.

**Calculators**
- **Capture**: catch chance by ball, HP, status and turn.
- **Stats**: final stats by level, IVs, EVs and nature.
- **Growth**: experience between levels, Rare Candies and growth curve.
- **Damage**: a move's damage range between two Pokémon and the chance to knock out.
- **Types**: offensive and defensive matchups for one or two types.
- **Coverage**: what a moveset hits, what resists it and who can carry it.
- **Egg moves**: the breeding chain that brings a move to the species you want.

**Utilities**
- **EV training**: plan a spread with vitamins, wings, reducing berries and the Macho Brace, hordes left and where to fight them.
- **Rock Smash**: log what each rock gives you and compare your rates by region and route.

**Team Builder**
- Build teams and see which formats they fit.

**Breeding**
- Breeding projects ledger with cost calculator and your own price catalog.

**Only in the app**
- **100% offline mode**: downloads the images and cries so the app works without a network.
- **Floating window**: NEODEX as a bubble over the game, to look things up without leaving it.
- Use it without an account; sign in to keep your teams and breeding projects across devices.

## Download

Get the latest APK from [Releases](../../releases/latest). Each release has one APK per processor
type plus a universal one, and lists every file's SHA-256 so you can check the download.

| File | For |
|---|---|
| `neodex-<version>-arm64-v8a.apk` | Almost every phone from the last ~8 years. **Pick this one if unsure.** |
| `neodex-<version>-armeabi-v7a.apk` | Older 32-bit phones. |
| `neodex-<version>-x86_64.apk` / `-x86.apk` | Chromebooks and x86 tablets. |
| `neodex-<version>-universal.apk` | Any of the above; larger download. |

1. Download the APK on your Android phone (Android 7.0 or later).
2. Open it. Android asks to allow installs from that source (your browser or file manager) the
   first time.
3. Install. Later versions install over the previous one and keep your data.

## What it does not do

- It does not modify, patch or inject into the game client, and does not read its memory.
- It does not read, intercept or change the network traffic between the client and the servers.
- It does not connect to the game servers and does not automate anything in the game.

Its data comes from the official data dump the game client exports from its Utilities menu, from
public information in the PokeMMO forum, and from data curated by hand.

## Support

NEODEX is free and has nothing to buy. If you want to support it: [Ko-fi](https://ko-fi.com/L5L826RYEB).
