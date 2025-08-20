---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Verfolgung (X)

**Regel:** Am Ende deines Zuges erleidet das gegnerische Tier mit der niedrigsten Ausdauer den Effekt X.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier"
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

