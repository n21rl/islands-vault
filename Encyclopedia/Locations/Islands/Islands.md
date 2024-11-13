---
dg-publish: false
tags:
  - location
the: true
---

The Islands are an archipelago with a warm climates, turquoise waters, and plentiful natural resources. The weather can be unpredictable, with frequent fog and storms. There are rumours of menacing beasts lurking under the sea, and mysterious events seem to happen much more frequently than in the Old Lands. 

## Locations within the Islands
```dataview
TABLE
FROM #location
WHERE parent_loc = link(this.file.name)
```