# Route 66 Music Trip · GitHub Paket v38

Dieses Paket enthält die aktuelle Webapp inklusive `route66MustStops.js`.

## Änderungen in v38

- `route66MustStops.js` ist eingebunden.
- Zusätzliche Must-Stops vor Austin wurden entfernt:
  - Chicago
  - St. Louis
  - Tulsa
  - Lawton
  - Austin
- Übrig bleiben Zusatz-Stops ab Texas / New Mexico / Arizona / Kalifornien.
- `service-worker.js` nutzt einen neuen Cache-Namen:
  - `route66-trip-v38-clean-cache`
- `route66MustStops.js` ist im App-Shell-Cache enthalten.

## Wichtig nach Upload auf GitHub Pages

Falls alte Marker noch sichtbar sind:

1. Website einmal hart neu laden.
2. Bei Chrome: DevTools → Application → Service Workers → Unregister.
3. Danach `Clear storage` ausführen.
4. Seite neu öffnen.

Durch die neue Cache-Version sollten normale Besucher automatisch die neue Version erhalten.
