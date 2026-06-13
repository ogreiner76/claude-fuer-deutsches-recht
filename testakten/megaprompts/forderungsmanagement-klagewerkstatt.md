# Megaprompt: forderungsmanagement-klagewerkstatt

## Zusammensetzung

Dieser Megaprompt enthaelt top-15 von 48 Skills des Plugins `forderungsmanagement-klagewerkstatt`.

## Inhaltsverzeichnis

1. **kaltstart-triage** — Dokumentengetriebene Ersttriage einer Forderungsakte: wertet zuerst Ordner, ZIP, Rechnungen, Mahnungen, Kontoauszuege, M…
2. **anspruchsschriftsatz-bausteine** — Bausteinkatalog für eine Anspruchsbegruendung in Klage oder Schriftsatz. Liefert Vorlagen für Rubrum Antrag Tatbestand A…
3. **forderung-arzthonorar-goae** — Arzthonorar nach GOAE und GOZ einklagen: Faelligkeit § 12 GOAE mit Rechnungserteilung mit Mindestinhalten Diagnose GOAE-…
4. **forderung-gegen-gmbh-gesellschafter** — Forderung gegen GmbH-Gesellschafter persoenlich: § 13 Abs. 2 GmbHG Trennungsprinzip Haftung nur Gesellschaftsvermoegen. …
5. **forderung-gegen-insolventen-schuldner** — Forderung gegen insolventen Schuldner: Anmeldung zur Insolvenztabelle § 174 InsO binnen Anmeldefrist mit Grund und Hoehe…
6. **forderung-gegen-verbraucher** — Forderung gegen Verbraucher: Verbraucherschutzregeln nach § 13 BGB, AGB-Kontrolle §§ 305-309 BGB, Widerrufsrecht bei Fer…
7. **forderung-im-ausland-vollstrecken** — Forderung im EU-Ausland vollstrecken: Bruessel Ia VO 1215/2012 (Anerkennung ohne Exequatur), Europaeischer Vollstreckung…
8. **forderung-internationaler-bezug** — Forderungssache mit Auslandsbezug Schuldner im EU-Ausland oder ausserhalb. Klaert anwendbares Recht internationale Zustä…
9. **forderungen-interessen-matrix** — Strukturierte Gegenueberstellung mehrerer Forderungen eines Mandanten gegen einen oder mehrere Schuldner. Erfasst Hauptf…
10. **fristen-risikoampel** — Ampel zur Bewertung saemtlicher Fristen in einer Forderungssache von Verjährung Klagefrist Einspruchsfrist Beschwerdefri…
11. **klage-einreichungslogik** — Praktische Einreichungslogik einer Zahlungsklage. Klaert Zuständigkeit Gerichtskostenvorschuss beA-Pflicht Anzahl Abschr…
12. **mandantenkommunikation** — Strukturierte Mandantenkommunikation waehrend einer Forderungssache. Definiert Anlaesse Inhalte und Form für Mandantenin…
13. **quellenkarte** — Kuratierte Quellenkarte für Forderungsmanagement Klagewerkstatt. Sortiert nach Gesetzen Rechtsprechung Verordnungen EU-R…
14. **redteam-qualitygate** — Red-Team-Review eines fertigen Schriftsatzes oder Mahnbescheidsantrags. Sucht aus Sicht der Gegenseite nach Angriffsflae…
15. **tatbestand-beweis-belege** — Schluessige Tatbestandsdarstellung in einer Klage oder einem Schriftsatz mit Verknuepfung zu Beweisen und Belegen. Verla…

---

## Skill: `kaltstart-triage`

_Dokumentengetriebene Ersttriage einer Forderungsakte: wertet zuerst Ordner, ZIP, Rechnungen, Mahnungen, Kontoauszuege, Mahnbescheid, Widerspruch oder Klageentwurf aus, bildet eine Aktenhypothese und fragt danach nur echte Luecken ab. Pinpoints ZPO 253/688 ff.; BGB 271/286/288/362/195/199; GVG 23/71._

# Kaltstart-Triage Forderungssache

Eingangsroutine für jede neue Forderungsakte. Ziel ist nicht ein Formularinterview, sondern eine belastbare Aktenhypothese mit moeglichst wenigen Rueckfragen.

## Grundsatz: Akte zuerst, Fragen danach

Wenn ein Ordner, eine ZIP-Datei oder mehrere Dokumente vorhanden sind, wird zuerst `aktenordner-schnellstart` ausgefuehrt. Aus Dateinamen, Briefkoepfen, Vollmacht, Rechnung, Mahnung, Kontoauszug, Mahnbescheid, Widerspruch, Klageentwurf und gerichtlichen Schreiben werden Mandant, Gegner, Forderungsart, Betrag, Zahlungslage, Mahnstand und Fristen rekonstruiert.

Der erste Output lautet nicht "Bitte beantworten Sie sieben Fragen", sondern:

```text
Ich sehe in der Akte vorlaeufig Folgendes:
- mutmasslicher Mandant:
- mutmasslicher Schuldner:
- Forderung / Restforderung:
- Stand Mahnung, Mahnbescheid, Klage oder Vollstreckung:
- auffaellige Risiken:
Ich frage jetzt nur noch die Punkte ab, die aus den Unterlagen nicht sicher folgen.
```

## Nur noch echte Luecken fragen

| Luecke | Frage | Nur stellen, wenn |
|---|---|---|
| Rolle unklar | "Ich vermute, du bist auf Seite [Gläubiger/Schuldner]. Stimmt das?" | Vollmacht, Briefkopf oder Anschreiben widerspruechlich |
| Ziel unklar | "Soll ich eintreiben, abwehren, vergleichen oder nur sortieren?" | kein Mandatsziel aus Mail/Anschreiben erkennbar |
| Frist unklar | "Gibt es eine Frist ausserhalb der Akte?" | gerichtliche Frist oder Verjaehrungsdruck nicht sicher |
| Zahlung unklar | "Ist nach dem letzten Kontoauszug noch etwas bezahlt worden?" | Kontoauszug endet vor aktueller Aktenlage |
| Gegner unklar | "Ist diese Anschrift noch aktuell?" | Zustellung, Umzug, HR-Auszug oder Insolvenzfund unsicher |

Mehr als drei Startfragen sind nur erlaubt, wenn Fristversaeumnis oder falsche Partei droht.

## Routing in drei Spuren

| Befund | Spur | Folgeskill |
|---|---|---|
| Akte ungeordnet oder Dokumentenlage unklar | Akteninventar | aktenordner-schnellstart oder dokumente-intake |
| Forderung schluessig, faellig, Schuldner bekannt, kein ernstliches Bestreiten | Mahnbescheid | mahnbescheid-online |
| Bestreiten wahrscheinlich oder Anspruch muss begruendet werden | Zahlungsklage | zahlungsklage-erstellen |
| Hauptforderung bezahlt, nur Kosten/Zinsen offen | Klageblocker | klagefreigabe-belegte-forderung |
| Forderung wackelig, Belege unklar, Vergleich wirtschaftlich sinnvoll | aussergerichtliche Mahnung oder Vergleich | mahnung-aussergerichtlich-stufenmodell |
| Titel liegt bereits vor | Vollstreckung | zwangsvollstreckung-überblick |

## Risikoampel Erstbewertung

| Ampel | Auslöser |
|---|---|
| gruen | Forderung dokumentiert Schuldner solvent Verjährung in weiter Ferne Zustellung gesichert |
| gelb | Belege luckenhaft Verjährung im laufenden Jahr Schuldner zahlungssaeumig |
| rot | Verjährung tritt in den naechsten sechzig Tagen ein Schuldner verzogen oder insolvent Belegstand schwach |

Rote Ampel triggert sofort Skill verjaehrung-prüfen und gegebenenfalls Mahnbescheid noch am gleichen Werktag.

## Startprodukt

Die Triage endet immer mit einem knappen Arbeitsplan:

| Punkt | Inhalt |
|---|---|
| Aktenbefund | Was liegt vor, was fehlt |
| Parteienhypothese | Mandant, Gegner, Vertreter, Anschriften, Beleg |
| Forderungsmatrix | Hauptforderung, Nebenforderung, Zinsen, Zahlungen, Rest |
| Chronologie | Vertrag, Leistung, Rechnung, Mahnung, Zahlung, Verfahren |
| Fristenampel | Verjaehrung, Widerspruch, Einspruch, gerichtliche Verfuegung |
| Naechster Skill | genau ein Hauptskill und maximal zwei Alternativen |

## Norm-Pinpoints

- ZPO 253 Abs. 2 Klage Pflichtbestandteile
- ZPO 688 ff. Mahnverfahren
- ZPO 690 Mahnbescheidsantrag
- ZPO 696 Abgabe nach Widerspruch
- ZPO 699 700 Vollstreckungsbescheid
- BGB 271 Faelligkeit
- BGB 286 Verzug
- BGB 288 Verzugszinsen
- BGB 362 Erfuellung
- BGB 195 199 Verjährung
- GVG 23 Nr. 1 ab 2026 Streitwertgrenze AG zehntausend Euro

## Quellen

- [ZPO 253](https://www.gesetze-im-internet.de/zpo/__253.html)
- [BGB 286](https://www.gesetze-im-internet.de/bgb/__286.html)
- [BGB 195](https://www.gesetze-im-internet.de/bgb/__195.html)
- [GVG 23](https://www.gesetze-im-internet.de/gvg/__23.html)

---

## Skill: `anspruchsschriftsatz-bausteine`

_Bausteinkatalog für eine Anspruchsbegruendung in Klage oder Schriftsatz. Liefert Vorlagen für Rubrum Antrag Tatbestand Anspruchsgrund Faelligkeit Verzug Zinsen Verzugsschaden Nebenforderungen Beweis. Pinpoints ZPO 253 Abs. 2 ZPO 130 Schriftsatzform ZPO 138 substantiierter Vortrag BGB 286 288. Lie..._

# Anspruchsschriftsatz Bausteine

Jeder substantiierte Schriftsatz besteht aus etwa zwoelf Modulen. Dieser Skill haelt sie als Bausteine bereit.

## Bausteinkatalog

| Baustein | Pflichtinhalt | Norm |
|---|---|---|
| Rubrum | Bezeichnung der Parteien zustellfaehige Anschriften Prozessbevollmaechtigte | ZPO 130 Nr. 1 ZPO 253 Abs. 2 Nr. 1 |
| Streitwertangabe | Hauptforderung Nebenforderungen ohne Zinsen | GKG 39 GKG 43 |
| Antrag | bestimmter Klageantrag | ZPO 253 Abs. 2 Nr. 2 |
| Tatbestand | Zeitliche Reihenfolge wer wann was | ZPO 138 Abs. 1 |
| Anspruchsgrund Vertrag | Vertragsschluss Leistungspflicht Inhalt | BGB 145 ff |
| Anspruchsgrund gesetzlich | Tatbestandsmerkmale Norm | je Anspruch |
| Faelligkeit | Datum Faelligkeit aus Vertrag oder Gesetz | BGB 271 |
| Verzug | Mahnung oder kalendarische Bestimmung | BGB 286 Abs. 1 oder Abs. 2 |
| Zinsen | Beginn Höhe Norm | BGB 288 |
| Verzugsschaden Pauschale | 40 Euro bei B2B Hauptforderung | BGB 288 Abs. 5 |
| Mahn- und Rechtsverfolgungskosten | Datum Rechnung Belege | BGB 280 BGB 286 |
| Beweis | Zeuge Urkunde Sachverstaendiger Parteivernehmung | ZPO 373 ff |

## Muster Klageantrag

```
Die Beklagte wird verurteilt an die Klaegerin
einen Betrag von [Hauptsumme] Euro nebst Zinsen
in Hoehe von neun Prozentpunkten ueber dem
Basiszinssatz seit [Datum] sowie
vorgerichtliche Rechtsanwaltskosten in Hoehe
von [Betrag] Euro nebst Zinsen in Hoehe von
fuenf Prozentpunkten ueber dem Basiszinssatz
seit Rechtshaengigkeit zu zahlen.
```

## Muster Verzugsbegruendung

```
Die Klaegerin hat die Beklagte mit Schreiben
vom [Datum] zur Zahlung bis zum [Datum]
gemahnt. Anlage K [...]. Die Beklagte befindet
sich seit dem [Datum] in Verzug
Paragraph 286 Absatz 1 BGB.
```

## Substantiierungspflicht

ZPO 138 Abs. 1 verlangt vollstaendigen und der Wahrheit gemäß Vortrag. Pauschales Bestreiten reicht beim Beklagten nicht ZPO 138 Abs. 2. Kläger muss anspruchsbegruendende Tatsachen konkret darlegen mit Datum Ort Personen Belegen.

## Norm-Pinpoints

- ZPO 130 Schriftsatzform
- ZPO 138 Wahrheitspflicht
- ZPO 253 Klage
- ZPO 373 ff Beweismittel
- BGB 286 288

## Quellen

- [ZPO 253](https://www.gesetze-im-internet.de/zpo/__253.html)
- [ZPO 138](https://www.gesetze-im-internet.de/zpo/__138.html)

## Normen und Rechtsprechung

### Kuratierte Normen-Bibliothek

- § 3a RVG
- § 71 GVG
- § 19 GmbHG
- § 8 RVG
- § 4 RDGEG
- § 41 GKG
- § 13 GmbHG
- § 31 GmbHG
- § 9 RVG
- § 23a GVG
- § 23 RVG
- § 215 VVG

### Leitentscheidungen

- BGH II ZR 256/02
- BGH VII ZR 162/00
- EuGH C-377/17
- BGH VIII ZR 261/06
- BGH XI ZR 564/15

---

## Skill: `forderung-arzthonorar-goae`

_Arzthonorar nach GOAE und GOZ einklagen: Faelligkeit § 12 GOAE mit Rechnungserteilung mit Mindestinhalten Diagnose GOAE-Ziffer und Steigerungsfaktor Regel-Schwellenwert sowie bei Ueberschreitung mit schriftlicher Begruendung. Verjährung § 195 BGB drei Jahre. Beweislast Steigerung beim Arzt. Klage..._

# Arzthonorar nach GOAE und GOZ

Geltendmachung des Honoraranspruchs aus Behandlungsvertrag mit Privatpatient. GKV-Patienten: nicht über GOAE, sondern KV-EBM, abrechnen mit KV (anderes Skill).

## Anspruchsgrundlage

| Konstellation | Norm |
|---|---|
| Privatbehandlung Arzt | § 630a BGB Behandlungsvertrag + GOAE |
| Privatbehandlung Zahnarzt | § 630a BGB + GOZ |
| Privatbehandlung Heilberuf (Hebamme, Logo) | je nach Gebührenordnung |
| IGeL-Leistungen GKV-Patient | § 18 BMV-Ä Vereinbarung + GOAE |

## Faelligkeit § 12 GOAE

**Voraussetzungen**:
1. Erteilung einer Rechnung.
2. Rechnung muss enthalten (§ 12 Abs. 2 GOAE):
   - Datum Behandlung
   - Bezeichnung der Leistung mit GOAE-Ziffer
   - Steigerungsfaktor
   - Betrag
   - Bei Schwierigkeitsanstieg über 2,3 (Schwellenwert): **schriftliche, fall- und patientenbezogene Begruendung**.

Faelligkeit tritt **erst mit ordnungsgemaesser Rechnungserteilung** ein. Vor Erteilung kein Verzug.

**§ 10 GOZ Zahnarzt** entsprechend.

## Steigerungsfaktoren

| Bereich | Faktor | Voraussetzung |
|---|---|---|
| Regelfall (Schwellenwert) | 2,3 (1,8 für techn. Leistungen Labor) | keine Begruendung |
| Erhoehung 1,0 - 2,3 | bis 2,3 | keine schriftliche Begruendung |
| Ueberschreitung 2,3 - 3,5 | bis 3,5 | schriftliche Begruendung (Schwierigkeit, Zeitaufwand) |
| Über 3,5 (Hoechstsatz) | mehr als 3,5 | Vereinbarung im Voraus schriftlich (§ 2 GOAE) |
| Laborleistungen | 1,15 oder 1,8 | feste Saetze |

GOZ: vergleichbar mit eigenen Saetzen.

## Honorarvereinbarung § 2 GOAE / § 2 GOZ

**Pflichtform**:
1. Schriftlich.
2. Vor Beginn der Behandlung.
3. Persoenliche Vereinbarung mit Patient.
4. Hinweis auf voraussichtliche Höhe.
5. Hinweis dass GKV/PKV moeglicherweise nicht voll erstattet.

Folge Formmangel: nur Mindestsatz GOAE (1,0).

## Schadensersatz / Schlechtleistung (§ 280, § 630a BGB)

Patient kann Schadensersatz und Minderung des Honorars verlangen bei:
- Behandlungsfehler (§ 630a BGB).
- Aufklaerungspflichtverletzung (§ 630e BGB).
- Dokumentationspflichtverletzung (§ 630f BGB, Beweislastumkehr § 630h BGB).

Arzt kann dann nicht das volle Honorar verlangen, sondern muss sich Schaden anrechnen lassen.

## Rechnungsmuster GOAE-konform

```
Rechnung Nr. ... vom ...
Patient: [Name, Anschrift, GebDatum]
Versichert bei: [PKV / Beihilfe / Selbstzahler]

Datum   GOAE-Ziff.   Bezeichnung       Faktor   Betrag
15.04.  1            Beratung          2,3      EUR 10,72
15.04.  5            Symptombez.UNT    2,3      EUR 19,17
15.04.  267          EKG (Ruhe)        1,8      EUR 18,80
15.04.  35           Sonographie       2,3      EUR 38,33
                                              ---------
                                       Summe   EUR 87,02

Bei Faktor > 2,3 Begruendung: ... (falls anwendbar)
Beihilfefaehig: ja
Beleg für PKV/Beihilfe: bitte Original einreichen.
```

## Klageantrag und Streitwert

Wie reine Geldforderung. Streitwert = Hauptforderung ohne Zinsen (§ 3 ZPO i.V.m. § 4 Abs. 1 ZPO).

**Beispiel:** EUR 1.245,60 Hauptforderung → AG (ab 01.01.2026 unter 10.000 EUR, § 23 Nr. 1 GVG), kein Anwaltszwang.

## Verjährung

| Anspruch | Frist | Norm |
|---|---|---|
| Honoraranspruch Arzt | 3 Jahre | § 195 BGB |
| Beginn | Schluss des Jahres mit Faelligkeit | § 199 Abs. 1 BGB |

Verjährung beginnt **erst** mit Rechnungsstellung (Faelligkeitsausloeser § 12 GOAE). Vorsicht: Arzt darf Rechnung nicht beliebig verzoegern, sonst u.U. Treu und Glauben (§ 242 BGB).

## Datenschutz

- Im Klageantrag: nur erforderliche Diagnose offenbaren.
- Mandantenschutz § 203 StGB Schweigepflicht beachten.
- Empfehlung: Diagnose pauschal "wegen GOAE-Leistungen erbrachte aerztliche Behandlung" und Rechnung mit Diagnose-Anlage K3.

## Prüfraster Honorarklage

1. **Behandlungsvertrag** geschlossen (§ 630a BGB)?
2. **Privatpatient** oder GKV-Patient? Bei GKV: Anspruch gegen KV, nicht Patient (Ausnahme IGeL).
3. **Rechnung** ordnungsgemaess (§ 12 GOAE) erteilt → Faelligkeit.
4. **Steigerungsfaktor** rechtens, ggf. mit schriftlicher Begruendung?
5. **Vereinbarung** § 2 GOAE bei Faktor über 3,5?
6. **Verzug** durch Mahnung (§ 286 BGB) oder 30-Tage-Regel (§ 286 Abs. 3 BGB) bei Verbraucher mit Hinweis.
7. **Klagegericht** (AG/LG, oertlich Wohnsitz Patient).

## Verteidigung Patient – Standardeinwendungen

| Einwendung | Prüfung |
|---|---|
| Behandlungsfehler | § 280, § 630a BGB Schadensersatz, Minderung |
| Aufklaerungspflichtverletzung | § 630e BGB, Beweislast Arzt |
| Keine Honorarvereinbarung bei Faktor > 3,5 | § 2 GOAE → nur 3,5 max. |
| Rechnung formunzureichend | § 12 GOAE → keine Faelligkeit, keine Verzug |
| Steigerung > 2,3 ohne Begruendung | § 12 GOAE → max. 2,3 |
| Praxis-AGB unwirksam | § 305 ff. BGB |

## Quellen
- GOAE [gesetze-im-internet.de/go__1982/](https://www.gesetze-im-internet.de/go__1982/)
- GOAE § 2 Vereinbarung [gesetze-im-internet.de/go__1982/__2.html](https://www.gesetze-im-internet.de/go__1982/__2.html)
- GOAE § 12 Faelligkeit [gesetze-im-internet.de/go__1982/__12.html](https://www.gesetze-im-internet.de/go__1982/__12.html)
- GOZ Zahnarztgebuehrenordnung [gesetze-im-internet.de/goz_1987/](https://www.gesetze-im-internet.de/goz_1987/)
- BGB § 630a Behandlungsvertrag [gesetze-im-internet.de/bgb/__630a.html](https://www.gesetze-im-internet.de/bgb/__630a.html)
- BGB § 630e Aufklaerung [gesetze-im-internet.de/bgb/__630e.html](https://www.gesetze-im-internet.de/bgb/__630e.html)
- BGB § 630h Beweislast [gesetze-im-internet.de/bgb/__630h.html](https://www.gesetze-im-internet.de/bgb/__630h.html)

---

## Skill: `forderung-gegen-gmbh-gesellschafter`

_Forderung gegen GmbH-Gesellschafter persoenlich: § 13 Abs. 2 GmbHG Trennungsprinzip Haftung nur Gesellschaftsvermoegen. Durchgriff bei § 19 GmbHG (Einlagepflicht) § 31 GmbHG (verbotene Auszahlung), existenzvernichtender Eingriff BGH II ZR 256/02 (Trihotel) und BGH II ZR 3/04 (Bremer Vulkan). Outp..._

# Forderung gegen GmbH-Gesellschafter

Ausgangslage: GmbH zahlt nicht, Forderung steht. Frage: kann der Gesellschafter persoenlich in Anspruch genommen werden?

## Grundsatz Trennungsprinzip § 13 Abs. 2 GmbHG

GmbH haftet **allein mit ihrem Gesellschaftsvermoegen**. Gesellschafter haftet **nicht** persoenlich für Schulden der Gesellschaft. Das Stammkapital ist als Mindesthaftsumme (§ 5 Abs. 1 GmbHG: 25.000 EUR; UG 1 EUR).

## Ausnahmen – wann haftet der Gesellschafter doch?

### 1. § 19 GmbHG Einlagepflicht (Differenzhaftung)

Gesellschafter haftet auf Erbringung der **gezeichneten Einlage**, soweit nicht vollstaendig geleistet:
| Tatbestand | Norm | Folge |
|---|---|---|
| Ausstehende Einlage | § 19 Abs. 1 GmbHG | Anspruch GmbH auf Volleinzahlung |
| Differenz Sacheinlage / Bewertung | § 9 Abs. 1 GmbHG | Differenzhaftung in Geld |
| Verdeckte Sacheinlage | § 19 Abs. 4 GmbHG (seit MoMiG 2008) | bei Anrechnung: Wert prüfen |
| Hin- und Herzahlung | § 19 Abs. 5 GmbHG | bestehende Forderung der GmbH |

Klage: GmbH (in Insolvenz: Insolvenzverwalter) klagt gegen Gesellschafter.

### 2. § 31 GmbHG Rueckzahlung verbotener Auszahlung

| Voraussetzung | Folge |
|---|---|
| Auszahlung an Gesellschafter | Prüfung § 30 GmbHG (Stammkapital-Auszehrung) |
| Verstoss gegen Kapitalerhaltung | Rückforderungsanspruch GmbH |
| Verjährung | 10 Jahre § 31 Abs. 5 GmbHG |

Wirtschaftlicher Hintergrund: GmbH darf bei drohendem Unterschreiten des Stammkapitals nicht an Gesellschafter ausschuetten.

### 3. Existenzvernichtender Eingriff (Haftung wegen § 826 BGB)

**BGH II ZR 256/02 Trihotel** und **II ZR 3/04 Bremer Vulkan**:
- Gesellschafter haftet **deliktisch nach § 826 BGB**, wenn er der GmbH planmaessig betriebsnotwendiges Vermögen entzieht und damit die Existenz der GmbH gefaehrdet.
- Schadensersatz an die GmbH (nicht direkt an Gläubiger).
- In der Insolvenz: Anspruch des Insolvenzverwalters; ohne Insolvenz Pfaendung des Anspruchs der GmbH.

### 4. Materielle Unterkapitalisierung

BGH abgelehnt als eigenen Haftungstatbestand (BGH II ZR 256/02). Nur über § 826 BGB / existenzvernichtenden Eingriff.

### 5. Sittenwidrige vorsaetzliche Schaedigung § 826 BGB

Wenn Gesellschafter direkt den Gläubiger taeuscht (Bonitaetstaeuschung, Eingehungsbetrug). Klage des Gläubigers gegen den Gesellschafter persoenlich.

### 6. Persoenliche Buergschaft, Schuldbeitritt, Garantie

Vertraglicher Haftungsgrund, hat nichts mit GmbH-Recht zu tun. Prüfung Form (§ 766 BGB Schriftform Buergschaft, ausser kaufmaennische Buergschaft § 350 HGB).

### 7. Haftung Geschäftsführer (nicht Gesellschafter, aber oft personenidentisch)

| Anspruchsgrundlage | Norm |
|---|---|
| Steuerhaftung | § 69, § 34 AO |
| Sozialversicherungsbeitraege | § 823 Abs. 2 BGB i.V.m. § 266a StGB |
| Insolvenzverschleppung | § 823 Abs. 2 BGB i.V.m. § 15a InsO |
| Verletzung Vorsorgepflichten | § 43 GmbHG (gegenueber GmbH) |
| Drittschadensliquidation | bei Sonderverbindung Gläubiger |

### 8. Strohmanngeschaeft / Treuhand

Wenn Gesellschafter wirtschaftlich agiert und GmbH nur Mantel ist: gerichtliche Wertung "Strohmanngeschaeft", direkte Haftung. Sehr enger Anwendungsbereich.

### 9. Gesellschafterdarlehen § 39 Abs. 1 Nr. 5 InsO

In der Insolvenz nachrangig. Vorher zurueckgezahltes Gesellschafterdarlehen kann angefochten werden (§ 135 InsO 1 Jahr).

## Prüfraster Forderung gegen GmbH-Gesellschafter

| Schritt | Frage | Beweislast |
|---|---|---|
| 1 | Gegen welche Person Klage – GmbH oder Gesellschafter? | Gläubiger |
| 2 | Vertragliche Haftung Gesellschafter (Buergschaft, Beitritt)? | Gläubiger |
| 3 | Einlage vollstaendig erbracht? | GmbH/Insolvenzverwalter |
| 4 | Verbotene Auszahlung § 30, 31 GmbHG erfolgt? | Insolvenzverwalter |
| 5 | Existenzvernichtender Eingriff (§ 826 BGB)? | Gläubiger/InsVerw |
| 6 | Strohmann/Treuhand? | Gläubiger |
| 7 | Insolvenz GmbH eroeffnet → Anspruchsverlagerung an Insolvenzverwalter | nachpruefen |

## Praxisfall – Inkasso-Strategie

```
Schritt 1: HRB-Auszug Gesellschafter und Geschaeftsfuehrer
Schritt 2: Bilanz pruefen (Bundesanzeiger) -> Eigenkapitalstand
Schritt 3: Insolvenzbekanntmachungen pruefen
Schritt 4: Sofort:
   - GmbH verklagen (Hauptanspruch)
   - bei Insolvenz: § 174 InsO anmelden, an Insolvenzverwalter wenden
Schritt 5: Parallel:
   - Buergschaft/Beitritt pruefen -> Klage Gesellschafter
   - Auffaellige Auszahlungen vor Insolvenz -> Hinweis Insolvenzverwalter
Schritt 6: Bei Verdacht Insolvenzverschleppung
   - Anzeige Staatsanwaltschaft § 15a InsO
   - Schadensersatz § 823 Abs. 2 BGB GfFhr
```

## Insolvenz-Anfechtung Sondervermoegens-Verschiebungen

| Anfechtungsgrund | Norm |
|---|---|
| Vorsaetzliche Gläubigerbenachteiligung | § 133 InsO (10 J., 4 J. Verkuerzung 2017) |
| Unentgeltliche Leistung | § 134 InsO (4 J.) |
| Gesellschafterdarlehen | § 135 InsO (1 J.) |
| Inkongruente Deckung | § 131 InsO (3 Monate) |
| Kongruente Deckung | § 130 InsO (3 Monate) |

## Klageantrag-Muster gegen Gesellschafter aus Buergschaft

```
Es wird beantragt:
1. Der Beklagte wird verurteilt, an die Klaegerin EUR 12.500,00
   aus der Buergschaftsurkunde vom 03.02.2024 (Anlage K2)
   nebst Zinsen in Hoehe von 9 Prozentpunkten ueber dem
   Basiszinssatz seit dem 15.05.2026 zu zahlen.
2. Hilfsweise: Der Beklagte wird verurteilt, an die Klaegerin
   EUR 12.500,00 nebst Zinsen ... aus existenzvernichtendem
   Eingriff (§ 826 BGB) zu zahlen.
3. Der Beklagte traegt die Kosten des Rechtsstreits.
```

## Typische Fehler

- Klage gegen Gesellschafter ohne Anspruchsgrundlage neben § 13 Abs. 2 GmbHG.
- Buergschaft formunwirksam (§ 766 BGB Schriftform).
- Existenzvernichtenden Eingriff zu pauschal vorgetragen; Beweislast hoch.
- Insolvenz uebersehen; danach nur Insolvenzverwalter aktivlegitimiert für Gesellschafteranspruch.

## Quellen
- GmbHG § 13 Trennungsprinzip [gesetze-im-internet.de/gmbhg/__13.html](https://www.gesetze-im-internet.de/gmbhg/__13.html)
- GmbHG § 19 Einlage [gesetze-im-internet.de/gmbhg/__19.html](https://www.gesetze-im-internet.de/gmbhg/__19.html)
- GmbHG § 30, § 31 Kapitalerhaltung [gesetze-im-internet.de/gmbhg/__30.html](https://www.gesetze-im-internet.de/gmbhg/__30.html)
- BGB § 826 [gesetze-im-internet.de/bgb/__826.html](https://www.gesetze-im-internet.de/bgb/__826.html)
- InsO § 15a Insolvenzverschleppung [gesetze-im-internet.de/inso/__15a.html](https://www.gesetze-im-internet.de/inso/__15a.html)
- InsO §§ 129-147 Anfechtung [gesetze-im-internet.de/inso/__129.html](https://www.gesetze-im-internet.de/inso/__129.html)
- BGH II ZR 256/02 Trihotel [bundesgerichtshof.de](https://www.bundesgerichtshof.de)
- BGH II ZR 3/04 Bremer Vulkan [bundesgerichtshof.de](https://www.bundesgerichtshof.de)

---

## Skill: `forderung-gegen-insolventen-schuldner`

_Forderung gegen insolventen Schuldner: Anmeldung zur Insolvenztabelle § 174 InsO binnen Anmeldefrist mit Grund und Hoehe. Aussonderung § 47 InsO. Absonderungsrecht §§ 49-52 InsO. Massenforderung § 55 InsO. Nachrangige § 39 InsO. Vollstreckungsverbot § 89 InsO. Output: Forderungsanmeldung formgere..._

# Forderung gegen insolventen Schuldner

Wenn über das Vermögen des Schuldners ein Insolvenzverfahren eroeffnet ist, gelten ausschließlich die Regeln der InsO. Klage und Vollstreckung sind grundsätzlich gesperrt.

## Insolvenzeroeffnung – Wirkungen

| Wirkung | Norm |
|---|---|
| Verwaltungs-/Verfuegungsbefugnis geht auf Verwalter über | § 80 InsO |
| Anhaengige Prozesse werden unterbrochen | § 240 ZPO |
| Vollstreckung unzulaessig | § 89 InsO |
| Sicherungen 1 Monat vor Eroeffnung unwirksam | § 88 InsO |
| Aufrechnung beschraenkt | §§ 94-96 InsO |

## Schritt 1: Insolvenzeroeffnung erkennen

[insolvenzbekanntmachungen.de](https://www.insolvenzbekanntmachungen.de) – kostenlose amtliche Insolvenzbekanntmachung, durchsuchbar nach Namen, Sitz, Aktenzeichen.

Bei Eroeffnungsbeschluss: Verwalter benannt, Anmeldefrist gesetzt (typisch 6-8 Wochen), Prüfungstermin festgelegt.

## Schritt 2: Forderungsanmeldung § 174 InsO

**Inhalt** (§ 174 Abs. 2 InsO):
| Pflichtangabe | Inhalt |
|---|---|
| Gläubigeranschrift | mit Bankverbindung |
| Forderungsgrund | Vertrag, Datum, Vertragstyp |
| Forderungsbetrag | Hauptforderung in EUR |
| Zinsen | bis Insolvenzeroeffnung |
| Belege | Vertrag, Rechnungen, Mahnungen, Titel |
| Rang | normal, nachrangig, vorrangig |
| Bei Vorzugsrecht | Anmeldung mit Hinweis Sicherungsrecht (§ 174 Abs. 3) |

**Frist:** Anmeldefrist im Eroeffnungsbeschluss. Verspaetete Anmeldung möglich (§ 177 InsO), aber **erhebliche Nachteile**:
- Später Prüfungstermin → Kosten § 187 InsO.
- Schlussverteilung schon ausgekehrt → kein Anteil mehr.

## Anmeldungs-Formular Muster

```
An den Insolvenzverwalter
[Name, Anschrift]
Az. ... AG [Insolvenzgericht] ... IN ...

Schuldner:           [Firma/Name]
Glaeubiger:          [Firma/Name, Anschrift]
Bankverbindung:      IBAN ...

Forderungsanmeldung gemaess § 174 InsO

Hauptforderung:      EUR ...
Verzugszinsen bis Eroeffnung am ... :   EUR ...
Kosten Mahnverfahren:                    EUR ...
Anwaltskosten vorgerichtlich (1,3 GG):  EUR ...
==================================================
Gesamtforderung:                          EUR ...

Forderungsgrund:
Werklohn aus Werkvertrag vom 15.03.2024 ueber Errichtung
Carport. Abnahme am 30.04.2024, Schlussrechnung Nr. R-2024-115
vom 02.05.2024 ueber EUR ... brutto. Verzug ab 01.06.2024
nach Mahnung vom 25.05.2024 (Anlage 4).

Belege:
Anlage 1: Werkvertrag
Anlage 2: Abnahmeprotokoll
Anlage 3: Schlussrechnung
Anlage 4: Mahnung mit Zustellnachweis
Anlage 5: Vollstreckungsbescheid vom 12.10.2025 (sofern vorhanden)

Rang: einfache Insolvenzforderung (§ 38 InsO).

Es wird beantragt, die Forderung zur Tabelle festzustellen.
```

## Forderungs-Raenge

| Rang | Inhalt | Norm |
|---|---|---|
| Massenforderung | nach Eroeffnung begruendet | § 55 InsO |
| Aussonderungsrecht | Eigentum, Anwartschaft | § 47 InsO |
| Absonderungsrecht | Pfandrecht, Sicherheit | §§ 49-52 InsO |
| Einfache Insolvenzforderung | Regelfall | § 38 InsO |
| Nachrangig | Zinsen ab Eroeffnung, Gesellschafterdarlehen | § 39 InsO |
| Ausgeschlossen | bestimmte Sanktionen | § 39 Abs. 1 Nr. 3-5 InsO |

## Aussonderung § 47 InsO

Anspruch auf Herausgabe gehoert nicht zur Masse. Voraussetzung: **dingliches Recht**:
- Eigentum (z.B. nicht gelieferte Sache, Mietgegenstand).
- Eigentumsvorbehalt § 449 BGB.
- Sicherungseigentum (Mobiliar zur Sicherheit uebereignet) – aber Verwertungsrecht des Verwalters § 51 Nr. 1 InsO!

## Absonderung §§ 49-52 InsO

| Sicherungsrecht | Norm |
|---|---|
| Grundpfandrecht | § 49 InsO |
| Pfandrecht (Vermieterpfandrecht, Werkunternehmerpfandrecht) | § 50 InsO |
| Sicherungseigentum, Sicherungsabtretung | § 51 Nr. 1 InsO |
| Forderungspfaendung vor Eroeffnung | § 50 InsO i.V.m. § 804 ZPO |

Folge: Verwalter verwertet, Gläubiger bekommt Erloes (abzgl. Verwertungskostenpauschale § 170, § 171 InsO: 4 % + 5 %).

## Forderung gegen Verbraucher (Verbraucherinsolvenz)

| Phase | Frist |
|---|---|
| Aussergerichtlicher Einigungsversuch | vor Antrag § 305 Abs. 1 Nr. 1 InsO |
| Insolvenzantrag | nach Scheitern |
| Wohlverhaltensphase | 3 Jahre (RegInsO 2020) |
| Restschuldbefreiung | § 286 ff. InsO |

Forderung wird Insolvenzforderung. Nach Restschuldbefreiung erlischt der Anspruch (Naturalobligation).

## Klage waehrend Insolvenz?

| Konstellation | Klage zulässig? |
|---|---|
| Vor Eroeffnung anhaengige Klage | unterbrochen § 240 ZPO, Aufnahme durch Verwalter |
| Nach Anmeldung Forderung im Prüfungstermin bestritten | Klage auf Feststellung § 180 InsO |
| Klage gegen Insolvenzverwalter persoenlich | nur Schadensersatz § 60 InsO |
| Klage gegen Schuldner persoenlich nach Aufhebung | wieder zulässig |
| Gegen Gesellschafter (parallel) | bleibt zulässig (siehe Skill GmbH-Gesellschafter) |

## Bestrittene Forderung – Feststellungsklage § 180 InsO

Wenn Verwalter / anderer Gläubiger im Prüfungstermin die Forderung bestreitet:
- Klage gegen den Bestreitenden auf Feststellung zur Tabelle.
- Zuständigkeit: ordentliches Gericht (idR AG/LG am Insolvenzgericht).
- Streitwert: bei zu erwartender Quote (haeufig nur Bruchteil der Forderung).

## Anfechtung durch Verwalter §§ 129-147 InsO

Verwalter kann zurueckgezahlte Forderungen anfechten:
| Anfechtungsgrund | Frist vor Eroeffnung |
|---|---|
| § 130 InsO kongruente Deckung | 3 Monate |
| § 131 InsO inkongruente Deckung | 3 Monate |
| § 132 InsO unmittelbar nachteiliges Rechtsgeschaeft | 3 Monate |
| § 133 InsO vorsaetzliche Benachteiligung | 4 Jahre (seit 2017) |
| § 134 InsO unentgeltliche Leistung | 4 Jahre |
| § 135 InsO Gesellschafterdarlehen | 1 Jahr |

## Strategie-Check

```
1. insolvenzbekanntmachungen.de pruefen
2. Eroeffnungsbeschluss anfordern (Geschaeftsstelle)
3. Frist Anmeldung notieren
4. Belege zusammenstellen (Vertrag, Rechnung, Mahnung, Titel)
5. Anmeldung absenden (Original + Kopie an Verwalter, Az. notieren)
6. Pruefungstermin abwarten
7. Bei Bestreiten: Feststellungsklage erwaegen
8. Parallel: Sicherheiten verwerten / Aussonderung beantragen
9. Quotenerwartung kalkulieren (oft 0-5 %)
```

## Typische Fehler

- Klage gegen den insolventen Schuldner waehrend Insolvenz → § 87 InsO unzulaessig.
- Vollstreckung trotz Eroeffnung → § 89 InsO Verbot.
- Anmeldung ohne Belege → Aufforderung Nachreichung, Fristverlust.
- Verzugszinsen nach Eroeffnung weiter berechnet → § 39 Abs. 1 Nr. 1 InsO nachrangig.
- Sicherungsrecht nicht angemeldet → kein Absonderungsrecht.

## Quellen
- InsO § 38 [gesetze-im-internet.de/inso/__38.html](https://www.gesetze-im-internet.de/inso/__38.html)
- InsO § 39 Nachrang [gesetze-im-internet.de/inso/__39.html](https://www.gesetze-im-internet.de/inso/__39.html)
- InsO § 47 Aussonderung [gesetze-im-internet.de/inso/__47.html](https://www.gesetze-im-internet.de/inso/__47.html)
- InsO §§ 49-52 Absonderung [gesetze-im-internet.de/inso/__49.html](https://www.gesetze-im-internet.de/inso/__49.html)
- InsO § 89 Vollstreckungsverbot [gesetze-im-internet.de/inso/__89.html](https://www.gesetze-im-internet.de/inso/__89.html)
- InsO § 174 Anmeldung [gesetze-im-internet.de/inso/__174.html](https://www.gesetze-im-internet.de/inso/__174.html)
- InsO § 180 Feststellungsklage [gesetze-im-internet.de/inso/__180.html](https://www.gesetze-im-internet.de/inso/__180.html)
- Insolvenzbekanntmachungen [insolvenzbekanntmachungen.de](https://www.insolvenzbekanntmachungen.de)

---

## Skill: `forderung-gegen-verbraucher`

_Forderung gegen Verbraucher: Verbraucherschutzregeln nach § 13 BGB, AGB-Kontrolle §§ 305-309 BGB, Widerrufsrecht bei Fernabsatz §§ 312g, 355 BGB, Belehrungspflicht. Verzugszinsen 5 Prozentpunkte ueber Basiszinssatz § 288 Abs. 1 BGB. Streitwert AG (bis 10000 EUR ab 01.01.2026). Gerichtsstand Wohns..._

# Forderung gegen Verbraucher

Verbraucher (§ 13 BGB) geniessen erhebliche Schutzrechte. Die Verfolgung der Forderung muss diese Schutzvorschriften beachten, sonst droht Klageabweisung oder erhebliche Aufschiebung.

## Verbraucher i.S.d. § 13 BGB

| Definition | Inhalt |
|---|---|
| Natuerliche Person | ja |
| Zwecke nicht ueberwiegend gewerblich/selbständig | ja |
| Doppelnutzung | Schwerpunkt-Prüfung; im Zweifel Verbraucher (BGH VIII ZR 7/02) |
| Vereine | grds. Verbraucher, wenn nicht gewerblich |
| Existenzgruender | nicht Verbraucher (BGH VIII ZR 219/00) |

## AGB-Kontrolle §§ 305-309 BGB

Bei vorformulierten Vertragsbedingungen gegenueber Verbraucher gilt erhoehte Kontrolle:

| Norm | Inhalt |
|---|---|
| § 305 BGB | Einbeziehung in Vertrag (Kenntnisnahme, Hinweis) |
| § 305c BGB | Ueberraschende Klauseln, Unklarheitenregel |
| § 306 BGB | Rechtsfolgen Unwirksamkeit (Vertrag im uebrigen wirksam) |
| § 307 BGB | Inhaltskontrolle (Transparenzgebot, Treu und Glauben) |
| § 308 BGB | Verbotene Klauseln mit Wertungsmoeglichkeit |
| § 309 BGB | Verbotene Klauseln ohne Wertungsmoeglichkeit |

**Beispiele unwirksamer Klauseln**:
- Pauschalierte Mahnkosten über 2,50 EUR (§ 309 Nr. 5 BGB).
- Pauschalierter Schadensersatz unangemessen (§ 309 Nr. 5 BGB).
- Aufrechnungsverbot ausser unbestrittene Forderung (§ 309 Nr. 3 BGB).
- Gerichtsstandsvereinbarung B2C im voraus (§ 38 Abs. 2 ZPO).
- Schiedsklauseln ohne Schriftform und Aufklaerung (§ 1031 Abs. 5 ZPO).

## Widerrufsrecht bei Fernabsatz und ausserhalb Geschäftsraeumen

| Vertragstyp | Norm | Widerrufsfrist |
|---|---|---|
| Fernabsatz (Online-/Telefonkauf) | §§ 312c, 312g BGB | 14 Tage § 355 BGB |
| Ausserhalb Geschäftsraeumen (Haustuer) | § 312b BGB | 14 Tage |
| Verbraucherdarlehen | § 495 BGB | 14 Tage |
| Lebensversicherung | § 8 VVG | 30 Tage |
| Versicherung Auslandsdarlehen | § 495 BGB i.V.m. RL | 30 Tage |

**Belehrungspflicht** (§ 312d, § 356 BGB i.V.m. Anlage 1 EGBGB): Muster-Widerrufsbelehrung. Bei fehlerhafter Belehrung: **Widerrufsfrist beginnt nicht** (BGH VIII ZR 19/14).

**Folge Widerruf:** Rueckabwicklung als Rueckgewaehrschuldverhaeltnis (§ 357 BGB), Frist 14 Tage je Partei.

## Verzug bei Verbraucher § 286 Abs. 3 BGB

| Konstellation | Verzugseintritt |
|---|---|
| Mahnung nach Faelligkeit | mit Zugang Mahnung (§ 286 Abs. 1 BGB) |
| Kalendermäßige Faelligkeit | mit Faelligkeit (§ 286 Abs. 2 Nr. 1 BGB) |
| 30 Tage nach Rechnungszugang | **nur mit Hinweis** in Rechnung (§ 286 Abs. 3 BGB) |

**Achtung:** Ohne Hinweis-Klausel "Bei Nichtzahlung binnen 30 Tagen treten Sie in Verzug" gilt 30-Tage-Regel nicht.

## Zinsen § 288 BGB

| Schuldner | Zinssatz |
|---|---|
| Verbraucher | 5 Prozentpunkte über Basiszinssatz (§ 288 Abs. 1 BGB) |
| Pauschale 40 EUR | gilt NICHT bei Verbraucher (nur B2B) |
| Vertragliche Höhe | nur soweit nicht sittenwidrig (§ 138 BGB), AGB-Kontrolle |

## Gerichtsstand bei Verbraucher

| Klagerichtung | Gerichtsstand |
|---|---|
| Klage gegen Verbraucher | Wohnsitz Verbraucher (§ 29c Abs. 1 S. 1 ZPO ausschließlich bei Haustuer-Geschäft / Verbraucherdarlehen) |
| Klage durch Verbraucher | sein Wohnsitz |
| Vereinbarung im voraus | nur eng zulässig § 38 Abs. 2 ZPO |
| Fernabsatz | allgemeiner Gerichtsstand Verbraucher |

EU-Bezug: Bruessel Ia Art. 17-19 – Klage gegen Verbraucher **nur am Wohnsitz Verbraucher**, ausser am Wohnsitz vereinbart und nach Entstehen Streit.

## Aufrechnungs- und Zurueckbehaltungsrechte

Verbraucher kann nach § 309 Nr. 3 BGB **nicht** durch AGB von Aufrechnungsrecht ausgeschlossen werden, ausser bei unbestrittener oder rechtskraeftiger Gegenforderung.

## Inkassokosten

| Posten | Wirksamkeit |
|---|---|
| Mahnkosten Verbraucher | wie bei B2B, aber Pauschalen begrenzt (§ 309 Nr. 5 BGB) |
| Inkassokosten | nach § 4 RDGEG max. RA-Geschäftsgebuehr |
| Vorgerichtliche RA-Kosten | nur erforderlich UND verhaeltnismaessig (BGH IX ZR 119/04) |

## Verbraucherbauvertrag § 650i BGB

Sonderregeln seit 2018:
- Schriftliche Bau-Beschreibung (§ 650j BGB).
- Verguetungssicherheit Auftragnehmer 7 Prozent (§ 650m BGB).
- Widerrufsrecht 14 Tage (§ 650l BGB).

## Verbraucherdarlehen §§ 491 ff. BGB

- Effektivzinsangabe Pflicht.
- Widerruf 14 Tage nach Vertragsschluss (§ 495 BGB).
- Bei fehlerhafter Belehrung: Widerruf zeitlich unbegrenzt (BGH XI ZR 564/15).

## Klage Strategie

1. **Rechnung prüfen**: Hinweis 30-Tage-Verzug nach § 286 Abs. 3 BGB enthalten?
2. **AGB prüfen**: Klauseln wirksam nach §§ 305 ff. BGB?
3. **Widerrufsbelehrung**: bei Fernabsatz/Haustuer korrekt? Bei Fehler: Widerruf möglich.
4. **Gerichtsstand**: Klage am Wohnsitz Verbraucher.
5. **Streitwert**: i.d.R. AG (unter 10.000 EUR).
6. **Verzugszinsen**: 5 Prozentpunkte über Basiszinssatz, KEINE 40-EUR-Pauschale.
7. **Mahn-/Inkassokosten**: nur erforderlich und verhaeltnismaessig.

## Klageantrag-Muster

```
Es wird beantragt:
1. Der/Die Beklagte wird verurteilt, an die Klaegerin EUR 1.250,80
   nebst Zinsen in Hoehe von 5 Prozentpunkten ueber dem
   Basiszinssatz aus EUR 1.250,80 seit dem 15.04.2026 zu zahlen.
2. Der/Die Beklagte traegt die Kosten des Rechtsstreits.
3. Das Urteil ist vorlaeufig vollstreckbar; dem/der Beklagten wird
   nachgelassen, die Vollstreckung durch Sicherheitsleistung in
   Hoehe von 110 % des jeweils zu vollstreckenden Betrages
   abzuwenden.
```

## Typische Fehler

- Vereinbarter Gerichtsstand bei Verbraucher → § 38 Abs. 2 ZPO unwirksam.
- Pauschale 40 EUR gegen Verbraucher beantragt – nicht zulässig.
- AGB-Pauschalen über 2,50 EUR für Mahnungen – § 309 Nr. 5 BGB.
- Widerrufsbelehrung fehlt / fehlerhaft → Widerruf noch möglich nach Klageerhebung.
- 30-Tage-Verzug ohne Hinweis in Rechnung angenommen.

## Quellen
- BGB § 13 [gesetze-im-internet.de/bgb/__13.html](https://www.gesetze-im-internet.de/bgb/__13.html)
- BGB §§ 305-310 AGB [gesetze-im-internet.de/bgb/__305.html](https://www.gesetze-im-internet.de/bgb/__305.html)
- BGB § 312g Fernabsatz [gesetze-im-internet.de/bgb/__312g.html](https://www.gesetze-im-internet.de/bgb/__312g.html)
- BGB §§ 355-357 Widerruf [gesetze-im-internet.de/bgb/__355.html](https://www.gesetze-im-internet.de/bgb/__355.html)
- BGB § 286 Abs. 3 Verbraucher [gesetze-im-internet.de/bgb/__286.html](https://www.gesetze-im-internet.de/bgb/__286.html)
- ZPO § 29c Verbrauchersache [gesetze-im-internet.de/zpo/__29c.html](https://www.gesetze-im-internet.de/zpo/__29c.html)
- ZPO § 38 Gerichtsstandsverbot Verbraucher [gesetze-im-internet.de/zpo/__38.html](https://www.gesetze-im-internet.de/zpo/__38.html)
- BGH XI ZR 564/15 zur fehlerhaften Widerrufsbelehrung [bundesgerichtshof.de](https://www.bundesgerichtshof.de)

---

## Skill: `forderung-im-ausland-vollstrecken`

_Forderung im EU-Ausland vollstrecken: Bruessel Ia VO 1215/2012 (Anerkennung ohne Exequatur), Europaeischer Vollstreckungstitel EuVTVO 805/2004, Europaeischer Zahlungsbefehl EuMVVO 1896/2006, geringfuegige Forderung EuGFVO 861/2007. Drittstaat: Anerkennung nach IPR und bilateralen Abkommen. Output..._

# Forderung im Ausland vollstrecken

Grenzueberschreitende Forderungsdurchsetzung. Die Wahl des Instruments haengt vom Wohnsitz des Schuldners und vom Streitwert ab.

## Instrumenten-Übersicht

| Instrument | Anwendungsbereich | Vorteil |
|---|---|---|
| Bruessel Ia VO (EU 1215/2012) | EU-Anerkennung deutscher Titel | Vollstreckung ohne Exequatur |
| EuVTVO (EG 805/2004) | unbestrittene Forderungen | Bestaetigung als EU-Titel |
| EuMVVO (EG 1896/2006) | grenzueberschreitendes Mahnverfahren | EU-weit ein einheitlich Verfahren |
| EuGFVO (EG 861/2007) | bis 5.000 EUR | vereinfachtes EU-Verfahren |
| Lugano-Uebereinkommen | CH, NO, IS | parallel zu Bruessel Ia |
| Drittstaaten | je Staat | Anerkennungsverfahren noetig |

## Bruessel Ia VO (EU 1215/2012)

**Anwendungsbereich:** Zivil- und Handelssachen mit Bezug zu mehreren MS. Nicht: Familie, Erbe, Insolvenz, Schiedsverfahren, Sozialversicherung, Steuer (Art. 1 Abs. 2).

**Gerichtsstaende (kuerz)**:
| Konstellation | Norm |
|---|---|
| Allgemein: Wohnsitz Bekl. | Art. 4 |
| Vertrag: Erfuellungsort | Art. 7 Nr. 1 |
| Deliktischer Ort: Tatort | Art. 7 Nr. 2 |
| Verbrauchersache | Art. 17-19 |
| Versicherung | Art. 10-16 |
| Arbeitsvertrag | Art. 20-23 |
| Ausschließlich (Grundstueck, Register) | Art. 24 |
| Vereinbarung | Art. 25 (Schriftform, Exklusivitaet) |

**Vollstreckung in anderem MS** (Art. 36-44):
- Anerkennung **automatisch** (kein Exequatur).
- Bestaetigung Formblatt I (Anhang I VO).
- Direktvollstreckung beim ausländischen Vollstreckungsorgan.
- Versagungsgruende beschraenkt (Art. 45): ordre public, Saeumnis ohne ordn. Zustellung, unvereinbares Urteil.

## EuVTVO (EG 805/2004) – Europaeischer Vollstreckungstitel

Bestaetigung **unbestrittener** Forderungen als EU-Titel. Voraussetzungen Art. 6:
1. Forderung im Urspr.-MS unbestritten (Anerkenntnis, Saeumnis, Vergleich).
2. Im Urspr.-MS gerichtlich tituliert.
3. Mindeststandards Zustellung eingehalten.
4. Verbraucher-Schutz beachtet.

Bestaetigung durch Urspr.-Gericht, Formblatt I. In ZielMS direkt vollstreckbar.

## EuMVVO (EG 1896/2006) – Europaeisches Mahnverfahren

| Charakteristikum | Inhalt |
|---|---|
| Antragsformular | Formblatt A |
| Zustaendiges Gericht DE | AG Wedding (Berlin) |
| Online-Antrag möglich | www.online-mahnantrag.de |
| Verteidigungsfrist Bekl. | 30 Tage nach Zustellung |
| Bei Einspruch | Uebergang ins streitige Verfahren (Prüfung Art. 17 EuMVVO) |
| Bei keinem Einspruch | Vollstreckbarerklaerung Formblatt G |
| Vollstreckungsorgan | im Wohnsitz-MS Schuldner |

## EuGFVO (EG 861/2007) – Geringfuegigkeitsverfahren

| Grenzwert | bis 5.000 EUR (ohne Zinsen/Kosten) |
|---|---|
| Antragsformular | Formblatt A |
| Schriftliches Verfahren | keine muendliche Verhandlung ueblich |
| Frist Bekl. für Stellungnahme | 30 Tage |
| Urteil | innerhalb von 30 Tagen nach Stellungnahme |
| Vollstreckung | im anderen MS direkt, Formblatt D |

## Lugano-Uebereinkommen 2007 (CH, NO, IS)

Parallel zu Bruessel Ia, aber alte Fassung mit Exequatur (Vollstreckbarerklaerung im ZielMS noetig). Voraussetzung Anerkennung: rechtskraeftiger Titel im Urspr.-Staat.

## Drittstaaten (ausserhalb EU/Lugano)

| Sachverhalt | Vorgehen |
|---|---|
| Anerkennung deutsches Urteil | §§ 328 ZPO Anerkennung in DE; Anerkennung in Drittstaat nach dort. IPR |
| Bilaterales Abkommen | Verträge z.B. mit Tunesien, Israel, T?rkei (Anerkennungsabkommen) |
| Kein Abkommen | erneute Klage im Drittstaat ueblich |
| Schiedsspruch | New York Convention 1958 (NYÜ) – sehr leistungsfaehig |

## Verfahrensweg-Prüfung Schritt für Schritt

```
1. Schuldner-Sitz ermitteln
   -> EU? Lugano? Drittstaat?

2. Streitwert pruefen
   -> bis 5.000 EUR -> EuGFVO bevorzugen
   -> mehr -> Bruessel Ia oder EuVTVO

3. Forderung unbestritten?
   -> ja  -> EuVTVO Bestaetigung
   -> nein -> EuMVVO (Mahnverfahren) oder Klage Bruessel Ia

4. Forderung bereits tituliert in DE?
   -> Bruessel Ia Direktvollstreckung (Art. 36-44)
   -> EuVTVO Bestaetigung als alternativer Pfad

5. Schuldner reagiert nicht
   -> Vollstreckung mit Formblatt I (Bruessel Ia)
   -> oder Formblatt G (EuMVVO)

6. Schuldner widerspricht
   -> Klage im DE-Inland nach Gerichtsstand Bruessel Ia
   -> oder EuGFVO falls Grenzwert
```

## Form der Zustellung im Ausland

**HZUe 1965** (Haager Zustellungsuebereinkommen) – für Drittstaaten.
**EuZustVO (EU 2020/1784)** seit 01.07.2022 – innerhalb EU:
- Direkte Zustellung Justizbehoerde zu Justizbehoerde.
- Postzustellung mit Einschreiben möglich (Art. 18).
- Diplomatischer Weg (Konsulat) bei Bedarf.
- Übersetzung in Amtssprache des ZielMS.

## Beweismittel im EU-Ausland

| Instrument | Inhalt |
|---|---|
| EuBVO (EU 1206/2001) → Neu: VO 2020/1783 | Beweiserhebung |
| Videokonferenz nach EuBVO | Art. 17 ff. |

## Kosten

| Verfahren | Gerichtskosten |
|---|---|
| EuMVVO | 0,5 nach KV 1100 GKG |
| EuGFVO | wie nationaler kleiner Klageweg |
| Bruessel Ia Vollstreckung | im ZielMS nach dortigem Tarif |
| Anerkennung Drittstaat | Anwalts- und Gerichtskosten lokal |

## Typische Fehler

- Klage in DE gegen Bekl. mit Wohnsitz EU ohne Prüfung Bruessel Ia → ggf. unzuständig.
- EuMVVO bei strittiger Forderung – Widerspruch fuehrt in nationale Klage des Bekl.-MS.
- Übersetzung vergessen → Zustellung schlaegt fehl.
- Schiedsklausel ueberhaupt nicht gepruef → New York Convention besserer Pfad.
- Lugano mit Bruessel verwechselt – Exequatur in CH noch noetig.

## Quellen
- Bruessel Ia VO 1215/2012 [eur-lex.europa.eu/eli/reg/2012/1215](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32012R1215)
- EuVTVO 805/2004 [eur-lex.europa.eu](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32004R0805)
- EuMVVO 1896/2006 [eur-lex.europa.eu](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32006R1896)
- EuGFVO 861/2007 [eur-lex.europa.eu](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32007R0861)
- EuZustVO 2020/1784 [eur-lex.europa.eu](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32020R1784)
- HZUe 1965 [hcch.net](https://www.hcch.net/en/instruments/conventions/full-text/?cid=17)
- New York Convention 1958 [newyorkconvention.org](https://www.newyorkconvention.org/)

---

## Skill: `forderung-internationaler-bezug`

_Forderungssache mit Auslandsbezug Schuldner im EU-Ausland oder ausserhalb. Klaert anwendbares Recht internationale Zuständigkeit Vollstreckung. Pinpoints VO 1215/2012 Brüssel Ia VO 1896/2006 EuMVVO VO 805/2004 EuVTVO VO 861/2007 EuGFVO Rom I VO 593/2008. Liefert Routing nach Schuldnerstandort und..._

# Forderung mit internationalem Bezug

Auslandsbezug ändert Zuständigkeit anwendbares Recht und Vollstreckungspfad.

## Routing nach Schuldnerstandort

| Schuldner-Standort | Zuständigkeit | Verfahren |
|---|---|---|
| EU-Mitgliedstaat | Brüssel Ia VO 1215/2012 | nationales Verfahren EuMVVO oder EuGFVO |
| EFTA Schweiz Norwegen Island | LugÜ 2007 | wie Brüssel Ia |
| Drittstaat z B GB nach Brexit USA | autonomes Recht 12 13 23 ZPO | Anerkennungs- und Vollstreckungsvertraege prüfen |

## Anwendbares Recht

| Vertragstyp | Norm |
|---|---|
| Kauf Werk Dienst Vertrag | Rom I VO 593/2008 Art 4 |
| Verbrauchervertrag | Rom I Art 6 Schutz |
| Versicherungsvertrag | Rom I Art 7 |
| Ausservertragliche Anspruchsgrundlage | Rom II VO 864/2007 |

## EU-Verfahren

| Verfahren | Norm | Anwendung |
|---|---|---|
| Europaeisches Mahnverfahren | VO 1896/2006 | grenzueberschreitende unbestrittene Geldforderungen |
| Europaeisches Verfahren für geringfuegige Forderungen | VO 861/2007 | bis fuenftausend Euro |
| Europaeischer Vollstreckungstitel | VO 805/2004 | nationaler Titel wird vollstreckbar EU-weit |

## Verbrauchergerichtsstand

Bei Verbrauchersachen kann Verbraucher nur im Wohnsitzstaat verklagt werden Art 18 Brüssel Ia. Gläubiger muss dort klagen.

## Vollstreckung in Drittstaaten

| Land | Grundlage |
|---|---|
| USA Brasilien | autonome Anerkennung Comity |
| Schweiz | LugÜ |
| Türkei | bilaterales Anerkennungsabkommen |
| China | sehr eingeschraenkt Reziprozitaet |

## Norm-Pinpoints

- VO 1215/2012 Art 4 5 7 17 24
- VO 1896/2006 Art 1 ff
- VO 861/2007 Art 1 ff
- VO 593/2008 Art 4 6
- LugÜ 2007 Art 2 5

## Quellen

- [VO 1215/2012](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32012R1215)
- [VO 1896/2006](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32006R1896)
- [VO 861/2007](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32007R0861)

---

## Skill: `forderungen-interessen-matrix`

_Strukturierte Gegenueberstellung mehrerer Forderungen eines Mandanten gegen einen oder mehrere Schuldner. Erfasst Hauptforderung Nebenforderung Zinsen Kosten Faelligkeit Beleg Verjährung. Pinpoints ZPO 260 Klagenhaeufung ZPO 33 Aufrechnungswiderklage BGB 366 Tilgungsreihenfolge. Liefert priorisie..._

# Forderungen-Interessen-Matrix

Wenn Mandant mehrere Forderungen gegen denselben oder verschiedene Schuldner hat braucht es eine Reihung und Bundelungs-Entscheidung.

## Matrix-Schema

| Forderung | Hauptsumme Euro | Faellig seit | Verjährung in Monaten | Beleg | Aussicht | Kostenprognose | Empfehlung |
|---|---|---|---|---|---|---|---|
| Werklohn Bauvorhaben A | 24500 | 2024-09-15 | 18 | Rechnung Abnahme | hoch | mittel | sofort Klage |
| Restkaufpreis Maschine | 8200 | 2025-03-01 | 26 | Kaufvertrag Lieferschein | hoch | gering | Mahnbescheid |
| Schadensersatz Stornogebuehr | 3100 | 2024-12-10 | 9 | E-Mail-Kette | mittel | gering | erst aussergerichtlich |
| Honorar Beratung 2022 | 4800 | 2022-10-01 | -2 verjaehrt | Rechnung | aussichtslos | hoch | nicht klagen |

## Bundelungs-Optionen

| Konstellation | Werkzeug | Norm |
|---|---|---|
| Mehrere Anspruchsgruende gegen denselben Beklagten | Objektive Klagehaeufung | ZPO 260 |
| Mehrere Beklagte aus derselben Lieferkette | Streitgenossenschaft | ZPO 59 ZPO 60 |
| Gegenforderung Beklagter | Widerklage | ZPO 33 |
| Tilgungsverrechnung bei mehreren Forderungen | Tilgungsreihenfolge | BGB 366 BGB 367 |

## Kostenmehrwert prüfen

Bundelung lohnt wenn alle Forderungen in dieselbe Zuständigkeit fallen GVG 23 oder GVG 71. Bei Mischung von AG- und LG-Forderungen kann Zusammenrechnung der Streitwerte nach ZPO 5 ein einheitliches LG-Verfahren ergeben.

## Tilgungsreihenfolge ohne Bestimmung BGB 366 Abs. 2

1. Faellige Schuld vor nicht faelliger
2. Unter mehreren faelligen die geringer gesicherte
3. Unter gleich gesicherten die laestigere
4. Bei gleicher Laestigkeit die aeltere
5. Bei gleichem Alter anteilig
6. Innerhalb einer Forderung Kosten vor Zinsen vor Hauptforderung BGB 367

## Norm-Pinpoints

- ZPO 5 Wertaddition mehrere Anspruechen
- ZPO 33 Widerklage
- ZPO 59 60 Streitgenossen
- ZPO 260 Klagenhaeufung
- BGB 366 367 Tilgung

## Quellen

- [ZPO 260](https://www.gesetze-im-internet.de/zpo/__260.html)
- [BGB 366](https://www.gesetze-im-internet.de/bgb/__366.html)

---

## Skill: `fristen-risikoampel`

_Ampel zur Bewertung saemtlicher Fristen in einer Forderungssache von Verjährung Klagefrist Einspruchsfrist Beschwerdefrist bis Vollstreckungsfristen. Pinpoints BGB 195 199 ZPO 339 Einspruchsfrist Versaeumnisurteil ZPO 700 Einspruch Vollstreckungsbescheid ZPO 222 Fristberechnung. Liefert Ampel-Log..._

# Fristen-Risikoampel

Fristverletzungen sind eine der haeufigsten Haftungsquellen. Diese Ampel hilft beim Frueherkennen.

## Fristen-Katalog

| Frist | Norm | Dauer |
|---|---|---|
| Regelverjaehrung | BGB 195 | drei Jahre |
| Verjährungsbeginn | BGB 199 Abs. 1 | Schluss des Jahres der Entstehung und Kenntnis |
| Hoechstverjaehrung subjektiv | BGB 199 Abs. 4 | zehn Jahre ab Entstehung |
| Verjährung Werkmaengel bei Bauwerken | BGB 634a Abs. 1 Nr. 2 | fuenf Jahre |
| Mahnbescheid Widerspruchsfrist | ZPO 692 Abs. 1 Nr. 3 | zwei Wochen |
| Vollstreckungsbescheid Einspruchsfrist | ZPO 700 ZPO 339 | zwei Wochen |
| Versaeumnisurteil Einspruch | ZPO 339 Abs. 1 | zwei Wochen |
| Berufung Einlegen | ZPO 517 | ein Monat |
| Berufungsbegruendung | ZPO 520 Abs. 2 | zwei Monate |
| Beschwerde sofortige | ZPO 569 | zwei Wochen |
| Kostenfestsetzung Beschwerde | ZPO 11 RpflG | zwei Wochen |

## Ampel-Logik

| Ampel | Auslöser |
|---|---|
| gruen | naechste Frist mehr als sechzig Tage in der Zukunft |
| gelb | naechste Frist zwischen vierzehn und sechzig Tagen |
| rot | naechste Frist binnen vierzehn Tagen oder unklar |

Rote Ampel verlangt Sofortbearbeitung und Aktennotiz.

## Fristberechnung ZPO 222 BGB 187 ff

- Tag des Ereignisses zaehlt nicht mit ausser bei Stunden- oder Geburtsfristen
- Tag des Endes wenn Sonn- oder Feiertag verschiebt sich auf den naechsten Werktag
- Monatsfrist endet am gleichen Tag des Folgemonats fehlt der Tag am letzten Tag des Monats

## Hemmung und Neubeginn

| Tatbestand | Wirkung | Norm |
|---|---|---|
| Verhandlungen | Hemmung | BGB 203 |
| Klageerhebung | Hemmung | BGB 204 Nr. 1 |
| Mahnbescheid | Hemmung mit Zustellung | BGB 204 Nr. 3 |
| Anerkenntnis | Neubeginn | BGB 212 Abs. 1 Nr. 1 |
| Vollstreckungshandlung | Neubeginn | BGB 212 Abs. 1 Nr. 2 |

## Norm-Pinpoints

- ZPO 222 339 517 520 569
- BGB 195 199 203 204 212

## Quellen

- [ZPO 339](https://www.gesetze-im-internet.de/zpo/__339.html)
- [BGB 203](https://www.gesetze-im-internet.de/bgb/__203.html)
- [BGB 212](https://www.gesetze-im-internet.de/bgb/__212.html)

---

## Skill: `klage-einreichungslogik`

_Praktische Einreichungslogik einer Zahlungsklage. Klaert Zuständigkeit Gerichtskostenvorschuss beA-Pflicht Anzahl Abschriften Anlagenbezeichnung und Zustellung. Pinpoints ZPO 130d beA-Pflicht ZPO 253 Klageinhalt ZPO 167 Rueckwirkung Zustellung GKG 12 Vorschuss. Liefert Checkliste für die Einreich..._

# Klage-Einreichungslogik

Eine inhaltlich richtige Klage scheitert oft an Formalien. Dieser Skill geht die Einreichung Schritt für Schritt durch.

## Einreichungs-Checkliste

| Punkt | Prüfung | Norm |
|---|---|---|
| Sachliche Zuständigkeit | Streitwert über zehntausend Euro LG sonst AG | GVG 23 Nr. 1 GVG 71 |
| Oertliche Zuständigkeit | Wohnsitz Beklagter Erfuellungsort Verbrauchergerichtsstand | ZPO 12 13 29 29c |
| Streitwertangabe | konkrete Eurozahl im Schriftsatz | GKG 39 |
| beA-Pflicht | Rechtsanwalt muss elektronisch einreichen | ZPO 130d |
| Anlagen | nummeriert K eins K zwei Bezugnahme im Text | ZPO 131 |
| Abschriften | bei Papier so viele wie Beklagte plus eine für Gericht | ZPO 133 |
| Vollmacht | original oder beglaubigte Abschrift mit Klage | ZPO 80 |
| Gerichtskostenvorschuss | nach Eingang Rechnung sofort einzahlen | GKG 12 |
| Zustellung | Gericht von Amts wegen an Beklagten | ZPO 271 |

## beA-Pflicht ZPO 130d

Seit 1.1.2022 müssen Rechtsanwaeltinnen Schriftsaetze elektronisch einreichen. Verstoss fuehrt zu Unwirksamkeit. Ausnahme nur bei voruebergehender technischer Stoerung mit Glaubhaftmachung ZPO 130d Satz 2 und Satz 3.

## Gerichtskostenvorschuss

Nach Eingang der Klage versendet das Gericht eine Kostenrechnung. Erst nach Eingang des Vorschusses wird die Klage zugestellt. Wer Verjährungshemmung will muss demnaechst zahlen ZPO 167. In der Praxis innerhalb von zwei Wochen.

## Streitwert und Gebühren Beispiele 2026

| Streitwert | Gerichtsgebuehr drei-Wert | Anwaltsgebuehr 1,3 Verfahren |
|---|---|---|
| 2000 | 267 | 261 |
| 10000 | 723 | 798 |
| 25000 | 1149 | 1268 |
| 50000 | 1719 | 1841 |

Werte gerundet ohne Auslagen ohne USt.

## Anlagen Bezeichnung

```
Anlage K 1 Rechnung vom 12.03.2025
Anlage K 2 Lieferschein vom 14.03.2025
Anlage K 3 Mahnschreiben vom 28.04.2025
```

Im Text Bezugnahme z B Anlage K 1.

## Norm-Pinpoints

- ZPO 80 Vollmacht
- ZPO 130 Form
- ZPO 130d beA
- ZPO 133 Abschriften
- ZPO 167 Rueckwirkung
- ZPO 253 271
- GKG 12 39

## Quellen

- [ZPO 130d](https://www.gesetze-im-internet.de/zpo/__130d.html)
- [ZPO 167](https://www.gesetze-im-internet.de/zpo/__167.html)
- [GKG 12](https://www.gesetze-im-internet.de/gkg_2004/__12.html)

---

## Skill: `mandantenkommunikation`

_Strukturierte Mandantenkommunikation waehrend einer Forderungssache. Definiert Anlaesse Inhalte und Form für Mandanteninformation Auftragsbestaetigung Sachstand Vergleich Zustimmung und Abschluss. Pinpoints BORA 11 unverzuegliche Information BRAO 49b Mandantenaufklaerung RVG 49b BGB 280 Schadense..._

# Mandantenkommunikation

Maendel der Mandantenpflicht endet jedes Forderungsmandat in Aerger. Dieser Skill regelt Anlaesse Form und Mindestinhalt.

## Pflicht-Anlaesse

| Anlass | Frist | Form | Mindestinhalt |
|---|---|---|---|
| Mandatsannahme | sofort | Textform | Auftragsbestaetigung Honorarbasis Vollmacht Datenschutz |
| Wesentliche Schritte | unverzueglich | Textform oder Telefon mit Vermerk | was wann mit welcher Erfolgsaussicht |
| Eingang Schuldner-Brief | innerhalb drei Werktagen | Textform | Sachstand Optionen Empfehlung |
| Vergleichsangebot Gegenseite | unverzueglich | Textform | Wortlaut Bewertung Vorschlag |
| Klageeinreichung | vorher | Textform | Risikohinweis Kostenrisiko Streitwert Gerichtskostenvorschuss |
| Urteil oder Vollstreckungsbescheid | spaetestens drei Tage | Textform | Tenor Rechtsmittelhinweis Folgeschritte |
| Mandatsende | sofort | Textform | Abschluss Aktenrueckgabe Aufbewahrungspflicht |

## Pflicht-Hinweise

- Risiko des Unterliegens Kostenfolge ZPO 91
- Streitwertabhaengige Gebühren RVG 13
- Vorschusspflicht des Gläubigers für Gerichtskosten GKG 12
- Hemmungs- und Verjährungswirkung der Klageerhebung BGB 204

## E-Mail-Muster Mandantensachstand

```
Betreff Sachstand Forderungssache [Name Schuldner] - Aktenzeichen [...]

Sehr geehrte Frau Sehr geehrter Herr [Mandant]

zur Forderung ueber [Hauptsumme] Euro gegen [Schuldner] berichten wir Folgendes.

Aktueller Stand
- [eingegangene Zahlung Verzug Schuldnerbrief]
- [eigene Massnahme letzte Frist]

Naechster Schritt
- [Mahnbescheid Klage Vollstreckung]
- voraussichtliche Frist bis [Datum]

Risiko und Kosten
- Aussicht [hoch mittel gering]
- Gerichtskosten ca [Betrag] Anwaltskosten ca [Betrag]

Wir bitten um Ihre Zustimmung bis [Datum].

Mit freundlichen Gruessen
```

## Schweigepflicht

- BRAO 43a Abs. 2 Verschwiegenheit
- StGB 203 Strafbarkeit der Verletzung
- DSGVO Art 6 Art 9 bei Verarbeitung

## Norm-Pinpoints

- BRAO 43a 49b
- BORA 11
- RVG 13 49b

## Quellen

- [BRAO 43a](https://www.gesetze-im-internet.de/brao/__43a.html)
- [BORA 11](https://www.gesetze-im-internet.de/bora/__11.html)

---

## Skill: `quellenkarte`

_Kuratierte Quellenkarte für Forderungsmanagement Klagewerkstatt. Sortiert nach Gesetzen Rechtsprechung Verordnungen EU-Recht und Praxis-Literatur. Pinpoints ZPO BGB GVG GKG RVG InsO und EU-Verordnungen Brüssel Ia EuMVVO EuVTVO EuGFVO. Liefert Linkliste auf gesetze-im-internet.de bundesgerichtshof..._

# Quellenkarte

Quellen die in diesem Plugin durchgaengig zitiert werden.

## Nationale Gesetze

| Norm | Bereich | Link |
|---|---|---|
| BGB 195 199 203 204 212 | Verjährung Hemmung Neubeginn | [BGB 195](https://www.gesetze-im-internet.de/bgb/__195.html) |
| BGB 286 288 | Verzug und Zinsen | [BGB 286](https://www.gesetze-im-internet.de/bgb/__286.html) |
| BGB 631 641 650a ff | Werkvertrag Bau | [BGB 631](https://www.gesetze-im-internet.de/bgb/__631.html) |
| ZPO 130 130d 138 142 253 | Form und Schriftsatz | [ZPO 253](https://www.gesetze-im-internet.de/zpo/__253.html) |
| ZPO 688 ff | Mahnverfahren | [ZPO 688](https://www.gesetze-im-internet.de/zpo/__688.html) |
| ZPO 704 ff | Vollstreckung | [ZPO 704](https://www.gesetze-im-internet.de/zpo/__704.html) |
| GVG 23 71 | Sachliche Zuständigkeit | [GVG 23](https://www.gesetze-im-internet.de/gvg/__23.html) |
| GKG 12 39 | Gerichtskosten | [GKG 12](https://www.gesetze-im-internet.de/gkg_2004/__12.html) |
| RVG 13 14 49b | Anwaltsgebuehren | [RVG 13](https://www.gesetze-im-internet.de/rvg/__13.html) |
| InsO 14 17 174 | Insolvenzantrag Anmeldung | [InsO 174](https://www.gesetze-im-internet.de/inso/__174.html) |

## Rechtsprechung Quellen

| Gericht | Link |
|---|---|
| Bundesgerichtshof | [bundesgerichtshof.de](https://www.bundesgerichtshof.de) |
| Bundesverwaltungsgericht | [bverwg.de](https://www.bverwg.de) |
| Bundesverfassungsgericht | [bverfg.de](https://www.bverfg.de) |
| dejure Datenbank | [dejure.org](https://www.dejure.org) |
| openJur | [openjur.de](https://openjur.de) |

## EU-Recht

| Norm | Bereich |
|---|---|
| VO 1215/2012 Brüssel Ia | Zuständigkeit Anerkennung Vollstreckung |
| VO 1896/2006 EuMVVO | Europaeisches Mahnverfahren |
| VO 805/2004 EuVTVO | Europaeischer Vollstreckungstitel |
| VO 861/2007 EuGFVO | Europaeisches Verfahren für geringfuegige Forderungen |

Quelle [eur-lex.europa.eu](https://eur-lex.europa.eu)

## Praxis-Materialien

- Bundesanzeiger für Basiszinssatz [bundesanzeiger.de](https://www.bundesanzeiger.de)
- Online-Mahnverfahren der Länder [online-mahnantrag.de](https://www.online-mahnantrag.de)
- e-Justice Portal EU [e-justice.europa.eu](https://e-justice.europa.eu)

## Zitierhinweise

- BGH-Entscheidungen mit Aktenzeichen und Datum
- BVerfGE Band X Rn Y
- ZPO und BGB ohne Klammerzitate

## Quellen

- [gesetze-im-internet.de](https://www.gesetze-im-internet.de)
- [bundesgerichtshof.de](https://www.bundesgerichtshof.de)
- [eur-lex.europa.eu](https://eur-lex.europa.eu)

---

## Skill: `redteam-qualitygate`

_Red-Team-Review eines fertigen Schriftsatzes oder Mahnbescheidsantrags. Sucht aus Sicht der Gegenseite nach Angriffsflaechen Schwaechen Beweisluecken und Form-Fehlern. Pinpoints ZPO 138 substantiiertes Bestreiten ZPO 296 Verspaetungspraeklusion ZPO 130d beA-Form. Liefert Checkliste mit Gegen-Angr..._

# Redteam Qualitygate

Vor Einreichung ein Prüfgang aus Sicht der Beklagten.

## Prüfraster

| Bereich | Fragen aus Beklagten-Sicht |
|---|---|
| Aktivlegitimation | Ist Klägerin Inhaberin der Forderung Tritt eine Abtretung dazwischen |
| Passivlegitimation | Stimmt der Beklagte mit dem Vertragspartner ueberein |
| Anspruchsgrund | Welche Tatsachen sind unstreitig welche streitig |
| Faelligkeit | Bestreite ich die Faelligkeit mit Erfolg |
| Verzug | Wurde die Mahnung tatsaechlich zugestellt |
| Verjährung | Kann ich die Einrede der Verjährung erheben |
| Aufrechnung | Habe ich Gegenforderungen |
| Erfuellung | Kann ich Teilzahlung nachweisen |
| Form Beleg | Welche Anlage fehlt oder ist unleserlich |
| Substantiierung | Welche Tatsache ist nur pauschal vorgetragen |

## Schwachstellen-Liste

| Schwachstelle | Konsequenz |
|---|---|
| Anlagen nicht klar nummeriert | Bezug unklar |
| Zinsbeginn ohne Mahnungsdatum | Zinsanspruch streitig |
| Pauschal-Behauptung ohne Datum | Substantiierungsruege |
| Vollmacht fehlt oder veraltet | Zurueckweisung ZPO 88 |
| Streitwert hoeher als notwendig | unnoetige Kosten |
| AGB-Klausel zur Faelligkeit nicht geprueft BGB 305 ff | Klausel unwirksam |

## Verspaetungspraeklusion

Später Vortrag kann nach ZPO 296 zurueckgewiesen werden. Beklagte versucht oft Verzoegerungstaktik. Kläger sollte Beweise mit Klage einreichen.

## Norm-Pinpoints

- ZPO 88 130d 138 296
- BGB 305 ff
- BGB 387 ff Aufrechnung

## Quellen

- [ZPO 296](https://www.gesetze-im-internet.de/zpo/__296.html)
- [ZPO 138](https://www.gesetze-im-internet.de/zpo/__138.html)

---

## Skill: `tatbestand-beweis-belege`

_Schluessige Tatbestandsdarstellung in einer Klage oder einem Schriftsatz mit Verknuepfung zu Beweisen und Belegen. Verlangt zeitliche Reihenfolge konkrete Tatsachen mit Beweismitteln Anlagenverweis. Pinpoints ZPO 138 Wahrheitspflicht ZPO 137 Verhandlungsgrundsatz ZPO 138 Abs. 2 substantiiertes Be..._

# Tatbestand Beweis Belege

Der Tatbestand muss konkret datiert beweisangebotenen Tatsachen enthalten. Pauschalsaetze fallen durch.

## Tatbestand-Muster

```
I. Sachverhalt

1. Am [Datum] schlossen die Parteien einen
[Vertragstyp] ueber [Leistungsgegenstand]
zum Preis von [Hauptsumme] Euro. Beweis
Anlage K 1 Vertragsurkunde.

2. Die Klaegerin lieferte die geschuldete
Leistung am [Datum] vollstaendig. Beweis
Anlage K 2 Lieferschein gezeichnet von
[Empfaenger]. Zeuge [Name Anschrift].

3. Die Klaegerin stellte unter dem [Datum]
Rechnung Nr [Rechnungsnummer]. Beweis Anlage
K 3.

4. Die Beklagte erhielt die Rechnung
spaetestens am [Datum]. Beweis Anlage K 4
Sendungsverlauf.

5. Mit Schreiben vom [Datum] mahnte die
Klaegerin die Zahlung mit Fristsetzung bis
[Datum]. Beweis Anlage K 5.

6. Eine Zahlung erfolgte bis heute nicht.
Beweis Kontoauszug Anlage K 6.
```

## Substantiierungsanforderungen

| Anforderung | Inhalt |
|---|---|
| Vollstaendigkeit | jeder anspruchsbegruendende Punkt |
| Zeitliche Reihenfolge | Datum bei jedem Schritt |
| Beweismittel | je Tatsache mindestens eines |
| Bezugnahme Anlage | im Text mit Anlagen-Nummer |
| Tatsachen nicht Wertungen | wer was wann wo |

## Bestreiten durch Beklagte

| Form | Wirkung |
|---|---|
| Substantiiertes Bestreiten | Kläger trifft Beweislast voll |
| Pauschales Bestreiten unzulaessig | gilt als zugestanden ZPO 138 Abs. 3 |
| Nichtwissen ZPO 138 Abs. 4 | nur bei Tatsachen ausserhalb eigener Wahrnehmung |

## Norm-Pinpoints

- ZPO 137 Verhandlungsgrundsatz
- ZPO 138 Wahrheitspflicht Substantiierung
- ZPO 286 freie Beweiswuerdigung

## Quellen

- [ZPO 138](https://www.gesetze-im-internet.de/zpo/__138.html)
- [ZPO 286](https://www.gesetze-im-internet.de/zpo/__286.html)

---

## Anwendungshinweise

1. Diesen Megaprompt als Kontext in den Chat einfuegen oder als Datei hochladen.
2. Den eigentlichen juristischen Fall beschreiben.
3. Den Chat-Agent bitten, sich anhand der oben aufgefuehrten Skills zu orientieren.
4. Bei Zitaten Quellenhygiene beachten: keine Modellwissens-Halluzinationen; alle Rspr. live verifizieren.

