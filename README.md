# Route66 GitHub Paket v49

Fix:
- Kingston Mines wird auf der Map jetzt fest als `MusicBars` geführt.
- Neuer Daten-/Koordinaten-Cache:
  - `route66ResolvedPlacesV49`
  - `route66CategoryOverridesV49`
- Dadurch werden alte lokale Kategorie-Zuordnungen aus früheren Versionen nicht mehr verwendet.
- Zusätzlich werden bekannte Chicago-Musikspots im Code fest als MusicBars normalisiert.

Wichtig:
Nach Upload bitte einmal Hard Reload machen. Die neue Cache-Version sollte alte Marker-Daten automatisch umgehen.