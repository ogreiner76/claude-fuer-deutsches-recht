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
| **Außenwirtschaft, Zoll, Sanktionen und CBAM – Globalmaschinen GmbH** (`aussenwirtschaft-zoll-sanktionen-globalmaschinen`) | [Gesamt-PDF lesen](../testakten/aussenwirtschaft-zoll-sanktionen-globalmaschinen/gesamt-pdf/aussenwirtschaft-zoll-sanktionen-globalmaschinen_gesamt.pdf) | [`testakte-aussenwirtschaft-zoll-sanktionen-globalmaschinen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-aussenwirtschaft-zoll-sanktionen-globalmaschinen.zip) |
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
| `allgemein` | Einstieg, Schnelltriage und Fallrouting im Aussenwirtschaft Zoll Sanktionen-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Fachmodule aus diesem Plugin vor und führt in einen klaren Arbeits... |
| `allgemeingenehmigung-agg-antidumping` | Nutze dies bei Aussenwirtschaft Allgemeingenehmigung Agg Finder, Aussenwirtschaft Antidumping Ausgleich, Aussenwirtschaft Antidumping Erstattung Review, Aussenwirtschaft Antidumping Taric Massnahmen: führt durch diese fachlich verbundene... |
| `asset-freeze-atlas-ausfuhranmeldung-audit` | Nutze dies bei Aussenwirtschaft Asset Freeze Sofortmassnahmen, Aussenwirtschaft Atlas Ausfuhranmeldung Check, Aussenwirtschaft Audit Trail Freigaben, Aussenwirtschaft Ausfuhrverantwortlicher Organisation: führt durch diese fachlich verbu... |
| `aussenwirtschaft-aml-kyc-finanzsanktionen` | Nutze dies bei Aussenwirtschaft Aml Kyc Sanktionen, Aussenwirtschaft Finanzsanktionen Eigentum Kontrolle, Aussenwirtschaft Sanktionen Embargos, Aussenwirtschaft Sanktionsscreening Fuzzy Match: führt durch diese fachlich verbundenen Modul... |
| `aussenwirtschaft-bafa-genehmigungen-cbam-co2` | Nutze dies bei Aussenwirtschaft Bafa Genehmigungen, Aussenwirtschaft Cbam Co2 Zoll, Aussenwirtschaft Cbam Zertifikate Kosten, Aussenwirtschaft Kommandocenter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad un... |
| `aussenwirtschaft-chemikalien-reach-cites` | Nutze dies bei Aussenwirtschaft Chemikalien Reach Pic, Aussenwirtschaft Cites Artenschutz, Aussenwirtschaft Dual Use Forschung Hochschule, Aussenwirtschaft Embargo Belarus: führt durch diese fachlich verbundenen Module, wählt den passend... |
| `aussenwirtschaft-embargo-iran-myanmar` | Nutze dies bei Aussenwirtschaft Embargo Iran, Aussenwirtschaft Embargo Myanmar, Aussenwirtschaft Embargo Nordkorea, Aussenwirtschaft Embargo Russland: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefer... |
| `aussenwirtschaft-embargo-syrien-endverwendung` | Nutze dies bei Aussenwirtschaft Embargo Syrien, Aussenwirtschaft Endverwendung Endverwender Euc, Aussenwirtschaft Eori Registrierung Stammdaten, Aussenwirtschaft Erp Stammdaten Kontrollpunkte: führt durch diese fachlich verbundenen Modul... |
| `aussenwirtschaft-ersatzteile-dual-exporteur` | Nutze dies bei Aussenwirtschaft Ersatzteile Dual Use, Aussenwirtschaft Exporteur Ausfuehrer Anmelder Rollen, Aussenwirtschaft Exportkontrolle Dual Use, Aussenwirtschaft F Gase Ozonstoffe: führt durch diese fachlich verbundenen Module, wä... |
| `aussenwirtschaft-financial-institutions` | Nutze dies bei Aussenwirtschaft Financial Institutions Correspondent Banking, Aussenwirtschaft Freiwillige Offenlegung Bafa Zoll, Aussenwirtschaft Gueterlisten Klassifizierung, Aussenwirtschaft Icp Kontrollsystem: führt durch diese fachl... |
| `aussenwirtschaft-kontingente-lizenzen` | Nutze dies bei Aussenwirtschaft Kontingente Lizenzen Trq, Aussenwirtschaft Kritische Infrastruktur Investment, Aussenwirtschaft Kulturgut Einfuhr Ausfuhr, Aussenwirtschaft Lebensmittel Futtermittel Vub: führt durch diese fachlich verbund... |
| `aussenwirtschaft-presse-krise` | Nutze dies bei Aussenwirtschaft Presse Krise, Aussenwirtschaft Produktsicherheit Vub Schnittstelle, Aussenwirtschaft Prüfung Ermittlung, Aussenwirtschaft Reexport Weitergabe Kettenlieferung: führt durch diese fachlich verbundenen Module,... |
| `aussenwirtschaft-sanktionsumgehung-red-zoll` | Nutze dies bei Aussenwirtschaft Sanktionsumgehung Red Flags, Aussenwirtschaft Zoll Straf Bussgeld Selbstkorrektur, Aussenwirtschaft Zollschuld Entstehung Haftung, Aussenwirtschaft Atlas Einfuhr Abgabenbescheid: führt durch diese fachlich... |
| `aussenwirtschaft-versandverfahren-ncts` | Nutze dies bei Aussenwirtschaft Versandverfahren Ncts, Aussenwirtschaft Zollverfahren Bewilligungen, Aussenwirtschaft Distributor Vertrag Exportkontrolle, Aussenwirtschaft Exportkontrollklauseln Vertrag: führt durch diese fachlich verbun... |
| `awv-beteiligungsmeldungen-awv-bundesbank-awv` | Nutze dies bei Aussenwirtschaft Awv Beteiligungsmeldungen, Aussenwirtschaft Awv Bundesbank, Aussenwirtschaft Awv Z4 Z10 Z11 Meldungen, Aussenwirtschaft Bafa Elan K2 Antragspaket: führt durch diese fachlich verbundenen Module, wählt den p... |
| `bafa-nullbescheid-catch-all-cbam` | Nutze dies bei Aussenwirtschaft Bafa Nullbescheid Azg, Aussenwirtschaft Catch All Prüfung, Aussenwirtschaft Cbam Berichtspflichten Uebergang, Aussenwirtschaft Cbam Lieferantendaten Emissionen: führt durch diese fachlich verbundenen Modul... |
| `incoterms-exportkontrolle-internal` | Nutze dies bei Aussenwirtschaft Incoterms Exportkontrolle, Aussenwirtschaft Internal Investigation Aussenwirtschaft, Aussenwirtschaft Investitionspruefung Bmwk, Aussenwirtschaft Know Your Customer Exportkontrolle: führt durch diese fachl... |
| `legal-hold-lieferanten-onboarding` | Nutze dies bei Aussenwirtschaft Legal Hold Datenextraktion, Aussenwirtschaft Lieferanten Onboarding Aussenhandel, Aussenwirtschaft Lieferkettensorgfalt Aussenhandel, Aussenwirtschaft Ma Sanctions Export Dd: führt durch diese fachlich ver... |
| `nichtpraeferenzieller-ursprung-ofac-sdn-post` | Nutze dies bei Aussenwirtschaft Nichtpraeferenzieller Ursprung Made In, Aussenwirtschaft Ofac Sdn Non Sdn, Aussenwirtschaft Post Merger Icp Integration, Aussenwirtschaft Praeferenzkalkulation Lieferantenerklaerung: führt durch diese fach... |
| `passive-veredelung-rueckwaren-erlass` | Nutze dies bei Aussenwirtschaft Passive Veredelung, Aussenwirtschaft Rueckwaren Erlass Erstattung, Aussenwirtschaft Technologie Transfer Cloud Download, Aussenwirtschaft Verbrauchsteuer: führt durch diese fachlich verbundenen Module, wäh... |
| `sammelgenehmigung-export-schulung` | Nutze dies bei Aussenwirtschaft Sammelgenehmigung Export, Aussenwirtschaft Schulung Exportkontrolle Rollout, Aussenwirtschaft Schutzmassnahmen Safeguards, Aussenwirtschaft Screening Tool Validierung: führt durch diese fachlich verbundene... |
| `software-verschluesselung-swiss-sanctions` | Nutze dies bei Aussenwirtschaft Software Verschluesselung Kryptografie, Aussenwirtschaft Swiss Sanctions Touchpoint, Aussenwirtschaft Trade Finance Lc Guarantees, Aussenwirtschaft Transferpricing Zollwert Abgleich: führt durch diese fach... |
| `uk-sanctions-us-ear-voruebergehende` | Nutze dies bei Aussenwirtschaft Uk Sanctions Touchpoint, Aussenwirtschaft Us Ear Itar, Aussenwirtschaft Voruebergehende Verwendung Ata Carnet, Aussenwirtschaft Vub Einfuhr Ausfuhr: führt durch diese fachlich verbundenen Module, wählt den... |
| `vzta-antrag-warennummer-hs-wto-handelspolitik` | Nutze dies bei Aussenwirtschaft Vzta Antrag Qualitaetsgate, Aussenwirtschaft Warennummer Hs Cn Taric Einreihung, Aussenwirtschaft Wto Handelspolitik, Aussenwirtschaft Zollpruefung Aussenpruefung: führt durch diese fachlich verbundenen Mo... |
| `zolllager-freilager-aussenwirtschaft` | Nutze dies bei Aussenwirtschaft Zolllager Freilager, Aussenwirtschaft Abfallverbringung, Aussenwirtschaft Aeo Bewilligung Monitoring, Aussenwirtschaft Aktive Veredelung: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `zolltarif-vzta-zollwert-royalties-ursprung` | Nutze dies bei Aussenwirtschaft Zolltarif Vzta, Aussenwirtschaft Zollwert Royalties Assists, Aussenwirtschaft Zollwert Ursprung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastb... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
