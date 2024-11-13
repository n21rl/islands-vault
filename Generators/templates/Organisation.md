---
aliases: 
tags: organisation
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

## Organisations within _Ship DB
```dataview
TABLE
FROM #organisation 
WHERE parent_org = link(this.file.name)
```

## Members of Organisation
```dataview
TABLE role as Role
WHERE contains(join(organisations), this.file.name)
```
