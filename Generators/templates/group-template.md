---
aliases: 
tags: group
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

## Groups within 
```dataview
TABLE
FROM #organisation 
WHERE parent_org = link(this.file.name)
```

## Members of 
```dataview
TABLE role as Role
WHERE contains(join(organisations), this.file.name)
```
