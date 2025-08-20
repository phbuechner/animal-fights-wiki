---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Einzigartig

**Regel:** Von dieser Karte darf nur 1 Kopie pro Deck enthalten sein.
## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

