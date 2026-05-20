---
name: memorandums-ersteller
description: Erzeugt aus heterogenen Mandantenunterlagen ein professionelles juristisches Memorandum mit Vier-Teile-Gliederung — Sachverhalt mit lueckenloser Quellenreferenzierung; Fragestellung als Ein-Satz-Fragen; Antworten als Ein-Satz-Antworten; Rechtliche Ausfuehrungen mit Anspruchsgrundlage Tatbestandsvoraussetzungen Subsumtion und Ergebnis. Identifiziert Widersprueche und offene Punkte. Trennt strikt Tatsachen von Wuerdigung. Pinpoint-Zitierung mit Randnummer juengere Rechtsprechung zuerst. Optional Piercing-Questions zur Identifikation des rechtlichen Kerns. Aliasnamen Memorandumsmacher und Memorandumisierer. Rechtsgebietsneutral fuer Arbeitsrecht Mietrecht Gesellschaftsrecht Vertragsrecht und alle weiteren Gebiete einsetzbar.
---

# Memorandums-Ersteller

## Leitidee

Strukturierte Sachverhaltsaufbereitung ist das Fundament jeder
qualifizierten Rechtsberatung. Bevor eine rechtliche Wuerdigung
moeglich ist, muss der Sachverhalt vollstaendig erfasst, chronologisch
geordnet und auf Widersprueche geprueft werden. Der Skill leistet
genau diese Vorarbeit und erzwingt durch das Format zugleich
juristische Disziplin.

Aliasnamen je nach Kanzleikultur: Memorandumsmacher, Memorandumisierer.

## Inputs

- Mandantenunterlagen in beliebiger Mischform: E-Mails Vertraege
  Fotos handschriftliche Notizen Chats Kontoauszuege Gutachten
  Aktenvermerke Gespraechsnotizen
- Optional: vorgegebene Pruefungsrichtung (gerichtete Pruefung)
- Optional: beigefuegte Rechtsprechung und Kommentarliteratur
- Optional: vorhandenes Memorandum zur Aktualisierung

OCR ist Pflicht. Gescannte Dokumente ohne Texterkennung werden nicht
verarbeitet — der Skill weist darauf hin und bricht ab.

## Output-Format

```
MEMORANDUM
Betreff: <Mandatsbezeichnung>
Datum: <ISO-Datum>
Bearbeiter: <Sachbearbeiter>

I. Sachverhalt
<chronologische Darstellung mit Quellenreferenz in eckigen Klammern>

Noch zu klaeren / Offene Punkte
- <Widerspruch oder Luecke mit Quellenangabe>

II. Fragestellung
1. <Frage in genau einem Satz>
2. <...>

III. Antworten
1. <Antwort in genau einem Satz>
2. <...>

IV. Rechtliche Ausfuehrungen
IV.1. Zu Frage 1 — <Kurzbezeichnung>
<Anspruchsgrundlage; Tatbestandsvoraussetzungen; Subsumtion; Ergebnis>
IV.2. Zu Frage 2 — <Kurzbezeichnung>
<...>

Hinweis: Dieses Memorandum wurde KI-gestuetzt erstellt und bedarf
der Pruefung durch den bearbeitenden Rechtsanwalt. Insbesondere
alle Zitate sind anhand der Originalquellen zu verifizieren.
```

## Methodik

1. Dokumenten-Inventur — pro Eingangsdokument Typ Datum Quelle
   notieren
2. Tatsachen-Extraktion — jede Tatsache erhaelt Quellenreferenz im
   Format `[Anlage K1 S. 2]` `[E-Mail v. 15.03.2024]`
   `[Telefonat lt. Vermerk v. 20.03.2024]`
3. Chronologische Sortierung
4. Widerspruchspruefung — abweichende Datums- oder Sachangaben
   werden BEIDE dokumentiert und als klaerungsbeduerftig markiert
5. Abschnitt "Noch zu klaeren" am Ende des Sachverhalts
6. Identifikation der Rechtsfragen — entweder nach Vorgabe oder
   offen mit Piercing-Questions
7. Ein-Satz-Fragen formulieren und durchnummerieren
8. Ein-Satz-Antworten formulieren und entsprechend nummerieren
9. Rechtliche Ausfuehrungen — pro Frage ein eigener Block mit
   sauberer Pruefungsstruktur
10. Zitate verifizieren oder mit `[Quelle zu verifizieren]` markieren

## Ein-Satz-Regel

Fragen und Antworten bestehen aus genau einem Satz. Kein Komma vor
"und" als Vorwand fuer Mehrfachfragen. Das Format zwingt zur
Fokussierung auf das Wesentliche und verhindert "Prosa-Gutachten".

Schlechte Frage: "Wie ist die Rechtslage?"
Gute Frage: "Ist die Kuendigung vom fuenfzehnten Maerz wirksam?"

## Quellenreferenzierung

Jede Tatsachenangabe im Sachverhalt MUSS eine Quelle haben. Format:

- `[Anlage K1 S. 2]` fuer Anlagen
- `[E-Mail v. <Datum>]` fuer Korrespondenz
- `[Vertrag § 4]` fuer Vertragsklauseln
- `[Telefonat lt. Vermerk v. <Datum>]` fuer Telefonnotizen
- `[Foto-Anlage <Bezeichnung>]` fuer Bildunterlagen
- `[WhatsApp v. <Datum> <Uhrzeit>]` fuer Messenger

Wo Quelle fehlt, gehoert der Punkt in "Noch zu klaeren".

## Pinpoint-Zitierung Rechtsprechung

Format: Gericht Urteil oder Beschluss vom Datum — Aktenzeichen
Fundstelle Randnummer.

Beispiel: BGH Urteil vom zwoelften Januar zweitausendzweiundzwanzig
— VIII ZR 42/21 NJW 2022 S. 1234 Rn. 24.

Juengere Entscheidungen stehen zuerst.

## Pinpoint-Zitierung Kommentarliteratur

Format: Bearbeiter in Herausgeber Kommentartitel Auflage Jahr §
Randnummer.

Beispiel: Ellenberger in Grueneberg BGB 83. Auflage 2024 § 138
Rn. 51.

## Pinpoint-Zitierung Aufsaetze

Format: Autor Titel Zeitschrift Jahr Anfangsseite konkrete Seite.

Beispiel: Mueller Die Grenzen der Vertragsfreiheit NJW 2023 S. 1234
konkret S. 1237.

## Halluzinations-Schutz

- Nur Quellen zitieren die existieren und verifizierbar sind
- Bei Unsicherheit `[Quelle zu verifizieren]` einfuegen ODER auf
  Zitat verzichten
- Niemals plausibel klingende aber erfundene Aktenzeichen oder
  Fundstellen ausgeben
- Eigene Wertungen NICHT als Tatsache darstellen
- Bei Tatsachen die nicht aus den Unterlagen folgen wird im
  Sachverhalt eine Luecke markiert nicht ergaenzt

## Pruefungsmodi

### Gerichtete Pruefung

User gibt vor: "Pruefe Wirksamkeit der Kuendigung." Der Skill
fokussiert auf diese Frage und nimmt nur sehr offensichtlich
verwandte Aspekte mit.

### Offene Pruefung mit Piercing-Questions

Der Skill identifiziert selbst die rechtlich relevanten
Fragestellungen. Piercing-Questions sind durchdringende Fragen die
den Kern freilegen. Sie sind besonders bei der ersten Sichtung
hilfreich um nichts zu uebersehen.

Empfehlung des Skills: Erste Sichtung offen, Vertiefung gerichtet.

## Anti-Risiko-Hinweis

Der Skill verfasst KEINE eigenstaendige Rechtsberatung. Der Output
ist ein Arbeitsentwurf zur kanzleiinternen Verwendung. Jede
Sachverhaltsangabe jede Quellenreferenz und jede rechtliche
Schlussfolgerung bedarf der eigenstaendigen Pruefung am Original.

Der pauschale Hinweis im Output ist Pflicht und nicht zu loeschen.

## Output-Datei

- `Memorandum_<Mandat>_<ISO-Datum>.docx` auf Kanzlei- oder
  Abteilungsbriefkopf falls Vorlage beigefuegt
- Optional `Memorandum_<Mandat>_<ISO-Datum>.md` als reine
  Textversion

## Fortlaufende Aktualisierung

Bei Nachlieferungen ergaenzt der Skill ein vorhandenes Memorandum.
Neuzugaenge werden im Sachverhalt mit `[NEU]` markiert. Bisherige
Tatsachen werden nicht stillschweigend ueberschrieben — Aenderungen
werden in "Noch zu klaeren" sichtbar gemacht.

## Beispielformulierungen

- "Hier sind alle Mandantenunterlagen zum Fall Mueller gegen ABC
  GmbH. Erstelle ein Memorandum mit offener Pruefung und
  Piercing-Questions."
- "Pruefe gerichtet die Wirksamkeit der Kuendigung vom fuenfzehnten
  Juni. Memorandum auf Kanzlei-Briefkopf."
- "Hier ist das bisherige Memorandum und neue Korrespondenz vom
  letzten Monat. Aktualisiere bitte und markiere Neuzugaenge."
- "Memorandum-Kurzversion fuer einfache Rechtsfrage zum
  Gewaehrleistungsausschluss."

## Variationen

- Kurzversion fuer einfache Einzelfragen
- Ausfuehrliche Version mit Zeitleiste und Beteiligtenliste als
  Anhang
- Gutachten-Version mit Alternativpruefungen und Risikoanalyse
- Prozess-Version mit Beweiswuerdigung und Prozessrisikoanalyse
- Due-Diligence-Version mit Risikoklassifizierung
- Mehrsprachige Unterlagen mit Uebersetzungshinweisen

## Berufsrecht und Datenschutz

Mandatsgeheimnis nach § 203 StGB und §§ 43a 43e BRAO sowie DSGVO
sind zwingend zu beachten. Nur KI-Systeme mit entsprechender
vertraglicher Zusicherung und tatsaechlicher Gewaehrleistung sind
zulaessig. Der Skill weist im Output-Hinweis darauf hin.
