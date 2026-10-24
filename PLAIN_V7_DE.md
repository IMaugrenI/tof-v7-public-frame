# Systemgrenzen — Verständliche Kurzfassung

**Dies ist die Kurzfassung der früheren Architekturreferenz mit dem Namen V7.** Die Bezeichnung bleibt im Repository-Namen aus Kontinuitätsgründen erhalten. Man muss die Version nicht kennen, um die öffentlichen ToF-Systems-Projekte zu verstehen.

## Was die Architektur erreichen soll

Ein **modulares, kontrolliertes technisches Fundament** entwickeln, statt Funktionen in einem undifferenzierten Chatbot oder LLM-Wrapper anzusammeln.

Konkret bedeutet das:

- Eingang, Prüfung, Verarbeitung, Zustand, Spurensicherung und Ausgabevorbereitung trennen;
- verhindern, dass Archivmaterial oder ungeprüfte Planung unbemerkt zum laufenden Zustand werden;
- Plattformintegration am Rand belassen;
- Identität und Ausdruck von technischer Berechtigung trennen;
- Funktionen erweitern, ohne Zuständigkeiten zu vermischen.

## Warum es dieses Repository gibt

Es erklärt ausgewählte Architekturentscheidungen und Verantwortungsgrenzen. Es liefert **keine** vollständige Runtime, Produktiv-Deployment-Anleitung, komplette Dienstliste oder private Sicherheits- und Betreiberimplementierung.

## Wichtigste Aussage

**Eine Architekturbeschreibung ist kein Betriebsnachweis.** Praktisch nutzbare öffentliche Werkzeuge findest du im [ToF Showcase](https://github.com/IMaugrenI/tof-showcase). Architekturdetails stehen in den Dokumenten, die das [README](README_DE.md) verlinkt.
