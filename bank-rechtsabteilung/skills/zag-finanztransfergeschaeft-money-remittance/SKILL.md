---
name: zag-finanztransfergeschaeft-money-remittance
description: "Finanztransfergeschäft und Money Remittance nach ZAG prüfen: Weiterleitung von Geldbeträgen ohne Zahlungskonto, Agentenmodelle, Plattformfälle, Bargeld, Ausnahmen und BaFin-Erlaubnisrisiko."
---

# Finanztransfergeschäft / Money Remittance nach ZAG

## Worum es geht

Dieser Skill prüft das Finanztransfergeschäft nach § 1 Abs. 1 Satz 2 Nr. 6 ZAG (Money Remittance): Weiterleitung von Geldbeträgen ohne Eröffnung eines Zahlungskontos. Er deckt Erlaubnisanforderungen, Geldwäscheprävention, FATF-Vorgaben und die Travel-Rule-Pflichten ab. Besonderheiten bei Bargeld, Krypto-Remittance und Agentennetzen werden adressiert.

## Kernnormen

- **§ 1 Abs. 1 Satz 2 Nr. 6 ZAG** – Finanztransfergeschäft: Dienst zur Übermittlung von Geldbeträgen; kein Zahlungskonto erforderlich; Ausführung der Transaktion über das Netz des Anbieters
- **§ 10 ZAG** – Erlaubnispflicht; Anfangskapital nach § 17 ZAG: 20 TEUR (geringstes Anfangskapital aller Zahlungsdienste); Geschäftsplan, Sicherungskonzept, Organigramm
- **§ 17 ZAG** – Anfangskapital 20 TEUR für Finanztransfer; laufende Eigenmittel Methode A, B oder C nach Zahlungsvolumen
- **§ 25 ZAG** – Agenten: Registrierung, Haftung des Hauptinstituts, Schulungspflichten, AML-Einbindung; Eintrag im BaFin-Agenten-Register
- **GwG §§ 3–10** – KYC-Pflichten: Identifizierung ab 15 Euro Bargeldtransaktion (§ 10 Abs. 3 Nr. 2 GwG), vereinfachte Sorgfalt nicht anwendbar beim Finanztransfer
- **GwG § 15** – Verstärkte Sorgfaltspflichten: Hochrisiko-Länder (FATF-Liste), PEP-Kunden, ungewöhnliche Transaktionsmuster; Transaktionsmonitoring
- **FATF Recommendation 16 (Travel Rule)** – Pflicht zur Übermittlung von Auftraggeber- und Empfängerinformationen bei Überweisungen; Umsetzung in EU durch Geldtransfer-VO 2015/847 (ab 2024 MiCA-Erweiterung VO 2023/1113)
- **GwG § 43** – Verdachtsmeldepflicht bei Geldwäscheverdacht; FIU-Meldung; Durchführungsverbot vor FIU-Freigabe

## Prüfschritte

1. **Dienst-Klassifikation** (§ 1 Abs. 1 Satz 2 Nr. 6 ZAG): Wird Geld weitergeleitet ohne eigenes Zahlungskonto des Empfängers? Bargeld-zu-Bargeld, Bargeld-zu-Konto, Online-Remittance?
2. **Erlaubnisantrag** (§ 10 ZAG): Anfangskapital 20 TEUR; Geschäftsplan mit Volumen-Projektion, Agentenstruktur, AML-Konzept.
3. **KYC-Pflichten** (GwG §§ 3–10): Identifizierung aller Auftraggeber; ab 1000 Euro erhöhte Sorgfalt; bei Bargeld-Einzahlung ab 15 Euro Identifizierungspflicht.
4. **Travel Rule** (Geldtransfer-VO 2015/847): Auftraggeber-Daten (Name, Konto/IBAN oder eindeutige Kennung, Adresse) mit jeder Überweisung übermitteln; Empfängerinstitut prüft Vollständigkeit.
5. **Hochrisiko-Check** (GwG § 15, FATF-Länderliste): Transaktionen in/aus Hochrisikoländern; verstärkte Sorgfalt; ggf. Einzel-Genehmigung GF.
6. **Agentennetz** (§ 25 ZAG): Jeder Agent registrieren; Schulung AML/KYC; Haftung des Instituts sicherstellen; Monitoring der Agentenaktivitäten.
7. **Verdachtsmeldung** (GwG § 43): Transaktionsmonitoring-System; Schwellenwerte und Muster festlegen; FIU-Meldung innerhalb Frist.
8. **Krypto-Remittance**: Ab VO 2023/1113 gilt Travel Rule auch für Kryptowert-Transfers; VASP-Status nach MiCAR prüfen.

## Typische Fallkonstellationen

- Western-Union-Modell (Bargeld-Einzahlung, Auszahlung im Ausland): § 1 Abs. 1 Satz 2 Nr. 6 ZAG, § 10 ZAG Erlaubnis, GwG KYC, Travel Rule
- Online-Remittance-Plattform (Bank-zu-Bank ohne eigenes Konto): § 1 Abs. 1 Satz 2 Nr. 6 ZAG; Abgrenzung zu Zahlungsgeschäft Nr. 3 (Kundenkonto vorhanden = Nr. 3)
- Krypto-Remittance (BTC-Überweisung als Geldwert): MiCAR VASP + VO 2023/1113 Travel Rule; ggf. ZAG-Erlaubnis parallel
- Transaktionen in FATF-gelistetes Land: GwG § 15 verstärkte Sorgfalt; Einzelgenehmigung Geschäftsleitung; Transaktionslimit erwägen
- Agentenausfall mit Kundengeldverlust: § 25 ZAG Institut-Haftung, § 16 ZAG Sicherungspflicht, BaFin-Meldepflicht

## Output

Erlaubnisantrags-Checkliste § 10 ZAG für Money Remittance; KYC-Pflichten-Matrix (Schwellenwerte, Dokumente); Travel-Rule-Compliance-Check; AML-Transaktionsmonitoring-Konzept; Agenten-Überwachungs-Protokoll.

## Quellenregel

gesetze-im-internet.de (ZAG, GwG), eur-lex.europa.eu (Geldtransfer-VO 2015/847, VO 2023/1113 Travel Rule), fatf-gafi.org (Recommendation 16, VASP Guidance 2021), bafin.de (Merkblatt Finanztransfer, AML-Hinweise). Live-Check: VO 2023/1113 gilt ab 30.12.2024; FATF-Länderliste wird laufend aktualisiert.
