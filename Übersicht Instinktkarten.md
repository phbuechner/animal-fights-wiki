# Übersicht aller Instinktkarten

---
## Persönliches Deck (Sterne-Karten)
*Karten, die Sie beim Deckbau auswählen können.*

```dataview
TABLE WITHOUT ID
  file.link as "Karte",
  edition as "Edition",
  sterne as "★",
  timing as "Timing"
FROM #instinktkarte
WHERE deck_typ = "Persönlich"
SORT sterne DESC
```

## Allgemeine Arenen 
*Karten für das allgemeine Deck*

```dataview
TABLE WITHOUT ID
  file.link as "Karte",
  edition as "Edition",
  sterne as "★",
  timing as "Timing"
FROM #instinktkarte  
WHERE deck_typ = "Allgemein"
SORT file.name DESC
```