---
name: anw-steuerbescheid-analyse
description: "Steuerbescheid strukturiert auswerten und Angriffspunkte für Einspruch identifizieren. Anwendungsfall Mandant hat Steuerbescheid bekommen und fragt ob und wie er sich wehren kann. Bescheidarten Festsetzungsbescheid Aenderungsbescheid Schaetzungsbescheid Haftungsbescheid Prüfungsbescheid. Erfasst Steuerart Veranlagungsjahr Nachforderung oder Erstattung Vorlaeufigkeitsvermerk Vorbehalt der Nachprüfung § 164 AO Aenderungsvorschriften §§ 172 ff. AO Bekanntgabe § 122 AO Vier-Tages-Fiktion seit 01.01.2025 PostModG. Output Analyse-Protokoll Angriffspunkte Fristenstatus Empfehlung Einspruch oder Akzeptanz. Nahtloser Übergang zu anw-einspruch-finanzamt."
---

# Steuerbescheid-Analyse

## V90 Fachkern — Steuerrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Steuerbescheid-Analyse` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** AO, EStG, KStG, GewStG, UStG, GrEStG, UmwStG, AStG, FZulG, MinStG; BMF-Schreiben nur mit Datum, Titel und offizieller BMF-URL verwenden.
- **Verifizierte Anker:** BMF-Schreiben vom 15.10.2025 zur obligatorischen E-Rechnung und UStAE-Anpassung; BMF-Seite Forschungszulage mit Hinweis zu Antrags-/Festsetzungslogik und BMF-Schreiben vom 07.02.2023; BMF/BZSt-Datensatzbeschreibung vom 05.08.2025 für Mindeststeuer-Berichte; BMF-Schreiben vom 25.05.2023 zu § 6a GrEStG; BMF-Schreiben vom 02.01.2025/01.08.2025 zum Umwandlungssteuer-Anwendungserlass live prüfen.
- **Arbeitsmodus:** Erst Steuerart, Zeitraum, Verwaltungsstand, Frist/Festsetzung, Zuständigkeit, Form/Portal und Beleglage klären; dann BMF-Verwaltungslinie von BFH-Rechtsprechung und Gesetz trennen.
- **Outputpflicht:** Steuerartenmatrix, BMF-Radar, Einspruchsbaustein, ELSTER-/Portal-To-do, Risikoampel, DBA-/GrESt-/USt-Tabelle oder Mandantenmemo.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Triage — kläre vor der Analyse

1. Welche Steuerart und welches Veranlagungsjahr betrifft der Bescheid?
2. Liegt der Bescheid im Original vor (nicht nur Kopie oder Screenshot)?
3. Ist die Einspruchsfrist bereits abgelaufen? (Bekanntgabefiktion § 122 Abs. 2 AO — vier Tage seit 1.1.2025)
4. Wurde der Bescheid unter Vorbehalt der Nachprüfung (§ 164 AO) oder mit Vorläufigkeitsvermerk (§ 165 AO) erlassen? → andere Anpassungsmöglichkeiten
5. Liegt eine Außenprüfung zugrunde? → Schätzungsprobleme und Sicherheitszuschläge prüfen
6. Soll AdV beantragt werden? → Liquidität und Frist klären

## Zweck

Bescheid systematisch lesen vor dem Einspruch.

## Aktuelle Rechtsprechung

- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

## Quellenregel

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.
## Eingaben

- Steuerbescheid (PDF Original; gescannt mit OCR).
- Steuererklärung des Veranlagungsjahres (zum Vergleich Soll-Ist).
- Bisheriger Mandatsstand.

## Prüfraster

### 1. Formale Prüfung

- **Behörde** zuständig (Wohnsitzfinanzamt § 19 AO; Betriebsstaettenfinanzamt § 18 AO)?
- **Adressat** korrekt (bei Eheleuten Zusammenveranlagung beide; bei Personengesellschaft gesonderte und einheitliche Feststellung — separater Bescheid)?
- **Steuerart** und **Veranlagungsjahr** klar?
- **Tenor** mit Steuerbetrag eindeutig?
- **Bekanntgabe** nach § 122 AO — Vier-Tages-Fiktion bei Postbescheiden (§ 122 Abs. 2 Nr. 1 AO n.F., seit 1.1.2025 PostModG; bei Aufgabe zur Post vor dem 1.1.2025: weiterhin Drei-Tages-Fiktion alter Fassung).
- **Rechtsbehelfsbelehrung** vollständig?

### 2. Inhaltliche Prüfung

- **Berechnung** der Steuer nachvollziehbar?
- **Einkünftearten** richtig zugeordnet (§§ 2 13–24 EStG)?
- **Werbungskosten / Betriebsausgaben** vollständig abgezogen?
- **Sonderausgaben Außergewöhnliche Belastungen** berücksichtigt?
- **Pauschalen** richtig?
- **Vorauszahlungen** richtig angerechnet (§ 36 EStG)?
- **Solidaritaetszuschlag Kirchensteuer** zutreffend?

### 3. Vorläufigkeit und Änderbarkeit

- **§ 164 AO** Vorbehalt der Nachprüfung — Bescheid jederzeit aenderbar bis Festsetzungsverjährung.
- **§ 165 AO** Vorläufigkeitsvermerk — Bescheid teilweise vorläufig.
- **§ 172 ff. AO** Änderungsvorschriften nach Bestandskraft (z. B. § 173 neue Tatsachen § 175 Änderungsbescheid).
- **§ 129 AO** offenbare Unrichtigkeit (Schreib- Rechenfehler).

### 4. Schätzung (§ 162 AO)

Bei Schätzungsbescheid:
- Begründung für Schätzungsbefugnis (Nicht-Abgabe Erklärung verletzte Mitwirkungspflicht).
- Schätzungsgrundlagen schlüssig?
- Höhe wirtschaftlich plausibel?
- Sicherheitszuschlaege im Rahmen?

### 5. Festsetzungsverjährung

- **§ 169 AO** Festsetzungsfrist regelmäßig vier Jahre; bei Hinterziehung zehn Jahre; bei Leichtfertigkeit fünf Jahre.
- **§ 170 AO** Beginn — mit Ablauf des Kalenderjahrs in dem die Steuer entstanden ist; bei Erklärungspflicht mit Ablauf des Kalenderjahrs der Abgabe spätestens nach drei Jahren.

### 6. Vollziehung

- **Fälligkeit** der Steuerschuld (§ 220 AO).
- **Anordnung sofortiger Vollziehung** durch Steuerbehörde nicht erforderlich — Einspruch hat **keine aufschiebende Wirkung** (§ 361 Abs. 1 AO Satz 1). Daher Antrag auf Aussetzung der Vollziehung notwendig wenn nicht gezahlt werden soll.

## Ausgabe

Analyseprotokoll mit:

1. Stammdaten Bescheid (Behörde Az Steuerart Jahr Datum Zugang)
2. Festsetzungsbetrag Soll-Ist-Vergleich
3. Rechtsbehelfsbelehrung mit Einspruchsfrist (ein Monat § 355 Abs. 1 AO)
4. Formfehler
5. Angriffspunkte sortiert nach Erfolgsaussicht
6. Empfehlung: Einspruch / Antrag § 129 AO / Änderungsantrag / nichts
7. Antrag auf Aussetzung der Vollziehung erforderlich?
8. Frist im Fristenbuch eintragen (Skill `anw-fristenbuch-steuerrecht`)
