---
name: referentenentwurf-bauen
description: "Erstellt einen vollstaendigen Referentenentwurf des Bundes oder Landes. Format gemaess HdR. Deckblatt Bezeichnung Inhaltsuebersicht A Problem und Ziel B Loesung C Alternativen D Haushaltsausgaben E Erfuellungsaufwand F weitere Kosten G weitere Folgen H Gleichstellungspolitische Bedeutung. Entwurfstext mit Artikeln und Paragrafen. Strukturen bei Sachverhalten Definition Hauptregel Ausnahmen Sanktionen Uebergang. Inkrafttretensregelung. Pruefliste gegen GGO und HdR. Endet mit Volltext-Entwurf bereit zur Ressortabstimmung. Anschluss `begruendung-allgemein-und-besonders` und `synopse-erstellen`."
---

# Referentenentwurf bauen

> Das Kernformat der ministeriellen Rechtssetzung.

## Aufbau eines Referentenentwurfs

### Vorblatt

Das Vorblatt vor dem eigentlichen Entwurfstext. Sieben bis acht Abschnitte (alphabetisch in der GGO geregelt):

- **A. Problem und Ziel** - was ist das Problem, was soll erreicht werden
- **B. Loesung** - die im Entwurf gewaehlte Loesung in drei Saetzen
- **C. Alternativen** - welche Alternativen wurden erwogen, warum verworfen
- **D. Haushaltsausgaben ohne Erfuellungsaufwand** - was kostet es den Haushalt
- **E. Erfuellungsaufwand** - Buerger, Wirtschaft, Verwaltung (Bund / Land / Gemeinde)
- **F. Weitere Kosten** - z.B. Preiseffekte
- **G. Weitere Folgen** - oekologisch, sozial, demografisch, gleichstellungspolitisch
- **H. Befristung** und Evaluierung

### Eingangsformel

"Der Bundestag hat das folgende Gesetz beschlossen:" (bei Bundesgesetz, regulaer)
Bei zustimmungspflichtigen Gesetzen: "Der Bundestag hat mit Zustimmung des Bundesrates das folgende Gesetz beschlossen:"

### Artikel und Paragrafen

Bei Aenderungsgesetzen: Artikel 1, Artikel 2, Artikel 3 ...
Pro Artikel je ein Stammgesetz, das geaendert wird.
Innerhalb des Artikels:
- "Paragraf X wird wie folgt geaendert:"
- "1. Absatz 2 wird wie folgt gefasst: ..."
- "2. Folgender Absatz wird angefuegt: ..."

Bei Stammgesetzen (neuen Vollgesetzen): Paragraf 1, Paragraf 2 etc.

### Aenderungsbefehle - Standardformulierungen

- "wird wie folgt geaendert"
- "wird durch folgenden Satz ersetzt"
- "wird folgender Satz angefuegt"
- "wird folgender Paragraf eingefuegt"
- "wird aufgehoben"
- "wird gestrichen"
- "wird die Angabe ... durch die Angabe ... ersetzt"

### Inkrafttretensregel

Letzter Artikel. Standardformel:
"Dieses Gesetz tritt am ... in Kraft."
Oder gestaffeltes Inkrafttreten:
"Artikel 1 tritt am ... in Kraft. Artikel 2 tritt am ... in Kraft."

### Schlussformel

"Berlin, den ... Der Bundespraesident ... Die Bundeskanzlerin ... Der Bundesminister ..."

## Inhaltliche Standardstruktur eines Paragrafen

1. **Anwendungsbereich / Definition**
2. **Grundregel** (Pflicht, Erlaubnis, Verbot)
3. **Ausnahmen**
4. **Sanktionen / Rechtsfolgen** bei Verstoss (oder Verweis ins Bussgeldrecht)
5. **Verfahren** (Antrag, Bescheid, Rechtsmittel)
6. **Uebergangsregelung** in eigenem Paragrafen am Ende des Stammgesetzes

## Pruefliste

- [ ] Vorblatt vollstaendig (alle Abschnitte A bis H)
- [ ] Eingangsformel passt zum Gesetz (Zustimmungserfordernis korrekt)
- [ ] Aenderungsbefehle in Standardform
- [ ] Inkrafttreten klar geregelt
- [ ] Schlussformel passend
- [ ] HdR-Spruchregeln eingehalten (siehe `hdr-stilcheck`)
- [ ] Keine Verweisschleife (siehe `zirkelschluss-pruefen`)
- [ ] Terminologie konsistent (siehe `terminologie-konsistenz`)

## Ausgabe

Markdown-Datei mit dem kompletten Entwurfstext, bereit fuer Ressortabstimmung.

## Anschluss

- `begruendung-allgemein-und-besonders`
- `synopse-erstellen`
- `xml-paralleldarstellung`
- `dokumente-rendern-docx-pdf` (am Ende, erzeugt lieferfertiges DOCX und PDF im offiziellen HdR-Layout)
