---
typ: "Edition"
saga: "[[Afrika Saga]]"
beschreibung: "Die dritte Edition der Afrika Saga durchquert die unbarmherzigen Wüsten und Halbwüsten Afrikas."
tags:
  - edition
---

# Die trockenen Weiten

**Die trockenen Weiten** ist die dritte Edition der **[[Afrika Saga]]**. Sie verlässt die fruchtbaren Savannen und feuchten Regenwälder und führt die Spieler in die extremsten und lebensfeindlichsten Umgebungen Afrikas. Überleben hängt hier nicht von roher Stärke ab, sondern von Ausdauer, Anpassung und Effizienz.

---
## Thematischer Fokus & Design-Ziele

Diese Edition perfektioniert die **[[Herde]]n-Mechanik** und rückt das Management von **[[Ausdauer]]** als zentrale Ressource in den Fokus.

- **Neue Mechaniken:** Die **[[Arid|Arid-Klimazone]]** wird zu einem entscheidenden Faktor. Neue Synergien für Herden und Fähigkeiten, die auf Ausdauer-Manipulation basieren, werden eingeführt.
- **Neue Archetypen:** Fokus auf "Attrition" (Zermürbung) und "Ausdauer-Management".
- **Potenzieller "Extreme Mode":** Diese Edition führt optional die "Gesetze der Dürre" ein, einen Survival-Modus für eine extremere und anspruchsvollere Spielerfahrung.

---
## Die Regionen & ihre Bewohner

Die Welt dieser Edition ist in sechs thematische Wüsten- und Trockenregionen unterteilt, die jeweils einzigartige Herausforderungen bieten:

1.  **[[Sahara-Wüste (Region)|Sahara-Wüste]]**: Die ikonische Wüste. Heimat des ausdauernden [[Dromedar]]s und der tödlichen [[Sahara-Hornviper]].
2.  **[[Sahelzone (Region)|Sahelzone]]**: Die semi-aride Savanne. Hier herrscht der [[Riesen-Elen]] als "Pflanzenfresser-Tank".
3.  **[[Kalahari-Wüste (Region)|Kalahari-Wüste]]**: Die "rote Wüste". Territorium der [[Oryx-Antilope]] und des [[Erdmännchen]]-Schwarms.
4.  **[[Äthiopisches Hochland (Region)|Äthiopisches Hochland]]**: Das "Dach Afrikas". Dominiert vom [[Äthiopischer Steinbock|Äthiopischen Steinbock]] und dem [[Äthiopischer Wolf|Äthiopischen Wolf]].
5.  **[[Makgadikgadi-Salzpfannen (Region)|Makgadikgadi-Salzpfannen]]**: Eine surreale Landschaft der Transformation. Heimat des [[Springbock]]s und riesiger [[Flamingo]]-Schwärme.
6.  **[[Karoo-Halbwüste (Region)|Karoo-Halbwüste]]**: Eine trockene Ebene mit Felsenhügeln. Das Reich des [[Sekretär (Vogel)|Sekretärs]] und der [[Kap-Kobra]].

---
## Neuer Spielmodus: Gesetze der Dürre (Extreme Mode)

Diese Edition führt einen optionalen, modularen Spielmodus ein, der die Regeln des Standard-Modus um eine oder mehrere der folgenden "Gesetze" erweitert, um den Überlebenskampf zu simulieren:

- **[[Gesetz 1 - Die unerbittliche Sonne]]**: Fokus auf [[Ausdauer]]. Tiere regenerieren keine Ausdauer mehr.
- **[[Gesetz 2 - Die versiegten Quellen]]**: Fokus auf [[Handkarten|Karten]]. Spieler ziehen keine Karten mehr am Rundenende.
- **[[Gesetz 3 - Der ewige Kampf]]**: Fokus auf [[Gesundheit]]. Heilung ist unmöglich.
- **[[Gesetz 4 - Der unerbittliche Jäger]]**: Fokus auf [[Trophäenstapel|Trophäen]]. Die Siegbedingung ändert sich zu "Besiege 3 gegnerische Tiere".

---
## Vollständige Kartenliste

```dataview
TABLE WITHOUT ID
  set_nummer as "Nr.",
  file.link as "Karte",
  erweiterung as "Erweiterung",
  sterne as "★",
  typ as "Typ"
FROM #tierkarte OR #arenakarte OR #instinktkarte
WHERE edition = "Die trockenen Weiten"
SORT set_nummer ASC