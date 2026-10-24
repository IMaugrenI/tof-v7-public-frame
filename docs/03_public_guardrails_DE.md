# Technische Leitplanken — Historischer Architekturkontext

Diese Seite beschreibt eine **reduzierte Auswahl von Entwurfsvorgaben** aus der früheren V7-Architektur. Sie ist keine allgemeine Checkliste, die automatisch für jedes öffentliche ToF-Systems-Repository gilt.

## Beschriebene Vorgaben

- Docker-first-Ausrichtung des Betriebs.
- Postgres-only-Datenbankausrichtung innerhalb dieser privaten Architektur.
- Klare Dienst- und Zuständigkeitsgrenzen.
- Fail-closed-Denken statt stiller Umgehungen.
- Spuren- und herkunftsbewusste Verarbeitung.
- Plattformneutrale Kernlogik mit Adaptern am Rand.
- Sprachmodell-Ausgabe spät in der konzeptionellen Kette, nicht als Quelle technischer Wahrheit.

## Wie diese Punkte zu verstehen sind

Sie beschreiben **Architekturabsichten**. Für sich genommen beweisen sie weder Testabdeckung noch Betriebsstatus oder Sicherheitsgarantien. Das eigenständige öffentliche Werkzeug Container Pulse funktioniert beispielsweise bewusst ohne Datenbank.

Private Sicherheits- und Betreiberdetails bleiben ausgespart. Tatsächliche Abhängigkeiten und Funktionen stehen in der [öffentlichen Projektübersicht](https://github.com/IMaugrenI/tof-showcase) und der jeweiligen Produktdokumentation.
