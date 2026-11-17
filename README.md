# Inklusives Musik-Lerninterface

**Konzept und interaktiver Prototyp für den Musikunterricht gehörloser und schwerhöriger Lernender**

Ein Lerninterface, das die Grundbegriffe Rhythmus, Tempo und Dynamik über drei Kanäle vermittelt: visuell, gestisch-motorisch und haptisch. Lernende wählen die Kanäle selbst, passen Zuordnung und Intensität an und können die Zuordnung vor der Nutzung erkunden.

**Live-Prototyp:** https://darigaorozova.github.io/inclusive-music-interface/

## Forschungsfrage

Wie kann ein inklusives multimodales Lerninterface gestaltet werden, das visuelle, gestische und haptische Elemente so kombiniert, dass gehörlose und schwerhörige Lernende grundlegende musikalische Konzepte erfassen können?

## Was im Prototyp steckt

- **Drei Kanäle** für Rhythmus, Tempo und Dynamik, jeweils wählbar
- **Erkundungsmodus**, in dem Lernende die Zuordnung zwischen Reiz und Musikbegriff ausprobieren, bevor sie die Lernsituation starten
- **Ansicht für Lehrkräfte** mit Einstellungen für Kanäle und Intensität
- **Optionales Maskottchen**, das nur mit Bild und Text arbeitet und in den Einstellungen abschaltbar ist
- Speichert den Lernfortschritt lokal im Browser (localStorage), ohne Server

Der Prototyp ist eine einzelne HTML-Datei ohne Build-Schritt. Er läuft auf dem Smartphone und im Desktop-Browser. Haptik nutzt die Vibrationsfunktion des Geräts, sofern sie verfügbar ist.

## Status und Grenzen

- Das Konzept ist **literaturbasiert** entwickelt. Die Anforderungen stammen aus einer Auswahl wissenschaftlicher Arbeiten zu Musik, Hörverlust und taktilen Displays.
- Der Prototyp ist **nicht mit gehörlosen oder schwerhörigen Lernenden getestet**. Die Wirkung auf das Lernen ist nicht belegt.
- Die Gebärden- und Bewegungsbeispiele zeigen Ausdrucksformen für Konzepte. Sie sind **keine Gebärdensprache**.
- Die Literaturauswahl ist eine gezielte Recherche und erhebt keinen Anspruch auf Vollständigkeit.

## Technik

- HTML, CSS und JavaScript ohne Frameworks
- Schrift: Inter (Google Fonts)
- Vibration über die Vibration-API, wo verfügbar

## Hinweis

Dies ist ein Arbeitsstand aus einer Hochschularbeit an der Westsächsischen Hochschule Zwickau. Rückmeldungen sind willkommen.
