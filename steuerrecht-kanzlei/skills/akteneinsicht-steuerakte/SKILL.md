---
name: akteneinsicht-steuerakte
description: Akteneinsicht in Steuerakten — Anspruch im Einspruchsverfahren nach § 364 AO im Klageverfahren nach § 78 FGO ergaenzend Art. 15 DSGVO bei personenbezogenen Daten. Behandelt Verwaltungsakten Pruefungsakten Aktenvermerke Aussenpruefungs-Berichte. Strategie bei Schwaerzungen wegen Steuergeheimnis Dritter (§ 30 AO). Erzeugt Antragsvorlage und Auswertungsraster fuer die uebermittelte Akte.
---

# Akteneinsicht in Steuerakten

## Rechtsgrundlagen

- **§ 364 AO** Akteneinsicht im Einspruchsverfahren — wesentlicher Aspekt des rechtlichen Gehoers; Behoerde teilt die Tatsachen mit auf die sie ihre Entscheidung stuetzen will.
- **§ 78 FGO** Akteneinsicht im Klageverfahren.
- **Art. 15 DSGVO** Auskunft ueber eigene personenbezogene Daten — ergaenzend.
- **§ 88 AO** Untersuchungsgrundsatz im Verwaltungsverfahren.

## Antrag

### Im Einspruchsverfahren

```
An das Finanzamt XYZ
- Steuernummer ...

In dem Einspruchsverfahren ueber den Bescheid vom (Datum) ueber
(Steuerart) (Jahr) Az (...)

beantragt der Einspruchsfuehrer
Akteneinsicht in die vollstaendige Steuerakte gemaess § 364 AO
einschliesslich
- Veranlagungsakten der Pruefungsjahre
- Aussenpruefungs-Berichte und Pruefungs-Notizen
- Aktenvermerke
- Korrespondenz mit Dritten
- Daten ueber Kontroll- und Ueberwachungspruefungen

bevorzugt durch elektronische Uebersendung ueber beA.
```

### Im Klageverfahren

Antrag beim Finanzgericht auf Akteneinsicht (§ 78 FGO) zusammen mit der Beiziehung der Verwaltungsakten (§ 71 Abs. 2 FGO).

## Sonderfaelle

### Steuergeheimnis Dritter (§ 30 AO)

- Akten enthalten haeufig Daten Dritter (z. B. Zeugenangaben Mitteilungen von Drittstellen).
- Schwaerzung zulaessig wenn Drittdatenschutz dies erfordert.
- Bei umfangreicher Schwaerzung: Antrag auf Begruendung; ggf. gerichtliche Pruefung.

### Pruefungsanmerkungen und interne Vermerke

- Auch interne Pruefer-Notizen sind Aktenbestandteil — Anspruch grundsaetzlich gegeben.
- Kontrollmitteilungen aus § 93a AO Steuer-Identifikationssystem ggf. relevant.

### Internationaler Datenaustausch

- Bei Auslandssachverhalten: Hinweise auf CRS-Daten DAC-Auskuenfte FATCA — Akteneinsicht auch hierauf.

## Auswertung der eingegangenen Akte

Pro Aktenbestandteil:

- laufende Nummer
- Datum
- Verfasser
- Inhaltskurzfassung
- Entscheidungserheblichkeit (entscheidend / hilfreich / neutral / belastend / luecke)
- Pinpoint-Verweis fuer zukuenftigen Schriftsatz

Anschluss an Skill `steuerbescheid-analyse` und Folge-Schriftsatz.

## Aktenchronik

Tabellarisch nach Datum mit:

| Datum | Aktenteil | Verfasser | Inhalt kurz | Bewertung |
|---|---|---|---|---|

## Datenschutz

- Steuerakte enthaelt besonders sensible Daten (Vermoegen Einkommen Familie Konten).
- Verarbeitung nur in Tools mit AVV.
- Mandantenakte unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/steuerrecht-kanzlei/mandate/<az>/`.

## Ausgabe

- Akteneinsichtsantrag `akteneinsichtsantrag-<az>-<datum>.docx`.
- Aktenchronik nach Eingang `aktenchronik-<az>.md`.
- Pruefer-Pruefkatalog mit `[prueferflag]`-Eintraegen.
