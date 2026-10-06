# Steuer-Rechner 2026 (kostenlos)

Statische Einzelseite – 13 Rechner für Freiberufler, Kleinunternehmer und Vermieter in Deutschland.
**Kein Build, keine Dependencies, kein CDN, kein Tracking, kein Cookie. Läuft komplett offline im Browser.**

Live: https://ycyxyd.github.io/steuer-rechner/

## Enthaltene Rechner

| # | Rechner | Rechtsgrundlage |
|---|---------|-----------------|
| 1 | Abgabefrist Steuererklärung (inkl. Wochenendverschiebung) | § 149 Abs. 2/3 AO, § 108 AO |
| 2 | Umsatzsteuer-Voranmeldung (monatlich/quartalsweise × Dauerfristverlängerung) | § 18 Abs. 1 UStG |
| 3 | Kleinunternehmer-Selbsttest | § 19 UStG (25.000 / 100.000 EUR) |
| 4 | Aufbewahrungsfristen & E-Rechnung-Übergang | § 147 AO, § 14/§ 14b/§ 27 Abs. 38 UStG |
| 5 | Gewinn / EÜR | § 4 Abs. 3 EStG |
| 6 | Umsatzsteuer umrechnen (19 % / 7 %), beide Richtungen | § 12 UStG |
| 7 | Reisekosten (Verpflegungspauschale + km-Satz) | § 9 Abs. 4a EStG |
| 8 | *(Software-Empfehlung mit Affiliate-Kennzeichnung)* | – |
| 9 | Homeoffice-Pauschale (6 EUR/Tag, max. 1.260 EUR) | § 4 Abs. 5 Nr. 6c EStG |
| 10 | Entfernungspauschale (0,38 EUR/km, max. 4.500 EUR) | § 9 Abs. 1 Nr. 4 EStG |
| 11 | Gewerbesteuer (Freibetrag, Messzahl, Hebesatz) | § 11 GewStG |
| 12 | Sondervorauszahlung bei Dauerfristverlängerung (1/11) | § 47 UStDV |
| 13 | Lineare AfA (inkl. Zwölftel im Anschaffungsjahr) | § 7 Abs. 1 EStG |

## Disclaimer

Diese Rechner sind eine unverbindliche Arbeitshilfe und **keine Steuer- oder Rechtsberatung**.
Maßgeblich sind die amtlichen Vordrucke, das EStG/UStG in der geltenden Fassung sowie die Hinweise
des Bundesfinanzministeriums und von ELSTER. Alle Werte wurden gegen gesetze-im-internet.de geprüft;
Vorschriften können sich ändern – im Zweifel Steuerberater/in fragen.

## Tests (lokal, deterministisch)

Die Test-Suite liegt im privaten Projekt-Repo (`tool/test_engine.js`, `tool/verify_all.py`
und ein Abgleich der Rechtswerte gegen gesetze-im-internet.de).
