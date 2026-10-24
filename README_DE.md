# Architekturreferenz — Systemgrenzen (V7)

<p align="center">
  <img src="https://raw.githubusercontent.com/IMaugrenI/IMaugrenI/main/assets/banner/ToF_Banner.png" alt="ToF Systems Architekturbanner" width="100%" />
</p>

**Wie sich Zuständigkeiten, Datenräume und operative Autorität in einem lokalen System sauber trennen lassen.**

Dieses Repository dokumentiert eine **reduzierte öffentliche Architekturreferenz** aus einer älteren, versionsbezogenen Entwicklungsphase von ToF. Der Repository-Name behält **V7** bei, damit bestehende Links und Dokumente gültig bleiben. Um die beschriebenen Prinzipien zu verstehen, muss man die interne Versionsgeschichte **nicht** kennen.

[English](README.md) · [Einstieg](START_HERE_DE.md) · [Projektübersicht](https://github.com/IMaugrenI/tof-showcase)

## Die Architekturfrage

Wie bleibt ein größeres lokales System nachvollziehbar und kontrollierbar, wenn Informationsquellen, Verarbeitungsschritte, Planung und operative Dienste unterschiedliche Aufgaben besitzen?

Die Referenz behandelt die Trennung von:
- **Runtime:** dem tatsächlich ausgeführten Betrieb.
- **Canon:** ausdrücklich geregelten und übernommenen Referenzinhalten.
- **Archiv:** erhaltenem Material ohne automatische Autorität über die aktive Runtime.
- **Werkbank:** Vorbereitung, Untersuchung und Review außerhalb des Betriebs.
- **Bridge Planning:** Überführung vorbereiteter Inhalte in mögliche nächste Schritte, ohne sie stillschweigend ausführbar zu machen.

Diese Begriffe beschreiben **Verantwortungsgrenzen**, keine nachgewiesene produktive Implementierung.

## Die Referenz lesen

| Dokument | Schwerpunkt |
| --- | --- |
| [Kernarchitektur](docs/01_core_frame.md) | Reduzierte öffentliche Architektursicht. |
| [Räumliche Trennung](docs/02_space_boundaries.md) | Warum unterschiedliche Bereiche und ihre Zuständigkeiten getrennt bleiben. |
| [Öffentliche Leitplanken](docs/03_public_guardrails.md) | Grenzen öffentlicher Aussagen und Veröffentlichungen. |
| [Verarbeitungskette](docs/04_public_chain.md) | Einordnung der reduzierten Kettendarstellung. |
| [Dienstübersicht](docs/05_reduced_service_map.md) | Eingeschränkte, bereinigte Darstellung von Dienstbeziehungen. |
| [Leseregeln](docs/06_reading_rules.md) | Dokumentation, Vorschlag und Betriebsnachweis auseinanderhalten. |

## Warum die Referenz öffentlich bleibt

Der übertragbare Teil ist die **Methode**: eindeutige Zuständigkeiten festlegen, Grenzen schützen, Herkunft nachvollziehbar halten und Vorschläge von freigegebenen und tatsächlich laufenden Zuständen unterscheiden. Dafür braucht man keine bestimmte interne Versionsnummer.

Die Referenz richtet sich an Menschen, die sich für Local-First-Systemarchitektur, Diensttrennung, überprüfbare Dokumentation und Autoritätsgrenzen interessieren.

## Was sie nicht behauptet

Dieses Repository enthält weder eine produktive Runtime noch eine vollständige private Dienstübersicht, Zugangsdaten oder die gesamte beschriebene Implementierung. Öffentliche Diagramme und Begriffe sind **Architekturbeschreibungen**, keine Betriebsbeweise oder pauschalen Produktionsfreigaben.

Die praktisch nutzbaren öffentlichen Werkzeuge findest du unter [ToF Showcase](https://github.com/IMaugrenI/tof-showcase) und auf dem [GitHub-Profil](https://github.com/IMaugrenI). Jedes Produkt-Repository dokumentiert seinen Funktionsumfang und seinen eigenen Betriebsweg.
