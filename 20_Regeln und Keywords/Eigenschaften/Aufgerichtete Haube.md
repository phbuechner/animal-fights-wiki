---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Aufgerichtete Haube

**Regel:** Wenn dieses Tier einen [[Einschüchterung-Test]] durchführt, addiert es
seine Basis-[[Agilität]] anstelle seiner Sternenanzahl zum Ergebnis.
## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

