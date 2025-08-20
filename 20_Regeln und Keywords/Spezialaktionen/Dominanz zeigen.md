---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Dominanz zeigen

**Regel:** Führe einen [[Einschüchterungstests]] durch. Dieser Versuch ignoriert **[[Resistenz]] ([[Einschüchterung]])**.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC


