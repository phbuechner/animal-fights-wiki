---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Eingreifen
**Regel:** Reaktion: Wenn ein anderes deiner Tiere als Ziel eines Angriffs gewählt wird, kannst du diese Aktion ausführen. Füge dem Angreifer 1 direkten Schaden zu.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
```
