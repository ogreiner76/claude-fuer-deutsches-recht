---
name: corporate-kanzlei-teaser-im-processdocs
description: "Teaser, Information Memorandum und Prozessdokumente für M&A-Auktionsprozesse erstellen: Verkaeuferkanzlei oder Investmentbank benoetigt anonymisierten Teaser, IM und VDD. Normen: § 311 Abs. 2 BGB (vorvertragliche Haftung), MAR (Insiderinformationen), WpueG (Public M&A). Prüfraster: Anonymisierungsgrad, Disclaimer, Materialitaet, Konsistenz mit DR-Inhalt. Output Teaser-Entwurf, IM-Gliederung, Management-Presentation-Template. Abgrenzung: Bieter-Prozess siehe simulation-bidder-process; Datenraum siehe datenraum-aufbau."
---

# Teaser, Information Memorandum und Prozessdokumente

## Fachlicher Anker

- **Normen:** §§ 3, §§ 76, §§ 105.
- **Entscheidungs-/Quellenanker:** Tragende Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle einsetzen; keine Entscheidung aus Modellwissen erzwingen.
- **Quellenhygiene:** `references/quellenhygiene.md` und `references/zitierweise.md` beachten.

## Fachkern: Teaser, Information Memorandum und Prozessdokumente

- **Corporate-Aufgabe (Teaser, Information Memorandum und Prozessdokumente):** Verkaeuferkanzlei oder Investmentbank benoetigt anonymisierten Teaser, IM und VDD.
- **Norm-/Dealanker:** GmbHG, AktG, HGB, BGB, UmwG, Registerrecht, Beurkundung, Signing/Closing-Mechanik, Beschlusslage, Vollmachten, Datenraum und Haftungsallokation fallbezogen trennen.
- **Entscheidende Weiche:** Gesellschaftsrechtliche Wirksamkeit, Dealprozess, Mandatsführung, Gremienfreigabe, Dokumentenbeweis und Eskalation nicht vermischen.
- **Arbeitsprodukt:** Partnerfähiges Memo, Closing-/Action-Liste, Redline-Hinweis oder PMO-Board mit Verantwortlichen und Blockern.

## Wann wird dieser Skill aufgerufen
Typische Auslöser:
- "Ich habe hier Teaser, Information Memorandum und Prozessdokumente und brauche einen belastbaren nächsten Schritt."
- "Bitte prüfe das aus Sicht der Gesellschaft, Geschäftsführung, Gesellschafter oder Inhouse-Rechtsabteilung."
- "Mach daraus eine Beschlussvorlage, Partnernotiz, Mandantenmail oder Organunterlage."
- "Welche Register-, Beschluss-, Compliance- oder Fristpunkte fehlen noch?"

Nicht dieser Skill ist vorrangig, wenn zuerst die Gesellschaftsakte selbst angelegt, die Mandatsrolle bestimmt oder ein unklarer Upload triagiert werden muss. Dann beginne mit `/corporate-kanzlei:corporate-kanzlei-kommandocenter` oder `/corporate-kanzlei:corporate-kanzlei-matter-file`. Wenn der Nutzer nur eine Kurzfassung für interne Abstimmung will, arbeite bewusst kürzer und liefere keine lange Prüfarchitektur.

## Voraussetzungen und Kontext laden
Lies zuerst, falls vorhanden, den Matter-Workspace unter `~/.config/claude-fuer-deutsches-recht/corporate-kanzlei/mandate/<slug>/`: `mandat.md`, `history.md`, `chronologie.md`, `fristen.yaml` und den aktuellen Dokumentenlog. Wenn kein Workspace existiert, frage nur die Mindestdaten ab: Gesellschaft, Rechtsform, Rolle, Organstatus, Beschluss-/Registerlage, Frist, gewünschter Output und ob börsen-, konzern- oder regulierungsrelevante Bezüge bestehen.

Benötigte Unterlagen:
- Datenraumindex, Q&A-Tracker, IRL und Disclosure-Log.
- NDA, Clean-Room-Protokoll und MAR-Insiderliste falls börsennotierte Gesellschaft betroffen ist.
- Registerauszüge, wesentliche Verträge, Litigation-Liste, IP/IT- und HR-Unterlagen.

Arbeite mit diesen Variablen: `gesellschaft`, `rolle`, `organ`, `beschlussdatum`, `registerstand`, `frist_oder_closing`, `materiality_threshold`, `owner`, `source_tag`.

## Workflow
1. **Corporate-Kontext fixieren.** Bestimme Gesellschaft, Rechtsform, Organrolle, Anlass, Beschluss-/Registerstand und Entscheidungsempfänger. Wenn Rolle oder Rechtsform fehlen, frage genau eine Rückfrage; bei Fristdruck arbeite mit `[Annahme - prüfen]` weiter.
2. **Quellen inventarisieren.** Liste Dokumente mit Datum, Version, Quelle, Register-/Urkunden-ID und Vertraulichkeitsstufe. Markiere Uploads als `[Mandant]`, Register als `[Register]`, Gerichts-/Behördenquellen als `[Primärquelle]` und Modellwissen als `[Modellwissen - prüfen]`.
3. **Organ- und Kompetenzebene trennen.** Unterscheide Geschäftsführung/Vorstand, Gesellschafterversammlung/Hauptversammlung, Aufsichtsrat/Beirat, Konzernleitung, Notar und Registergericht.
4. **Materiality-Schwelle setzen.** Fehlt eine Vorgabe, arbeite mit Ampel: Nichtigkeit/Unwirksamkeit, Anfechtungs-/Haftungsrisiko, Registerhindernis, Zustimmungserfordernis, Housekeeping.
5. **Normenprüfung durchführen.** Prüfe die unten genannten Normgruppen bezogen auf den konkreten Corporate-Schritt: Zuständigkeit, Form, Frist, Mehrheit, Vollmacht, Registerfähigkeit, Haftung und Beweisquelle.
6. **Belegkette bauen.** Jede wesentliche Aussage braucht Quelle, Dokument, Fundstelle und Unsicherheitsmarker. Keine Fundstelle erfinden. Wenn Registerauszug, BGH-/EuGH-Entscheidung oder Behördenpraxis nicht abrufbar ist, steht `[zu verifizieren]`.
7. **Risikomatrix erstellen.** Gib pro Punkt aus: Sachverhalt, Rechtsfrage, Norm, Subsumtion, Risikoampel, Rechtsfolge, empfohlene Aktion, Owner, Deadline und Folge-Skill.
8. **Draft oder Review-Gate wählen.** Wenn die Tatsachen reichen, liefere den gewünschten Output. Wenn nicht, liefere eine Information-Request-Liste oder eine Partner-/Organvorlage mit genau den offenen Entscheidungen.
9. **Hand-off vorbereiten.** Überführe Findings in Beschlussentwurf, Board Paper, Registeranmeldung, SPA-Markup, CP-Tracker, Mandantenmail oder Closing Bible. Verweise auf den konkreten Anschluss-Skill unten.
10. **Abschlusskontrolle.** Prüfe: keine ungeprüften Aktenzeichen, keine BeckRS-Blindzitate, keine automatische Außenkommunikation, keine vertraulichen Informationen außerhalb des Need-to-know-Kreises.

## Pruefraster im Gutachtenstil
**Obersatz:** Zu prüfen ist, ob der im Skill bearbeitete Corporate-Schritt gesellschaftsrechtlich wirksam, registerfähig, organschaftlich vertretbar und für die Mandatsseite praktisch umsetzbar ist.

**1. Mandats- und Rollenrahmen.** Zunächst muss feststehen, wer vertreten wird: Gesellschaft, Organmitglied, Gesellschafter, Investor, Käufer, Verkäufer oder Konzernmutter. Ist die Rolle unklar, darf kein parteilicher Beschluss-, Vertrags- oder Verhandlungsoutput als final erscheinen; zulässig ist nur eine neutrale Struktur- oder Fragenliste.

**2. Zuständigkeit, Form und Corporate Authority.** Bei Anteils-, Beschluss- und Strukturmaßnahmen sind Vertretungsmacht, Zustimmungserfordernisse, Mehrheit, Form und Registerlage zu prüfen. Relevanter Kern:
- BGB §§ 311 Abs. 2, 241 Abs. 2 und 280 für vorvertragliche Aufklärungspflichten.
- GeschGehG §§ 2, 4, 6 und 17 für Geschäftsgeheimnisse im Datenraum.
- GWB §§ 35 ff. und § 41 sowie Art. 7 FKVO für Gun-Jumping und Clean-Room-Fragen.
- MAR Art. 7, 17 und 18 bei börsennotierter Gesellschaft.

**3. Organpflichten und Business Judgment.** Bei Geschäftsleitungs-, Aufsichtsrats- oder Beiratsentscheidungen ist zu fragen, ob die Entscheidung auf angemessener Informationsgrundlage, ohne sachfremde Interessen und zum Wohl der Gesellschaft vorbereitet ist. Für Organverantwortung: BGH, 21.04.1997 - II ZR 175/95, ARAG/Garmenbeck, https://dejure.org/1997,161 `[dejure.org]`.

**4. Register- und Gesellschafterlistenlogik.** Bei GmbH-Anteilen, Einziehung, Vollmachtskette oder Beschlussfähigkeit ist § 16 GmbHG gesondert zu prüfen. Zur Legitimationswirkung der Gesellschafterliste: BGH, 20.11.2018 - II ZR 12/17, https://dejure.org/2018,47817 `[BGH-Datenbank/dejure.org]`.

**5. Vollzugshindernisse.** Wenn Fusionskontrolle, AWV/FDI, MAR, GwG, Sanktionen, Bankzustimmung, Satzungszustimmung oder branchenspezifische Genehmigungen berührt sind, muss das Ergebnis lauten: Anmeldung erforderlich? Vollzugsverbot? Registerhindernis? Beschlussmangel? Long-Stop-Date gefährdet? Bußgeld-, Nichtigkeits- oder Haftungsfolge?

**6. Subsumtion.** Subsumtion erfolgt dokumentennah. Beispiel: `§ 15 GmbHG notarielle Form erfüllt?` nur bejahen, wenn Entwurf/Urkunde/Notarbestätigung vorliegt. `§ 46 GmbHG Zustimmung erforderlich?` nur bejahen, wenn Satzung, Geschäftsordnung und Maßnahme geprüft sind.

**Zwischenergebnis:** Formuliere als Ampel: grün mit Beleg, gelb mit offener Information, rot mit Handlungssperre. Rot bedeutet im Corporate-Kontext: nicht beschließen, nicht anmelden, nicht signieren, nicht closen oder nicht extern versenden, bevor Partner, Organ oder Spezialist freigegeben hat.

## Output-Module
- **Corporate-Vermerk:** Kurzbild, Sachverhalt, Normen, Subsumtion, Risikoampel, Empfehlung.
- **Beschluss-/Board-Paper-Modul:** Zuständigkeit, Beschlussvorschlag, Informationsgrundlage, BJR-Dokumentation, Anlagenliste.
- **Issue List:** Finding, Quelle, Risiko, Rechtsfolge, Register-/Vertragsfolge, Owner, Deadline.
- **Information Request:** konkrete Fragen an Mandant, Organ, Notar, Registerteam, Steuerberater oder Gegenseite.
- **Matter-Update:** kurzer Eintrag für `history.md` und ggf. Frist-/Owner-Eintrag für `fristen.yaml`.

## Quellen und Zitierregel
Nutze nur frei prüfbare Quellen oder vom Nutzer bereitgestellte/lizenzierte Quellen. Rechtsprechung nur mit Gericht, Entscheidungsdatum, Aktenzeichen und Link auf `dejure.org`, `openjur.de`, `bundesgerichtshof.de`, `bundesverfassungsgericht.de`, `curia.europa.eu` oder `eur-lex.europa.eu`. Keine BeckRS-Alleinzitate, keine anwalt24-Belege, keine erfundenen Randnummern. Quellen-Tags: `[Mandant]`, `[Register]`, `[BGH-Datenbank]`, `[dejure.org]`, `[EUR-Lex]`, `[Web-Recherche - prüfen]`, `[Modellwissen - prüfen]`.

## Hand-Off zu anderen Skills
Nach diesem Skill weiter mit:
- `/corporate-kanzlei:corporate-kanzlei-datenraum-aufbau` - wenn Dokumente, Datenraumlücken oder Clean-Room-Fragen der nächste Engpass sind.
- `/corporate-kanzlei:corporate-kanzlei-datenraum-gap-clean-room` - wenn Informationslücken, Wettbewerberdaten oder Clean-Room-Grenzen geklärt werden müssen.
- `/corporate-kanzlei:corporate-kanzlei-due-diligence-legal` - wenn aus Unterlagen ein Corporate-/Legal-DD-Befund gebaut werden soll.
- `/corporate-kanzlei:corporate-kanzlei-qa-information-requests` - wenn Findings in Information Requests und Q&A übersetzt werden müssen.
- `/corporate-kanzlei:corporate-kanzlei-due-diligence-reporting` - wenn ein adressatengerechter DD-Report entstehen soll.

## Was dieser Skill nicht macht
- Er ersetzt keine Partner-, Organ- oder Mandantenentscheidung über Beschluss, Signing, Registeranmeldung oder Closing.
- Er führt keine automatische Außenkommunikation an Gegenseite, Behörde, Notar, Registergericht, Datenraumteilnehmer oder Mandant aus.
- Er behauptet keine Registerlage, Behördenpraxis oder Rechtsprechung ohne prüfbare Quelle.
- Er vermischt nicht Corporate-Befund, Vertragsrisiko und wirtschaftliche Bewertung; diese Ebenen bleiben getrennt.
- Er trifft keine steuerliche, kartellrechtliche, sanktionsrechtliche oder ausländische Rechtsaussage final ohne Spezialisten-Review.
- Er behandelt vertrauliche Daten nur innerhalb des Need-to-know-Kreises und markiert sensible Informationen für Clean-Room oder Insiderlisten.

## Berufsrechtliche Hinweise
Vor Mandatsarbeit sind Interessenkonflikte nach § 43a BRAO und § 3 BORA, Verschwiegenheit nach § 43a Abs. 2 BRAO, Vergütungsrahmen nach § 49b BRAO und GwG-Sorgfaltspflichten zu beachten. Bei personenbezogenen Daten gelten DSGVO Art. 5, 6, 25 und 32. Bei Drittakten, Datenräumen, Akteneinsicht oder Clean-Room-Material ist der Zweckbindungsrahmen zu prüfen; Material aus einem Mandat darf nicht stillschweigend in ein anderes Mandat übernommen werden.

## Bisheriger Skill-Kern, integriert und weiterzuverwenden

# Teaser, Information Memorandum und Prozessdokumente

## Triage — klaere vor Erstellung

1. Welches Dokument: Teaser (anonym), IM (nach NDA), Management Presentation, VDD Report?
2. Borsennotiertes Unternehmen? → MAR-Compliance; keine kursrelevanten Infos ohne Ad-hoc
3. Adressaten: strategische Kaeufer, PE-Fonds, Family Offices, Debt-Investoren?
4. Vertraulichkeit: Was darf schon im Teaser preisgegeben werden (Name, Branche, Standort)?
5. Timing: Parallel zu Datenraum-Aufbau oder vorher?
6. Governance: Wer genehmigt IM? (Vorstand/GF-Unterschrift; AR-Kenntnis erforderlich?)

## Zentrale Normen

- **§§ 311 II, 241 II BGB** — vorvertragliche Aufklaerungspflichten; IM-Inhalt muss vollstaendig und korrekt sein; Haftung bei Fehlinformationen
- **§ 123 BGB** — Anfechtung bei arglistiger Taeuschung im IM; 1 Jahr Frist (§ 124 BGB)
- **Art. 17 MAR** — kursrelevante Informationen im IM nicht ohne Ad-hoc-Prüfung veröffentlichen; nationale Sanktionen nach WpHG mitdenken
- **§§ 11, 14, 15 WpUeG** — Angebotsunterlage bei börsennotierten Zielgesellschaften erstellen, der BaFin übermitteln und erst nach Prüfung veröffentlichen
- **§§ 8-15 UWG** — irreführende Werbung; IM darf keine unwahren Angaben enthalten

## Aktuelle Rechtsprechung

- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

## Quellenregel

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.
## Dokumententypen im M&A-Prozess

| Dokument | Inhalt | Vertraulichkeit | Zeitpunkt |
|---|---|---|---|
| Teaser (anonym) | Branche, Groesse, EBITDA-Range, USP; kein Name | Oeffentlich / vor NDA | Prozess-Start |
| NDA | Vertraulichkeit; Rueckgabepflicht; Wettbewerbsschutz | Beiderseits | Vor IM-Versand |
| Information Memorandum (IM) | Vollstaendige Unternehmensbeschreibung; Finanzkennzahlen; Markt; Strategie; Risiken | Nach NDA | Phase I |
| Management Presentation | Ausfuehrliche Praesentation; Management-Fragen; Q&A | Shortlist-Bieter | Phase II |
| Vendor Due Diligence (VDD) | Sell-Side-aufbereiteter DD-Report (Legal, Tax, Financial); fuer Kaeufer-Nutzung | Shortlist/Binding-Phase | Phase II |
| Process Letter | Ablauf; Anforderungen; Bieterrichtlinien | Nach NDA | Prozess-Start |
| LoI / Term Sheet | Indikativer Preis; Struktur; Zeitplan | Verhandlung | Preferred Bidder |

## IM-Struktur: Standard

```
INFORMATION MEMORANDUM — [DEAL-CODENAME]
STRENG VERTRAULICH — NUR FUER ADRESSATEN NACH NDA
[Datum / Version / Investmentbank]

DISCLAIMER
Dieses IM enthält zukunftsgerichtete Aussagen und Prognosen. [Kanzlei/Bank] übernimmt keine Verantwortung für Richtigkeit;
empfohlene eigenstaendige Pruefung durch den Leser. Haftungsfreizeichnung gilt nicht bei Arglist.

INHALT
I. EXECUTIVE SUMMARY (2-3 Seiten)
 - Investment Highlights
 - Transaktionsueberblick
 - Finanzielle Eckdaten

II. UNTERNEHMENSPROFIL
 - Geschichte und Entwicklung
 - Geschaeftsmodell und Produktportfolio
 - Markt und Wettbewerb
 - Strategie und Wachstumspotenzial

III. FINANZIELLE INFORMATIONEN
 - GuV und EBITDA-Entwicklung (letzte 3 Jahre)
 - Bilanzkennzahlen
 - Working Capital und Net Debt
 - Forecast laufendes Jahr und Planungshorizont

IV. MANAGEMENT
 - Fuehrungsteam und Biographien
 - Organisationsstruktur
 - Key Person Risiken

V. RECHTLICHE UND REGULATORISCHE INFORMATIONEN
 - Unternehmensstruktur (Vereinfacht; kein vollstaendiges Organigramm vor Phase II)
 - Wesentliche Vertraege und Kunden (anonymisiert)
 - Laufende Verfahren (wenn wesentlich offenbarungspflichtig)

VI. TRANSAKTIONSSTRUKTUR UND PROZESS
 - Transaktionsgegenstand
 - Angestrebte Kaufpreisstruktur
 - Zeitplan und Prozess

ANLAGEN (Phase II)
```

## Schritt-fuer-Schritt-Workflow

1. **Abstimmung mit Mandant** — welche Informationen koennen offenbart werden; Vertraulichkeitsgrenzen
2. **Datenerhebung** — Jahresabschluesse, Management-Interviews, Marktdaten
3. **Teaser erstellen** — anonym; EBITDA-Range; Branche; USP; 2-3 Seiten
4. **IM erstellen** — nach NDA; vollstaendig, korrekt; Disclaimer einbauen; Forward-Looking-Warnings
5. **Interne Freigabe** — Geschaeftsfuehrung / Vorstand zeichnet ab; ggf. AR-Kenntnis
6. **Disclaimer und Haftungsklausel** — Standardformulierung; Empfaenger-Beschraenkung
7. **Verteilung** — nur nach unterzeichnetem NDA; Empfaengerliste protokollieren
8. **Update-Management** — bei wesentlichen Aenderungen: neue Version; alle Empfaenger informieren

## Rote Schwellen

- Wesentliche Fehlinformationen im IM → c.i.c.-Haftung § 311 II BGB; Anfechtung moeglich
- Kursrelevante Informationen ohne Ad-hoc → Art. 17 MAR; BaFin-Bussgeld
- IM ohne Disclaimer → erhoehtes Haftungsrisiko bei fahrlassiger Fehlinformation
- Verteilung ohne NDA → Vertraulichkeitsverlust; Insider-Probleme
- Zukunftsgerichtete Aussagen ohne angemessene Qualifikation → Haftungsrisiko

## Quellen

- §§ 311 II, 241 II, 123 BGB; Art. 17 MAR; §§ 11, 14, 15 WpUeG; §§ 8-15 UWG
- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
- Holzapfel/Poellath, Unternehmenskauf (16. Aufl. 2022) Kap. 2
