---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Ausguck

**Regel:** In Arenen mit dem Keyword [[Höhenlage (Keyword)|Höhenlage]] verlieren gegnerische Tiere die Eigenschaft [[Lauerjäger]] und [[Tarnung]].
## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

