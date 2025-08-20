---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Jagdruf
**Regel:** Wähle ein gegnerisches Tier. Bis zum Ende der Runde gilt dieses Tier für deine Gruppierungs-Fähigkeiten (z.B. **[[Kooperative Jagd]]**) als 'bereits von einem Gruppenmitglied angegriffen'.

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",  
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC