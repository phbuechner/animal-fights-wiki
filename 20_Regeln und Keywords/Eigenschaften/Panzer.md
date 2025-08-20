---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Panzer (X)

**Regel:** Reduziert allen erlittenen Schaden aus Angriffen um den angegebenen Wert (X).

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````


