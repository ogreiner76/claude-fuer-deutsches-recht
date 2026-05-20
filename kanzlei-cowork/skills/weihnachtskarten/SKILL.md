---
name: weihnachtskarten
description: Pflegt den Weihnachtskartenversand der Kanzlei. Verteiler mit Empfaenger Anschrift E-Mail Versandart (postalisch / digital) Anredeform Bezug zur Kanzlei. Texte fuer formell-zurueckhaltend warm und persoenlich. Druckliste fuer Postversand inkl Adressetiketten und Frankierhinweis. Versandzeitraum (vor Weihnachten) und Erinnerungen. Datenschutz Art. 6 Abs. 1 lit. f DSGVO berechtigtes Interesse Mandantenpflege; Widerspruchsrecht.
---

# Weihnachtskarten Mandantenpflege

## Verteilerpflege

```yaml
- name: Mueller, Hans
  anrede: foermlich
  empfaenger: Mueller GmbH (zu Hd. Hans Mueller)
  anschrift: ...
  e-mail: hmueller@mueller-gmbh.de
  versandweg: digital  # digital / post / beides
  beziehung: Mandant Aktenkreis 2026/0042
  ton: warm-foermlich
  letzte-karte: 2025-12-15
  widerspruch: false
```

## Texte

### Foermlich-zurueckhaltend (Mandanten gemischter Branchen)

```
Sehr geehrter Herr [Nachname],

zum Ende dieses Jahres moechte ich Ihnen fuer die vertrauensvolle
Zusammenarbeit danken. Ich wuensche Ihnen ruhige besinnliche Feiertage
einen guten Uebergang ins neue Jahr und vor allem Gesundheit.

Mit freundlichen Gruessen

[Anwalt]
Kanzlei XYZ
```

### Warm (langjaehrige Geschaeftspartner Kollegen)

```
Liebe(r) [Vorname],

am Ende eines arbeitsreichen Jahres ein herzliches Dankeschoen fuer die
gute Zusammenarbeit. Ich wuensche Ihnen besinnliche Festtage einen
guten Rutsch und ein gesundes glueckliches neues Jahr.

Beste Gruesse
[Anwalt]
```

### Persoenlich (engster Kreis)

Individuell formuliert — kein Templating; auf der persoenlichen Beziehung aufbauend.

## Versandformen

### Postversand

- **Karten** mit handgeschriebener Unterschrift Pflicht.
- **Druckliste** fuer Adressetiketten oder Briefumschlag-Druck.
- **Frankierung** als Standardbrief oder Postkarte.
- **Versandzeitraum** zweite Dezemberwoche damit vor Weihnachten ankommt.

### Digitaler Versand

- **E-Mail** mit kurzer persoenlicher Anrede.
- **Anhang** optional als PDF-Karte (Briefkopf der Kanzlei).
- **Versandzeitraum** kurz vor Weihnachten (z. B. 22./23. Dezember).
- **Massenversand vermeiden** — pro Empfaenger einzeln im Bcc nicht zulaessig wegen DSGVO; lieber serienmaessig versenden.

### Hybrid

- Engste Mandanten und Partner Postkarte plus zusaetzlich kurze E-Mail.
- Sonstige nur digital.

## Druckliste fuer Postversand

CSV mit Spalten: Name Anschrift Stadt PLZ Land Ansprache.

## Versandkontrolle

- **Doppelversand** vermeiden (mit `letzte-karte`-Eintrag).
- **Verstorbene Empfaenger** entfernen.
- **Mandate beendet im Streit** ggf. entfernen.
- **Widerspruch** dauerhaft beachten.

## Datenschutz

- Erlaeuterung im Mandantenintake auf moegliche Weihnachtsgruesse.
- Widerspruchsrecht jederzeit moeglich (Art. 21 DSGVO).
- Loeschung auf Widerspruch (Art. 17 DSGVO).

## Ausgabe

- Aktualisierter Verteiler.
- Druckliste (CSV).
- E-Mail-Entwuerfe zur Freigabe.
- Audit mit Versanddatum pro Empfaenger.
