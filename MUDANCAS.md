# Changelog — v2.0.0-beta.04, NeoForge 1.21.1 Mod Updates and Modpack Cleanup

## Add
- Add [Custom Player Animations](https://modrinth.com/mod/EhthJpjM) `5.9.10` to improve player animation customization and visual movement improvements [Modrinth](https://modrinth.com/mod/cpa/version/5.9.10-neoforge%2B26.1.2?utm_source=chatgpt.com)
- Add [Building Gadgets 2](https://www.curseforge.com/projects/298187) `1.3.9` to provide additional building and construction utilities
- Add [Petting - Tame any mob!](https://modrinth.com/mod/) `4.2.2` to allow players to tame and interact with additional mobs

## Removed
- Remove [InvMove] due to no longer being included in the modpack
- Remove [Tropicraft] due to server performance concerns caused by adding another world dimension

## Updated
- Update [Player Animation Library](https://modrinth.com/mod/ha1mEyJS) migration to the NeoForge version to maintain compatibility with [Custom Player Animations](https://modrinth.com/mod/EhthJpjM)
- Update the mod list to reflect newly added and removed mods
- Update the version file for the `v2.0.0-beta.04` release

## MISC
- Cleanup duplicated dependencies by keeping shared libraries only in the required mods section
- Remove duplicate optional dependency entries already provided by the mandatory modpack installation
- Improve modpack organization by reducing redundant dependency declarations

**Updated systems**

- Gameplay and visual improvements:
  - New player animation features through [Custom Player Animations](https://modrinth.com/mod/EhthJpjM)
  - New construction utilities with [Building Gadgets 2](https://www.curseforge.com/projects/298187)
  - Additional mob interaction features with [Petting - Tame any mob!](https://modrinth.com/mod/)

- Compatibility and dependency improvements:
  - Migrated [Player Animation Library](https://modrinth.com/mod/ha1mEyJS) to the NeoForge ecosystem
  - Removed duplicated dependencies:
    - [Architectury](https://modrinth.com/mod/lhGA9TYQ)
    - [Cloth Config v15 API](https://modrinth.com/mod/9s6osm5g)
    - [CreativeCore](https://modrinth.com/mod/OsZiaDHq)
    - [Fzzy Config](https://modrinth.com/mod/hYykXjDp)
    - [Kotlin for Forge](https://modrinth.com/mod/ordsPcFz)
    - [MezzConfig](https://modrinth.com/mod/7tEfOcA7)
    - [Simply Tooltips](https://modrinth.com/mod/6avVoBVB)
    - [SuperMartijn642's Config Library](https://modrinth.com/mod/LN9BxssP)