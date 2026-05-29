# RuneForge Studio: City NPC Collection

**10 fully developed D&D 5e NPCs for urban campaigns.**

- **Tiers:** A (3), B (5), C (2)
- **Foundry VTT:** v12+ | **dnd5e system:** v3.3–5.3
- **Compendiums:** NPCs (Actors) + GM Journal

## Contents

| NPC | Tier | CR | Role |
|-----|------|----|------|
| Quilby "Quick" Thistledown | A | 1/2 | Tavern keeper & information broker |
| "Needle" Voss | A | 3 | Arcane trickster & guild asset |
| Lady Elira Storme | A | 3 | Council matriarch |
| Lady Orvaine | A | 4 | Council rival |
| Faelar Ironbloom | B | 1 | Elf master bowyer & quest giver |
| Brunna Rootmantle | B | 1/4 | Dwarf farmer & market baker |
| Garron Vale | B | 1 | Former watch lieutenant |
| Marla Crowshade | B | 1 | Urban warlock |
| Finnan | B | 1 | Half-elf street bard |
| Leoric Bramwell | C | 1/2 | Spice merchant & charlatan |

## Installation (GitHub Release)

In Foundry VTT → Add-on Modules → Install Module, paste the manifest URL:
```
https://github.com/runeforgestudio/city-npc-collection/releases/latest/download/module.json
```

## Manual Installation

1. Download `module.zip` from the GitHub Release
2. Extract it so that `runeforgestudio-city-npcs/module.json` is inside your `Data/modules/` folder
3. Restart Foundry and enable the module in your world

## Adding Images

The module ships without token/portrait images due to CDN restrictions.
To add images:

1. Download the token PNGs from your RuneForge Studio blog posts
2. Place them in `Data/modules/runeforgestudio-city-npcs/assets/tokens/` as:
   - `quilby-quick-thistledown.png`
   - `needle-voss.png`
   - `faelar-ironbloom.png`
   - `brunna-rootmantle.png`
   - `lady-elira-storme.png`
   - `garron-vale.png`
   - `marla-crowshade.png`
   - `leoric-bramwell.png`
   - `finnan.png`
   - `lady-orvaine.png`
3. Copy the same files into `assets/portraits/`
4. Reimport the module compendium (or update each actor's image manually)

## Building from Source

Push to a GitHub repo and create a version tag:
```bash
git tag v1.0.0
git push origin v1.0.0
```
GitHub Actions compiles the JSON source files into LevelDB packs and attaches
`module.json` + `module.zip` to the release automatically.

## License

Original content © 2026 RuneForge Studio. All rights reserved.  
Game mechanics under CC-BY-4.0 (D&D 5e SRD 5.1).
