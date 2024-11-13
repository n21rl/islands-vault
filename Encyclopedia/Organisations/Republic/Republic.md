---
tag: organisation
dg-publish: false
dg-pinned: false
tags:
  - organisation
aliases:
  - Republic
---
A few pirates crews formed a republic based on the island of [[New Destiny]]. They are working on establishing a Code.

## Organisations within the Republic
```dataview
TABLE
FROM #organisation 
WHERE parent_org = link(this.file.name)
```

## Members
```dataview
TABLE role as Role
WHERE contains(join(organisations), this.file.name)
```
