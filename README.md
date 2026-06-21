# Project readme:
> [!NOTE]
> This is a work-in-progress, unnamed project and **not a complete game**. This isn't a release, there is almost definitely unfinished code, placeholder graphics/dialogue/maps, and credits that aren't up to date.

## Features:
The initial plan for this project was to implement an open world Pokemon game in an entirely new region (currently named Kavora), driven by 'quests' and a semi-structured plot, rather than the linear stories of generation 1-8. I've integrated in & built a number of systems to support this:
- [Level-scaling logic](https://github.com/fisham-org/pokeemerald-expansion-features/wiki/Level-Scaling) (tied into level caps) to allow players to take their own path through the region
- [Quest system](https://github.com/fisham-org/pokeemerald-expansion-features/tree/feature/quest-menu) (**but note that this is 99% just the [psf Unbound Quest Menu](https://github.com/PokemonSanFran/pokeemerald/wiki/Unbound-Quest-Menu) + [belle's quest icons](https://github.com/lienne/pokemon-starbound/commit/6fc1ea7046e10402eb068fb338d2076045b8c104)**)
- [QoL field moves](https://github.com/fisham-org/pokeemerald-expansion-features/wiki/Modern-QoL-Field-Moves) - Pokemon implicitly knowing field moves without being taught the move itself/tools players can use instead of a Pokemon (a modern implementation but **highly influenced by [PSF QoL Field Moves](https://github.com/PokemonSanFran/pokeemerald/wiki/QoL-Field-Moves)**)

I've also implemented other systems that I feel are useful & add to the experience:
- [Bivurnum's Manual EV allocation](https://github.com/TeamAquasHideout/Team-Aquas-Asset-Repo/wiki/Feature-Branches#ev-allocator)
- In-built Nuzlocke mode (a slightly modified version of [NecroDingo's implementation](https://github.com/NecroDingo/pokeemerald-expansion-dingo/wiki/Nuzlocke-Challenge-Implementation))
- [VGC-like Pokemon selection for battles](https://github.com/fisham-org/pokeemerald-expansion-features/wiki/Select-Pokemon-for-Battle)
- [Battle mode selection](https://github.com/fisham-org/pokeemerald-expansion-features/wiki/Battle-Mode-Toggle) (change between singles or doubles battles in options menu)
  - note: there's also a [battle speed toggle feature](https://github.com/rh-hideout/pokeemerald-expansion/commit/00a3328d676c8f77a8e8ed0830860984f4305805) I've added to this, however it's essentially just Pokabbie/The Pit's implementation within [this repo](https://github.com/TeamAquasHideout/pokeemerald/tree/thepit_v2), applied to my options menu extension

## Scope:
I'm currently intended to deliver the following:
### World:
- roughly 17 towns/cities (including 8 gyms & an elite 4-like finale)
- 35 routes
- TBD dungeons (e.g. caves, forests, etc.)
- 3 'main quests' that cover separate themes to explore within the region, TBD sidequests of short/medium length

### Pokedex:
- ~450 Pokemon - unsure if mega evolutions are included yet
- Unsure about custom regional forms/mega evolutions - assuming no
- No fakemon
 
---

# About `pokeemerald-expansion`

![Gif that shows debugging functionality that is unique to pokeemerald-expansion such as rerolling Trainer ID, Cheat Start, PC from Debug Menu, Debug PC Fill, Pokémon Sprite Visualizer, Debug Warp to Map, and Battle Debug Menu](https://github.com/user-attachments/assets/cf9dfbee-4c6b-4bca-8e0a-07f116ef891c) ![Gif that shows overworld functionality that is unique to pokeemerald-expansion such as indoor running, BW2 style map popups, overworld followers, DNA Splicers, Gen 1 style fishing, OW Item descriptions, Quick Run from Battle, Use Last Ball, Wild Double Battles, and Catch from EXP](https://github.com/user-attachments/assets/383af243-0904-4d41-bced-721492fbc48e) ![Gif that shows off a number of modern Pokémon battle mechanics happening in the pokeemerald-expansion engine: 2 vs 1 battles, modern Pokémon, items, moves, abilities, fully customizable opponents and partners, Trainer Slides, and generational gimmicks](https://github.com/user-attachments/assets/50c576bc-415e-4d66-a38f-ad712f3316be)

<!-- If you want to re-record or change these gifs, here are some notes that I used: https://files.catbox.moe/05001g.md -->

**`pokeemerald-expansion`** is a GBA ROM hack base that equips developers with a comprehensive toolkit for creating Pokémon ROM hacks. **`pokeemerald-expansion`** is built on top of [pret's `pokeemerald`](https://github.com/pret/pokeemerald) decompilation project. **It is not a playable Pokémon game on its own.**

# [Features](FEATURES.md)

**`pokeemerald-expansion`** offers hundreds of features from various [core series Pokémon games](https://bulbapedia.bulbagarden.net/wiki/Core_series), along with popular quality-of-life enhancements designed to streamline development and improve the player experience. A full list of those features can be found in [`FEATURES.md`](FEATURES.md).

# [Credits](CREDITS.md)

 [![](https://img.shields.io/github/all-contributors/rh-hideout/pokeemerald-expansion/upcoming)](CREDITS.md)

If you use **`pokeemerald-expansion`**, please credit **RHH (Rom Hacking Hideout)**. Optionally, include the version number for clarity.

```
Based off RHH's pokeemerald-expansion 1.16.0 https://github.com/rh-hideout/pokeemerald-expansion/
```

Please consider [crediting all contributors](CREDITS.md) involved in the project!

# Choosing `pokeemerald` or **`pokeemerald-expansion`**

- **`pokeemerald-expansion`** supports multiplayer functionality with other games built on **`pokeemerald-expansion`**. It is not compatible with official Pokémon games.
- If compatibility with official games is important, use [`pokeemerald`](https://github.com/pret/pokeemerald). Otherwise, we recommend using **`pokeemerald-expansion`**.
- **`pokeemerald-expansion`** incorporates regular updates from `pokeemerald`, including bug fixes and documentation improvements.

# [Getting Started](INSTALL.md)

❗❗ **Important**: Do not use GitHub's "Download Zip" option as it will not include commit history. This is necessary if you want to update or merge other feature branches.

If you're new to git and GitHub, [Team Aqua's Asset Repo](https://github.com/Pawkkie/Team-Aquas-Asset-Repo/) has a [guide to forking and cloning the repository](https://github.com/Pawkkie/Team-Aquas-Asset-Repo/wiki/The-Basics-of-GitHub). Then you can follow one of the following guides:

## 📥 [Installing **`pokeemerald-expansion`**](INSTALL.md)
## 🏗️ [Building **`pokeemerald-expansion`**](INSTALL.md#Building-pokeemerald-expansion)
## 🚚 [Migrating from **`pokeemerald`**](INSTALL.md#Migrating-from-pokeemerald)
## 🚀 [Updating **`pokeemerald-expansion`**](INSTALL.md#Updating-pokeemerald-expansion)

# [Documentation](https://rh-hideout.github.io/pokeemerald-expansion/)

For detailed documentation, visit the [pokeemerald-expansion documentation page](https://rh-hideout.github.io/pokeemerald-expansion/).

# [Contributions](CONTRIBUTING.md)
If you are looking to [report a bug](CONTRIBUTING.md#Bug-Report), [open a pull request](CONTRIBUTING.md#Pull-Requests), or [request a feature](CONTRIBUTING.md#Feature-Request), our [`CONTRIBUTING.md`](CONTRIBUTING.md) has guides for each.

# [Community](https://discord.gg/6CzjAG6GZk)

[![](https://dcbadge.limes.pink/api/server/6CzjAG6GZk)](https://discord.gg/6CzjAG6GZk)

Our community uses the [ROM Hacking Hideout (RHH) Discord server](https://discord.gg/6CzjAG6GZk) to communicate and organize. Most of our discussions take place there, and we welcome anybody to join us!
