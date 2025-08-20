---
typ: "Fähigkeit-Spezifisch"
tags:
  - anpassungstyp
---  

# Anpassung (Felsen)  
Dies ist eine spezifische Art der [[Anpassung]]. Sie ist an das Terrain-Keyword [[Felsen (Keyword)|Felsen]] gekoppelt.  
## Tiere mit dieser Fähigkeit  

```dataview 
TABLE WITHOUT ID   
  file.link as "Tier",   
  sterne as "Sterne",
  L.children.Effekt as "Effekt"
FROM #tierkarte
FLATTEN file.lists as L
WHERE contains(L.outlinks, this.file.link) AND L.children
SORT sterne DESC
```

## Arenen mit dem Keyword Felsen

```dataview 
TABLE   
	sterne as "Sterne",   
	habitat as "Habitat",   
	klima as "Klima" 
FROM #arenakarte 
WHERE contains(terrain_keywords, "Felsen") 
SORT sterne DESC
```