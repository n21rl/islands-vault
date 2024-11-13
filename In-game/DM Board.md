---
obsidianUIMode: preview
tags:
  - test
---

```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, AC, pasperc As "Pass Perc (WIS)"
where contains(Role, "Player") 
where contains(Status, "Active")
```

```button
name New Journal Entry
type note(NewJournal, split) template
action TemplateJournal
templater true
```
^button-NewJournalID

```button
name New NPC
type note(NewNPC, split) template
action TemplateNPC
templater true
```
^button-NewNPCID

```button
name New Location
type note(NewLocation, split) template
action TemplateSettlement
templater true
```
^button-NewLocationID

```button
name New Guild
type note(NewGroup, split) template
action TemplateGroup
templater true
```
^button-NewGroupID

```button
name New Magic Item
type note(NewMagicItem, split) template
action TemplateMagicItem
templater true
```
^button-NewMagicItemID]