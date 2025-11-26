---
aliases:
  - Republic
dg-pinned: false
dg-publish: false
parent_grp: "[[Groups]]"
sub_grps:
  - "[[Republic's Council]]"
  - "[[The Bards]]"
  - "[[The Drunks]]"
  - "[[The Night's Embrace]]"
  - "[[The Reed Rangers]]"
  - "[[The Sea Dogs]]"
tags:
  - group
campaign: "[[Wings on the Wind]]"
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
