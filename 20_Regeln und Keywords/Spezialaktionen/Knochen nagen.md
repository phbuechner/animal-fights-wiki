---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Knochen nagen
**Regel:** Entferne eine 1-Stern-Karte aus einem Trophäenstapel, um zu 1 Gesundheit und 1 Ausdauer zu regenerieren.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC