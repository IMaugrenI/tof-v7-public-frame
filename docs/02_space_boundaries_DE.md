# Grenzen zwischen Zuständigkeiten und Datenräumen

Die frühere Architekturreferenz mit der Bezeichnung **V7** betont die strikte Trennung von Datenräumen und Autorität. Diese Unterscheidungen bleiben auch ohne Kenntnis der Versionsgeschichte sinnvoll.

## Bereiche im öffentlichen Modell

| Bereich | Zweck | Nicht gleichzusetzen mit |
| --- | --- | --- |
| **Runtime** | Tatsächlich aktive Dienste und aktueller Betriebszustand | Planungsdokumente oder archivierte Belege |
| **Kanon** | Geregeltes Referenzmaterial | Aktueller Runtime-Zustand |
| **Archiv** | Gespeicherte Aufzeichnungen und Herkunft | Automatisch gültige aktuelle Fakten |
| **Werkbank** | Untersuchung und Vorbereitung älteren Materials | Freigegebene und ausgerollte Änderungen |
| **Bridge Planning / Vorplanung** | Planung und Prüfung möglicher nächster Schritte | Laufende Implementierung |

## Warum das wichtig ist

Material darf andere Bereiche nur über einen **ausdrücklichen und kontrollierten Übergang** beeinflussen. Historische Belege werden nicht automatisch zur aktuellen Wahrheit; ein Plan nicht automatisch zu ausführbarem Code; Identität oder Darstellung nicht zum Ersatz technischer Kontrollen.

Das Dokument zeigt konzeptionelle Grenzregeln, **nicht** die vollständige private Weiterleitung, Berechtigungsstruktur oder einen unabhängigen Betriebsnachweis.

[Grundprinzipien](01_core_frame_DE.md) · [Leseregeln](06_reading_rules_DE.md)
