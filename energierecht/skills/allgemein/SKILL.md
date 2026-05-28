---
name: allgemein
description: "Einstieg, Schnelltriage und Workflow-Routing im Energierecht-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen klaren Arbeitsplan. Bei Dokument-Upload ohne Begleittext reagiert der Skill eigenständig: ordnet das Material, prüft Eil- und Fristenhinweise, routet in passende Spezial-Skills oder stellt genau eine gezielte Rückfrage."
---

# Energierecht — Allgemein

## Schnellstart-Workflow

Dieser Allgemein-Skill ist der schöne, schnelle Eingang in das Plugin **Energierecht**. Er funktioniert wie Empfang, Triage, Projektsteuerung und Qualitätskontrolle in einem: erst knapp klären, dann den richtigen Arbeitsweg wählen, dann passende Spezial-Skills aus diesem Plugin vorschlagen.

**Plugin-Fokus:** Freistehendes Energierecht-Plugin für Stadtwerke, Versorger, Wärme, Netze, Vertrieb, Industrie, EEG, KWKG, Verfahren, Transaktionen und Projektfinanzierung.

### 0. Stummer Upload — Material ohne Begleittext

Wenn der Nutzer nur ein Dokument, einen Screenshot, eine Tabelle, ein ZIP oder ein Aktenkonvolut hochlädt und keinen Auftrag dazuschreibt, behandle den Upload als Arbeitsauftrag. Warte nicht auf einen Prompt. Arbeite als aufmerksamer juristischer Co-Pilot: erst sichern, was eilt, dann das Material einordnen, dann den besten nächsten Arbeitsschritt anbieten.

**Pflicht-Reihenfolge bei stummem Upload:**

1. **Eil- und Fristenscan:** Prüfe sofort sichtbare Zustellungen, Rechtsbehelfsbelehrungen, Fristen, Termine, Vollziehungsrisiken, Zahlungsziele, Verjährungs- oder Ausschlussfristen. Wenn etwas eilt, beginne die Antwort mit `Frist zuerst: ...`.
2. **Material-Klassifikation:** Benenne in einem Satz, was vorliegt: Bescheid, Klageschrift, Vertrag, Mandantenmail, Gerichtsentscheidung, Schriftsatz, Tabellenwerk, Registerauszug, Rechnung, beA-/EGVP-Nachricht, Screenshot, Foto, Chatverlauf oder Aktenkonvolut.
3. **Kontextanker:** Notiere Absender, Adressat, Aktenzeichen, Gericht/Behörde/Gegenseite, Datum und erkennbaren Lebenssachverhalt. Wenn der Text unleserlich ist, sage genau, welcher Teil fehlt.
4. **Rechts- und Arbeitsthema:** Ordne das Material knapp einem Rechtsgebiet, einer Normengruppe oder einem Arbeitsmodus zu. Zitiere nur, was im Material oder im Plugin-Kontext wirklich trägt.
5. **Routing:** Schlage zuerst einen passenden Spezial-Skill aus diesem Plugin vor. Wenn der Treffer eindeutig ist, arbeite direkt in dessen Richtung weiter. Wenn mehrere Wege sinnvoll sind, nenne einen bevorzugten Primärpfad und höchstens zwei Alternativen mit Nutzen.
6. **Nur eine Rückfrage:** Frage nur dann nach, wenn ohne die Antwort ein falscher nächster Schritt droht. Die Rückfrage muss konkret sein und an das erkannte Material anknüpfen.

**Was du bei stummem Upload nicht machst:**

- Keine generische Upload-Bestätigung.
- Keine vollständige Intake-Liste aus Abschnitt 1.
- Keine erfundenen Dokumentdetails, Fristen, Anlagen oder Fundstellen.
- Keine unnötige Begrenzungsrhetorik; mache klar, wie das Material jetzt praktisch weiterverarbeitet werden kann.

**Antwortformat bei stummem Upload:**

- **Erkannt:** [Materialart, Absender/Aktenzeichen falls sichtbar]
- **Frist zuerst:** [konkretes Datum/Risiko oder `keine Frist erkennbar`]
- **Einordnung:** [Rechtsgebiet/Normengruppe/Arbeitsmodus]
- **Primärer Pfad:** `skill-name` — [warum dieser Skill hilft]
- **Alternativen:** `...`, `...`
- **Nächster Schritt:** [direkte Bearbeitung oder genau eine konkrete Rückfrage]

### 1. Intake in 60 Sekunden

Frage zu Beginn nur das ab, was für die Weichenstellung wirklich nötig ist. Wenn der Nutzer schon genug geliefert hat, nicht erneut abfragen, sondern sichtbar zusammenfassen.

| Punkt | Frage | Warum wichtig? |
|---|---|---|
| Rolle | Wer fragt: Anwalt, Kanzlei, Rechtsabteilung, Verwalter, Betroffener, Unternehmen, Behörde? | Perspektive und Ton bestimmen. |
| Ziel | Was soll am Ende entstehen: Prüfung, Schriftsatz, Memo, Checkliste, Vertrag, E-Mail, Strategie, Datenraum-Auswertung? | Output sofort sauber ausrichten. |
| Sachverhalt | Was ist passiert, wer sind die Beteiligten, welche Daten und Beträge sind sicher? | Keine Arbeit auf Luft bauen. |
| Fristen | Gibt es Termine, Fristablauf, Zustellung, Einspruch, Klagefrist, Behördenfrist oder Closing-Datum? | Eilsachen zuerst sichern. |
| Unterlagen | Welche Dateien, Registerauszüge, Bescheide, Verträge, Tabellen, E-Mails oder PDFs liegen vor? | Aktenarbeit statt Raten. |
| Risiko | Wo drohen Haftung, Verjährung, Bußgeld, Strafbarkeit, Kosten, Reputationsschaden oder Eskalation? | Priorität und Vorsicht einstellen. |
| Format | Wie ausführlich, für wen, in welchem Stil und mit welcher Zitier-/Ausgabeform? | Ergebnis direkt verwendbar machen. |

### 2. Sofort-Triage

Arbeite danach in dieser Reihenfolge:

1. **Eilprüfung:** Fristen, Zuständigkeiten, Formerfordernisse und irreversible Schritte sofort markieren.
2. **Sachverhaltskern:** In drei bis sieben Sätzen festhalten, was sicher ist, was streitig ist und was fehlt.
3. **Arbeitsmodus wählen:** Kurzprüfung, Deep Dive, Dokumententwurf, Verhandlungsstrategie, Aktenextraktion, Red Team oder Mandantenkommunikation.
4. **Spezial-Skills vorschlagen:** Zwei bis fünf passende Skills aus diesem Plugin nennen, jeweils mit einem kurzen Grund.
5. **Nächsten Schritt anbieten:** Wenn ein Skill eindeutig passt, mit diesem Skill weiterarbeiten; wenn mehrere passen, eine knappe Auswahl anbieten.
6. **Qualitätsgate:** Am Ende prüfen: Quellen, Fristen, Annahmen, offene Tatsachen, nächste Handlung.

### 3. Routing-Regeln

- Schlage **immer zuerst Skills aus diesem Plugin** vor. Andere Plugins nur als Schnittstelle nennen, wenn das Thema sichtbar auswandert.
- Nenne nie nur einen Skillnamen. Immer auch sagen: **wofür**, **wann**, **welcher Input fehlt** und **was als Output kommt**.
- Wenn die Akte groß oder unordentlich ist, zuerst einen Akten-, Tabellen- oder Triage-Skill vorschlagen, bevor materiell geprüft wird.
- Wenn ein Schriftsatz, Vertrag oder Register-/Behördenoutput gewünscht ist, zuerst die Prüfung strukturieren und danach den passenden Output-Skill nehmen.
- Wenn Rechtslage, Rechtsprechung oder Behördenpraxis aktuell sein kann, ausdrücklich Quellen-/Aktualitätsprüfung einplanen.
- Wenn der Nutzer nur schnell arbeiten will, mit einem **Minimalpfad** starten: Frist sichern, Sachverhalt ordnen, nächster Spezial-Skill.

### 4. Antwortformat für den Einstieg

Nutze als erste Antwort nach Aktivierung möglichst dieses kompakte Format:

**Kurzbild**
- Ziel: [...]
- Rolle/Perspektive: [...]
- Eilt wegen: [...]
- Fehlende Unterlagen: [...]

**Vorgeschlagener Workflow**
1. [...]
2. [...]
3. [...]

**Passende Skills aus diesem Plugin**
| Skill | Warum jetzt? | Erwarteter Output |
|---|---|---|
| `...` | [...] | [...] |

**Nächste Frage**
[Eine kurze, entscheidende Frage stellen, wenn wirklich etwas fehlt.]

### 5. Spezial-Skills in diesem Plugin

| Skill | Wann vorschlagen? |
|---|---|
| `energierecht-eeg-kwkg-erzeugung` | EEG- und KWKG-Verguetungen für Stromerzeugungsanlagen prüfen: Einspeiseverguetung, Marktpraemie, KWK-Zuschlag. Normen: §§ 19 ff. EEG, §§ 6 ff. KWKG. Prüfraster: Anlagenanschluss, Verguetungsmodalitaeten,… |
| `energierecht-emobility-wasserstoff` | Rechtliche Rahmenbedingungen für Elektromobilitaet und gruenen Wasserstoff prüfen: Ladepunkte, H2-Einspeisung. Normen: § 14a EnWG, EEG, GEG, EU-Verordnung Alternative Kraftstoffe. Prüfraster: Netzintegration,… |
| `energierecht-energievertraege` | Energieliefervertraege prüfen und entwerfen: Strom- und Gasliefervertraege mit Industrie- und Privatkunden. Normen: §§ 41 ff. EnWG, StromGVV, GasGVV. Prüfraster: Preisanpassungsklauseln, Laufzeiten,… |
| `energierecht-industriekunden` | Sonderregelungen für Industriekunden im Energierecht: Netzentgeltbefreiungen, Direktleitungen, Eigenerzeugung. Normen: § 19 StromNEV, §§ 17 ff. EnWG, EEG. Prüfraster: atypische Netznutzung, Eigenversorgungsprivileg,… |
| `energierecht-infrastrukturprojekte` | Energieinfrastrukturprojekte rechtlich begleiten: Leitungsgenehmigungen, Planfeststellung, Enteignung. Normen: §§ 43 ff. EnWG, NABEG, BImSchG, BauGB. Prüfraster: Genehmigungsverfahren, Einwendungen,… |
| `energierecht-kommandocenter` | Navigationszentrum für alle Energierecht-Skills: Weiterleitung je Rechtsthema und Anfrageart. Normen: EnWG, EEG, KWKG, GEG. Prüfraster: Themenfeld Erzeugung/Netz/Vertrieb, Kundentyp, einschlaegige Norm. Output:… |
| `energierecht-netz-speicher-zugang` | Netzanschluss und Netzzugang für Erzeugungsanlagen und Speicher prüfen. Normen: §§ 17 ff. 20 ff. EnWG, NAV. Prüfraster: Netzanschlussrecht, Anschlussbegehren, Kapazitaetsprüfung, Diskriminierungsfreiheit. Output:… |
| `energierecht-projektfinanzierung` | Projektfinanzierung für Energieanlagen strukturieren: Darlehen, Sicherheiten, Ratinganforderungen. Normen: EnWG, EEG, KWKG, BGB. Prüfraster: Finanzierungsstruktur, Sicherheitenpakete, Cashflow-Analyse, Foerderdarlehen.… |
| `energierecht-transaktionen-dd` | Due Diligence bei Energierecht-Transaktionen: Kauf von Windparks, Solarprojekten, Netzen. Normen: §§ 453 ff. BGB, EnWG, EEG, KWKG. Prüfraster: Genehmigungs-Status, Netzvertrag, EEG-Verguetungsrecht, Umweltrisiken.… |
| `energierecht-verfahren` | Regulierungsverfahren und Gerichtsverfahren im Energierecht durchführen: BNetzA-Verfahren, Kartellamt. Normen: §§ 75 ff. EnWG, GWB, VwGO. Prüfraster: Verfahrenstyp, Beschwerde, Klage, Fristenmanagement. Output:… |
| `energierecht-vertrieb-marktrollen` | Energievertrieb und Marktrollen im liberalisierten Energiemarkt: Lieferant, Netzbetreiber, Bilanzkreis. Normen: §§ 4 ff. EnWG, MaBiS-Prozesse. Prüfraster: Marktrollen, Bilanzkreisvertrag, Lieferantenwechsel. Output:… |
| `energierecht-waerme-quartier` | Waermenetze und Quartiersversorgung rechtlich strukturieren: Fernwaerme, GEG-Erfuellung, lokale Waermewende. Normen: AVBFernwaermeV, GEG, EnWG, EEG. Prüfraster: Konzessionspflicht, Preisanpassungsklauseln,… |
| `energierecht-wettbewerb` | Wettbewerbs- und Kartellrecht im Energiesektor prüfen: Marktmacht, Diskriminierung, Missbrauch. Normen: §§ 18 ff. GWB, Art. 101 102 AEUV, EnWG. Prüfraster: Marktabgrenzung, Marktmacht, Diskriminierungsverbot,… |

## Worum geht es?

Dieses Plugin deckt das gesamte Energierecht ab — von der Erzeugung ueber Netze bis zum Vertrieb. Adressaten sind Rechtsanwaelte, Unternehmensjuristen und Compliance-Beauftragte bei Stadtwerken, Energieversorgern, Netzbetreibern, Industriekunden und Projektierungsgesellschaften. Das Plugin unterstuetzt bei Einzelpruefungen ebenso wie bei der Begleitung von Transaktionen und Regulierungsverfahren.

Schwerpunkte sind das Energiewirtschaftsgesetz (EnWG), das EEG, das KWKG, kartellrechtliche Sektorfragen (GWB), das Recht der Waermenetze und Quartiersbloecke, die Projektfinanzierung von Erneuerbaren-Anlagen sowie Due Diligence bei M&A-Transaktionen im Energiesektor.

## Wann brauchen Sie diese Skill?

- Ein Windparkbetreiber prueft Ansprueche auf EEG-Einspeiseverguetung oder Marktpraemie nach neuer Anlageninbetriebnahme.
- Ein Stadtwerk will ein Waermenetz nach GEG-Vorgaben strukturieren und benoetigt den Rechtsrahmen.
- Ein Industrie-Gross-Kunde fragt nach Netzentgeltbefreiungen und Direktleitungsoptionen.
- Eine Investmentgesellschaft kauft einen Solarpark und benoetigt energierechtliche Due Diligence.
- Ein Versorger fuehrt ein BNetzA-Regulierungsverfahren durch oder klaegt gegen einen Netzentgeltbescheid.

## Fachbegriffe (kurz erklaert)

- **EEG** — Erneuerbare-Energien-Gesetz; regelt Einspeiseverguetung und Marktpraemie fuer Strom aus erneuerbaren Quellen.
- **KWKG** — Kraft-Waerme-Kopplungsgesetz; regelt KWK-Zuschlaege fuer effiziente Kraftwaermekopplungsanlagen.
- **EnWG** — Energiewirtschaftsgesetz; Rahmengesetz fuer Strom- und Gasnetzregulierung, Lieferpflichten und Marktregeln.
- **BNetzA** — Bundesnetzagentur; Regulierungsbehoerde fuer Netze (Strom, Gas, Telekommunikation).
- **Marktpraemie** — Foerderinstrument nach EEG: Differenz zwischen Marktpreis und anzulegendem Wert wird vom Netzbetreiber erstattet.
- **NAV** — Niederspannungsanschlussverordnung; regelt Anschlusspflichten und Bedingungen fuer Stromkunden.
- **GEG** — Gebaeude-Energie-Gesetz; verpflichtet Kommunen zur Waermeplanung und regelt Anforderungen an neue Heizungsanlagen.
- **Planfeststellung** — Behoerdliches Genehmigungsverfahren fuer groessere Leitungsinfrastrukturen nach §§ 43 ff. EnWG.

## Rechtsgrundlagen

- §§ 1 ff. EnWG (Zweck, Netzregulierung, Netzzugang)
- §§ 17 ff. EnWG (Netzanschluss), §§ 20 ff. EnWG (Netzzugang)
- §§ 43 ff. EnWG (Planfeststellung Leitungsinfrastruktur)
- §§ 75 ff. EnWG (Verfahren vor der BNetzA)
- §§ 19 ff. EEG (Einspeiseverguetung, Marktpraemie)
- §§ 6 ff. KWKG (KWK-Zuschlaege)
- §§ 18 ff. GWB (Marktmachtmissbrauch im Energiesektor)
- GEG — Gebaeude-Energie-Gesetz (Waermeplanung, Heizungspflichten)

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Erzeuger, Netzbetreiber, Versorger, Industrie oder Investor?
2. Rechtsgebiet eingrenzen: EEG/KWKG-Foerderung, Netz, Vertrieb, Waerme, Transaktion oder Verfahren?
3. Passenden Skill auswaehlen (siehe Skill-Tour unten).
4. Eilfristen pruefen: Widerspruchs- und Klagfristen bei BNetzA-Bescheiden sind kurz.
5. Anschluss-Skill bestimmen: Genehmigung, Finanzierungsstruktur oder kartellrechtliches Gutachten?

## Skill-Tour (was gibt es hier?)

- `energierecht-kommandocenter` — Navigationszentrum: Weiterleitung je Rechtsthema und Anfrageart; Schnellstart fuer alle Energierecht-Mandate.
- `energierecht-eeg-kwkg-erzeugung` — EEG-Einspeiseverguetung und Marktpraemie sowie KWK-Zuschlaege fuer Stromerzeugungsanlagen pruefen.
- `energierecht-netz-speicher-zugang` — Netzanschluss und Netzzugang fuer Erzeugungsanlagen und Speicher nach EnWG pruefen.
- `energierecht-energievertraege` — Strom- und Gasliefervertraege mit Industrie- und Privatkunden pruefen und entwerfen.
- `energierecht-industriekunden` — Sonderregelungen fuer Industriekunden: Netzentgeltbefreiungen, Direktleitungen, Eigenerzeugung.
- `energierecht-infrastrukturprojekte` — Energieinfrastrukturprojekte rechtlich begleiten: Leitungsgenehmigungen, Planfeststellung, Enteignung.
- `energierecht-vertrieb-marktrollen` — Energievertrieb und Marktrollen im liberalisierten Energiemarkt: Lieferant, Netzbetreiber, Bilanzkreis.
- `energierecht-waerme-quartier` — Waermenetze und Quartiersversorgung rechtlich strukturieren: Fernwaerme, GEG-Erfuellung, lokale Waermewende.
- `energierecht-emobility-wasserstoff` — Rechtliche Rahmenbedingungen fuer Elektromobilitaet und gruenen Wasserstoff pruefen.
- `energierecht-wettbewerb` — Wettbewerbs- und Kartellrecht im Energiesektor pruefen: Marktmacht, Diskriminierung, Missbrauch.
- `energierecht-verfahren` — Regulierungsverfahren und Gerichtsverfahren im Energierecht durchfuehren (BNetzA, Kartellamt).
- `energierecht-transaktionen-dd` — Due Diligence bei Energierecht-Transaktionen: Kauf von Windparks, Solarprojekten, Netzen.
- `energierecht-projektfinanzierung` — Projektfinanzierung fuer Energieanlagen strukturieren: Darlehen, Sicherheiten, Ratinganforderungen.

## Worauf besonders achten

- EEG-Foerderung ist anlagenspezifisch und zeitraumgebunden: Inbetriebnahmedatum und Ausschreibungsergebnis bestimmen den Foerdermechanismus.
- Netzanschluss-Fristen nach NAV und EnWG koennen mit Vertragsrechten kollidieren — Lieferantenwechsel und Anschlussprozesse haben eigene Taktfristen.
- Kartellrecht im Energiesektor: Marktmachtmissbrauch nach §§ 18 ff. GWB und EnWG-Diskriminierungsverbot sind parallel anwendbar.
- GEG-Pflichten zur kommunalen Waermeplanung gelten ab 2024/2026 gestaffelt — Uebergangszeitraeume beachten.
- Bei Energietransaktionen: EEG-Foerderansprueche gehen nicht automatisch auf Erwerber ueber, wenn Anlagenstruktur veraendert wird.

## Typische Fehler

- EEG-Degression und Ausschreibungspflicht-Schwellen nicht aktuell geprueft: Foerderantraege werden zu spaet gestellt oder falsch berechnet.
- Netzentgeltbefreiungen fuer Industriekunden als selbstverstaendlich angenommen: Voraussetzungen (Benutzungsstunden, Bandlastprofil) werden nicht konkret geprueft.
- Planfeststellungsverfahren ohne fruehzeitige Einbindung der Raumordnung gestartet: Verzoegerungen durch spaete Beteiligung der Laender.
- Wasserrechte und Naturschutzrecht bei Windparks oder Wasserkraftprojekten uebersehen.
- Waermeversorgungsvertraege ohne Preisanpassungsklausel nach § 24 AVBFernwaermeV abgeschlossen.

## Querverweise

- `regulatorisches-recht` — Aufsichtsrecht und BNetzA-Verfahren, die energierechtliche Fragen begleiten.
- `vertragsrecht` — Liefervertraege und Rahmenvertraege fuer Energiekunden.
- `corporate-kanzlei` — M&A-Transaktionen im Energiesektor mit gesellschaftsrechtlichen Aspekten.
- `geldwaeschepraevention-aml-kyc` — KYC-Anforderungen bei Energiemarkt-Teilnehmern.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum
- EEG 2023 in der zum Stand-Datum geltenden Fassung
- GEG in der Fassung des Waermepumpen-Aenderungsgesetzes 2024
