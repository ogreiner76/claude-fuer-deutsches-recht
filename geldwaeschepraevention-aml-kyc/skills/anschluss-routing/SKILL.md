---
name: anschluss-routing
description: "Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad."
---

# Anschluss-Routing

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

- **Engpass zuerst.** Bei Geldwäscheprävention AML/KYC typischer Engpass: Verdachtsmeldung unverzüglich § 43 GwG oder KYC-Akte.
- **Skill-Auswahl** nach Sachverhalt, Rolle (Verpflichteter (Bank, Anwalt, Notar), Kunde), Frist und gewünschtem Output.
- **Nicht parallel aufblasen.** Erst den Engpass lösen, dann den nächsten Pfad öffnen.
- **Grenzfall.** Zwei Skills kurz gegenüberstellen mit Vor-/Nachteil und einer Empfehlung.
- **Akten-Spur.** Router-Entscheidung dokumentieren mit Begründung und Verworfenem.

## Output

Routing-Entscheidung mit Anschluss-Skill, Reihenfolge, Abbruchkriterien und nächster Aktion innerhalb von Geldwäscheprävention AML/KYC.

## Qualitätsanker

- Normen und Rechtsprechung nach `references/quellenhygiene.md` und `references/zitierweise.md` behandeln.
- Wenn eine Spezialfrage sichtbar wird, den passenden Skill nennen und kurz erklären, warum genau dieser Skill passt.
- Bei Zeitdruck zuerst Frist, Zuständigkeit, Form und Beweislast sichern.
