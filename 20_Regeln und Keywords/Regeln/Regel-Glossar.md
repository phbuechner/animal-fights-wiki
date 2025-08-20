> [!NOTE] Regel-Glossar
> Dies ist der zentrale Hub für alle Regeln, Konzepte und Keywords von *Animal Fights*. Nutze die Links, um zu den detaillierten Erklärungen zu springen.

---
## 1. Das Spiel beginnen
*Alles, was du vor und während deines ersten Zuges wissen musst.*

- **[[Spielmodi]]**: Scharmützel oder Standard? Die grundlegende Entscheidung.
- **[[Deckbau-Regeln]]**: Wie du dein Deck zusammenstellst.
- **[[Spielvorbereitung]]**: Die Schritte vom Mischen bis zum ersten Zug.

---
## 2. Der Spielablauf
*Die Kern-Mechaniken, die das Spiel antreiben.*

- **[[Grundwerte einer Tierkarte]]**: Was Stärke, Agilität & Co. bedeuten.
- **[[Kartentypen]]**: Die Unterschiede zwischen Tieren, Arenen und Instinktkarten.
- **[[Spielzonen]]**: Wo sich deine Karten befinden (Deck, Hand, Arena etc.).
- **[[Rundenablauf]]**: Die fünf Phasen einer Runde im Detail.
- **[[Aktionen im Spiel]]**: Was deine Tiere in der Aktionsphase tun können.

---
## 3. Der Kampf
*Wie Auseinandersetzungen zwischen Tieren entschieden werden.*

- **[[Kampfablauf]]**: Die detaillierten Schritte eines Kampfes.
- **[[Direkter Schaden]]**: Schaden, der Verteidigung ignoriert.
- **[[Die Zweite Chance (Ausweichen)]]**: Die taktische Entscheidung nach einem misslungenen Ausweichmanöver.

---
## 4. System & Spezialregeln
*Übergreifende Regeln und besondere Spielsituationen.*
- **[[Goldene Regel (Boni & Mali stapeln)]]**
- **[[Kettenregel (Last-in, First-Out)]]**
- **[[Fortwährende Effekte & Spielzustand]]**
- **[[Unverteidigte Arena]]**
- **[[Ruhestand]]**

---
## 5. Keyword-Lexikon
*Alle spielrelevanten Begriffe und ihre Effekte.*

### A) Zustände & Effekte
- **[[Status-Effekte (Übersicht)]]**: Eine Liste aller positiven und negativen Zustände.
- **[[Extreme Hitze]]**
- **[[Monsun]]**

### B) Umgebungs-Keywords
- **[[Habitat-System|Habitat]]** (Savanne, Wald, etc.)
- **[[Klimazonen]]** (Arid, Tropisch, etc.)
- **[[Terrain-Keyword|Terrain-Keywords]]** (Höhle, Wasser, Offenes Gelände, etc.)

### C) Tier-Keywords
- **[[Aktivitätszyklen]]** (Tagaktiv, Nachtaktiv, etc.)
- **[[Bewegungstypen]]** (Boden, Fliegend, etc.)
- **[[Größenkategorien]]** (Klein, Mittel, Groß, Gigantisch)

---
## Vollständige Keyword-Datenbank
*Diese Tabelle listet automatisch **alle** Notizen auf, die als Keyword, Zustand oder Fähigkeit markiert sind.*

```dataview
TABLE WITHOUT ID
  file.link as "Begriff",
  typ as "Kategorie"
FROM #keyword OR #status-effekt OR #fähigkeit
SORT file.name ASC