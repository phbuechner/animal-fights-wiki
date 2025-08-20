---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Einzelgänger

**Regel:** Solange dieses Tier dein einziges Tier im Spiel ist, erhält es +1 Stärke, +1 Verteidigung, +1 AP und regeneriert +1 zusätzliche Ausdauer am Rundenende.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

