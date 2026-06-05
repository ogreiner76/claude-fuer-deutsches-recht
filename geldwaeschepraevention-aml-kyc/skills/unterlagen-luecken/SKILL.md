---
name: unterlagen-luecken
description: "Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen."
---

# Unterlagen und Lücken

## Einsatzlage

Nutze diesen Skill, wenn im Bereich **Geldwaeschepraevention Aml Kyc** ein Fall noch sortiert, Dokumente eingeordnet, Quellen geprüft oder der nächste Arbeitsweg gewählt werden muss. Der Skill soll nicht allgemein reden, sondern schnell in den passenden Fachpfad führen.

## Fachlandkarte dieses Plugins

- `allgemein-workflow-chronologie-workflow-fristen` — Allgemein Chronologie Fristen
- `geldwaesche-audit-internal-datenqualitaet-register-immobilien` — Geldwaesche Audit Internal Datenqualitaet Register Immobilien
- `geldwaesche-krypto-zahlungsdienstleister-kyc-onboarding` — Geldwaesche Krypto Zahlungsdienstleister Kyc Onboarding
- `geldwaesche-pep-hochrisikoland-risikoanalyse-unternehmen` — Geldwaesche Pep Hochrisikoland Risikoanalyse Unternehmen
- `geldwaesche-sicherungsmassnahmen-geldwaesche-simulation` — Geldwaesche Sicherungsmassnahmen Geldwaesche Simulation
- `geldwaesche-transaktionsstopp-freeze-transparenzregister-ubo` — Geldwaesche Transaktionsstopp Freeze Transparenzregister Ubo
- `geldwaesche-verdachtsmeldung-geldwaesche-verpflichteten` — Geldwaesche Verdachtsmeldung Geldwaesche Verpflichteten
- `goaml-gwg-spezial-kommandocenter` — Goaml Gwg Kommandocenter
- `livecheck-red-risikoanalyse-verdachtsmeldeweiche-simulation` — Livecheck Red Risikoanalyse Verdachtsmeldeweiche Simulation
- `onboarding-bauleiter-trade-based-verdachtsmeldung-fiu` — Onboarding Bauleiter Trade Based Verdachtsmeldung Fiu
- `risikoanalyse-geldwaesche-bussgeld-geldwaesche` — Risikoanalyse Geldwaesche Bussgeld Geldwaesche
- `sanktionen-geldwaesche-gruppenweite-aml-kryptotransaktionen` — Sanktionen Geldwaesche Gruppenweite Aml Kryptotransaktionen
- `sonderfall-edge-geldwaesche-geldwaeschepraevention` — Sonderfall Edge Geldwaesche Geldwaeschepraevention
- `testlauf-beweislast-transaktionsmonitoring-international` — Testlauf Beweislast Transaktionsmonitoring International

## Arbeitsweg

- **Fehlende Tatsache vs. fehlender Beleg.** Bei Geldwäscheprävention AML/KYC oft fehlend: KYC-Akte, Risk Assessment, Compliance-Manual.
- **Pro Lücke.** Beweisthema, Beweismittel (Dokumente wirtschaftlich Berechtigter, Transaction Logs), Beschaffungsweg, Ersatznachweis.
- **Prioritätsregel.** Frist > Beweislast > materielle Voraussetzung > Taktik; konkret: Verdachtsmeldung unverzüglich § 43 GwG.
- **Beschaffung extern.** FIU (Akteneinsicht, Auskunft), Mandant (Originale), Dritte (Auskunftsverlangen).
- **Lücken offen ausweisen** im Mandantenmemo — niemals durch Pauschalformulierungen kaschieren.

## Output

Priorisierte Lückenliste mit Frist, Beweiszweck, Beschaffungsweg, Ersatznachweis und Verantwortlichem; im Mandat Geldwäscheprävention AML/KYC typischerweise KYC-Akte, Risk Assessment zuerst.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
