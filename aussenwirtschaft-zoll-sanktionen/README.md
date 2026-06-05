# Außenwirtschaft, Sanktionen, Zoll und CBAM

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`aussenwirtschaft-zoll-sanktionen`) | [`aussenwirtschaft-zoll-sanktionen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/aussenwirtschaft-zoll-sanktionen.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Waldkrone HealthTech GmbH - NDA, Meldekanal und Lieferantenhinweis** (`hinweisgeberschutz-nda-meldekanal-waldkrone`) | [Gesamt-PDF lesen](../testakten/hinweisgeberschutz-nda-meldekanal-waldkrone/gesamt-pdf/hinweisgeberschutz-nda-meldekanal-waldkrone_gesamt.pdf) | [`testakte-hinweisgeberschutz-nda-meldekanal-waldkrone.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-hinweisgeberschutz-nda-meldekanal-waldkrone.zip) |
| **Akte Vellbruck Robotics GmbH — Roboterflotte AtlasCare / LumaMove / Werkbank C7** (`robotikrecht-roboterflotte-vellbruck-muenchen`) | [Gesamt-PDF lesen](../testakten/robotikrecht-roboterflotte-vellbruck-muenchen/gesamt-pdf/robotikrecht-roboterflotte-vellbruck-muenchen_gesamt.pdf) | [`testakte-robotikrecht-roboterflotte-vellbruck-muenchen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-robotikrecht-roboterflotte-vellbruck-muenchen.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Außenwirtschafts-, Sanktions-, Zoll- und CBAM-Plugin für international tätige Unternehmen, Einzelpersonen, Verbände, Import-/Exportabteilungen, Zollteams, Compliance, Geschäftsleitung und anwaltliche Krisenmandate.

Dieses Plugin ist **vollständig freistehend**. Es verweist nicht auf andere Plugins und bringt eigene Skills, Vorlagen, Leitplanken, Vorschau und Testakte mit. Wenn keine Schnittstelle zu ERP, Zollsoftware, Screening-Tool, CBAM-Register, ELAN-K2, Bundesbank-Portal oder Kanzleisystem besteht, arbeitet es mit manuellen Uploads oder einem ausdrücklich gekennzeichneten Simulationsmodus.

#

## Schnellstart

1. Plugin aktivieren oder ZIP aus dem Release installieren.
2. Neue Sache mit `aussenwirtschaft-kommandocenter` starten.
3. Ware, Software, Technologie, Dienstleistung oder Zahlung nennen.
4. Länder, Beteiligte, Banken, Endverwender, Zolltarifnummer und vorhandene Dokumente hochladen oder simulieren.
5. Am Ende immer das Qualitätstor ausgeben lassen: Quellenstand, Trefferlog, Fristen, Verbote, Genehmigungen, Meldungen, Abgaben, Anlagen und Sofortmaßnahmen.

## Enthaltene Skills

- `aussenwirtschaft-kommandocenter` - Außenwirtschaft-Kommandocenter
- `aussenwirtschaft-exportkontrolle-dual-use` - Exportkontrolle und Dual-Use
- `aussenwirtschaft-gueterlisten-klassifizierung` - Güterlisten- und Klassifizierungslog
- `aussenwirtschaft-bafa-genehmigungen` - BAFA-Genehmigungen und Anfragen
- `aussenwirtschaft-sanktionen-embargos` - Sanktionen, Embargos und Bereitstellungsverbote
- `aussenwirtschaft-us-ear-itar` - US EAR, ITAR und Extraterritorialität
- `aussenwirtschaft-zolltarif-vzta` - Zolltarif, TARIC und vZTA
- `aussenwirtschaft-zollwert-ursprung` - Zollwert, Ursprung und Präferenzen
- `aussenwirtschaft-zollverfahren-bewilligungen` - Zollverfahren, Bewilligungen und Vereinfachungen
- `aussenwirtschaft-vub-einfuhr-ausfuhr` - Verbote und Beschränkungen bei Ein- und Ausfuhr
- `aussenwirtschaft-cbam-co2-zoll` - CBAM und CO2-Grenzausgleich
- `aussenwirtschaft-verbrauchsteuer` - Verbrauchsteuer
- `aussenwirtschaft-antidumping-ausgleich` - Antidumping- und Ausgleichszölle
- `aussenwirtschaft-wto-handelspolitik` - WTO und handelspolitische Maßnahmen
- `aussenwirtschaft-awv-bundesbank` - AWV- und Bundesbank-Meldepflichten
- `aussenwirtschaft-aml-kyc-sanktionen` - AML, KYC und Sanktions-Compliance
- `aussenwirtschaft-pruefung-ermittlung` - Prüfungen, Ermittlungen und Offenlegung
- `aussenwirtschaft-presse-krise` - Presse, Reputation und Krisenkommunikation
- `aussenwirtschaft-icp-kontrollsystem` - Internal Compliance Program

## Vorlagen

- `assets/templates/aussenwirtschaft-mandatskarte.md` - Außenwirtschaft-Mandatskarte
- `assets/templates/transaction-screening-matrix.md` - Transaktions-Screening-Matrix
- `assets/templates/exportkontrolle-dual-use-pruefung.md` - Exportkontrolle- und Dual-Use-Prüfung
- `assets/templates/gueterlisten-klassifizierungslog.md` - Güterlisten-Klassifizierungslog
- `assets/templates/bafa-genehmigungsantrag.md` - BAFA-Genehmigungs- und Anfragepaket
- `assets/templates/sanktions-embargo-trefferlog.md` - Sanktions- und Embargo-Trefferlog
- `assets/templates/us-ear-itar-touchpoint.md` - US EAR/ITAR-Touchpoint-Check
- `assets/templates/zolltarif-vzta-antrag.md` - Zolltarif- und vZTA-Antrag
- `assets/templates/zollwert-ursprung-praeferenz.md` - Zollwert, Ursprung und Präferenzmatrix
- `assets/templates/zollverfahren-bewilligungen.md` - Zollverfahren- und Bewilligungsmatrix
- `assets/templates/vub-einfuhr-ausfuhr.md` - VuB-Check Einfuhr/Ausfuhr
- `assets/templates/cbam-emissionsdaten-register.md` - CBAM-Emissionsdatenregister
- `assets/templates/verbrauchsteuer-bewilligung.md` - Verbrauchsteuer-Bewilligungs- und Entlastungscheck
- `assets/templates/antidumping-ausgleichszoll-check.md` - Antidumping- und Ausgleichszollcheck
- `assets/templates/wto-handelspolitik-memo.md` - WTO- und Handelspolitik-Memo
- `assets/templates/awv-bundesbank-meldekalender.md` - AWV-Bundesbank-Meldekalender
- `assets/templates/aml-kyc-sanktions-risk-assessment.md` - AML/KYC- und Sanktions-Risikoanalyse
- `assets/templates/pruefung-ermittlung-sofortplan.md` - Prüfungs- und Ermittlungs-Sofortplan
- `assets/templates/offenlegung-verstoss-plan.md` - Offenlegungs- und Nachholplan
- `assets/templates/presse-krisenkommunikation.md` - Presse- und Krisenkommunikationskarte
- `assets/templates/icp-kontrollsystem.md` - Internal-Compliance-Program-Blueprint

## Offizielle Startquellen

- [BAFA Exportkontrolle](https://www.bafa.de/DE/Aussenwirtschaft/Ausfuhrkontrolle/Allgemeine_Einfuehrung/allgemeine_einfuehrung.html)
- [BAFA Embargos und Namenslistenhinweise](https://www.bafa.de/DE/Aussenwirtschaft/Ausfuhrkontrolle/Embargos/embargos.html)
- [EU Sanctions Map und konsolidierte Finanzsanktionsliste](https://finance.ec.europa.eu/eu-and-world/sanctions-restrictive-measures/overview-sanctions-and-related-resources_en)
- [EU TARIC](https://taxation-customs.ec.europa.eu/customs/common-customs-tariff-cct/tariff-classification-goods/eu-customs-tariff-taric_de)
- [EU CBAM](https://taxation-customs.ec.europa.eu/carbon-border-adjustment-mechanism_en)
- [Deutsche Bundesbank AWV-Zahlungsmeldungen](https://www.bundesbank.de/de/service/meldewesen/aussenwirtschaft-formular-center/zahlungsmeldungen)
- [EU Trade Defence Antidumping](https://policy.trade.ec.europa.eu/enforcement-and-protection/trade-defence/anti-dumping-measures_en)
- [Zoll Verbrauchsteuererhebung](https://www.zoll.de/DE/Der-Zoll/Aufgaben-des-Zolls/Einnahmen-fuer-Deutschland-und-Europa/Verbrauchsteuererhebung/verbrauchsteuererhebung.html)

## Freistehende Leitplanken

- Keine Entscheidung auf Basis eingebauter Altdaten: Sanktionen, Embargos, TARIC, CBAM und AWV werden live oder mit dokumentiertem Abrufstand geprüft.
- Keine Sanktionsfreigabe ohne Trefferlog, Eigentum/Kontrolle, Umgehungsprüfung und Freigabeprozess.
- Keine Exportkontrollfreigabe ohne Produktdaten, technische Spezifikation, Güterlistenprüfung, Endverwendung und Endverwender.
- Keine Zollfreigabe ohne Einreihung, Ursprung, Zollwert, Dokumentencodes und TARIC-Maßnahmen.
- Keine CBAM-Aussage ohne Warencode, Warenmenge, Emissionsdatenquelle und sichtbare Annahmen.
- Bei Prüfung, Anhörung, Durchsuchung, Presseanfrage oder möglichem Verstoß: erst Legal Hold, Zuständigkeiten und Verteidigungsstrategie.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `asset-freeze-atlas-ausfuhranmeldung-audit` | Asset Freeze Atlas Ausfuhranmeldung Audit im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Sofortmassnahmen bei Verdacht auf sanktionierten Besitz, Qualitaetssicherung und Fehleranalyse von, Aufbau und Pflege revisionssichere... |
| `aussenwirtschaft-aml-kyc-finanzsanktionen` | AML KYC Finanzsanktionen im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Schnittstelle von AML/KYC-Pflichten und Sanktionsrecht, Pruefung von Eigentum und Kontrolle sanktionierter Personen, Ueberblick und Triage ueber EU-San... |
| `aussenwirtschaft-bafa-genehmigungen-cbam-co2` | Bafa Genehmigungen Cbam CO2 im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret BAFA-Exportgenehmigungsverfahren fuer Dual-Use-Gueter und, Carbon Border Adjustment Mechanism (CBAM), Kosten und Beschaffung von CBAM-Zertifikaten a... |
| `aussenwirtschaft-chemikalien-reach-cites` | Chemikalien Reach Cites im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret REACH-Konformitaet und PIC-Verfahren (Prior Informed, Artenschutz-Pflichten bei Im- und Export von, Exportkontrolle im Hochschul- und Forschungskontext,... |
| `aussenwirtschaft-embargo-iran-myanmar` | Embargo Iran Myanmar im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret EU-Iran-Sanktionsregime nach VO (EU) 267/2012 (Nuklear) und, EU-Myanmar-Sanktionsregime nach VO (EU) 401/2013 und, EU- und UN-Sanktionsregime gegen Nordkor... |
| `aussenwirtschaft-embargo-syrien-endverwendung` | Embargo Syrien Endverwendung im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret EU-Syrien-Sanktionsregime nach VO (EU) 36/2012 und, Endverwender-Pruefung und End-Use-Certificate (EUC), EORI-Nummer-Registrierung und Stammdatenpf... |
| `aussenwirtschaft-ersatzteile-dual-exporteur` | Ersatzteile Dual Exporteur im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Exportkontrollpruefung fuer Ersatzteile und Komponenten mit, Abgrenzung der Rollen Exporteur, Ausfuehrer und Zollanmelder nach UZK Art, Dual-Use-Prue... |
| `aussenwirtschaft-financial-institutions` | Financial Institutions im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Sanktions-Compliance fuer Banken und Finanzinstitute im, Strategische und operative Vorbereitung einer freiwilligen, Technische Klassifizierung von Waren... |
| `aussenwirtschaft-kontingente-lizenzen` | Kontingente Lizenzen im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Verwaltung von Zollkontingenten und Tariff-Rate-Quotas, Investitionspruefung bei Erwerb kritischer Infrastruktur, Rechtliche Anforderungen bei grenzuebersc... |
| `aussenwirtschaft-presse-krise` | Presse Krise im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Krisenmanagement bei medialer Berichterstattung ueber, Schnittstelle zwischen Produktsicherheitsanforderungen und, Verteidigung bei BAFA-Aussenpruefung und zollrec... |
| `aussenwirtschaft-sanktionsumgehung-red-zoll` | Sanktionsumgehung RED Zoll im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Erkennung und rechtliche Bewertung von, Zollstraf- und Bussgeldsachen sowie freiwillige, Zollschuldentstehung nach UZK Art, Pruefen und Anfechten von... |
| `aussenwirtschaft-versandverfahren-ncts` | Versandverfahren Ncts im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Unionszollkodex-Versandverfahren (T1/T2) im NCTS (New, Zollverfahren und Bewilligungen nach UZK Art, Exportkontrollklauseln in Distributor- und, Gestaltun... |
| `aussenwirtschaft-zoll-allgemeingenehmigung-agg-antidumping` | Allgemeingenehmigung AGG Antidumping im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Allgemeine Genehmigungen nach AWV, Antidumping-Ausgleichsmassnahmen nach EU-Grundverordnung, Erstattung zu viel gezahlter Antidumping-Zoell... |
| `aussenwirtschaft-zoll-sanktionen-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting im Aussenwirtschaft Zoll Sanktionen-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbeits... |
| `awv-beteiligungsmeldungen` | AWV Beteiligungsmeldungen im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Meldepflichten fuer Direktinvestitionen und, Melde- und Auskunftspflichten nach AWV gegenueber der, Meldepflichten nach AWV fuer spezifische Formulare... |
| `bafa-nullbescheid-catch-all-cbam` | Bafa Nullbescheid Catch ALL Cbam im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Nullbescheid und Auskunfts-Zollanmeldung (AZG), Catch-All-Pruefung nach Art, CBAM-Berichtspflichten in der Uebergangsphase (2023-2025), Beschaf... |
| `incoterms-exportkontrolle-internal` | Incoterms Exportkontrolle Internal im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Schnittstelle zwischen Incoterms 2020 und, Interne Ermittlung bei Verdacht auf Verstoss gegen, Investitionspruefung durch das BMWK nach AWG §... |
| `legal-hold-lieferanten-onboarding` | Legal Hold Lieferanten Onboarding im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Legal Hold und digitale Datenextraktion bei Exportkontroll-, Exportkontroll- und sanktionsrechtliches Onboarding neuer, Lieferkettensorgfaltsp... |
| `nichtpraeferenzieller-ursprung-ofac-sdn-post` | Nichtpraeferenzieller Ursprung Ofac SDN Post im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Nichtpraeferenzieller Ursprung nach UZK Art, US-OFAC-Sanktionsregime fuer deutsche und EU-Unternehmen, Integration des Internal Com... |
| `passive-veredelung-rueckwaren-erlass` | Passive Veredelung Rueckwaren Erlass im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Passive Veredelung nach UZK Art, Zollerlass und -erstattung fuer Rueckwaren nach UZK Art, Exportkontrolle fuer Technologietransfer durch, V... |
| `sammelgenehmigung-export-schulung` | Sammelgenehmigung Export Schulung im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Globale und Sammelausfuhrgenehmigungen bei BAFA, Konzeption und Durchfuehrung von Exportkontroll-Schulungen, EU-Schutzmassnahmen (Safeguards)... |
| `software-verschluesselung-swiss-sanctions` | Software Verschluesselung Swiss Sanctions im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Exportkontrolle fuer Verschluesselungssoftware und, Schweizer Sanktionsrecht als Touchpoint im, Sanktions- und Exportkontrollpruefung... |
| `uk-sanctions-us-ear-voruebergehende` | UK Sanctions US EAR Voruebergehende im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret UK-Sanktionsrecht als Touchpoint im EU-Exportkontrollmandat, US-Exportkontrolle als Touchpoint im deutschen Mandat, Voruebergehende Verwendu... |
| `vzta-antrag-warennummer-hs-wto-handelspolitik` | Vzta Antrag Warennummer HS WTO Handelspolitik im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Verbindliche Zolltarifauskunft (vZTA) nach UZK Art, Wareneinreihung nach Harmonisiertem System (HS), WTO-Handelspolitik und Schutz... |
| `zolllager-freilager-aussenwirtschaft` | Zolllager Freilager Aussenwirtschaft im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Zolllager und Freilager nach UZK Art, Grenzueberschreitende Abfallverbringung nach EU-AbfVerbrV, AEO-Zugelassener-Wirtschaftsbeteiligter-Be... |
| `zolltarif-vzta-zollwert-royalties-ursprung` | Zolltarif Vzta Zollwert Royalties Ursprung im Außenwirtschaftsrecht, Zoll und Sanktionen: prüft konkret Zolltarifrecht und verbindliche Zolltarifauskuenfte (vZTA), Zollwerterhöhungen durch Lizenzgebuehren (Royalties) und, Zusammenhang vo... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
