---
name: bea-versand-pruefen
description: Prueft den beA-Versand nach Pflichten des § 130a ZPO § 32d StPO § 65d SGG § 55a VwGO § 52d FGO sowie § 31a BRAO. Erforderliche Beachtung sicherer Uebermittlungsweg (sUW durch persoenliches Versenden des beA-Inhabers) oder qualifizierte elektronische Signatur (qeS). Prueft Versand-Quittung Eingangsbestaetigung und Verwertbarkeit fuer Fristnachweis. Hinweis Wiedereinsetzung bei beA-Stoerung mit Glaubhaftmachung. Pflichtschritt bei elektronischem Versand an Gerichte und Behoerden.
---

# beA-Versand pruefen

## Rechtsgrundlagen

- **§ 31a BRAO** beA-Pflicht fuer Rechtsanwaelte.
- **§ 130a ZPO** elektronische Einreichung Zivilprozess.
- **§ 32d StPO** elektronische Einreichung Strafprozess.
- **§ 65d SGG** Sozialgerichtsverfahren.
- **§ 55a VwGO** Verwaltungsgerichtsverfahren.
- **§ 52d FGO** Finanzgerichtsverfahren.
- **§ 12 ERVV** Elektronischer-Rechtsverkehr-Verordnung.

## Zwei zulaessige Versandwege

### 1. Sicherer Uebermittlungsweg (sUW)

- Versand erfolgt persoenlich durch den beA-Inhaber.
- Anmeldung mit beA-Karte und PIN.
- Keine qualifizierte elektronische Signatur erforderlich am einzelnen Schriftsatz.
- Signatur durch sUW gilt als ausreichend (§ 130a Abs. 3 Satz 1 Var. 2 ZPO).

### 2. Qualifizierte elektronische Signatur (qeS)

- Schriftsatz wird mit qeS unterzeichnet.
- Versand durch eine andere Person (z. B. Sekretariat) zulaessig.
- qeS muss vom Anwalt mit beA-Karte erstellt sein.

## Pflichtpruefung

### Vor Versand

- [ ] Schriftsatz unterzeichnet durch qeS **oder** Versand durch den beA-Inhaber selbst (sUW)?
- [ ] Empfaenger ueber das beA-Adressbuch identifiziert (SAFE-ID)?
- [ ] PDF im Format PDF/A oder Standard-PDF (lesbar)?
- [ ] Anlagen als einzelne PDF oder im Hauptdokument eingebunden?
- [ ] Gesamtnachrichtgroesse unter beA-Limit (200 MB; bei sehr grossen Anlagen sequenziell)?

### Nach Versand

- [ ] **Versandbestaetigung** des beA-Systems gespeichert?
- [ ] **Eingangsbestaetigung** des Empfangsgerichts / der Empfangsbehoerde liegt vor?
- [ ] Zeitstempel auf der Quittung passt zum Versand?
- [ ] Bei Fristsache: Quittung **vor** Fristablauf erzeugt?

## Quittungsformate

Das beA gibt zwei Quittungen:

1. **Sendebericht** der eigenen beA-Anwendung — Zeitpunkt der erfolgreichen Uebertragung an den Server.
2. **Eingangsbestaetigung** des Empfaengers (Gericht) — bestaetigt Eingang in der Posteingangsstelle.

Beide gehoeren in die Mandatsakte unter `mandate/<az>/03_schriftsaetze/<datum>-bea-quittung.pdf`.

## Fristnachweis

- **Eingang beim Gericht** bestimmt Fristwahrung (§ 130a Abs. 5 ZPO Eingang in die fuer das Gericht bestimmte Posteingangsstelle).
- **Eigene Sendebestaetigung allein** reicht nicht — entscheidend ist die Eingangsbestaetigung beim Empfaenger.

## Stoerung des beA

- **Stoerungsdokumentation** Screenshot Fehlermeldung Datum Uhrzeit.
- **Ersatzeinreichung** schriftlich + qeS gemaess § 130d Satz 3 ZPO.
- **Glaubhaftmachung** der Stoerung unverzueglich nach Wegfall (§ 130d Satz 2 ZPO iVm § 67 SGG analog).
- **Wiedereinsetzung** § 233 ZPO bei unverschuldetem Fristversaeumnis.

## Audit

- Eintrag im `versand-audit.jsonl`.
- Quittungs-PDFs gesichert.
- Verbindung zum Fristenbuch (Fristerledigung markiert).

## Sonderfaelle

### Mehrere Anlagen

- Inhaltsverzeichnis der Nachricht klar (Hauptschriftsatz + Anlagen K1 K2 ...).
- Anlagen einzeln als PDF oder im Konvolut — je nach Gerichtspraxis.

### Empfaenger ohne beA

- Wenn die Empfaenger-Behoerde noch nicht ueber beA / EGVP erreichbar: Postversand mit qualifizierter Bestaetigung (Bote Einschreiben).
- Bei Gerichten in Deutschland generell EGVP-Eingang vorhanden — Pruefung im beA-Adressbuch.

### RA-zu-RA

- Versand an gegnerischen Anwalt ueber beA ist zulaessig.
- Nicht Pflicht (§ 14 BORA gilt fuer Pflichten zwischen Anwaelten; beA-Pflicht ist nur ggu. Gerichten und Behoerden).

## Ausgabe

- Eintrag im `versand-audit.jsonl`.
- Quittungen unter Mandatsakte.
- Bei Stoerung: Stoerungsdokumentation als PDF.
