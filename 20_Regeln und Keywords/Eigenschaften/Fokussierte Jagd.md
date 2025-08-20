---
typ: "Fähigkeit"
tags:
  - fähigkeit
---

# Fokussierte Jagd

**Regel:** Wenn du in deinem Zug einen Angriff mit diesem Tier deklariert hast, kann es bis zum Beginn deines nächsten Zuges die [[Ausweichen]]-Reaktion nicht wählen.

## Karten mit dieser Fähigkeit

```dataview
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne" 
FROM #tierkarte
WHERE contains(file.outlinks, this.file.link)
````

