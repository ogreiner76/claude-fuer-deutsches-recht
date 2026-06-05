---
name: quellen-livecheck
description: "Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert."
---

# Rechtsquellen-Livecheck

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

- **Tragende Normen amtlich.** Bei Geldwäscheprävention AML/KYC: GwG, FATF 40 Recommendations, EU-AMLD VI — gesetze-im-internet, Eur-Lex oder amtliche Datenbank.
- **Behördenpraxis.** FIU (Bescheide, Auslegungserlasse, FAQ); Stand-Datum prüfen.
- **Rechtsprechung.** Gericht, Entscheidungsform, Datum, Az, Rn, frei prüfbare Fundstelle. Keine BeckRS-/juris-Blindzitate aus Modellwissen.
- **Kommentare/Literatur** nur mit Nutzerquelle oder lizenziertem Live-Zugriff; alte Auflage explizit markieren.
- **Quellenstand und Unsicherheit** im Output sichtbar machen — keine Scheinpräzision.

## Output

Quellenkarte mit Primärnormen, Rechtsprechungssuche (Gericht/Datum/Az/Rn), Behördenstand und Zitierform nach `references/zitierweise.md`.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
