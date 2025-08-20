---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Überrennen:
**Regel:** Führe einen Angriff durch. Wenn dieser Angriff Schaden verursacht, verliert das Ziel 1 AP in seinem nächsten Zug.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
