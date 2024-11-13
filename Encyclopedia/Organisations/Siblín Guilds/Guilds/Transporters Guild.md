---
tag: organisation
tags:
  - organisation
parent_org: "[[Siblín Guilds]]"
---

## Members
```dataview
TABLE role as Role
WHERE contains(join(organisations), this.file.name)
```