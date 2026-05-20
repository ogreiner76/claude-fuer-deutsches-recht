---
name: akteneinsicht-auswerten
description: Systematische Auswertung der beigezogenen Verwaltungs- oder Gerichtsakte — chronologische Sichtung Identifikation entscheidungserheblicher Aktenstuecke (Antrag Bescheid Widerspruch medizinische Gutachten Sachverstaendigenstellungnahmen Aktenvermerke). Erzeugt Aktenchronik Aktenliste mit Bewertung pro Eintrag (entscheidend / hilfreich / neutral / belastend) Widerspruechen zwischen Aktenteilen und Pruefkatalog fuer Folgeschriftsatz. Anschluss an Skill `widerspruch-formulieren` oder `klage-sozialgericht`.
---

# Akteneinsicht auswerten

## Zweck

Aus einer eingegangenen Akte rasch das Entscheidungserhebliche herausziehen. Was sagt die Akte was die Behoerde im Bescheid weggelassen oder anders dargestellt hat?

## Eingabe

- Vollstaendige Verwaltungsakte (PDF; ggf. gescannt mit OCR).
- Bisheriges Analyseprotokoll aus `bescheidanalyse`.

## Ablauf

### 1. Inventarisierung

Jeder Aktenteil mit:
- laufender Nummer
- Datum
- Verfasser / Quelle
- Typ (Antrag / Bescheid / Gutachten / Vermerk / Stellungnahme / Schreiben Dritter / Beleg)
- Seitenanzahl
- Pruefer-Flag falls schlecht lesbar oder geschwaerzt

### 2. Chronologische Aktenchronik

Tabelle nach Datum sortiert mit Kurzinhalt — eine Zeile pro Aktenteil.

### 3. Inhaltsbewertung pro Aktenteil

Pro Aktenteil eine Klassifizierung:
- **entscheidend** — traegt das Ergebnis (entweder fuer oder gegen den Mandanten)
- **hilfreich** — stuetzt unsere Argumentation
- **neutral** — Sachverhaltsdokumentation ohne Wertung
- **belastend** — stuetzt die Behoerdenentscheidung
- **luecke** — verweist auf Vorgang der nicht in der Akte ist

### 4. Widerspruchspruefung

- **Bescheid vs Aktenstand** — sagt der Bescheid Dinge die in der Akte anders stehen?
- **Verfahrensvermerke** — wurde die Anhoerung gefuehrt aktenkundig?
- **Medizinische Gutachten** — sind sie schluessig nachvollziehbar? Wurden Befunde aus Arztbriefen ueberhaupt zur Kenntnis genommen?
- **Ermittlungsumfang** — hat die Behoerde alles erhoben was sie haette erheben muessen (§ 20 SGB X)?
- **Datenherkunft** — woher hat die Behoerde Drittauskuenfte und durfte sie diese erheben?

### 5. Folge-Pruefkatalog

Fuer den naechsten Schriftsatz:
- Welche Aktenstuecke zitieren wir mit Pinpoint (Seite Absatz)?
- Welche Aktenstuecke widerlegen die Bescheidbegruendung?
- Wo brauchen wir eine Stellungnahme des Mandanten?
- Wo brauchen wir ein eigenes Privatgutachten zur Untermauerung?
- Welche Beweisantraege koennten wir im Klageverfahren stellen?

## Ausgabe

- `aktenchronik-<mandat>.md` mit Chronik und Bewertung.
- `aktenpruefliste-<mandat>.md` mit Pruefer-Flags zur Klaerung mit Mandant.
- Vorlage `schriftsatzbausteine-<mandat>.md` mit zitierfaehigen Pinpoint-Verweisen aus der Akte fuer den Folgeschriftsatz.

## Hinweis zur Vertraulichkeit

Verwaltungs- und Sozialakten enthalten besonders sensible Daten (Gesundheit Sozialleistungen Vermoegen). Verarbeitung nur in Tools mit AVV. Mandantenakte unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/sozialrecht-kanzlei/mandate/<az>/` ablegen.
