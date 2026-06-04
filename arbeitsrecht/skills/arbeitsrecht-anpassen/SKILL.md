---
name: arbeitsrecht-anpassen
description: "Gezielte Anpassung des Arbeitsrechts-Praxisprofils – Standort-Fußabdruck, Risikoeinstellung, Eskalationskontakte, Einstellungsregeln, Kündigungsregeln, Handbuchpositionen oder Untersuchungseinstellungen ändern, ohne das gesamte Kaltstart-Interview neu zu durchlaufen."
---

# /arbeitsrecht:arbeitsrecht-anpassen

## V90 Fachkern — Arbeitsrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `/arbeitsrecht:arbeitsrecht-anpassen` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** BGB §§ 611a, 613a, 615, 623; KSchG §§ 1, 4, 7; TzBfG §§ 14, 15, 16; AGG §§ 1, 3, 7, 15, 22; EntgTranspG §§ 3, 5, 7; BUrlG §§ 1, 3, 7; BetrVG §§ 87, 99, 102; ArbZG; NachwG; SGB IX §§ 164, 167, 168.
- **Verifizierte Anker:** BAG, Urteil vom 23.10.2025 - 8 AZR 300/24 (Entgeltgleichheit, Paarvergleich, Beweislast, bundesarbeitsgericht.de); BAG, Urteil vom 03.06.2025 - 9 AZR 104/24 (kein Verzicht auf gesetzlichen Mindesturlaub im bestehenden Arbeitsverhältnis); bei Kündigungszugang immer § 623 BGB, Zugang nach § 130 BGB, Dreiwochenfrist §§ 4, 7 KSchG und Beweis des konkreten Umschlags trennen.
- **Arbeitsmodus:** Zuerst Status, Zugang, Frist, Beteiligungsrechte, Sonderkündigungsschutz, Beweislast und prozessualen nächsten Schritt sichern; dann erst Materiellrecht vertiefen.
- **Outputpflicht:** Fristenblatt, Zugangsmatrix, Beweisangebot, Mandantenmail, Betriebsrats-/Gegnerbrief oder Klage-/Erwiderungsbaustein.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Zweck

Der Nutzer möchte etwas im Praxisprofil ändern – eine Jurisdiktion, eine Risikoeinstellung, einen Eskalationskontakt, eine Handbuchposition – ohne das gesamte Kaltstart-Interview zu wiederholen.

## Eingaben

- Beschreibung der gewünschten Änderung (Freitext oder Abschnittsname)
- Aktuelle Konfigurationsdatei `~/.claude/plugins/config/claude-fuer-deutsches-recht/arbeitsrecht/CLAUDE.md`

## Ablauf

### 1. Konfiguration lesen

`~/.claude/plugins/config/claude-fuer-deutsches-recht/arbeitsrecht/CLAUDE.md` und `~/.claude/plugins/config/claude-fuer-deutsches-recht/unternehmens-profil.md` einlesen.

Falls das Plugin noch nicht eingerichtet ist oder `[PLATZHALTER]` enthält:
> Das Plugin wurde noch nicht eingerichtet. Führen Sie `/arbeitsrecht:arbeitsrecht-kaltstart-interview` aus.

### 2. Gewünschte Änderung klären

Wenn die Angabe des Nutzers unklar ist, einen einzigen klärenden Prompt stellen – nicht mehrere Nachfragen hintereinander:

> Was möchten Sie ändern?
> - Neuen Standort / neues Bundesland hinzufügen
> - Tarifvertrag oder Betriebsratssituation aktualisieren
> - Eskalationskontakt ändern
> - Einstellungs- oder Kündigungsregeln anpassen
> - Handbuch-/Betriebsvereinbarungsreferenz aktualisieren
> - Integrationen neu prüfen (`--check-integrations`)
> - Anderes – bitte beschreiben

### 3. Nur den betroffenen Abschnitt aktualisieren

Den relevanten Abschnitt in der Konfigurationsdatei isolieren, die Änderung durchführen, den Rest unberührt lassen. Keine komplette Neugenerierung.

**Besonderheiten:**
- **Neuer Standort / Bundesland:** Eskalationstabelle um das neue Bundesland ergänzen. Auf besondere Landesgesetze hinweisen (z.B. Bayerisches Urlaubsgesetz, abweichendes Landesdatenschutzrecht). KSchG-Schwellenwert neu berechnen.
- **Neuer Tarifvertrag:** Nachwirkung (§ 4 Abs. 5 TVG) und Günstigkeitsprinzip (§ 4 Abs. 3 TVG) berücksichtigen. Ggf. Hinweis auf Allgemeinverbindlichkeit (§ 5 TVG).
- **Betriebsrat neu eingetragen:** § 102 BetrVG-Verpflichtung in Eskalationstabelle aufnehmen; Hinweis auf § 99 BetrVG (Einstellung) und § 87 BetrVG (Mitbestimmung).
- **Eskalationskontakt:** Nur dieses Feld ändern; Risikologik bleibt.

### 4. Änderung schreiben und bestätigen

Die geänderte Konfiguration zurückschreiben und dem Nutzer mitteilen, was geändert wurde (Vorher/Nachher, ein Diff).

## Quellen und Zitierweise

Zitierstandard: `../references/zitierweise.md`. Methodik: `../references/methodik-buergerliches-recht.md`.

Relevante Normen je nach Änderungsbereich:
- Neues Bundesland: Landesurlaubsgesetze, LDSG des Landes, ggf. Tarifvertrag mit Landesbezug
- Betriebsrat: BetrVG §§ 1, 87, 99, 102, 111 ff.
- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

## Ausgabeformat

```
Profil-Änderung: [Kürzel der Änderung]
================================================
Geändert:  [Abschnitt in CLAUDE.md]

Vorher:
  [Alt-Wert]

Nachher:
  [Neu-Wert]

Gespeichert: ~/.claude/plugins/config/claude-fuer-deutsches-recht/arbeitsrecht/CLAUDE.md
```

## Beispiele

```
/arbeitsrecht:arbeitsrecht-anpassen
Neuen Standort Hamburg hinzufügen, ca. 25 Mitarbeiter, kein Betriebsrat.
```

```
/arbeitsrecht:arbeitsrecht-anpassen
Eskalationskontakt für betriebsbedingte Kündigungen auf Dr. Müller (GC) ändern.
```

```
/arbeitsrecht:arbeitsrecht-anpassen
Wir sind seit Januar diesem Jahr an den Tarifvertrag Einzelhandel NRW gebunden.
```

## Risiken / typische Fehler

- **Landesrecht übersehen.** Bayern, Brandenburg und andere Länder haben eigene Urlaubsgesetze mit abweichenden Mindesturlaubstagen. Bei neuem Bundesland immer Landesspezifika prüfen.
- **Tarifbindung durch Bezugnahmeklausel.** Auch ohne Verbandsmitgliedschaft kann ein Tarifvertrag vertraglich einbezogen sein. Prüfen, ob neue Tarifbindung auch bestehende Verträge erfasst.
- **Betriebsrat-Zuständigkeit.** Bei neuem Betriebsrat: § 102 BetrVG gilt für JEDE Kündigung, § 99 BetrVG für jede Einstellung – sofort in Eskalationstabelle aufnehmen.
