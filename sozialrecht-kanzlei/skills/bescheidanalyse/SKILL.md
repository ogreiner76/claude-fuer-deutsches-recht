---
name: bescheidanalyse
description: Strukturierte Auswertung eines sozialrechtlichen Bescheids — erfasst Behoerde Aktenzeichen Bescheiddatum Zugangsdatum Bescheidart (Ablehnung / teilweise Bewilligung / Aufhebung / Rueckforderung / Sanktion) Tenor Begruendungs-Kernpunkte angewandte Rechtsgrundlagen Rechtsbehelfsbelehrung. Prueft formale Anforderungen (§§ 33 ff. SGB X) Anhoerung (§ 24 SGB X) Begruendungspflicht (§ 35 SGB X) und identifiziert Anhaltspunkte fuer Widerspruchsgruende. Erzeugt Analyseprotokoll als Vorstufe fuer den Widerspruchsentwurf.
---

# Bescheidanalyse Sozialrecht

## Zweck

Vor dem Widerspruch steht die Analyse. Dieser Skill liest einen Bescheid systematisch und extrahiert das, was der Anwalt fuer den naechsten Schritt braucht.

## Eingaben

- Bescheid als PDF Foto oder Text (auch gescannt mit OCR).
- Mandantenangaben aus `mandanten-intake`.
- Optional: vorangegangene Bescheide derselben Sache.

## Pruefraster

### Formale Pruefung

- **Behoerde** zustaendig (sachlich oertlich)?
- **Adressat** korrekt bezeichnet (Vor- und Nachname; bei Bedarfsgemeinschaft alle Mitglieder)?
- **Bescheiddatum** und **Zugangsdatum** klar (Zugang nach § 37 SGB X — Drei-Tages-Fiktion bei Post)?
- **Tenor** eindeutig?
- **Begruendung** nach § 35 SGB X mit wesentlichen tatsaechlichen und rechtlichen Gruenden vorhanden?
- **Rechtsbehelfsbelehrung** vollstaendig (Behoerde Frist Form Adressat)?
- **Anhoerung** nach § 24 SGB X erfolgt bei belastenden Bescheiden?
- **Unterschrift / Namenswiedergabe** vorhanden (§ 33 SGB X)?

### Materielle Vorpruefung

- **Anspruchsgrundlage** korrekt bezeichnet?
- **Tatbestandsmerkmale** in der Begruendung vollstaendig abgehandelt?
- **Ermessen** ausgeuebt wo erforderlich (§ 39 SGB I)?
- **Mitwirkungsobliegenheiten** § 60 ff. SGB I — wurden sie korrekt eingefordert?
- **Bestandskraft** vorheriger Bescheide?

### Besondere Bescheidarten

- **Aufhebung und Erstattung** §§ 45 / 48 / 50 SGB X — Pruefung von Vertrauensschutz Atypik Ermessen.
- **Sanktion / Leistungsminderung** § 31 SGB II / § 32 SGB II — Schwere Wiederholung Mitverschulden.
- **Aufrechnung** § 43 SGB I / § 51 SGB I — Schwellenwerte.

## Ausgabe

Analyseprotokoll mit:

1. Stammdaten Bescheid (Behoerde Az Datum Zugang)
2. Tenor und Hoehe der Beschwer
3. Rechtsbehelfsbelehrung mit Fristberechnung (Widerspruchsfrist ein Monat § 84 SGG)
4. Formelle Fehler (Anhoerung Begruendung Rechtsbehelfsbelehrung)
5. Materielle Angriffspunkte sortiert nach Erfolgsaussicht
6. Empfehlung: Widerspruch / Ueberpruefungsantrag § 44 SGB X / Untaetigkeitsklage / nichts
7. Frist im Fristenbuch eintragen — Verweis auf `fristenbuch-sozialrecht`

## Grenzen

Die Analyse ersetzt nicht die anwaltliche Entscheidung. Sie strukturiert die Vorbereitung.
