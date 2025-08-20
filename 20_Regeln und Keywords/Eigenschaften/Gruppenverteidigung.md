---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Gruppenverteidigung (X)

**Regel:** Erhält +X Verteidigung, solange du ein anderes Tier derselben [[Gruppierungseigenschaft|Gruppierung]] kontrollierst.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````
