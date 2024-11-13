---
PromptInfo:
 promptId: GenArmory
 name: 🎲 Generate Armory 🛡️
 description: Generate a fantasy store that sells armor and weapons. 
 author: Ant
 tags: fantasy, ttrpg
 version: 0.0.1
---

## prompt: Shop  Name
Prompt: Provide a detailed description of this shop that could be located in the place described by {{context}}. It should be a shop selling armor, shield, and weapons. Provide a description of the shopkeeper and any employees. Mention races and genders. Any proper names should be in bold in Markdown format.

### Wares
#### Standard weapons and armour
Prompt: Create a table in Markdown of an appropriate number (up to 15) of appropriate items that might be found in this shop. Please include items from the official Basic Rules of Dungeons and Dragons 5th Edition. Every one of these items should be categorised as Weapon, Armor, or Shield in the Basic Rules. Please include columns for: Item Name, Cost, Type, Damage/AC, Properties. Please format the item name as a link to an existing D&D Beyond page by formatting it like this [item name](dndbeyond.com/equipment url). The damage column should mention damage amount and type. The items should be sorted by price.

#### Magic weapons and armour
Prompt: Create a table in Markdown of an appropriate number (up to 10) of appropriate items that might be found in this shop. Please include magic items from the official rules of Dungeons and Dragons 5th Edition that are categorised as Weapon, Armor, or Wondrous Item. The items should be primarily Common and Uncommon items, however please include at least one Rare item. Please include columns for: Item Name, Cost, Type, Damage/AC, Properties. Please format the item name as a link to an existing D&D Beyond page by formatting it like this [item name](https://www.dndbeyond.com/magic-items url). The cost column should contain a random cost based on the Dungeon Master's Guide rules. The properties column should contain a very short description of the item and mention wether the item requires attunement. The items should be sorted by price.