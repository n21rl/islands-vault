## Organisations within NPC Generator

```dataview
TABLE
FROM #organisation 
WHERE parent_org = link(this.file.name)
```