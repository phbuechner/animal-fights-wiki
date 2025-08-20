---
typ: "Gruppierung"
tags:
  - gruppierungstyp
---

# Patriarch des Rudel

Zählt als Gruppierung **[[Rudel (Löwe)]]**, aber erhält keine Gruppen-Boni. Solange eine 'Massai-Löwin' im Spiel ist: +1 Stärke und regeneriere +1 zusätzliche Ausdauer.

## Spezifische Herden-Arten

```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT name ASC