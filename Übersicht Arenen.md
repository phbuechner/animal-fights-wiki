# Übersicht aller Arenen

---
## Persönliches Deck (Sterne-Karten)
*Karten, die Sie beim Deckbau auswählen können.*

```dataview
TABLE WITHOUT ID
  file.link as "Karte",
  edition as "Edition",
  sterne as "★",
  habitat as "Habitat",
  terrain_keywords as "Terrain-Keywords",
  klima as "Klima"
FROM #arenakarte 
WHERE deck_typ = "Persönlich"
SORT sterne DESC
```

## Allgemeine Arenen 
*Karten für das allgemeine Deck*

```dataview
TABLE WITHOUT ID
  file.link as "Karte",
  edition as "Edition",
  habitat as "Habitat",
  terrain_keywords as "Terrain-Keywords",
  klima as "Klima"
FROM #arenakarte 
WHERE deck_typ = "Allgemein"
SORT file.name DESC