---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Hinterhalt
**Regel:** Kann nur aus dem **[[Lauernd]]**-Status genutzt werden. Führe einen Angriff durch. Das Ziel erhält -2 auf sein Verteidigungs-Ergebnis.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC