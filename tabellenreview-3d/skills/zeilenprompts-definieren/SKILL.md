---
name: zeilenprompts-definieren
description: "Definiert die Zeilenprompts der zweiten Wuerfel-Achse — pro Dokument eine optionale Sonderanweisung die das Lesen genau dieses Dokuments steuert. Beispiele: 'Konzernvertrag — AktG Paragraph 311 zusaetzlich pruefen' / 'Anlage 7 fehlt — als Luecke markieren' / 'Auf englisch verfasst — uebersetzungspflichtig' / 'Aelter als 5 Jahre — Aenderungsvereinbarungen pruefen' / 'Mit Insolvenzklausel der Gegenseite gemaess InsO Paragraph 119 unwirksam'. Zeilenprompts ueberschreiben oder ergaenzen die Spaltenprompts dieser Zeile. Erzeugt `zeilenprompts.yaml`."
---

# /tabellenreview-3d:zeilenprompts-definieren

## Zweck

Spaltenprompts machen alle Dokumente vergleichbar. Zeilenprompts erlauben genau die Sonderbehandlung dort wo ein Dokument abweicht. Der Wuerfel bleibt strukturiert aber die Genauigkeit pro Dokument steigt.

## Typische Zeilenprompt-Muster

### Konzern- und Gruppenkontext

"Dieser Vertrag laeuft zwischen Mutter- und Tochtergesellschaft im 100-Prozent-Konzern — AktG Paragraph 311 und Paragraph 312 (Konzernrecht und Abhaengigkeitsbericht) zusaetzlich pruefen. Marktueblichkeit der Konditionen ist Pflichtspalte."

### Fehlende Anlagen

"Anlage 7 (Leistungsbeschreibung) ist im Datenraum nicht enthalten — als Datenraum-Luecke in der Spalte Vollstaendigkeit markieren und im Disclosure-Letter abfragen."

### Sprachfremde Dokumente

"Vertrag in englischer Sprache. Bei Zitat: Originalwortlaut PLUS deutsche Arbeitsuebersetzung in Klammern. Auslegungsmassstab nach BGB Paragraph 133 und Paragraph 157 trotz Englisch."

### Aelterer Vertrag

"Erstunterzeichnung aelter als 5 Jahre. Pruefen ob Aenderungsvereinbarungen Nachtraege oder muendliche Aenderungen aktenkundig sind. Schriftformklausel beachten BGB Paragraph 125 Satz 2."

### Insolvenzbezogene Sonderklausel

"Klausel vorhanden die im Insolvenzfall eine Kuendigung oder Aufrechnung erlaubt. Pruefen ob diese nach InsO Paragraph 119 unwirksam ist (insolvenzabhaengige Loesungsklausel)."

### Konsumentenrelevanz

"Vertragspartner ist Verbraucher gemaess BGB Paragraph 13. Daher AGB-Kontrolle nach BGB Paragraph 305 ff. strenger; Klauselverbote BGB Paragraph 308 und Paragraph 309 zusaetzlich pruefen."

### Datenraum-Disclosure

"Im Disclosure-Letter offengelegt — Disclosure-Bezug in der Spalte Garantiebezug eintragen."

## Pflichtfelder pro Zeilenprompt

```yaml
- zeile-id: vertrag-042
  pfad: "vdr/kunden/042-kundenvertrag-mueller-gmbh.pdf"
  hash: "sha256:..."
  zeilenprompt: |
    Konzernvertrag (Tochter zur Muttergesellschaft).
    Zusaetzlich: AktG Paragraph 311 / Paragraph 312 (Konzernrecht).
    Marktueblichkeit der Verguetung in der Spalte 'Verguetung' bewerten.
  ueberschreibt-spalten: ["verguetung"]
  ergaenzt-spalten: ["change-of-control"]
```

## Ausgabe

- `zeilenprompts.yaml` mit pro Zeile (Dokument) der jeweiligen Sonderanweisung
- Konflikt-Pruefung: wenn ein Zeilenprompt einer Pflicht-Spalte widerspricht meldet der Skill den Konflikt zur Pruefer-Entscheidung.

## Grenzen

Wenn die meisten Zeilen einen aehnlichen Zeilenprompt brauchen ist das ein Hinweis dass die Spaltenprompts angepasst werden muessen — der Effekt soll in den Spalten landen nicht in 80 Zeilenprompts.
