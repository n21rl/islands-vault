---
tags:
  - organisation
dg-publish: false
aliases:
  - party
dg-pinned: false
the: true
---

Collectively referred to as "the party", these adventurers are the heroes of the story. They sail on the [[Star and Dove]].

## Members of the party

### Current
```dataview
TABLE race as Race, class as Class, role as Role, location as Location
WHERE contains(join(organisations), "Adventurers") and status = "alive"
```

### Past
```dataview
TABLE race as Race, class as Class, role as Role, location as Location
WHERE contains(join(organisations), "Adventurers") and status != "alive"
```