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

## Gestaltung und Vertiefung, dritte Fassung
Die Website ist eine Ergänzung des Plakats: identische Titel, Farben, originale Symbolflächen und das dreizeilige Lernbeispiel. Abstände ersetzen dekorative Trennlinien; nur der Zeitstrahl hat einen funktionalen Verbinder. Alle Kernaussagen sind sichtbar, zusätzliche Erklärungen und Beispiele stehen in nativen Aufklappern.

Neu: Hintergründe zu allen 15 Stationen, Pixel/Label/Loss, Gewichte und Optimierer, Overfitting und Testdaten, zehn Alltagsbeispiele zu Chancen und Risiken sowie vier ausführlichere Zukunftsszenarien mit Grenzen. Eigene Unterrichtsbeispiele sind keine Studienergebnisse. Quellennachweise sind separat in QUELLEN.md dokumentiert; auf den Webseiten werden keine Quellenhinweise eingeblendet. Bestehende Seitenadressen bleiben erhalten.

## Faktencheck vom 11.11.2026

Alle vier Seiten einschließlich Vertiefungen und alle fünf Plakate wurden quellenbasiert geprüft. Präzisiert wurden historische Einordnung, das schematische überwachte Lernbeispiel, Test/Generalisierung, Online-Datenübertragung, Ressourcenbedarf und bedingte Zukunftsaussagen. Die 15 historischen Stationen bleiben eine Auswahl bis 2022. Quellen und Einschränkungen stehen in QUELLEN.md. Das unveränderte Layout und die bestehenden vier Seitenadressen bleiben erhalten.
