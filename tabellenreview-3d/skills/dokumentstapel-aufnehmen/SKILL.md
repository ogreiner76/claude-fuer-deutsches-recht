---
name: dokumentstapel-aufnehmen
description: "Nimmt einen Dokumentenstapel als Zeilenachse des Wuerfels auf. Quellen: VDR-Export (Datasite Intralinks Box) lokaler Ordner SharePoint-Bibliothek E-Mail-Anhang-Sammlung gescannte PDF mit OCR-Pipeline. Erzeugt pro Dokument einen Zeileneintrag mit kanonischem Pfad SHA-256-Hash Dokumenttyp-Klassifikation Sprache OCR-Konfidenz Seitenzahl und initial leerem Zeilenprompt. Erkennt Duplikate ueber Hash und Quasi-Duplikate ueber Aehnlichkeitsmass. Markiert Datenraum-Luecken (Referenzen auf nicht vorhandene Anlagen). Schreibt `zeilen-inventar.yaml`."
---

# /tabellenreview-3d:dokumentstapel-aufnehmen

## Zweck

Bevor der Reviewlauf startet muss der Dokumentenstapel sauber sein — kein Dokument doppelt kein Dokument vergessen kein Dokument falsch klassifiziert. Dieser Skill ist die Eingangsphase der Zeilenachse.

## Eingabequellen

- **VDR-Export:** Verzeichnis mit Originalstruktur — Datasite Intralinks Box SharePoint
- **Lokaler Ordner:** flach oder verschachtelt
- **E-Mail-Anhaenge:** automatische Extraktion aus EML / MSG
- **Gescannte PDF:** OCR-Pipeline mit Konfidenzwert pro Seite
- **Manuelle Liste:** vom Nutzer eingegebene Dateipfade

## Ablauf

1. **Inventarisierung:** alle Dateien rekursiv erfassen, kanonischen Pfad bilden.
2. **Hashing:** SHA-256 pro Datei berechnen — Basis fuer Duplikaterkennung und Belegkette.
3. **Klassifikation:** Dokumenttyp aus Dateiname Mimetype und Inhalt (z. B. Vertrag-Kunde / Vertrag-Lieferant / NDA / Bankvereinbarung / Lizenzvertrag / Personalakte / Grundbuchauszug / Mietvertrag / Gesellschaftsvertrag).
4. **Sprache:** Sprachidentifikation pro Dokument (Deutsch / Englisch / sonstige).
5. **OCR bei Scans:** OCR ausfuehren, Konfidenz protokollieren. Konfidenz unter 90 Prozent = `prueferflag`.
6. **Duplikatpruefung:** Hash-Identitaet erkennt exakte Duplikate. Aehnlichkeit (z. B. Cosine ueber Embedding) erkennt Quasi-Duplikate (Fassungen / Aenderungsvereinbarungen).
7. **Datenraum-Luecken:** wenn ein Dokument auf `Anlage 7` verweist und im Stapel keine `anlage 7` vorhanden ist, als `luecke` markieren.
8. **Zeilen-Inventar schreiben:** `zeilen-inventar.yaml` mit allen Zeilen, jede mit `id` `pfad` `hash` `typ` `sprache` `ocr-konfidenz` `pruefer-flag` und leerem `zeilenprompt`.

## Pflichtfelder pro Zeile

```yaml
- id: z-0042
  pfad: "vdr/kunden/042-rahmenvertrag-mueller-gmbh-2023.pdf"
  hash: "sha256:a1b2..."
  typ: "rahmenvertrag-kunde"
  sprache: "de"
  seitenzahl: 47
  ocr-konfidenz: 0.97
  pruefer-flag: null
  zeilenprompt: ""
  datenraum-luecken: []
```

## Ausgabe

- `zeilen-inventar.yaml` — vollstaendige Zeilenachse
- `duplikatreport.md` — exakte und Quasi-Duplikate mit Pruefer-Entscheidung
- `datenraum-luecken.md` — referenzierte aber nicht vorhandene Dokumente

## Grenzen

Klassifikation ist heuristisch. Bei Konfidenz unter 80 Prozent fragt der Skill zurueck. OCR-Qualitaet haengt vom Scan ab. Belegkette ist nur so gut wie die OCR-Konfidenz.
