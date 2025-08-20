---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Sturzflug
**Regel:** Führe einen Angriff gegen ein Ziel durch, wenn die Arena eines der folgenden [[Terrain-Keyword]]s enthält: [[Wasser (Keyword)|Wasser]], [[Fluss (Keyword)|Fluss]], [[Überschwemmt (Keyword)|Überschwemmt]], [[Sumpf (Keyword)|Sumpf]] oder [[Flussufer (Keyword)|Flussufer]]. Dieser Angriff erhält [[Durchbruch]].

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC