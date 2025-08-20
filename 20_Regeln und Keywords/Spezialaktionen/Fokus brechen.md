---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Fokus brechen
**Regel:** Wähle ein gegnerisches Tier. Dieses Tier verliert bis zum Ende seines nächsten
Zuges eine seiner passiven Eigenschaften (außer Gruppierungseigenschaften) deiner Wahl.

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
