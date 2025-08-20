---
typ: "Terrain-Keyword"
tags:
  - terrain-keyword
---

# Nacht

**Nacht** ist ein spezielles [[Terrain-Keyword]], das die Bedingungen für den Kampf bei Dunkelheit simuliert und [[Nachtaktiv]]e Tiere stark begünstigt.

## Globale Regel: "Kampf bei Nacht"

Immer, wenn ein Tier **ohne** das Keyword [[Nachtaktiv]] einen Angriff oder eine Ausweich-Aktion deklariert, muss sein Besitzer den Würfel (W6) für diese Aktion **zweimal werfen und das niedrigere Ergebnis verwenden.**

Dieser Effekt stellt den Nachteil dar, den nicht angepasste Tiere bei schlechten Lichtverhältnissen haben.

---
## Arenen mit diesem Terrain

Die folgende Tabelle listet automatisch alle Arena-Karten auf, in denen die "Kampf bei Nacht"-Regel aktiv ist.

```dataview
TABLE
  sterne as "Sterne",
  habitat as "Habitat"
FROM #arenakarte
WHERE contains(terrain_keywords, "Nacht")
SORT sterne DESC