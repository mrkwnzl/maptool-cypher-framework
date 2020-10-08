# MapTool Cypher System Framework

A [Cypher System](http://cypher-system.com) framework for [MapTool](https://www.rptools.net). This project is also a playground for me to familiarize myself with GitHub. Expect some inconsistencies as I experiment. 

![Screen Shot](https://github.com/mrkwnzl/maptool-cypher-framework/blob/master/Screen%20Shot.png?raw=true)

## Requirements

The Cypher System Framework requires [MapTool 1.7.0](https://github.com/RPTools/maptool/releases/tag/1.7.0).

## Features

### Character Sheet

- Support for Cypher System Rulebook/Numenera, Gods of the Fall, Predation, and Unmasked.
- Interactive Character Sheet with options for one additional Pool (e.g. Luck), Lasting and Permanent Damage, and Power Shifts.

### Macros

- Dice Macros for stat rolls and generic d6, d10, d20, and d100 rolls. Quick stat rolls skip the difficulty modification.
- Macros to quickly change states.
- Macros for counters and automatic counting during initiative.

### Token

Introduces several token types:

1. PCs: Those are for the player characters and have access to the full character sheet.
2. NPCs: Those are for the non-player characters with NPC character sheets and health bars.
3. Horde/Army: NPC hordes and armies with their respective sheets (from Numenera Destiny).
4. Community: Tokens for communities with its own community sheet (from Numenera Destiny).
5. Counter: Tokens as counters to tally ammo or the duration of effects. Counters can count automatically during the initiative.
6. Marker: Markers are tokens for everything else. All players can control markers and there is no sheet attached.

### Map

- **Grid Area:** All players get ownership of all PC tokens, while only the GM has ownership of NPC tokens.
- **Organisational Area:** Outside the grid, all players and the GM have ownership of all tokens. This is intended for images, handouts, maps.
- **Player Areas:** There are four small pages intended as player areas. Each player has one page for XP tokens, temporary equipments, and Cyphers.
