# Dienstgrenzen — Reduziertes öffentliches Modell

Dieses Repository veröffentlicht keine vollständige private Service-Map. Stattdessen hebt die historische Architekturreferenz mehrere Entwurfsziele hervor:

- **Getrennte Dienste mit eindeutigen Zuständigkeiten** statt eines ununterscheidbaren Monolithen bevorzugen.
- Externe Plattformprotokolle und Adapter am **Systemrand** belassen.
- Laufenden Runtime-Zustand von symbolischer Identität oder Darstellung unabhängig halten.
- Audit-Aufzeichnungen, aktuellen State, Retention und Archiv als unterschiedliche Aufgaben behandeln.
- Kontrollierte Übergänge zwischen Arbeitsbereichen beibehalten.

Das ist eine **konzeptionelle Beziehungsskizze**, keine Liste aktiver Dienste, Docker-Container, Netzwerkrouten oder ausgerollter Schnittstellen.

Konkrete, nutzbare öffentliche Projekte stehen im [ToF Systems Showcase](https://github.com/IMaugrenI/tof-showcase). Jedes Werkzeug dokumentiert seine eigene Einrichtung und Funktion.
