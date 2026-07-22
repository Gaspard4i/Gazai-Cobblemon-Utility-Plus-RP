# Gazai's Cobblemon Utility+ Resource Pack

Resource pack that retextures and renames the items from the **Cobblemon Utility+**
mod (modid `cobblemon_utility`) to fit the [Steamon modpack](https://modrinth.com/modpack/steamon) — MC 1.21.1.

## What it changes

- **Bottle caps → Candies**: every IV bottle cap reskinned as a stat-colored candy
  (silver = real Cobblemon IV candy, obsidian = negative IV candy, void, shining, golden, wooden).
- **Shiny Card → Shiny Powder**, **Transmutation Orb**, **Common / Master Candy**,
  **Devolution Wand**, **Ball Synchronizer**, **Golden Aprijuice**,
  **Golden / Stale Poké Snack**, **Apricorn Energy** cans, **Void Vial**, and more.

Languages: English, French, Spanish, German, Italian.

## Structure
- `assets/cobblemon_utility/textures/item/*.png` — item textures (32×32).
- `assets/cobblemon_utility/lang/*.json` — item display names per language.
- `pack.mcmeta` — pack_format 34 (MC 1.21.1).
- `pack.png` — pack icon.

## Usage
Drop the folder (or a zip of it) into `.minecraft/resourcepacks/` and enable it in
Video Settings → Resource Packs, above other packs so its textures win.

## Releasing
Push a tag `vX.Y.Z` — the CI (`.github/workflows/release.yml`) zips the pack and
publishes it to Modrinth (and CurseForge if `CURSEFORGE_ID` / `CURSEFORGE_TOKEN` are set).
