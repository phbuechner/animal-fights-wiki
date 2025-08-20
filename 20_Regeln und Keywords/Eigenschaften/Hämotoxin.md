---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Hämotoxin

**Regel:** Wenn ein Angriff dieses Tieres Schaden verursacht, senke stattdessen die
maximale [[Gesundheit]] des Ziels permanent um 1.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

