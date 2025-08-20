---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Pflege

**Regel:** Wähle ein anderes Tier in deiner Gruppe. Entferne einen negativen [[Status-Effekte (Übersicht)### Negative Zustände|Zustand]] von ihm oder heile 1 Schaden bei ihm.


## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC