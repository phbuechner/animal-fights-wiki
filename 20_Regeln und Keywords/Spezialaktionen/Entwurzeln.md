---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Entwurzeln
**Regel:** Wähle ein [[Terrain-Keyword]] der aktiven Arena (z.B. Unterholz, Baumkronen, Felsen). Dieses Keyword gilt bis zum Beginn deines nächsten Zuges als deaktiviert. Kein Tier kann in dieser Zeit Fähigkeiten nutzen, die dieses Keyword erfordern.

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
