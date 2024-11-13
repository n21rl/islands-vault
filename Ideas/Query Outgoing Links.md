```dataview
TABLE WITHOUT ID link(file.name) AS Monster
WHERE contains(file.inlinks, this.file.link) AND mechanic_type = "creature"
```

```dataview
TABLE WITHOUT ID link(file.name) AS "Magic Items"
WHERE contains(file.inlinks, this.file.link) AND Type = "Magic Item"
```