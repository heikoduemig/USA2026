# Route 66 Music Trip · v36 Must Stops

Dieses Paket enthält die bestehende App plus eingebautes `route66MustStops.js`.

## Änderungen

- `index.html` lädt jetzt zusätzlich `route66MustStops.js`.
- Die Must-Stops werden nach `RAW_PLACES` und `musicBars` gemergt.
- Doppelte Namen werden übersprungen.
- `service-worker.js` cached die neue Datei.
- Cache wurde auf `route66-trip-v36-muststops` / `route66ResolvedPlacesV36` erhöht.

## Upload zu GitHub Pages

Alle Dateien aus diesem Ordner ins Repository laden:

- `index.html`
- `routeData.v35.js`
- `musicBars.js`
- `route66MustStops.js`
- `service-worker.js`
- `manifest.webmanifest`
- `USA 2026.kmz`

Danach im Browser einmal hart neu laden oder alte PWA-Daten löschen, damit der neue Service Worker greift.
