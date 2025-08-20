---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Erster Schlag

**Regel:** Der erste Angriff, den dieses Tier in jeder Runde deklariert, kann nicht durch die Abwehrens-Reaktion begegnet werden (nur Ausweichen ist erlaubt).

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

