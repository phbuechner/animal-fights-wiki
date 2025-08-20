---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Finte

**Regel:** Immer, wenn ein Angriff auf dieses Tier fehlschlägt, verliert der Angreifer 1 [[Ausdauer]].

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

