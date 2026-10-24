# Architekturreferenz — Grundprinzipien

Dieses Dokument erklärt die **Systemgrenzen** einer früheren ToF-Architekturphase, die intern **V7** genannt wurde. Die Versionsnummer bleibt aus historischen Gründen erhalten; Besucher müssen sie nicht kennen, um die Prinzipien zu verstehen.

## Zentrale Grundsätze

- **Technische Autorität bleibt vom Ausdruck getrennt.** Identität, Formulierung oder Symbole schaffen keine Betriebsberechtigung.
- **Unterschiedliche Bereiche behalten eigene Zuständigkeiten.** Planung, Werkbank, Archiv, geregelte Referenzen und Runtime-Zustand dürfen nicht unbemerkt verschmelzen.
- **Dokumentation und Runtime-Zustand sind nicht austauschbar.** Ein Dokument mit beabsichtigtem Verhalten beweist keinen laufenden Dienst.
- **Sprachmodell-Ausgabe ist keine Autoritätsquelle.** Generierte Texte brauchen geeignete Belege und dürfen Aktionen nicht selbstständig freigeben.

## Was diese historische Referenz beschreibt

Die frühere V7-Ausrichtung betonte eine kontrollierte Systemarchitektur, eindeutige Grenzen und die bewusste Weiterentwicklung früherer Arbeit statt einer ungeordneten Sammlung von Funktionen.

Der Ansatz war **nicht** nur als Bot- oder Chat-Oberfläche oder einfacher LLM-Wrapper gedacht. Dieses öffentliche Repository ist aber ebenso **keine** vollständige Implementierung, Runtime-Freigabe oder Offenlegung privater Betriebsmechanismen.

## Weiterführende Dokumente

[Raum- und Zuständigkeitsgrenzen](02_space_boundaries_DE.md) · [Verarbeitungsmodell](04_public_chain_DE.md) · [Öffentliche Projektfamilie](https://github.com/IMaugrenI/tof-showcase)
