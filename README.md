# Gazai Cobblemon Utility+ Resource Pack

Resource pack for the **Cobblemon Utility+** mod (modid `cobblemon_utility`) — MC 1.21.1 NeoForge.

Retextures (and optionally renames) the mod's items: IV bottle caps, EV items,
Golden Cap, Shiny Card, candies, relics, etc.

## Structure
- `assets/cobblemon_utility/textures/item/*.png` — the item textures (originals
  included as a base, repaint them).
- `assets/cobblemon_utility/lang/en_us.json` — item display names. Edit the
  values to rename items (e.g. `"item.cobblemon_utility.goldencap": "Gold Cap"`).
- `pack.mcmeta` — pack_format 34 (MC 1.21.1).

## Usage
Drop the folder (or a zip of it) into `.minecraft/resourcepacks/` and enable it
in Video Settings > Resource Packs. Load it ABOVE other packs so its textures win.

## Renaming items
A resource pack CAN rename items via the lang file — edit
`assets/cobblemon_utility/lang/en_us.json`. Add `fr_fr.json` etc. for other languages.
