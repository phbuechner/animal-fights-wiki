---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Wasserlog-Gefieder

**Regel:** Immer, wenn dieses Tier einen Angriff deklariert, während es den
Zustand [[Schwimmend]] besitzt, verliert es bis zum Beginn seines nächsten Zuges die Eigenschaften Fliegend und Tarnung.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier"
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````
