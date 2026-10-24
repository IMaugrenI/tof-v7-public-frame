# Verarbeitungsmodell — Reduzierte öffentliche Sicht

Diese Architekturreferenz veröffentlicht bewusst **keine** vollständige Runtime-Kette. Die folgende Abfolge bewahrt übergeordnete Aufgabenbereiche des früheren V7-Verarbeitungsmodells:

1. **Eingang / Edge-Wahrnehmung:** externe Eingaben über definierte Schnittstellen aufnehmen.
2. **Gate / Governance:** Annahme, Kontext und Berechtigung prüfen.
3. **Safety / Analyse:** geeignete Schutzprüfungen durchführen und angenommene Inhalte auswerten.
4. **Worker / State / Retention:** begrenzte Verarbeitung mit Trennung von aktuellem Zustand und gespeicherten Aufzeichnungen.
5. **Archiv / Vector / LLM / Ausgabe:** spätere Rollen für Aufbewahrung, Suche, Generierung und Darstellung.

Die Gruppierung ist **illustrativ**. Sie behauptet weder exakt fünf laufende Dienste noch eine starre Reihenfolge jeder Anfrage oder eine vollständig öffentlich nachgewiesene Umsetzung.

Die wesentliche Unterscheidung ist, dass Sprachmodell-Ausgabe im beschriebenen Ansatz erst nach kontrollierter Eingabeverarbeitung steht. Sie ist **nicht** selbst Wahrheitskern oder Berechtigungsinstanz.

[Grundprinzipien](01_core_frame_DE.md) · [Dienstgrenzen](05_reduced_service_map_DE.md)
