---
typ: "Edition"
saga: "[[Afrika Saga]]"
beschreibung: "Die vierte und letzte Edition der Afrika Saga führt uns zu den höchsten Gipfeln und den isoliertesten Inseln des Kontinents."
tags:
  - edition
---

# Gipfel & Inseln

**Gipfel & Inseln** ist die vierte und letzte Edition der **[[Afrika Saga]]**. Sie schließt den Zyklus ab, indem sie die extremsten Lebensräume einführt: die eisigen Höhen der höchsten Berge und die einzigartigen, durch Isolation geprägten Welten der afrikanischen Inseln.

Diese Edition führt die komplexesten und einzigartigsten "Trickser"-Tiere ein und legt einen starken Fokus auf die Umgebung als entscheidenden Faktor.

---
## Thematischer Fokus & Design-Ziele

- **Zwei gegensätzliche Konzepte:** Das Set ist klar in die vertikale Welt der "Gipfel" und die isolierte Welt der "Inseln" unterteilt.
- **Einzigartige Mechaniken:** Einführung von Konzepten wie [[Höhenzonen]], [[Wetter]]-Effekten und Mechaniken, die auf "Evolution pur" und [[Gigantismus]] basieren.
- **Komplexe Archetypen:** Fokus auf anspruchsvolle Strategien, die nicht auf direkten Kampf, sondern auf Kontrolle und einzigartige Siegbedingungen setzen.

---
## Die Regionen: Gipfel & Inseln

Die Welt dieser Edition ist in zwei Hälften mit jeweils drei thematischen Regionen unterteilt.

### Die drei Throne Afrikas (Gipfel)
*Diese Regionen fokussieren sich auf Vertikalität, Anpassung an extreme Bedingungen und Kontrolle aus erhöhten Positionen.*
1.  **[[Kilimandscharo-Massiv (Region)|Kilimandscharo-Massiv]]**: Thematischer Fokus auf wechselnde **[[Höhenzonen]]** und extreme **[[Anpassung]]**.
2.  **[[Atlasgebirge (Region)|Atlasgebirge]]**: Thematischer Fokus auf **Kälte**, Wälder und eine einzigartige, fast "europäische" Fauna.
3.  **[[Drakensberge (Region)|Drakensberge]]**: Thematischer Fokus auf **Vertikalität**, den [[Fliegend]]-Archetyp und dynamische **[[Wetter]]**-Effekte.

### Drei Konzepte der Isolation (Inseln)
*Diese Regionen fokussieren sich auf einzigartige, evolutionär entstandene Fähigkeiten und das Konzept der Isolation.*
4.  **[[Madagaskar (Region)|Madagaskar]]**: Die "achte Welt". Thematischer Fokus auf **"Evolution pur"** und einzigartige Tierarten, die nirgendwo sonst zu finden sind.
5.  **[[Aldabra-Atoll & Seychellen (Region)|Aldabra-Atoll & Seychellen]]**: Thematischer Fokus auf **[[Gigantismus]]**, ultimative [[Verteidigung]] und **Meerestiere**.
6.  **[[Inseln im Golf von Guinea (Region)|Inseln im Golf von Guinea]]**: Ein vulkanischer **[[Primat]]en-Hotspot** mit einzigartigen Dschungel-Mechaniken.

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
WHERE edition = "Gipfel & Inseln"
SORT set_nummer ASC