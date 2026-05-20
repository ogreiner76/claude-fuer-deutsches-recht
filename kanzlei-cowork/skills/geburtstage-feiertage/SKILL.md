---
name: geburtstage-feiertage
description: Pflegt einen Mandanten- und Geschaeftspartner-Geburtstagsverteiler. Reminders einige Tage vor dem Tag. Vorlagen fuer kurze persoenliche Glueckwunsch-E-Mail (formell-warm). Bei Geschaeftspartnern auch Firmenjubilaeen. Geburtstagsverteiler getrennt von Mandantenfaellen — Pflege als Geschaeftspartnerstamm. Datenschutz beachten Art. 6 Abs. 1 lit. f DSGVO berechtigtes Interesse Geburtstagsglueckwunsch zulaessig; Widerspruchsrecht Mandant beachten.
---

# Geburtstage und Feiertage

## Pflege des Verteilers

### Quellen

- Mandantenstammdaten aus `mandantenakte-anlegen`.
- Geschaeftspartner (Steuerberater Notar Sachverstaendige Kollegen).
- Eingangsbedingung: ausdrueckliche oder konkludente Einwilligung des Empfaengers.

### Datenmodell

```yaml
- name: Mueller, Hans
  geburtstag: 1972-08-15
  funktion: Geschaeftsfuehrer Mueller GmbH (Mandant Aktenkreis 2026/0042)
  ansprache: foermlich  # foermlich / vornamen / locker
  versandweg: e-mail
  e-mail: hmueller@mueller-gmbh.de
  vorlauf-tage: 2
  letzte-glueckwuensche: 2025-08-14
  widerspruch-eingelegt: false
```

### Datenschutz

- **Art. 6 Abs. 1 lit. f DSGVO** berechtigtes Interesse — Mandantenpflege ist allgemein zulaessig.
- **Widerspruchsrecht** beachten — auf Widerspruch hin Eintrag deaktivieren.
- **Information bei Mandatsbeginn** (Datenschutzhinweis § 13 DSGVO) auf moegliche Glueckwunschsendungen.
- **Verarbeitungsverzeichnis** nach Art. 30 DSGVO ergaenzen.

## Tagesbrief-Integration

Im `sekretariats-tagesbrief` morgens Eintrag:

```
Heute / in den naechsten Tagen Geburtstag:
- 22.05.2026 Hans Mueller, Geschaeftsfuehrer Mueller GmbH — Glueckwunsch vorbereiten
- 24.05.2026 RA Dr. Schulz, Kollege Kanzlei XYZ — kurze Mail
```

## Vorlagen

### Foermlich

```
Betreff: Herzliche Glueckwuensche zum Geburtstag

Sehr geehrter Herr [Nachname],

zu Ihrem heutigen Geburtstag uebermittle ich Ihnen meine besten persoenlichen
Glueckwuensche. Ich wuensche Ihnen vor allem Gesundheit Zufriedenheit und
Erfolg im neuen Lebensjahr.

Mit freundlichen Gruessen
[Anwalt]
```

### Vertraut (langjaehriger Geschaeftspartner)

```
Betreff: Alles Gute zum Geburtstag

Lieber [Vorname],

zu Ihrem heutigen Geburtstag herzliche Glueckwuensche. Vielen Dank fuer die
gute und vertrauensvolle Zusammenarbeit im vergangenen Jahr.

Beste Gruesse aus der Kanzlei
[Anwalt]
```

## Firmenjubilaeen

- Erfassung des Gruendungsdatums (Handelsregister) bei juristischen Personen als Mandanten.
- 10 25 50 75 100 Jahre als Schwellen.
- Bei runder Jahreszahl: persoenliche Glueckwunschkarte zusaetzlich zur E-Mail.

## Feiertagsversand

- Weihnachten: siehe Skill `weihnachtskarten`.
- Ostern Neujahr: optional je nach Kanzlei.

## Sicherheits-Check

- Vor Versand: Empfaenger noch aktiv? Lebt noch? Mandat nicht beendet im Streit?
- Bei Streit beendeten Mandaten: Eintrag manuell deaktivieren oder loeschen.

## Audit

- Letzte Versendung dokumentiert (vermeidet Doppelversand und ermoeglicht Auswertung).
- Bei Widerspruch unverzueglich loeschen oder anonymisieren (DSGVO Art. 17).

## Ausgabe

- Aktualisierter Geburtstagsverteiler.
- Tagesbrief-Eintrag.
- Versand-E-Mails als Entwurf zur Freigabe.
