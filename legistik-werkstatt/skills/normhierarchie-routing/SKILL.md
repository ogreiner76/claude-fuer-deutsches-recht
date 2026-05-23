---
name: normhierarchie-routing
description: "Entscheidet welche Norm-Ebene fuer einen legistischen Auftrag richtig ist Bundesgesetz Landesgesetz Rechtsverordnung Bund Rechtsverordnung Land Satzung Koerperschaft. Pruefkatalog Gesetzgebungskompetenz Bund Art. 70 bis 74 GG ausschliesslich konkurrierend Erforderlichkeitsklausel Art. 72 Abs. 2 GG. Landeskompetenz Auffangzustaendigkeit. Verordnungsermaechtigung Art. 80 GG. Satzungskompetenz Art. 28 Abs. 2 GG. Vorrang des Gesetzes Wesentlichkeitstheorie BVerfG. Wenn Buergerrechte oder Strafe nur Gesetz nicht VO oder Satzung. Endet mit Entscheidung plus Begruendung in drei Saetzen plus Verweis auf naechsten Pruef-Skill."
---

# Normhierarchie-Routing

> Entscheidet: Welche Norm-Ebene ist fuer dieses Vorhaben richtig?

## Eingabe

Auftragsblatt aus `legistik-auftragsaufnahme`.

## Pruefraster

### A - Ist es ueberhaupt eine zu kodifizierende Materie?

Wenn die politische Vorgabe nur Verwaltungspraxis aendern soll, reicht ein Erlass / eine Verwaltungsvorschrift. Kein Norm-Schritt noetig.

### B - Wenn Gesetz: Bund oder Land?

1. Pruefung **ausschliessliche Gesetzgebung Bund** (Art. 71 und 73 GG): auswaertige Angelegenheiten, Verteidigung, Staatsangehoerigkeit, Wahrungseinheit, Bundeseisenbahnen, Luftverkehr, Postwesen, Telekommunikation, Bundeskriminalpolizei, Zoelle, Schutz deutsches Kulturgut.
2. Pruefung **konkurrierende Gesetzgebung** (Art. 72 und 74 GG): Buergerliches Recht, Strafrecht, Gerichtsverfassung, Aufenthaltsrecht, Sozialrecht, Wirtschaftsrecht, Arbeitsrecht, Strassenverkehr, oeffentliche Fuersorge, Recht der Wirtschaft, etc. Pruefung **Erforderlichkeitsklausel** Art. 72 Abs. 2 GG bei den dort genannten Materien.
3. Wenn weder Art. 71 noch Art. 73 noch Art. 74: **Landeszustaendigkeit** Art. 70 Abs. 1 GG (Auffangkompetenz).

### C - Wenn Gesetz oder Rechtsverordnung?

- **Wesentlichkeitstheorie BVerfG**: Grundrechtsrelevante Regelungen muessen vom parlamentarischen Gesetzgeber selbst getroffen werden. Faustregel: Wer betrifft den Buerger in seinen Grundrechten erheblich, muss als Gesetz geregelt werden.
- **Strafgesetz und Bussgeldgesetz**: nur Gesetz (Art. 103 Abs. 2 GG iVm Wesentlichkeitstheorie).
- **Detailregelungen technischer Art**: Rechtsverordnung kommt in Betracht.

### D - Wenn Rechtsverordnung Bund: Gibt es Ermaechtigungsgrundlage Art. 80 GG?

Pruefen mit Skill `verordnungsermaechtigung-art80`. Wenn keine ausreichende Ermaechtigung vorhanden: zunaechst Gesetz aendern, um Ermaechtigung zu schaffen, dann VO erlassen.

### E - Wenn Satzung: Gibt es Satzungskompetenz?

- Kommunale Satzungen: Selbstverwaltungsgarantie Art. 28 Abs. 2 GG plus Gemeindeordnung des Landes plus ggf. spezielle Fachgesetze (z.B. BauGB fuer Bebauungsplaene, KAG fuer Beitragssatzungen, BImSchG fuer Laermsatzungen).
- Berufsstaendische Satzungen: Kammerngesetz (z.B. BRAO, BAeO, IHK-Gesetz) plus Vorbehalt des Gesetzes BVerfG E 33 / 125 (Facharzt).
- Hochschulsatzungen: Hochschulgesetz Land plus Selbstverwaltung Art. 5 Abs. 3 GG.
- Sozialversicherungstraeger: Satzungsbefugnis nach SGB IV.
- Rundfunkanstalten: Rundfunkstaatsvertrag plus Landesrundfunkgesetze.

### F - Wenn Mehrebenen-Vorhaben

Manchmal braucht es: Bundesgesetz (Rahmen), Bundesverordnung (Details), Landesgesetz (Umsetzung), Verwaltungsvorschrift (Vollzug). Dann ist eine Tabelle der Ebenen zu erstellen.

## Ausgabe

- Entscheidung Norm-Ebene
- drei Saetze Begruendung
- Verweis auf naechsten Skill `gesetzgebungskompetenz-pruefen` oder `verordnungsermaechtigung-art80` oder `satzungskompetenz-pruefen`

## Stolperfallen

- Goldplating durch Wahl der falschen Ebene (Bund regelt, was Land regeln duerfte): pruefen unter `goldplating-vermeiden`
- Wesentlichkeitstheorie wird oft uebersehen, wenn das Ministerium "schnell per VO" regeln will
- Subsidiaritaetsprinzip EU bei Kompetenzfragen mitdenken
