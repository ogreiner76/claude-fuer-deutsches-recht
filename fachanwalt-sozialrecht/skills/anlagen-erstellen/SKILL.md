---
name: anlagen-erstellen
description: "Anwalt muss Anlagenkonvolut zu Widerspruch Klage oder Schriftsatz in korrekter juristischer Konvention erstellen. Anlagenanhaenge Sozialrecht K1/W1/A1-Konvention. Prüfraster: Sigel Bezeichnung Quelle Datum Seitenzahl Bezug im Text. Erzeugt Anlagenverzeichnis und prüft Vollständigkeit jede Anlage muss im Text zitiert sein. Output: Anlagenverzeichnis als Vorblatt mit korrekter Nummerierung. Abgrenzung zu akteneinsicht-auswerten (Aktensichtung) und normenkontrollantrag-schriftsatz in anderen Plugins."
---

# Anlagen erstellen

## V90 Fachkern — Sozialrecht und Sozialversicherungsrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Anlagen erstellen` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** SGB I, IV § 7 und § 7a, V, VI, VII, IX, X §§ 20, 24, 44, 45, 48, 50, 60 ff.; SGB II, XII; SGG §§ 54, 86a, 86b, 87, 90, 103, 109, 144, 151, 160; Pflegebegutachtung/MD-Richtlinien live prüfen.
- **Verifizierte Anker:** BSG, Urteil vom 05.11.2024 - B 12 BA 3/23 R (Lehrende/Dozenten: Status immer einzelfallabhängig); BSG, Urteil vom 23.04.2024 - B 12 BA 9/22 R (Pilot/Freelancer, Eingliederung und unternehmerisches Risiko); BSG, Urteil vom 01.02.2022 - B 12 KR 37/19 R und Urteil vom 20.02.2024 - B 12 KR 1/22 R (GmbH-Geschäftsführer, Sperrminorität/mittelbare Beteiligung).
- **Arbeitsmodus:** Immer Verwaltungsakt, Frist, Widerspruch/Klage/eA, Amtsermittlung, medizinische Tatsachen, Mitwirkungspflichten und Beweisgutachten trennen; bei Status § 7 SGB IV: tatsächliche Eingliederung, Weisung, Rechtsmacht und Unternehmerrisiko abgleichen.
- **Outputpflicht:** Bescheidanalyse in einfacher Sprache, Widerspruch, eA-Antrag, Statusmatrix, medizinische Beweisfragen, Belegliste, Fristenplan oder SG-Schriftsatz.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Fachkern: Anlagen erstellen

- **Spezialfrage (Anlagen erstellen):** Sigel Bezeichnung Quelle Datum Seitenzahl Bezug im Text. Erzeugt Anlagenverzeichnis und prüft Vollständigkeit jede Anlage muss im Text zitiert sein. Output: Anlagenverzeichnis als Vorblatt mit korrekter Nummerierung. Abgrenzung zu akteneinsicht-auswerten (Aktensichtung) und normenkontrollantrag-schriftsatz in anderen Plugins.
- **Arbeitsweise:** Erst Sachverhalt, Norm, Frist, Zuständigkeit und Beweis klären; Rechtsprechung nur verifiziert als tragenden Beleg einsetzen.


## Aktuelle Rechtsprechung
- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
- Quellenregel: Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff; keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen.
- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

## Konvention

| Verfahrensart | Sigel-Praefix |
|---|---|
| Klage zum Sozialgericht | `K1`, `K2`, ... |
| Widerspruch | `W1`, `W2`, ... |
| Eilantrag | `E1`, `E2`, ... |
| Beweisantrag im Verfahren | `B1`, `B2`, ... |
| Allgemeines Anlagenkonvolut | `A1`, `A2`, ... |

## Eingaben

- Schriftsatz im Entwurf (aus `widerspruch-formulieren` `klage-sozialgericht` `eilantrag-sozialrecht`).
- Originaldokumente (PDF Foto Scan).

## Ablauf

### 1. Anlagenliste erstellen

Pro Anlage:
- **Sigel** (K1 W1 ...)
- **Kurzbezeichnung** ("Bescheid des Jobcenters vom 12.03.2026")
- **Quelle** (Mandant Behörde Drittstelle)
- **Datum** des Originaldokuments
- **Seitenzahl** im Original
- **Fundstelle im Schriftsatz** (z. B. "Seite 4 Randnummer 12")

### 2. PDF-Anlagen vorbereiten

- Original als PDF ablegen.
- Stempel oben rechts auf erste Seite jeder Anlage: das Sigel (`K1`).
- Doppelseitige Scans prüfen.
- Persönliche Daten Dritter schwaerzen wenn nicht erforderlich (DSGVO Datenminimierung).

### 3. Anlagenverzeichnis als Vorblatt

Vorblatt zur Klage- oder Widerspruchsakte:

```
Anlagenverzeichnis

K1   Bescheid des Jobcenters XYZ vom 12.03.2026
K2   Widerspruch vom 05.04.2026
K3   Widerspruchsbescheid vom 18.07.2026
K4   Schwerbehindertenausweis vom 14.11.2024 (GdB 70)
K5   Aerztliches Attest Dr. M. vom 03.02.2026
K6   Mietvertrag mit Anlagen
```

### 4. Vollständigkeitsprüfung

- Wird jede Anlage im Schriftsatz zitiert? Andernfalls Anlage streichen oder Schriftsatz ergänzen.
- Wird jedes Sigel im Schriftsatz auf das richtige Anlagedokument verweisen?
- Reichen die Anlagen aus um die Behauptungen glaubhaft zu machen / zu beweisen?

### 5. Anlagenkonvolut zusammenstellen

- Alle Anlagen in Reihenfolge K1 K2 K3 ... in eine PDF-Datei.
- Lesezeichen pro Anlage für schnelle Navigation.
- Endgültige Dateibenennung: `klage-anlagen-<az>-<datum>.pdf`.

## Ausgabe

- `anlagenverzeichnis-<az>.md`
- `anlagenkonvolut-<az>.pdf` mit Lesezeichen und Sigel-Stempeln
- Eintrag im Postausgang verlinkt mit dem Schriftsatz

## Versand

Vor Versand der Skill `versand-vor-check` aus dem Plugin `kanzlei-allgemein`.
