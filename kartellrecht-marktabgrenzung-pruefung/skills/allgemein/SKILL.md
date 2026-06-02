---
name: allgemein
description: "Einstieg, Schnelltriage und Workflow-Routing im Kartellrecht Marktabgrenzung Pruefung-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen klaren Arbeitsplan. Bei Dokument-Upload ohne Begleittext reagiert der Skill eigenständig: ordnet das Material, prüft Eil- und Fristenhinweise, routet in passende Spezial-Skills oder stellt genau eine gezielte Rückfrage."
---

<!-- konvers-stil-v1 -->

## Konversationsstil – konzis starten, schnell zum Dokument

- **Erste Antwort kurz.** Sachverhalt einordnen, höchstens **eine** unverzichtbare Rückfrage stellen, dann arbeiten.
- **Kein Lehrbuch-Intro.** Keine Norm-Wiederholung, keine Selbstankündigung – sofort einsteigen.
- **Schnell zum Dokument.** Sobald die Mindestangaben vorliegen, liefere einen ersten Entwurf mit `[noch zu klären: …]`-Platzhaltern, statt weiter abzufragen.
- **Allgemein-Skill = Einstieg, nicht Vorlesung.** Triage, Rückfrage falls nötig, dann auf die Spezial-Skills dieses Plugins verweisen oder direkt den ersten Entwurf produzieren.
- **Ausführlich nur, wenn es das Arbeitsergebnis verlangt:** echte Subsumtion im Gutachtenstil, Tabellen, Chronologien, Risiko-/Beweislastanalysen, Schriftsatz- oder Memo-Text.
- **Erklärungen nur auf Nachfrage.** Wenn der Nutzer Hintergrund will, ausführlich. Sonst nicht.



# Kartellrecht-Marktabgrenzungs-Pruefer — Allgemein

## Schnellstart-Workflow

Dieser Allgemein-Skill ist der schöne, schnelle Eingang in das Plugin **Kartellrecht Marktabgrenzung Pruefung**. Er funktioniert wie Empfang, Triage, Projektsteuerung und Qualitätskontrolle in einem: erst knapp klären, dann den richtigen Arbeitsweg wählen, dann passende Spezial-Skills aus diesem Plugin vorschlagen.

**Plugin-Fokus:** Kritische kartellrechtliche Prüfinstanz für vorgelegte Marktabgrenzungen nach Paragraf 18 GWB und Art 101 und 102 AEUV. SSNIP-Test Nachfrage- und Angebotsumstellung räumlicher Markt Evidenzbasierung Konsistenzcheck EuGH-Leitentscheidungen Red Flags alternative Marktdefinitionen Marktbeherrschung.

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
| `alternative-marktdefinition-eng` | Mandant will eine engere Marktabgrenzung argumentieren um niedrigere Marktanteile oder fehlende Marktbeherrschung zu zeigen. Generiert engere alternative Marktdefinition mit juristischer und oekonomischer Begründung.… |
| `alternative-marktdefinition-weit` | Mandant will eine weitere Marktabgrenzung argumentieren um niedrigere Marktanteile zu zeigen oder Behoerden-Markt anzugreifen. Generiert weitere alternative Marktdefinition mit juristischer und oekonomischer… |
| `auswirkungen-marktanteile-marktbeherrschung` | Wie aendert sich der Marktanteil des Mandanten je nachdem wie eng oder weit der Markt abgegrenzt wird. Quantifiziert Auswirkungen alternativer Marktabgrenzungen auf Marktanteile und Marktbeherrschungsvermutungen.… |
| `cluster-und-systemmaerkte` | Behoerde oder Gegenseite argumentiert mit Cluster-Markt oder Aftermarkt-Doktrin oder Mandant will dies nutzen. Prüft Cluster-Maerkte Buendelung nicht-substitutiver Produkte und Systemmaerkte Primaermarkt plus… |
| `dma-und-gatekeeper-markt` | Digital Markets Act (VO 2022/1925): Gatekeeper-Designierung Kernplattformdienste quantitative und qualitative Schwellenwerte. Auswirkungen der DMA-Designierung auf die Marktdefinition in kartellrechtlichen Verfahren.… |
| `elastizitaeten-diversion-ratios` | Oekonomischer Gutachter oder Mandant legt Elastizitaetsdaten oder Diversion-Ratio-Analyse vor und Belastbarkeit ist zu prüfen. Prüft Eigenpreis-Elastizitaet Kreuzpreis-Elastizitaet und Diversion Ratios als Instrumente… |
| `eu-bekanntmachung-marktdefinition-2024` | Skill zur neuen EU-Kommissions-Bekanntmachung zur Marktdefinition (Februar 2024) und ihrer praktischen Anwendung. Vergleich zur Bekanntmachung von 1997. Neue Elemente: digitale Maerkte Innovationswettbewerb… |
| Rechtsprechung live prüfen | Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren. |
| `evidenz-qualitaet-bewertung` | Bewertet die Qualitaet und Belastbarkeit der vorgelegten Belege für eine Marktabgrenzung: interne Unternehmensdokumente Kundenverhaltensdaten Marktdaten Elastizitaeten Diversion Ratios Branchenberichte. Erkennt… |
| `fusionskontrolle-modus` | Prüft Marktabgrenzung im Kontext der EU-Fusionskontrolle (FKVO 139/2004): Phase I und Phase II SIEC-Test (Significant Impediment to Effective Competition) horizontale und nicht-horizontale Fusionen Effizienzeinrede und… |
| `gesamtbewertung-tragfaehigkeit` | Gesamturteil zur Tragfähigkeit einer Marktabgrenzung: hoch mittel oder gering. Fasst zentrale Schwachstellen in 3 bis 5 scharfen Punkten zusammen. Bewertet Angreifbarkeit vor Gericht oder Behoerde und empfiehlt… |
| `innovations-und-technologiemaerkte` | Marktabgrenzung in dynamischen Technologiemaerkten wo kuenftige Innovation den Wettbewerb praegt oder Patent-Pools streitig sind. Prüft Innovationsmaerkte technologische Substitution Standard-Essential-Patents… |
| `kartellverbot-modus` | Prüft Marktabgrenzung im Kontext des Kartellverbots (Art 101 AEUV und Paragraf 1 GWB): Wettbewerbsbeschraenkung bezweckt oder bewirkt Single-Brand vs Inter-Brand Wettbewerb Spuerbarkeit nach Bagatellbekanntmachung und… |
| `konsistenzpruefung-marktdefinition` | Prüft die interne Widerspruchsfreiheit einer Marktabgrenzung: Übereinstimmung von Sachmarkt und räumlichem Markt tatsaechlichem Marktverhalten Behoerdenpraxis und oekonomischen Grundprinzipien. Erkennt Zirkelschluesse… |
| `marktabgrenzung-kontextanalyse` | Verfahren beginnt und Verfahrensart und Parteistellung muessen bestimmt werden bevor die Marktabgrenzung-Analyse starten kann. Identifiziert Verfahrensart Fusionskontrolle Kartellverbot Missbrauchsverfahren und… |
| `mehrseitige-maerkte-plattformen` | Sonderprobleme der Marktdefinition für mehrseitige Plattformen: zweiseitige Marktdefinition indirekte Netzwerkeffekte getrennte vs. integrierte Marktbetrachtung. Einschluss von App-Store App-Markt Werbe- und… |
| `missbrauchsverbot-modus` | Unternehmen in marktbeherrschender Stellung soll auf Missbrauch geprüft werden oder Wettbewerber klagt auf Missbrauch. Prüft Marktabgrenzung und Missbrauchstatbestaende Art. 102 AEUV § 19 GWB. Prüfraster… |
| `paragraf-18-gwb-pruefung` | Prüft Marktbeherrschung nach Paragraf 18 GWB: Einzelmarktbeherrschung Abs 1 Marktanteils-Schwellen Abs 4 (40 Prozent) gemeinsame Marktbeherrschung Abs 5 und 6 intermediaere Plattformen Abs 3a sowie relative Marktmacht… |
| `potenzieller-wettbewerb-marktzutritt` | Behoerde oder Gegenseite argumentiert fehlende Markteintrittsbarrieren um Marktbeherrschung zu verneinen. Analysiert Markteintrittsschranken und Wahrscheinlichkeit potenziellen Wettbewerbs im Zeitrahmen 2 bis 3 Jahre.… |
| `produktmarkt-angebotsumstellung` | Prüft angebotsseitige Substitution (Supply-Side Substitution): Kann ein anderer Anbieter kurzfristig und ohne erhebliche Kosten auf den relevanten Markt wechseln? Bewertet Umstellungskosten regulatorische Anforderungen… |
| `produktmarkt-nachfragesubstitution` | Kernschritt jeder Marktabgrenzung: sachlicher Markt aus Nachfragersicht bestimmen. Prüft funktionale Austauschbarkeit Preisreagibilitaet qualitative Unterschiede Verwendungszweck Bedarfsdeckungsaequivalenz. Normen § 18… |
| `raeumlicher-markt-abgrenzung` | Prüft den räumlich relevanten Markt: national europaeisch global. Analysiert Preisstrukturen Transportkosten regulatorische Unterschiede Homogenitaetsannahmen Handelsstroeme und Arbitragemoeaeglichkeiten. Bewertet ob… |
| `red-flags-checkliste` | Strukturierte Checkliste problematischer Muster in Marktabgrenzungen: ergebnisgetriebene Argumentation Zirkelschluesse fehlende oekonomische Fundierung selektive Datenwahl kuenstliche Marktverengung oder -erweiterung… |
| `ssnip-test-anwendung` | Sachlichen Markt mit dem SSNIP-Test abgrenzen ob ein hypothetischer Monopolist profitabel Preise um 5 bis 10 Prozent erhoehen koennte. Wendet Small but Significant Non-transitory Increase in Price… |

## Worum geht es?

Dieses Plugin ist die kritische Pruefinstanz fuer vorgelegte Marktabgrenzungen in kartellrechtlichen Verfahren. Es prueft Marktabgrenzungen nach § 18 GWB sowie Art. 101 und 102 AEUV — unabhaengig davon, ob es sich um Fusionskontrollverfahren, Missbrauchsverfahren oder Kartellverbotsverfahren handelt.

Das Plugin orientiert sich an der EU-Bekanntmachung zur Marktdefinition von Februar 2024 (ABl. 2024/C 1645), an der Rechtsprechung des EuGH und EuG sowie an der Praxis des BKartA. Es identifiziert systematisch methodische Schwachstellen, selektive Datenwahl, Zirkelschluesse und alternative Marktdefinitionen, die prozessual oder behoerdlich angreifbar sind.

## Wann brauchen Sie diese Skill?

- Sie pruefen eine von der Gegenseite oder einer Behoerde vorgelegte Marktabgrenzung auf Angreifbarkeit.
- Sie erstellen eine eigene Marktabgrenzungsargumentation fuer ein Fusionskontroll-, Missbrauchs- oder Kartellverfahren.
- Sie begleiten ein BKartA- oder Kommissionsverfahren und muessen den Verfahrenskontext und die Parteistellung klaeren.
- Sie pruefen, ob eine DMA-Gatekeeper-Designation kartellrechtlich relevante Marktdefinitionen verschiebt.
- Sie wollen die Qualitaet und Belastbarkeit oekonomischer Gutachten zu Elastizitaeten oder Diversion Ratios beurteilen.

## Fachbegriffe (kurz erklaert)

- **SSNIP-Test** — Hypothetischer-Monopolisten-Test (Small but Significant Non-transitory Increase in Price): Klaert, welche Produkte und Regionen so nah substituierbar sind, dass ein Monopolist keinen profitablen Preisaufschlag von 5 bis 10 Prozent erzielen koennte.
- **Nachfragesubstitution** — Kernschritt der Marktabgrenzung: Welche Produkte wechseln Nachfrager bei einem kleinen Preisanstieg? Bestimmt den sachlichen Markt.
- **Angebotsumstellung** — Supply-Side-Substitution: Koennen andere Anbieter kurzfristig und ohne erhebliche Kosten auf den relevanten Markt wechseln?
- **Marktbeherrschung** — Erheblicher Wettbewerbsdruck fehlt; Vermutung bei 40-Prozent-Einzelmarktanteil nach § 18 Abs. 4 GWB.
- **Cellophane-Fallacy** — Methodischer Fehler beim SSNIP-Test: Pruefung von der bereits ueberhoeahten Marktmacht-Position aus fuehrt zu kuenstlich weitem Markt.
- **Inkongruente Deckung** — Begriff aus dem Anfechtungsrecht; hier nicht relevant.
- **Diversion Ratio** — Oekonomisches Mass fuer den Anteil der Nachfrage, der bei einem Preisanstieg zu einem bestimmten Wettbewerber abwandert; hohe Ratio spricht fuer engen Markt.
- **Gatekeeper** — Designierter Plattformbetreiber nach DMA; Designation beeinflusst kartellrechtliche Marktdefinition in parallelen Verfahren.

## Rechtsgrundlagen

- § 18 GWB — Marktbeherrschung, Marktanteils-Vermutungen, Plattformen.
- § 19 GWB — Missbrauch marktbeherrschender Stellung.
- § 20 GWB — Relative Marktmacht.
- § 35 GWB und FKVO 139/2004 — Fusionskontrolle und SIEC-Test.
- Art. 101 AEUV — Kartellverbot.
- Art. 102 AEUV — Missbrauchsverbot.
- EU-Bekanntmachung zur Marktdefinition 2024 (ABl. 2024/C 1645) — Methodischer Rahmen.
- DMA (VO 2022/1925) Art. 2 und 3 — Kernplattformdienste und Gatekeeper-Designation.

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Verfahrenskontext und Parteistellung klaeren: Skill `marktabgrenzung-kontextanalyse`.
2. Verfahrensmodus auswaehlen: `fusionskontrolle-modus`, `missbrauchsverbot-modus` oder `kartellverbot-modus`.
3. Sachlichen Markt pruefen: `produktmarkt-nachfragesubstitution` und `produktmarkt-angebotsumstellung`.
4. Raeumlichen Markt pruefen: `raeumlicher-markt-abgrenzung`.
5. Marktanteile und Beherrschung bewerten: `auswirkungen-marktanteile-marktbeherrschung` und `paragraf-18-gwb-pruefung`.
6. Gesamturteil und Angreifbarkeit: `gesamtbewertung-tragfaehigkeit`.

## Skill-Tour (was gibt es hier?)

**Einstieg und Kontext**

- `marktabgrenzung-kontextanalyse` — Verfahrensart und Zielrichtung bestimmen, Routing-Empfehlung.
- `fusionskontrolle-modus` — SIEC-Test, Phase I und II, horizontale und nicht-horizontale Fusionen.
- `missbrauchsverbot-modus` — Marktabgrenzung im Kontext von Art. 102 AEUV und § 19 GWB.
- `kartellverbot-modus` — Marktabgrenzung im Kontext von Art. 101 AEUV und § 1 GWB.

**Sachlicher Markt**

- `produktmarkt-nachfragesubstitution` — Sachlicher Markt aus Nachfragersicht; Kernschritt jeder Marktabgrenzung.
- `produktmarkt-angebotsumstellung` — Angebotsseitige Substitution; kurzfristiger Marktzutritt anderer Anbieter.
- `ssnip-test-anwendung` — SSNIP-Test (Hypothetischer-Monopolisten-Test) anwenden.
- `elastizitaeten-diversion-ratios` — Belastbarkeit oekonomischer Elastizitaetsdaten und Diversion-Ratio-Analysen pruefen.

**Raeumlicher Markt**

- `raeumlicher-markt-abgrenzung` — Raeumlich relevanter Markt: national, europaeisch oder global.

**Spezialmaerkte**

- `cluster-und-systemmaerkte` — Cluster-Maerkte und Aftermarket-Doktrin (Pelikan-Doktrin, Kyocera-Doktrin).
- `mehrseitige-maerkte-plattformen` — Zweiseitige Marktdefinition, indirekte Netzwerkeffekte, Plattform-Spezifika.
- `innovations-und-technologiemaerkte` — Innovationsmaerkte, SEPs, FuE-Maerkte in dynamischen Technologiesektoren.
- `dma-und-gatekeeper-markt` — DMA-Gatekeeper-Designation und Auswirkungen auf Marktdefinition.

**Marktanteile und Beherrschung**

- `paragraf-18-gwb-pruefung` — Marktbeherrschung nach § 18 GWB: Einzelbeherrschung, Schwellen, gemeinsame Beherrschung.
- `auswirkungen-marktanteile-marktbeherrschung` — Sensitivitaetsanalyse Marktanteil je Marktabgrenzungs-Szenario.
- `potenzieller-wettbewerb-marktzutritt` — Markteintrittsbarrieren und potenzieller Wettbewerb im Zeitrahmen zwei bis drei Jahre.

**Alternative Marktdefinitionen**

- `alternative-marktdefinition-eng` — Engere Marktdefinition argumentieren fuer niedrigere Marktanteile.
- `alternative-marktdefinition-weit` — Weitere Marktdefinition argumentieren gegen Beherrschungsvermutung.

**Evidenz und Qualitaet**

- `evidenz-qualitaet-bewertung` — Qualitaet und Belastbarkeit der Belege fuer eine Marktabgrenzung beurteilen.
- `eu-bekanntmachung-marktdefinition-2024` — Neue EU-Bekanntmachung Februar 2024 und Vergleich zur Bekanntmachung von 1997.
- `eugh-rechtsprechung-leitentscheidungen` — EuGH/EuG/BGH/BKartA-Leitentscheidungen zur Marktdefinition.

**Konsistenz und Gesamturteil**

- `konsistenzpruefung-marktdefinition` — Interne Widerspruchsfreiheit einer Marktabgrenzung pruefen.
- `red-flags-checkliste` — Problematische Muster in Marktabgrenzungen: ergebnisgetriebene Argumentation, Zirkelschluesse.
- `gesamtbewertung-tragfaehigkeit` — Gesamturteil zur Tragfaehigkeit; Angreifbarkeit und Prozesstaktik.

## Worauf besonders achten

- **Verfahrenskontext bestimmt Marktdefinition** — Die Richtung der Marktabgrenzungsargumentation haengt davon ab, ob Mandant Klaeger, Beklagter oder Zusammenschlusspartei ist; `marktabgrenzung-kontextanalyse` immer zuerst.
- **Cellophane-Fallacy** — Beim SSNIP-Test immer pruefen, ob Ausgangspreis bereits Marktmacht-Preis ist; Fehler fuehrt zu kuenstlich weitem Markt.
- **EU-Bekanntmachung 2024** — Seit Februar 2024 gelten neue Methodik-Standards fuer digitale Maerkte und Innovationswettbewerb; aeltere Marktabgrenzungen koennen veraltet sein.
- **DMA-Designation nicht gleichsetzen** — Eine DMA-Gatekeeper-Designation ist kein kartellrechtlicher Marktbeherrschungs-Befund; die Rechtsfragen sind trennbar.
- **Potenzielle Anbieter nicht uebergewichten** — Markteintrittsbarrieren muessen realistisch im Zeitfenster zwei bis drei Jahre bewertet werden; bloss theoretische Marktzutrittsmoeoglichkeit genuegt nicht.

## Typische Fehler

- Nachfragesubstitution und Angebotsumstellung werden verwechselt oder zusammengeworfen.
- SSNIP-Test wird ohne Cellophane-Fallacy-Pruefung auf einem bereits durch Marktmacht verzerrten Preisniveau angewendet.
- Leitentscheidungen werden ohne Pinpoint-Zitat zitiert und koennen prozessual nicht verwertet werden.
- Alternative Marktdefinitionen werden nicht erwaehnt, obwohl sie die Anteilsschwellen verschieben wuerden.
- Raeumlicher und sachlicher Markt werden nicht aufeinander abgestimmt (Konsistenzbruch).

## Querverweise

- `europarecht-kompass` — Fuer allgemeine EU-Rechtsfragen, Vorlagenverfahren und EU-Verfahrensrecht.
- `dsa-dma-digitalregulierung` — Fuer DMA-Gatekeeper-Pflichten und DSA-Fragen parallel zum Kartellrecht.
- `insolvenzplan-starug-planwerkstatt` — Bei Restrukturierungen mit kartellrechtlich relevantem Marktaustritt.

## Quellen und Aktualitaet

- Stand: 05/2026
- GWB §§ 18 ff. in der geltenden Fassung
- Art. 101 und 102 AEUV
- EU-Bekanntmachung zur Marktdefinition 2024 (ABl. 2024/C 1645)
- FKVO 139/2004 in der geltenden Fassung

<!-- BEGIN ACTUAL-SKILL-ROUTING -->

## Aktuelle Anschluss-Skills

Diese Tabelle wird aus dem tatsächlichen Skillbestand des Plugins gebildet. Wenn ein Nutzer nach dem Einstieg weitergeleitet werden soll, nimm bevorzugt diese Namen.

| Skill | Wann einsetzen? |
| --- | --- |
| `1-gwb-kartellverbot-nationale-pruefung` | § 1 GWB Kartellverbot nationale Prüfung: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 f... |
| `19-gwb-behinderungs-ausbeutungsmissbrauch` | § 19 GWB Behinderungs Ausbeutungsmissbrauch: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und... |
| `19a-gwb-ueberragende-marktuebergreifende-bedeutung` | § 19a GWB überragende marktübergreifende Bedeutung: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 1... |
| `20-gwb-relative-marktmacht` | § 20 GWB relative Marktmacht: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff.,... |
| `alleinvertrieb-kundengruppen-gebietsschutz` | Alleinvertrieb Kundengruppen Gebietsschutz: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 3... |
| `alternative-marktdefinition-eng` | Mandant will eine engere Marktabgrenzung argumentieren um niedrigere Marktanteile oder fehlende Marktbeherrschung zu zeigen. Generiert engere alternative Marktdefinition mit juristischer und... |
| `alternative-marktdefinition-weit` | Mandant will eine weitere Marktabgrenzung argumentieren um niedrigere Marktanteile zu zeigen oder Behoerden-Markt anzugreifen. Generiert weitere alternative Marktdefinition mit juristischer... |
| `anmeldepflicht-joint-venture` | Anmeldepflicht Joint Venture: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff.,... |
| `arbeitsmarkt-no-poach-wage-fixing` | Arbeitsmarkt No-Poach Wage-Fixing: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33... |
| `art-101-aeuv-kooperationspruefung-einstieg` | Workflow zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Art 101 AEUV Kooperationsprüfung Einstieg. |
| `art-101-aeuv-tatbestand-vereinbarung-beschluss-abgestimmte-verha` | Art 101 AEUV Tatbestand Vereinbarung Beschluss abgestimmte Verhaltensweise: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV,... |
| `art-102-aeuv-marktbeherrschung-missbrauch` | Art 102 AEUV Marktbeherrschung Missbrauch: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32... |
| `art-102-aeuv-missbrauchspruefung-einstieg` | Workflow zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Art 102 AEUV Missbrauchsprüfung Einstieg. |
| `auswirkungen-marktanteile-marktbeherrschung` | Wie aendert sich der Marktanteil des Mandanten je nachdem wie eng oder weit der Markt abgegrenzt wird. Quantifiziert Auswirkungen alternativer Marktabgrenzungen auf Marktanteile und Marktbeh... |
| `bietergemeinschaft-vergabekartellrecht` | Bietergemeinschaft Vergabekartellrecht: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff... |
| `bussgeldbemessung-unternehmen-verband` | Bußgeldbemessung Unternehmen Verband: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff.,... |
| `cluster-und-systemmaerkte` | Behoerde oder Gegenseite argumentiert mit Cluster-Markt oder Aftermarkt-Doktrin oder Mandant will dies nutzen. Prüft Cluster-Maerkte Buendelung nicht-substitutiver Produkte und Systemmaerkte... |
| `compliance-programm-kartellrecht-mittelstand` | Compliance-Programm Kartellrecht Mittelstand: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und... |
| `compliance-schulung-kartellrisiken` | Workflow zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Compliance-Schulung Kartellrisiken. |
| `datenzugang-und-interoperabilitaet` | Datenzugang und Interoperabilität: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33... |
| `dawn-raid-kartellbehoerde-sofortplan` | Dawn Raid Kartellbehörde Sofortplan: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff.,... |
| `de-minimis-inlandsauswirkung-fusionskontrolle` | De-minimis Inlandsauswirkung Fusionskontrolle: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a un... |
| `disclosure-33g-gwb-akteneinsicht` | Disclosure § 33g GWB Akteneinsicht: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 3... |
| `dma-schnittstelle-kartellrecht` | DMA Schnittstelle Kartellrecht: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff... |
| `dma-und-gatekeeper-markt` | Digital Markets Act (VO 2022/1925): Gatekeeper-Designierung Kernplattformdienste quantitative und qualitative Schwellenwerte. Auswirkungen der DMA-Designierung auf die Marktdefinition in kar... |
| `einkaufskooperation-nachfragemacht` | Einkaufskooperation Nachfragemacht: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 3... |
| `einstweiliger-rechtsschutz-kartellrecht` | Einstweiliger Rechtsschutz Kartellrecht: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 f... |
| `elastizitaeten-diversion-ratios` | Oekonomischer Gutachter oder Mandant legt Elastizitaetsdaten oder Diversion-Ratio-Analyse vor und Belastbarkeit ist zu prüfen. Prüft Eigenpreis-Elastizitaet Kreuzpreis-Elastizitaet und Diver... |
| `energiekartellrecht-netz-und-vertrieb` | Energiekartellrecht Netz und Vertrieb: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff.... |
| `eu-bekanntmachung-marktdefinition-2024` | Skill zur neuen EU-Kommissions-Bekanntmachung zur Marktdefinition (Februar 2024) und ihrer praktischen Anwendung. Vergleich zur Bekanntmachung von 1997. Neue Elemente: digitale Maerkte Innov... |
| `eu-fusionskontrolle-fkvo-zustaendigkeit` | EU-Fusionskontrolle FKVO Zuständigkeit: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff... |
| `eugh-rechtsprechung-leitentscheidungen` | Workflow-Skill zu eugh rechtsprechung leitentscheidungen. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Pruefung mit Gericht, Datum und Aktenzeichen. |
| `evidenz-qualitaet-bewertung` | Bewertet die Qualitaet und Belastbarkeit der vorgelegten Belege für eine Marktabgrenzung: interne Unternehmensdokumente Kundenverhaltensdaten Marktdaten Elastizitaeten Diversion Ratios Branc... |
| `exklusivitaetsrabatte-treuerabatte` | Exklusivitätsrabatte Treuerabatte: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33... |
| `follow-on-klage-bindungswirkung` | Follow-on Klage Bindungswirkung: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 f... |
| `franchise-vertrag-kartellrecht` | Franchise-Vertrag Kartellrecht: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff... |
| `freistellung-art-101-abs-3-aeuv-effizienz-verbraucheranteil` | Freistellung Art 101 Abs 3 AEUV Effizienz Verbraucheranteil: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18... |
| `fusionskontrolle-anmeldung-routing` | Workflow zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Fusionskontrolle Anmeldung Routing. |
| `fusionskontrolle-gwb-umsatzschwellen` | Fusionskontrolle GWB Umsatzschwellen: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff.,... |
| `fusionskontrolle-modus` | Prüft Marktabgrenzung im Kontext der EU-Fusionskontrolle (FKVO 139/2004): Phase I und Phase II SIEC-Test (Significant Impediment to Effective Competition) horizontale und nicht-horizontale F... |
| `geoblocking-und-kartellrecht-schnittstelle` | Geoblocking und Kartellrecht Schnittstelle: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 3... |
| `gesamtbewertung-tragfaehigkeit` | Gesamturteil zur Tragfähigkeit einer Marktabgrenzung: hoch mittel oder gering. Fasst zentrale Schwachstellen in 3 bis 5 scharfen Punkten zusammen. Bewertet Angreifbarkeit vor Gericht oder Be... |
| `geschaeftsleiterhaftung-kartellverstoss` | Geschäftsleiterhaftung Kartellverstoß: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff.... |
| `handelsvertreterprivileg-echtes-unechtes-agenturmodell` | Handelsvertreterprivileg echtes unechtes Agenturmodell: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 u... |
| `healthcare-kartellrecht-kooperation-kliniken` | Healthcare Kartellrecht Kooperation Kliniken: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und... |
| `horizontal-gvo-forschung-und-entwicklung` | Horizontal-GVO Forschung und Entwicklung: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32... |
| `horizontal-gvo-spezialisierung` | Horizontal-GVO Spezialisierung: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff... |
| `hub-and-spoke-kartell` | Hub-and-Spoke Kartell: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff., 35 ff.... |
| `informationsaustausch-wettbewerber` | Informationsaustausch Wettbewerber: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 3... |
| `innovations-und-technologiemaerkte` | Marktabgrenzung in dynamischen Technologiemaerkten wo kuenftige Innovation den Wettbewerb praegt oder Patent-Pools streitig sind. Prüft Innovationsmaerkte technologische Substitution Standar... |
| `kart-innovationswettbewerb-spezial` | Spezialfall Innovationswettbewerb und Killer Acquisitions: Pipeline-Produkte, Innovation Theory of Harm. Pruefraster fuer Fusionskontrollanmeldung. |
| `kart-marktanteilsanalyse-leitfaden` | Leitfaden Marktanteilsanalyse: Umsatz- und Mengenmarktanteile, HHI, Marktstrukturmerkmale. Pruefraster fuer Fusionskontrollmeldung. |
| `kart-marktdefinition-bauleiter` | Bauleiter Marktdefinition: sachlich, raeumlich, zeitlich. SSNIP-Test, Hypothetischer Monopolist, Mehrproduktmaerkte. Pruefraster fuer typische Branchen. |
| `kart-zweiseitige-plattformen-spezial` | Spezialfall zweiseitige Plattformen / Mehrseitige Maerkte: Netzwerkeffekte, Tipping, DMA-Gatekeeper. Pruefraster fuer Digitalplattformen. |
| `kartellrecht-kaltstart-mandat-neu` | Workflow zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Kartellrecht Kaltstart Mandat neu. |
| `kartellrechtliche-vertragsklausel-redline` | Kartellrechtliche Vertragsklausel-Redline: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32... |
| `kartellschadensersatz-33a-gwb` | Kartellschadensersatz § 33a GWB: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 f... |
| `kartellverbot-modus` | Workflow-Skill zu kartellverbot modus. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Pruefung mit Gericht, Datum und Aktenzeichen. |
| `ki-preisgestaltung-kartellrecht` | KI Preisgestaltung Kartellrecht: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 f... |
| `konsistenzpruefung-marktdefinition` | Prüft die interne Widerspruchsfreiheit einer Marktabgrenzung: Übereinstimmung von Sachmarkt und räumlichem Markt tatsaechlichem Marktverhalten Behoerdenpraxis und oekonomischen Grundprinzipi... |
| `kronzeugenprogramm-bonusregelung` | Kronzeugenprogramm Bonusregelung: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33... |
| `landwirtschaftliche-erzeugerkooperation` | Landwirtschaftliche Erzeugerkooperation: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 f... |
| `margin-squeeze-telekom-energie-plattform` | Margin Squeeze Telekom Energie Plattform: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32... |
| `marktabgrenzung-kontextanalyse` | Verfahren beginnt und Verfahrensart und Parteistellung muessen bestimmt werden bevor die Marktabgrenzung-Analyse starten kann. Identifiziert Verfahrensart Fusionskontrolle Kartellverbot Miss... |
| `mehrseitige-maerkte-plattformen` | Workflow-Skill zu mehrseitige maerkte plattformen. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Pruefung mit Gericht, Datum und Aktenzeichen. |
| `ministererlaubnis-42-gwb` | Ministererlaubnis § 42 GWB: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff., 3... |
| `missbrauchsverbot-modus` | Unternehmen in marktbeherrschender Stellung soll auf Missbrauch geprüft werden oder Wettbewerber klagt auf Missbrauch. Prüft Marktabgrenzung und Missbrauchstatbestaende Art. 102 AEUV § 19 GW... |
| `nachhaltigkeitskooperation-wettbewerbsrecht` | Nachhaltigkeitskooperation Wettbewerbsrecht: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und... |
| `nicht-horizontale-fusion-vertikal-konglomerat` | Nicht-horizontale Fusion vertikal konglomerat: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a un... |
| `paragraf-18-gwb-pruefung` | Prüft Marktbeherrschung nach Paragraf 18 GWB: Einzelmarktbeherrschung Abs 1 Marktanteils-Schwellen Abs 4 (40 Prozent) gemeinsame Marktbeherrschung Abs 5 und 6 intermediaere Plattformen Abs 3... |
| `passing-on-einwand-schadensweitergabe` | Passing-on Einwand Schadensweitergabe: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff.... |
| `potenzieller-wettbewerb-marktzutritt` | Behoerde oder Gegenseite argumentiert fehlende Markteintrittsbarrieren um Marktbeherrschung zu verneinen. Analysiert Markteintrittsschranken und Wahrscheinlichkeit potenziellen Wettbewerbs i... |
| `predatory-pricing-kampfpreise` | Predatory Pricing Kampfpreise: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff.... |
| `preisalgorithmen-kollusives-risiko` | Preisalgorithmen kollusives Risiko: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 3... |
| `preisbindung-der-zweiten-hand-rpm` | Preisbindung der zweiten Hand RPM: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33... |
| `presseverlage-plattformen-leistungsschutz-schnittstelle` | Presseverlage Plattformen Leistungsschutz Schnittstelle: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20... |
| `private-enforcement-schadensersatz-intake` | Workflow zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Private Enforcement Schadensersatz Intake. |
| `produktmarkt-angebotsumstellung` | Prüft angebotsseitige Substitution (Supply-Side Substitution): Kann ein anderer Anbieter kurzfristig und ohne erhebliche Kosten auf den relevanten Markt wechseln? Bewertet Umstellungskosten... |
| `produktmarkt-nachfragesubstitution` | Kernschritt jeder Marktabgrenzung: sachlicher Markt aus Nachfragersicht bestimmen. Prüft funktionale Austauschbarkeit Preisreagibilitaet qualitative Unterschiede Verwendungszweck Bedarfsdeck... |
| `raeumlicher-markt-abgrenzung` | Prüft den räumlich relevanten Markt: national europaeisch global. Analysiert Preisstrukturen Transportkosten regulatorische Unterschiede Homogenitaetsannahmen Handelsstroeme und Arbitragemoe... |
| `red-flags-checkliste` | Strukturierte Checkliste problematischer Muster in Marktabgrenzungen: ergebnisgetriebene Argumentation Zirkelschluesse fehlende oekonomische Fundierung selektive Datenwahl kuenstliche Marktv... |
| `refusal-to-supply-essential-facilities` | Refusal to Supply Essential Facilities: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff... |
| `remedies-zusagen-veraeusserung-zugang` | Remedies Zusagen Veräußerung Zugang: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff.,... |
| `sammelklagen-abtretungsmodelle-kartellschaden` | Sammelklagen Abtretungsmodelle Kartellschaden: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a un... |
| `schiedsverfahren-kartellrecht-einwand-nichtigkeit` | Schiedsverfahren Kartellrecht Einwand Nichtigkeit: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19... |
| `selektivvertrieb-luxus-internetplattform` | Selektivvertrieb Luxus Internetplattform: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32... |
| `self-preferencing-plattformen` | Self-Preferencing Plattformen: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff.... |
| `sep-frand-kartellrecht` | SEP FRAND Kartellrecht: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff., 35 ff... |
| `siec-test-horizontale-fusion` | SIEC-Test horizontale Fusion: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: Art. 101/102 AEUV, GWB §§ 1 und 18-20 und 19a und 32 ff., 33 ff.,... |
| `spezial-aeuv-behoerden-gericht-und-registerweg` | Aeuv: Behörden-, Gerichts- oder Registerweg: konkreter Spezialworkflow mit Sachverhaltsklärung, Rechtsrahmen, Belegen, Risikoampel und verwertbarem Output. |

Weitere Skills: insgesamt 125 Anschluss-Skills in diesem Plugin.

<!-- END ACTUAL-SKILL-ROUTING -->
