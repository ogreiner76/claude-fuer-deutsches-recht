---
name: wuerfel-aufbauen
description: "Baut die dreidimensionale Wuerfel-Struktur fuer ein neues Pruefprojekt auf — drei Achsen: Spalten (Datenpunkte als Spaltenprompts) Zeilen (Dokumente mit optionalen Zeilenprompts) Arbeitsblaetter (Perspektiven wie Recht / Steuer / Wirtschaft / Datenschutz / IT / Betrieb). Erzeugt das Wuerfel-Schema `wuerfel-schema.yaml` mit allen drei Achsen Ankerpunkten Materialitaetsschwellen Spaltenprompt-Bibliotheksverweisen und Belegkette-Konventionen. Vorlauf zu jedem Reviewlauf. Geeignet fuer M&A-DD Vendor-Onboarding Immobilienportfolios Arbeitsvertrags-Stapel und Eigenwuerfel."
---

# /tabellenreview-3d:wuerfel-aufbauen

## Zweck

Bevor ein Reviewlauf startet, muss die Wuerfel-Struktur stehen. Dieser Skill fragt die drei Achsen ab und schreibt sie in eine versionierte `wuerfel-schema.yaml`. Die Reviewlauf-Skills lesen ausschliesslich diese Datei. Wer den Wuerfel aendern will aendert das Schema; nichts verschwindet still.

## Eingaben

- Praxisprofil unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/tabellenreview-3d/CLAUDE.md`
- Projektname (kebab-case)
- Anwendungsfall (M&A-DD / Immobilien / Vendor / Arbeitsvertrag / Mietvertrag / Anlage / Eigenwuerfel)
- Optional: Vorlage aus dem Plugin (siehe Skills `vorlage-*`)
- Optional: bestehende Spaltenprompt-Bibliothek

## Methodik

1. **Achse 1 — Spalten (Datenpunkte) definieren**
   - Jede Spalte ist ein Spaltenprompt: eine einzige praezise Frage, die fuer ALLE Dokumente gleich beantwortet wird.
   - Pflichtfelder pro Spalte: `id`, `titel`, `prompt`, `antworttyp` (Freitext / Zitat-mit-Fundstelle / ja-nein / Datum / Geldbetrag / Aufzaehlung), `pflichtfeld` (ja / nein), `ampel-regel` (wann rot / gelb / gruen).
2. **Achse 2 — Zeilen (Dokumente) definieren**
   - Jede Zeile ist ein Dokument mit Quellpfad Hash und optionalem Zeilenprompt.
   - Pflichtfelder pro Zeile: `id`, `pfad`, `hash`, `dokumenttyp`, optional `zeilenprompt` fuer dokumentspezifische Sonderanweisungen.
3. **Achse 3 — Arbeitsblaetter (Perspektiven) definieren**
   - Jedes Arbeitsblatt ist eine eigene Pruefperspektive die ueber denselben Dokumentenstapel laeuft.
   - Beispiele: Recht (Anwaltsperspektive) / Steuer (Steuerberater) / Wirtschaft (Buyside) / Datenschutz (DSGVO) / IT (Architektur) / Betrieb (Operations)
   - Pflichtfelder pro Arbeitsblatt: `id`, `titel`, `perspektive`, `eigene-spalten-zusaetze` (Arbeitsblatt-spezifische Zusatzspalten) und `auslassungen` (Spalten die fuer dieses Blatt nicht gelten).
4. **Risikoampel-Konsolidierung** je Achse festlegen: Wann ist eine Zelle rot? Wann eine ganze Zeile rot? Wann ein ganzes Arbeitsblatt rot?
5. **Belegkette-Konvention:** jedes Zitat in einer Zelle muss zurueckverfolgbar sein auf Datei-Hash und Stelle (Seite Absatz Ziffer).
6. **Audit-Trail:** Prompt-Versionen Reviewlauf-Zeitstempel Pruefer-Abnahmen werden separat protokolliert.

## Ausgabe

- `wuerfel-schema.yaml` mit allen drei Achsen, vollstaendig definiert
- `wuerfel-vorschau.md` — menschenlesbare Uebersicht zur Pruefer-Abnahme
- Optional: `spaltenprompt-bibliothek.yaml` als Referenz auf Standard-Spaltenprompts

## Quellenpflicht

Verbindlich gegen `references/zitierweise.md` im Repository. Jede juristische Anspielung im Spaltenprompt benoetigt einen Verweis auf Norm Rechtsprechung oder Kommentarstelle.

## Beispiel

Wuerfel fuer M&A-DD bei Erwerb einer SaaS-GmbH:
- **Spalten:** 12 Datenpunkte (Vertragsart Laufzeit Kuendigungsfrist Change-of-Control Abtretungsverbot Haftungsbegrenzung Service-Level Datenschutz-Auftragsverarbeitung Geheimhaltung Verguetung-Anpassungsklausel anwendbares Recht Gerichtsstand)
- **Zeilen:** 87 Vertraege aus dem Datenraum (Kunden Lieferanten Banken Lizenzen Personal)
- **Arbeitsblaetter:** 4 Perspektiven (Recht / Steuer / Wirtschaft / Datenschutz)
- Ergebnis: 12 mal 87 mal 4 = 4176 Zellen, jede mit woertlichem Zitat und Fundstelle.

## Grenzen

Das Schema ist nur die Architektur. Der eigentliche Reviewlauf erfolgt im Skill `review-durchfuehren`. Wer das Schema nachtraeglich aendert nachdem schon ein Lauf erfolgt ist muss `prompt-versionierung` und `caching-und-teil-rerun` beachten.
