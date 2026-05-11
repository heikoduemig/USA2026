# Route66 GitHub Paket v46

Fix:
- Klick auf Top Highlights / MusicBars im oberen Tagesbereich funktioniert jetzt robuster.
- Es wird nicht mehr direkt ein String im onclick verwendet.
- Stattdessen werden Tagesziele intern indexiert und über Event Delegation geöffnet.
- Der Marker wird fokussiert, geöffnet, gezoomt und kurz animiert.
- Bei kombinierten Einträgen wie `Kingston Mines oder Buddy Guy's Legends` wird der erste passende Marker geöffnet.

Cache-Version:
`route66-trip-v46-click-fix`