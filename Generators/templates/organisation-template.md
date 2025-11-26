---
aliases: 
tags:
  - group
the: false
---

## Description
Name: 
Political system:
Ruler:
Land:
Religion:
Values:
Inspiration:
History:
Relationships:

## Organisations within `=choice(this.the, "the " + this.file.name, this.file.name)`
```dataview
TABLE
FROM #organisation 
WHERE parent_org = link(this.file.name)
```

## Members of `=choice(this.the, "the " + this.file.name, this.file.name)`
```dataview
TABLE role as Role
WHERE contains(join(organisations), this.file.name)
```
