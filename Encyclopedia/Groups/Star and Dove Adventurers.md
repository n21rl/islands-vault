---
tags:
  - group
dg-publish: false
aliases:
  - party
dg-pinned: false
the: true
campaign: "[[Wings on the Wind]]"
---

These adventurers sail on the [[Star and Dove]].

## Members of the Star and Dove Adventurers

### Current
```dataview
TABLE race as Race, class as Class, role as Role, location as Location
WHERE contains(join(affiliations), "Dove") and status = "alive"
```

### Past
```dataview
TABLE race as Race, class as Class, role as Role, location as Location
WHERE contains(join(affiliations), "Star") and status != "alive"
```
