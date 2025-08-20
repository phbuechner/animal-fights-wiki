---
typ: "Tiertyp"
tags:
  - tiertyp
---

# Elefant

Elefanten sind eine der mächtigsten Tierarten im Spiel. Sie zeichnen sich durch extrem hohe [[Gesundheit]]- und [[Stärke]]-Werte aus, leiden aber oft unter niedriger [[Agilität]]. Sie gehören zur Größenkategorie [[Gigantisch]].

Viele Elefanten teilen die Gruppierungseigenschaft **[[Herde (Elefant)]]**.

---
## Elefanten-Karten im Überblick

Die folgende Tabelle listet alle spezifischen Elefanten-Karten auf.

```dataview
TABLE WITHOUT ID
  file.link as "Karte",
  sterne as "★",
  stärke as "S",
  verteidigung as "V",
  gesundheit as "G",
  agilität as "A"
FROM #tierkarte
WHERE contains(tags, "elefant")
SORT sterne DESC
````