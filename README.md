# KI-Wandzeitung
Vier responsive, deutschsprachige Themen-Seiten zur Affinity-Wandzeitung. HTML, CSS und Vanilla JavaScript, ohne Buildschritt oder Framework.

## Lokal ansehen
Im Website-Ordner `python3 -m http.server 4173` ausführen und `http://localhost:4173` öffnen.

## Veröffentlichen
GitHub Pages: `main`, `/ (root)`. `.nojekyll` deaktiviert Jekyll. Alle Pfade sind relativ und funktionieren unter `/ki-wandzeitung/`. HTML, `styles.css` und `app.js` direkt bearbeiten; Änderungen auf `main` aktualisieren Pages.

## Seiten
- `geschichte.html` – 15 ausgewählte historische Stationen
- `lernen.html` – Lernen anhand handgeschriebener Ziffern
- `chancen-risiken.html` – fünf Gegenüberstellungen
- `zukunft.html` – erprobte Entwicklungen und bedingte Möglichkeiten

`index.html` führt zur Geschichte. Das Center hat keine Web-Seite. Native `details` und alle Texte funktionieren ohne JavaScript. Animationen beachten `prefers-reduced-motion`.

## Herkunft
Inhalte, Palette und Diagramme aus der vom Auftraggeber am 11.11.2026 ausgewählten, live geöffneten Affinity-Fassung, einschließlich ungespeicherter Änderungen. Quellen und Einordnung separat in QUELLEN.md. Ziffern und Balken sind schematische Illustrationen, keine Messdaten oder tatsächlich ausgeführtes Modell.

Bootstrap Icons v1.13.1 (Original-SVG-Geometrie, MIT; siehe `assets/icons/LICENSE`). Inter und Instrument Serif: SIL Open Font License, siehe `assets/fonts/`. Inhalte und Gestaltung erhalten keine pauschale Open-Source-Lizenz.

Keine externen Skripte, Font-Dienste, Analyse- oder Trackingdienste. `.local/` enthält nur lokale Arbeitsdaten und wird nicht veröffentlicht.

## Gekürzte Plakatbegleitung, 11.11.2026

Die Website konzentriert sich wieder auf die Kernaussagen und Grafiken der Wandzeitung. Zusätzliche Einleitungen, Abschlusskästen und die drei Epochenüberschriften sind entfernt. Die 15 Stationen behalten je einen kurzen optionalen Hintergrundsatz. Lernen bietet zwei kurze Aufklapper; vielfältige Handschriften werden direkt im dritten Lernschritt erwähnt. Zukunft zeigt ausschließlich die vier Plakatthemen mit heutigen Ansätzen und bedingten Möglichkeiten unter den knappen Labels „Heute“ und „Möglich“. Chancen und Risiken besteht ausschließlich aus den fünf Gegenüberstellungen des Plakats. Mobile Abstände innerhalb der Lern-, Vergleichs- und Zukunftsgruppen sind enger; zwischen Themen bleibt mehr Luft. Navigation und vier Seitenadressen bleiben erhalten.

Der lokale Generator `.local/build.py` reproduziert diese Fassung. Quellen und fachliche Einschränkungen bleiben separat in QUELLEN.md dokumentiert. Die sichtbare Oberfläche enthält weiterhin keine Quellenhinweise.

## Faktencheck vom 11.11.2026

Alle vier Seiten einschließlich Vertiefungen und alle fünf Plakate wurden quellenbasiert geprüft. Präzisiert wurden historische Einordnung, das schematische überwachte Lernbeispiel, Test/Generalisierung, Online-Datenübertragung, Ressourcenbedarf und bedingte Zukunftsaussagen. Die 15 historischen Stationen bleiben eine Auswahl bis 2022. Quellen und Einschränkungen stehen in QUELLEN.md. Das unveränderte Layout und die bestehenden vier Seitenadressen bleiben erhalten.
