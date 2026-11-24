# Kralnu Assets

Shared art and audio for **Kralnu Games** projects.

Only assets that are free for commercial use go in here: **CC0** (no credit needed) or **CC-BY** (credit needed). The licence file for each pack stays inside its folder. Every pack is listed in [CREDITS.md](CREDITS.md).

## How it's used

Games don't link to this repo directly. When a game needs an asset, copy just the files it uses into that game's own repo, keeping the folder structure, so a game never breaks if something here is moved or renamed.

Every pack folder has a `Preview.png` showing what's inside. Most 2D packs come in a few versions:
- `PNG/`: separate image files, the easiest to use.
- `Spritesheet/` or `Tilesheet/`: everything on one big image, usually with an `.xml` file listing where each piece is. These are better for performance.
- `Vector/`: SVG files that stay sharp at any size.

## KayKit packs (by Kay Lousberg, all CC0)

Chunky, colourful low-poly 3D, all in the `kaykit/` folder. Models come as `gltf` (best for web games and three.js; keep each `.bin` file and texture next to its `.gltf`), `fbx` and `obj`.

| Pack | What's in it |
|---|---|
| [adventurers](kaykit/adventurers) | 6 rigged heroes (Knight, Barbarian, Mage, Ranger, Rogue, Hooded Rogue) plus swords, axes, bows, crossbows, shields, staffs and mugs. The animations are in separate files under `Animations/` (general and basic movement sets). |
| [forest-nature](kaykit/forest-nature) | 200+ trees, dead trees, bushes, grass and rocks in several colour variants. |
| [dungeon-pack](kaykit/dungeon-pack) | 180+ modular dungeon pieces (floors, walls, doors, stairs, scaffolds, chests, traps, loot, potions) plus 4 characters (Knight, Mage, Barbarian, Rogue) with extra heads. |
| [mini-game-variety](kaykit/mini-game-variety) | Bright platformer and party-game kit: coloured tiles, hurdles, rings, balls, spikes and pickups, plus Bear, Dog and Duck characters. |

The Dungeon and Mini-Game packs include official KayKit logos in `KayKit Brand Resouces/`. Kay suggests putting one in your credits as a thank-you.

## Kenney packs (all CC0)

### 3D
| Pack | What's in it |
|---|---|
| [mini-characters](kenney/mini-characters) | 20 chunky low-poly characters plus weapons and props. Fully animated: walk, sprint, jump, punches, kicks, drive, die and more. GLB, FBX and OBJ formats. |
| [mini-dungeon](kenney/mini-dungeon) | Low-poly dungeon kit: walls, floors, stairs, gates, chests, traps, barrels, coins, potions, plus a human and an orc character. |

### Characters & creatures (2D)
| Pack | What's in it |
|---|---|
| [modular-characters](kenney/modular-characters) | Mix-and-match character parts: heads, hair, faces, bodies, arms and legs in several skin tones and outfits. See `instruction.png`. |
| [monster-builder-pack](kenney/monster-builder-pack) | Build-your-own monsters: bodies, eyes, mouths, horns, arms and legs in 6 colours. |

### Board, card & tabletop (great for the Grand Compendium)
| Pack | What's in it |
|---|---|
| [boardgame-pack](kenney/boardgame-pack) | Full playing-card deck and backs, dice, poker chips and pawns/pieces in 7 colours. `Bonus/` has sound effects for cards, chips and dice. |
| [board-game-icons](kenney/board-game-icons) | 250+ white icons for board games: resources, actions, dice faces, arrows, cards, tokens. |
| [puzzle-pack-1](kenney/puzzle-pack-1) | Coloured gems, bricks and blocks for match-3, breakout and puzzle games. |

### Environments & tiles (2D)
| Pack | What's in it |
|---|---|
| [background-elements](kenney/background-elements) | Clouds, trees, hills, mountains and castles for layered side-on backgrounds. |
| [racing-pack](kenney/racing-pack) | Top-down racing: road and track tiles, cars, motorbikes, barriers, cones and trees. |
| [sports-pack](kenney/sports-pack) | Balls, players and kit for lots of sports, plus pitch and court ground tiles in 10 colour schemes. |
| [roguelike-caves-dungeons](kenney/roguelike-caves-dungeons) | Pixel-art tilesheet for caves and dungeons (16px tiles). |
| [roguelike-indoors](kenney/roguelike-indoors) | Pixel-art tilesheet for house interiors and furniture (16px tiles). |

### Items & effects
| Pack | What's in it |
|---|---|
| [generic-items](kenney/generic-items) | 100+ everyday item icons: tools, food, gadgets, books, kitchenware and more. |
| [particle-pack](kenney/particle-pack) | Smoke, fire, sparks, magic, flares, stars and explosions, on transparent and black backgrounds. |

### UI (menus, buttons, panels)
| Pack | What's in it |
|---|---|
| [ui-pack](kenney/ui-pack) | Clean all-purpose buttons, sliders, checkboxes and panels in several colours. Includes the **Kenney Future** fonts and click/tap sounds. |
| [ui-pack-adventure](kenney/ui-pack-adventure) | Wood, parchment and metal fantasy panels, banners, bars and minimap frames. |
| [ui-pack-pixel-adventure](kenney/ui-pack-pixel-adventure) | Pixel-art version of the adventure UI. |
| [ui-pack-rpg-expansion](kenney/ui-pack-rpg-expansion) | RPG panels, bars, buttons, arrows and cursors in brown, beige and grey. |
| [ui-pack-space-expansion](kenney/ui-pack-space-expansion) | Sci-fi panels, bars and buttons, with fonts. |
| [fantasy-ui-borders](kenney/fantasy-ui-borders) | Decorative fantasy frames, borders and dividers. |

## Tidy-up notes

Removed from the original zips because they're no use in web games: old Flash (`.swf`), Illustrator (`.ai`) and Unity (`.unitypackage`) files, Unity-only `fbx(unity)` copies, Collada (`.dae`) copies, Windows `Thumbs.db` files, web shortcut (`.url`) files and Kenney's offline overview pages. Nothing else was changed.

## Kept out of this repo on purpose

Some free assets don't allow re-sharing the files themselves, so they can't sit in a public repo. They're listed in [CREDITS.md](CREDITS.md) with their terms, so we remember the rules when a game uses them.
