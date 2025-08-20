---
typ: "Spezialaktion"
tags:   
  - fähigkeit
  - spezialaktion
---  

# Anpassungsfähiger Jäger
**Regel:** Wähle ein Terrain-Keyword auf der aktiven Arena. Dieses Tier erhält
bis zum Beginn deines nächsten Zuges die in der folgenden Liste zugeordnete Fähigkeit:
	o [[Wasser (Keyword)|Wasser]] / [[Flussufer (Keyword)|Flussufer]]: Deine Angriffe können nicht [[Ausweichen|ausgewichen]] werden.
	o [[Unterholz (Keyword)|Unterholz]] / [[Dickicht (Keyword)|Dickicht]]: Du erhältst [[Tarnung]].
	o [[Felsen (Keyword)|Felsen]]: Du erhältst [[Kletternd]] und deine Angriffe aus einer Position mit [[Höhenlage (Keyword)|Höhenlage]] erhalten zusätzlich +1 Stärke.
	o [[Baumkronen (Keyword)|Baumkronen]] / [[Lianen (Keyword)|Lianen]]: Deine Angriffe erhalten [[Durchbruch]].
	o [[Sumpf (Keyword)|Sumpf]] / [[Mangroven (Keyword)|Mangroven]]: Du erhältst [[Jäger kleiner Beute]].
	o [[Aas (Keyword)|Aas]]: Du erhältst [[Aasfresser]] (Heile 1).

## Karten mit dieser Fähigkeit  
```dataview 
TABLE WITHOUT ID   
	file.link as "Tier",   
	sterne as "Sterne",   
	ap as "AP-Kosten" 
FROM #tierkarte 
WHERE contains(file.outlinks, this.file.link) 
SORT sterne DESC
