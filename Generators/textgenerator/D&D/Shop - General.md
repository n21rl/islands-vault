---
PromptInfo:
 promptId: GenStore
 name: 💰 Generate General Shop 🪙
 description: Generate a fantasy general shop. 
 author: Ant
 tags: fantasy, ttrpg
 version: 0.0.1
---

## prompt: Shop  Name
Prompt: Provide a detailed description of this general shop appropriate for the location described by {{context}}. Also provide a description of the shopkeeper and any employees. Mention races and genders. Any proper names should be in bold in Markdown format.

### Wares
Prompt: Create a table in Markdown of an appropriate number (up to 20) of appropriate items that might be found in this shop. Please include columns for: Item Name, Cost and Weight of the items. The cost should be indicated in cp, sp, or gp. Please include up to 5 random trinkets with an appropriate price and weight at the beginning of the table. Then include items from the official Basic Rules of Dungeons and Dragons 5th Edition. Every one of these items should be categorised as Tool, Adventuring Gear, or Equipment Pack in the Basic Rules. For these items, please format the item name as a link to an existing D&D Beyond page by formatting it like this [item name](dndbeyond.com/equipment/ url). Be mindful of the formatting for the url: remove apostrophes and trailing special characters, replace spaces and parentheses with dashes, and never include two dashes in a row.  For example, [Alchemist's Fire (flask)](https://www.dndbeyond.com/equipment/alchemists-fire-flask) or [Rope, Hempen (50 feet)](https://www.dndbeyond.com/equipment/rope-hempen-50-feet). The items should be sorted by price.