## Locations within NPC Generator

```dataview
TABLE
FROM #location
WHERE parent_loc = link(this.file.name)
```