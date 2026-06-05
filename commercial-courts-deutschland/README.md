# commercial-courts-deutschland

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`commercial-courts-deutschland`) | [`commercial-courts-deutschland.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/commercial-courts-deutschland.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

> Prozessarbeitsplatz für englischsprachige Wirtschaftsverfahren vor deutschen Commercial Courts und Commercial Chambers. Das Plugin hilft bei Forumwahl, Klage, Verteidigung, Case Management, Beweis, Geheimnisschutz, Wortprotokoll, Rechtsmittel, Kosten, Vollstreckung und bilingualer Mandantenkommunikation.

## Wofür dieses Plugin gedacht ist

Commercial Courts sollen internationale Wirtschaftsverfahren in Deutschland attraktiver machen. Dieses Plugin macht daraus einen geführten Arbeitsablauf: nicht Common Law spielen, sondern deutsches Prozessrecht in englischer Arbeitssprache präzise beherrschen.

Es unterstützt insbesondere:

- englische oder zweisprachige Schriftsatzentwürfe,
- Forum- und Klauselprüfung,
- Zuständigkeits- und Sprachwahlprüfung,
- Case-Management-Termin und Timetable,
- Beweis- und Anlagenorganisation,
- Geheimnisschutz und vertrauliche Anlagen,
- Wortprotokoll/verbatim transcript,
- Rechtsmittel und BGH-Fortsetzung,
- Board- und Mandantenbriefings in DE/EN.

## Kaltstart

Der Einstieg fragt zuerst:

1. Deutsch, Englisch oder zweisprachig?
2. Commercial Court, Commercial Chamber, Schiedsgericht oder anderes Forum?
3. Welche Klausel und welcher Streitwert?
4. Was ist die nächste Prozesshandlung?
5. Welche Anlagen und Fristen liegen vor?

Danach routet er in die passenden Spezialskills.

## Typische Outputs

- English Statement of Claim / Statement of Defence
- Case Management Conference Pack
- Procedural Timetable
- Evidence Map und Exhibit Index
- Confidentiality Application
- Verbatim Transcript Request Strategy
- Hearing Script
- Settlement Term Sheet
- Appeal/Revision Memo
- Board Briefing DE/EN

## Quellenhygiene

Vor produktiver Verwendung müssen Bundesrecht, Landesrecht und Gerichtsseite live geprüft werden. Dieses Plugin nennt keine erfundenen Commercial-Court-Standorte und keine Paywall-Fundstellen. Rechtsprechung wird nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle ausgegeben.

## Verhältnis zu anderen Plugins

- `prozessrecht`: allgemeine ZPO-Mechanik.
- `word-legal-ai-plugin-and-skill-for-german-lawyers`: Schriftsatz- und Stilfinish.
- `gesellschaftsrecht-legal-english`: Transaktionsenglisch und Corporate-Begriffe.
- `common-law-kompass`: falsche Freunde bei Common-Law-Erwartungen.
- `zitierweise-deutsches-recht`: Quellen- und Zitierhygiene.

## Skills

| Skill | Funktion |
| --- | --- |
| `commercial-courts-deutschland-allgemein` | Einstieg, Schnelltriage und Workflow-Routing für Commercial-Courts-Verfahren in Deutschland; erkennt Forum, Sprache, Streitwert, Parteivereinbarung, Case Management, Geheimnisschutz, Beweis, Transcript, Rechtsmittel und englischen Outputbedarf. |
| `commercial-court-kaltstart-interview` | Kaltstart-Interview für neue Commercial-Court-Mandate: Parteien, Streitgegenstand, Streitwert, Gerichtsstands-/Sprachklausel, gewünschte Sprache, Unterlagen, Fristen, Output. |
| `zustandigkeit-119b-gvg-check` | Prüft, ob Commercial Court oder Commercial Chamber eröffnet ist: Wirtschaftsstreitigkeit, Streitwert, Parteivereinbarung, Landesrecht, OLG/LG, internationale Zuständigkeit und Rügefragen. |
| `commercial-chamber-vs-commercial-court` | Vergleicht Commercial Chamber beim Landgericht und Commercial Court beim Oberlandesgericht: Instanz, Zuständigkeit, Streitwert, Verfahrenssprache, Tempo, Rechtsmittel und Mandantenstrategie. |
| `forumwahl-commercial-court-vs-schiedsgericht` | Vergleicht Commercial Court, ordentliche Kammer, Schiedsgericht, DIS/ICC/LCIA und Gerichtsstandsvereinbarung; Output ist eine Vorstandsvorlage mit Empfehlung. |
| `englische-verfahrenssprache-184a-gvg` | Prüft und gestaltet die englische Verfahrenssprache: Parteivereinbarung, Schriftsätze, Anlagen, mündliche Verhandlung, Protokoll, Urteil, Übersetzungen und BGH-Fortsetzung. |
| `jurisdiction-clause-drafting-de-en` | Entwirft deutsch-englische Commercial-Court-Gerichtsstands- und Sprachklauseln für Verträge, AGB-nahe Konstellationen und M&A/Finance-Deals. |
| `pre-litigation-notice-and-standstill` | Bereitet Pre-Action Letter, Standstill Agreement und Verjährungshemmung vor, wenn ein Commercial-Court-Verfahren droht. |
| `claim-intake-fakten-und-exhibits` | Macht aus unordentlichen Deal-Unterlagen ein Claim Intake: Parteien, Vertrag, Breach, Damages, Exhibits, Timeline und Streitwert. |
| `klageschrift-english-statement-of-claim` | Erstellt eine englische Commercial-Court-Klageschrift mit deutschem ZPO-Unterbau: parties, jurisdiction, facts, causes of action, relief sought, evidence und exhibits. |
| `defence-answer-and-jurisdiction-objections` | Bereitet Klageerwiderung/Statement of Defence vor: Zuständigkeitsrügen, Sprachrügen, Bestreiten, Einwendungen, Counterclaim, Set-off und Beweise. |
| `ruegelose-einlassung-und-sprache` | Warnt vor rügeloser Einlassung: Zuständigkeit, Sprache, Einlassungsfrist, Verteidigungsanzeige, Prozessstrategie und Mandantenfreigabe. |
| `case-management-conference` | Bereitet Case-Management-Termin vor: issues list, timetable, evidence, confidentiality, settlement, transcript, language and hearing logistics. |
| `procedural-calendar-timetable-order` | Erstellt einen prozessualen Verfahrenskalender mit Schriftsatzfristen, Anlagen, Übersetzungen, Witness Statements, Sachverständigen und Hearing Date. |
| `issues-list-and-roadmap` | Formuliert eine Issues List für Commercial-Court-Verfahren: legal issues, factual issues, evidence issues, quantum, jurisdiction and language. |
| `evidence-map-zpo-vs-common-law` | Erklärt Mandanten den Unterschied zwischen deutscher Beweisaufnahme und Common-Law-Erwartungen; erstellt Evidence Map ohne Discovery-Fantasien. |
| `document-production-142-zpo` | Prüft Urkundenvorlage und Dokumentenherausgabe nach deutschem Prozessrecht im Commercial-Court-Kontext: § 142 ZPO, Substantiierung, Geheimnisse, proportionality. |
| `exhibits-translation-608-zpo` | Plant Anlagen, Übersetzungen und Sprache: welche Dokumente englisch bleiben können, wann Übersetzung nötig ist, wie Exhibit Index und Bundle aussehen. |
| `third-party-notice-607-zpo` | Prüft Streitverkündung, Nebenintervention und Drittbeteiligung bei englischsprachigen Commercial-Court-Verfahren. |
| `confidentiality-trade-secrets-273a-zpo` | Schützt Geschäftsgeheimnisse: Geheimhaltungsantrag, abgestufter Zugang, redacted exhibits, in camera concerns, Trade Secrets Act und Prozessstrategie. |
| `public-hearing-and-press` | Steuert Öffentlichkeit, Presse, Public Relations und sensitive Unternehmenskommunikation bei hochkarätigen Commercial-Court-Verfahren. |
| `video-hearing-128a-284-zpo` | Prüft Videoverhandlung, hybride Beweisaufnahme, ausländische Zeugen, Techniktest und Protokollierung. |
| `verbatim-transcript-613-zpo` | Plant das Wortprotokoll/verbatim transcript: Antrag, Kosten, Verhandlungsstrategie, Korrektur, Zitierfähigkeit und Nutzung im Rechtsmittel. |
| `hearing-script-english-advocacy` | Erstellt englische Hearing Scripts für deutsche Anwälte: opening, issue roadmap, witness questions, judicial questions, closing and settlement signals. |
| `witness-preparation-english-zpo` | Bereitet Zeugen in englischsprachigen deutschen Verfahren vor: Wahrheitspflicht, keine Coaching-Grenzüberschreitung, Sprachsicherheit, Dokumente, Ablauf. |
| `expert-evidence-german-court-expert` | Plant Sachverständigenbeweis: Privatgutachten, gerichtlicher Sachverständiger, Fragenkatalog, technische Anlagen, Parteigutachten und Anhörung. |
| `interim-relief-arrest-injunction` | Prüft einstweilige Verfügung, Arrest und interim relief im Commercial-Court-Umfeld, einschließlich Eilbedürftigkeit, Sicherheitsleistung und Vollziehung. |
| `settlement-court-recorded-settlement` | Bereitet gerichtlichen Vergleich, settlement agreement, consent order, Vollstreckbarkeit und mehrsprachige Vergleichsdokumentation vor. |
| `enforcement-and-translation` | Prüft Vollstreckung aus Commercial-Court-Urteilen/Vergleichen: Titel, Klausel, Zustellung, Übersetzung, EU-/Auslandsbezug und assets. |
| `appeal-and-revision-614-zpo` | Prüft Rechtsmittel und Revision/BGH-Pfad nach Commercial-Court-Verfahren: Zulassung, Sprache, Transcript, Tatbestand, Rechtsfehler und Strategie. |
| `bgh-english-proceedings-184b-gvg` | Routet englischsprachige Fortführung vor dem Bundesgerichtshof: Voraussetzungen, Übersetzungen, Revisionsbegründung, Tenor und Mandantenkommunikation. |
| `costs-court-fees-risk-budget` | Erstellt Kosten- und Risikobudget: Gerichtskosten, Anwaltskosten, Übersetzung, Transcript, Sachverständige, Security, Settlement und Enforcement. |
| `service-abroad-hague-eu` | Plant Zustellung ins Ausland: EuZVO, Haager Zustellungsübereinkommen, Übersetzung, service agents, Fristen und Nachweis. |
| `cross-border-jurisdiction-brussels-ia` | Prüft internationale Zuständigkeit, Gerichtsstandsvereinbarung, Brüssel Ia, Lugano-Bezug, Drittstaaten und Anti-suit-/lis-pendens-Risiken. |
| `governing-law-rome-i-ii` | Prüft anwendbares Recht: Rom I/Rom II, Rechtswahl, Eingriffsnormen, UN-Kaufrecht, Beweis fremden Rechts und Übersetzung der Normbegriffe. |
| `post-ma-warranty-claim` | Bearbeitet Post-M&A Warranty Claims vor Commercial Courts: notice, knowledge qualifiers, baskets, caps, leakage, earn-out, accounts and expert determination. |
| `earn-out-accounting-dispute` | Strukturiert Earn-out- und Kaufpreisanpassungsstreitigkeiten: accounting principles, expert determination, disclosure, damages and procedural tactics. |
| `shareholder-board-dispute` | Bearbeitet Gesellschafter-, Organ- und Joint-Venture-Streitigkeiten mit englischen Vertragsunterlagen vor deutschen Commercial Courts. |
| `director-officer-liability-dispute` | Prüft D&O-/Organhaftungsstreitigkeiten im Commercial-Court-Kontext: business judgment, damages, insurance, privilege-like concerns and evidence. |
| `supply-chain-international-sale-dispute` | Routet Lieferketten-, Vertrieb- und CISG-nahe Streitigkeiten: delivery, defects, force majeure, limitation, governing law and evidence. |
| `finance-banking-dispute` | Bearbeitet Finance-, Banking- und Capital-Markets-Streitigkeiten mit englischen Dokumenten: facility agreement, covenants, events of default, security, notices. |
| `contract-interpretation-de-en` | Erklärt und prüft englische Vertragsbegriffe unter deutschem Recht: reasonable efforts, best endeavours, indemnity, warranty, termination, material adverse change. |
| `english-legal-writing-for-german-courts` | Verbessert englische Schriftsätze für deutsche Gerichte: klar, zpo-tauglich, ohne US-Discovery-Duktus, mit sauberem Tatsachenvortrag und Beweisangebot. |
| `bilingual-client-board-briefing` | Erstellt bilinguale Board- und Mandantenbriefings zu Commercial-Court-Verfahren: risk, timeline, budget, settlement range, next decisions. |
| `bundle-index-electronic-filing` | Organisiert elektronisches Bundle, Anlagenindex, beA/ERV-Dateinamen, PDF/A, Lesezeichen, Übersetzungen und Exhibit References. |
| `bea-erv-english-pleadings` | Prüft beA/ERV-Einreichung englischer Schriftsätze: Dateiformat, Signatur, Anlagen, Fristen, Empfangsbekenntnis und Kanzlei-Workflow. |
| `protective-measures-confidential-exhibits` | Plant Schutzmaßnahmen für vertrauliche Anlagen: redactions, confidentiality club, restricted access, sealed bundles und Verhandlungsorganisation. |
| `mediation-settlement-window` | Findet Vergleichsfenster, Mediation, judicial settlement signals und Prozessvergleichsstrategie in Commercial-Court-Verfahren. |
| `arbitration-clause-conflict-check` | Prüft Konflikte zwischen Schieds-, Gerichtsstands-, Escalation- und Commercial-Court-Klauseln. |
| `limitation-and-tolling-check` | Prüft Verjährung, Hemmung, Standstill, Klageerhebung, Zustellung demnächst und internationale Limitation Issues. |
| `counterclaim-setoff-claim-amendment` | Plant Widerklage, Hilfswiderklage, Aufrechnung, Klageänderung und amendment strategy in englischsprachigen Wirtschaftsprozessen. |
| `default-judgment-and-nonappearance` | Prüft Versäumnis, Anerkenntnis, Säumnisfolgen, Einspruch und taktische Nichtteilnahme in Commercial-Court-Verfahren. |
| `late-submissions-296-zpo` | Steuert verspätetes Vorbringen, Präklusion, Fristverlängerung, gerichtliche Hinweise und Schriftsatznachlass. |
| `local-rules-and-court-guidelines` | Erstellt Live-Check zu Landesrecht, Geschäftsverteilung, Commercial-Court-Guidelines und Gerichts-Webseite vor jeder Einreichung. |
| `redteam-commercial-court-qualitygate` | Red-Team-Gate für alle Commercial-Court-Outputs: Zuständigkeit, Sprache, Fristen, Beweise, Übersetzungen, Geheimnisschutz, Kosten, Rechtsmittel. |
| `glossary-commercial-court-de-en` | Erstellt ein DE/EN-Glossar für Commercial-Court-Mandate: ZPO-Begriffe, Anträge, Beweis, Tenor, Vergleich, Rechtsmittel und falsche Freunde. |
| `judgment-publication-and-anonymisation` | Prüft Urteil, Veröffentlichung, Anonymisierung, Geheimnisschutz, Übersetzungsbedarf und externe Kommunikation nach Entscheidung. |

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 30 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `arbitration-clause-bea-erv` | Arbitration Clause BEA ERV im Commercial Courts in Deutschland: prüft konkret Prüft Konflikte zwischen Schieds-, Gerichtsstands-, Escalation- und Commercial-C, Prüft beA/ERV-Einreichung englischer Schriftsätze. Liefert priorisierten Outp... |
| `bgh-english-bilingual-client` | BGH English Bilingual Client im Commercial Courts in Deutschland: prüft konkret Routet englischsprachige Fortführung vor dem, Erstellt bilinguale Board- und Mandantenbriefings zu. Liefert priorisierten Output mit Norm-Pinpoints, Risikoam... |
| `bundle-index-case-management` | Bundle Index Case Management im Commercial Courts in Deutschland: prüft konkret Organisiert elektronisches Bundle, Anlagenindex, beA/ERV-Dateinamen, PDF/A. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `claim-intake-chamber-vs` | Claim Intake Chamber VS im Commercial Courts in Deutschland: prüft konkret Macht aus unordentlichen Deal-Unterlagen ein Claim Intake, Vergleicht Commercial Chamber beim Landgericht und. Liefert priorisierten Output mit Norm-Pinpoints, Ri... |
| `commercial-court-kaltstart-interview` | Kaltstart-Interview für neue Commercial-Court-Mandate: Parteien, Streitgegenstand, Streitwert, Gerichtsstands-/Sprachklausel, gewünschte Sprache, Unterlagen, Fristen, Output. |
| `commercial-courts-deutschland-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting für Commercial-Courts-Verfahren in Deutschland; erkennt Forum, Sprache, Streitwert, Parteivereinbarung, Case Management, Geheimnisschutz, Beweis, Transcript, Rechtsmittel und englischen Outputbedarf. |
| `confidentiality-trade-contract-interpretation` | Confidentiality Trade Contract Interpretation im Commercial Courts in Deutschland: prüft konkret Schützt Geschäftsgeheimnisse, Erklärt und prüft englische Vertragsbegriffe unter. Liefert priorisierten Output mit Norm-Pinpoints, Risikoamp... |
| `costs-court-counterclaim-setoff` | Costs Court Counterclaim Setoff im Commercial Courts in Deutschland: prüft konkret Erstellt Kosten- und Risikobudget, Plant Widerklage, Hilfswiderklage, Aufrechnung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächst... |
| `cross-border-default-judgment` | Cross Border Default Judgment im Commercial Courts in Deutschland: prüft konkret Prüft internationale Zuständigkeit, Gerichtsstandsvereinbarung, Brüssel Ia, Luga. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem... |
| `defence-answer-director-officer` | Defence Answer Director Officer im Commercial Courts in Deutschland: prüft konkret Bereitet Klageerwiderung/Statement of Defence vor, Prüft D&O-/Organhaftungsstreitigkeiten im. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel... |
| `document-production-earn-out` | Document Production Earn OUT im Commercial Courts in Deutschland: prüft konkret Prüft Urkundenvorlage und Dokumentenherausgabe nach, Strukturiert Earn-out- und Kaufpreisanpassungsstreitigkeiten. Liefert priorisierten Output mit Norm-Pinp... |
| `enforcement-translation-english-legal` | Enforcement Translation English Legal im Commercial Courts in Deutschland: prüft konkret Prüft Vollstreckung aus, Verbessert englische Schriftsätze für deutsche Gerichte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und n... |
| `englische-verfahrenssprache-late-submissions` | Englische Verfahrenssprache Late Submissions im Commercial Courts in Deutschland: prüft konkret Prüft und gestaltet die englische Verfahrenssprache, Steuert verspätetes Vorbringen, Präklusion, Fristverlängerung. Liefert priorisierten Out... |
| `evidence-map-exhibits-translation` | Evidence MAP Exhibits Translation im Commercial Courts in Deutschland: prüft konkret Erklärt Mandanten den Unterschied zwischen deutscher, Plant Anlagen, Übersetzungen und Sprache. Liefert priorisierten Output mit Norm-Pinpoints, Risikoa... |
| `expert-evidence-finance-banking` | Expert Evidence Finance Banking im Commercial Courts in Deutschland: prüft konkret Plant Sachverständigenbeweis, Bearbeitet Finance-, Banking- und Capital-Markets-Streitigkeiten mit englischen. Liefert priorisierten Output mit Norm-Pinpo... |
| `forumwahl-court-glossary` | Forumwahl Court Glossary im Commercial Courts in Deutschland: prüft konkret Vergleicht Commercial Court, ordentliche Kammer, Schiedsgericht, DIS/ICC/LCIA un. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `governing-law-hearing-script` | Governing LAW Hearing Script im Commercial Courts in Deutschland: prüft konkret Prüft anwendbares Recht, Erstellt englische Hearing Scripts für deutsche Anwälte. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem S... |
| `interim-relief-issues-list` | Interim Relief Issues List im Commercial Courts in Deutschland: prüft konkret Prüft einstweilige Verfügung, Arrest und interim relief im Commercial-Court-Umfe, Formuliert eine Issues List für Commercial-Court-Verfahren. Liefert priorisie... |
| `judgment-publication-jurisdiction-clause` | Judgment Publication Jurisdiction Clause im Commercial Courts in Deutschland: prüft konkret Prüft Urteil, Veröffentlichung, Anonymisierung, Geheimnisschutz. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `klageschrift-english-limitation-tolling` | Klageschrift English Limitation Tolling im Commercial Courts in Deutschland: prüft konkret Erstellt eine englische Commercial-Court-Klageschrift mit, Prüft Verjährung, Hemmung, Standstill. Liefert priorisierten Output mit Norm-Pinpoints,... |
| `local-rules-mediation-settlement` | Local Rules Mediation Settlement im Commercial Courts in Deutschland: prüft konkret Erstellt Live-Check zu Landesrecht, Geschäftsverteilung, Commercial-Court-Guidel, Findet Vergleichsfenster. Liefert priorisierten Output mit Norm-Pinpoin... |
| `post-ma-pre-litigation` | Post MA PRE Litigation im Commercial Courts in Deutschland: prüft konkret Bearbeitet Post-M&A Warranty Claims vor Commercial Courts, Bereitet Pre-Action Letter, Standstill Agreement und Verjährungshemmung vor, wen. Liefert priorisierten... |
| `procedural-calendar-protective-measures` | Procedural Calendar Protective Measures im Commercial Courts in Deutschland: prüft konkret Erstellt einen prozessualen Verfahrenskalender mit, Anlagen, Plant Schutzmaßnahmen für vertrauliche Anlagen. Liefert priorisierten Output mit Norm... |
| `public-hearing-appeal-revision` | Public Hearing Appeal Revision im Commercial Courts in Deutschland: prüft konkret Steuert Öffentlichkeit, Presse, Public Relations und sensitive Unternehmenskommu, Prüft Rechtsmittel und Revision/BGH-Pfad nach. Liefert priorisierten Outp... |
| `redteam-commercial-court-qualitygate` | Red-Team-Gate für alle Commercial-Court-Outputs: Zuständigkeit, Sprache, Fristen, Beweise, Übersetzungen, Geheimnisschutz, Kosten, Rechtsmittel. |
| `ruegelose-einlassung-service-abroad` | Ruegelose Einlassung Service Abroad im Commercial Courts in Deutschland: prüft konkret Warnt vor rügeloser Einlassung, Plant Zustellung ins Ausland. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `settlement-court-shareholder-board` | Settlement Court Shareholder Board im Commercial Courts in Deutschland: prüft konkret Bereitet gerichtlichen Vergleich, settlement agreement, consent order, Vollstrec. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näch... |
| `supply-chain-third-party` | Supply Chain Third Party im Commercial Courts in Deutschland: prüft konkret Routet Lieferketten-, Vertrieb- und CISG-nahe Streitigkeiten, Prüft Streitverkündung, Nebenintervention und Drittbeteiligung bei englischsprac. Liefert priorisie... |
| `verbatim-transcript-video-hearing` | Verbatim Transcript Video Hearing im Commercial Courts in Deutschland: prüft konkret Plant das Wortprotokoll/verbatim transcript, Prüft Videoverhandlung, hybride Beweisaufnahme, ausländische Zeugen. Liefert priorisierten Output mit Norm-... |
| `witness-preparation-zustandigkeit-119b` | Witness Preparation Zustandigkeit 119b im Commercial Courts in Deutschland: prüft konkret Bereitet Zeugen in englischsprachigen deutschen Verfahren, Prüft, ob Commercial Court oder Commercial Chamber eröffnet ist. Liefert priorisierten O... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
