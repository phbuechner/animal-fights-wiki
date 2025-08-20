---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Verwunden
**Regel:** Führe einen Angriff durch. Schaden, der durch diesen Angriff verursacht wird, kann bis zum Ende des nächsten gegnerischen Zuges nicht geheilt werden.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
