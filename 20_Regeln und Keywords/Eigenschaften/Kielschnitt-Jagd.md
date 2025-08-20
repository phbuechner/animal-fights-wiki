---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Kielschnitt-Jagd

**Regel:** Deine Angriffe zielen nicht mehr auf ein einzelnes Tier. Stattdessen wähle bis zu 2 gegnerische Tiere in dieser Arena. Jedes dieser Tiere erleidet 1 [[Direkter Schaden|direkten Schaden]]. Dieser Schaden ignoriert die Eigenschaft [[Tarnung]], wenn sie durch ein [[Terrain-Keyword]] gewährt wird, dass die Kielschnitt-Jagd ermöglicht.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````


