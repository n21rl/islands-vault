## Description

## Locations within `=choice(this.the, "the " + this.file.name, this.file.name)`
```dataview
TABLE
FROM #location 
WHERE parent_org = link(this.file.name)
```