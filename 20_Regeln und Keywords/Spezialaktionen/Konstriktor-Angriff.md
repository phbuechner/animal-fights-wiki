---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Konstriktor-Angriff

**Regel:** Kann nur aus dem [[Lauernd]]-Status heraus genutzt werden. Führe einen Angriff durch. Dieser Angriff kann nicht ausgewichen werden. Wenn dieser Angriff Schaden verursacht, erleidet das Ziel zusätzlich den Zustand [[Festgehalten]].

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC