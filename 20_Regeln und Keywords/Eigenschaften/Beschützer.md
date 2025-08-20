---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Beschützer (X)

**Regel:** Andere deiner Tiere mit einer Basis-Gesundheit von X oder weniger können nicht als Ziel von Angriffen oder Spezialaktionen gewählt werden.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

