---
PromptInfo:
 promptId: GenEncounter
 name: 🍻 Generate Encounter 🛏️
 description: Generate a enocunter. 
 author: JoshP
 tags: fantasy, ttrpg
 version: 0.0.1
---

## prompt: Encounter Name
Prompt: Generate a random encounter for Dungeons and Dragons 5e for a party of 5 level 5 players. The theme of the encounter should be appropriate to the {{context}}. 

The encounter should be listed in the exact format provided below if there is an encounter in the room. Remove and or change the monsters used if appropriate. Always write the monsters name as a singular monster, plurals are not supported by the Initiative Tracker plugin. The monsters name must match exactly what is listed in the Monster Manual or rules. Do not add any additional text to the monsters name within the encounter code block. The encounter code block should be at the bottom with all descriptive text above it. 

```encounter
name: Example
creatures:
 - 3: Goblin
 - 1: Orc
```
