# Route 66 Must Stops Pack

Erweiterungspaket für deine bestehende Route-66-Webapp.

## Inhalt
- route66MustStops.js
- zusätzliche Kategorien
- Highlight-Badges
- neue ikonische Stops

## Empfohlene Kategorien
- photospot
- food
- neon
- historic_motel
- americana
- route66

## Integration

### 1. Datei einbinden
In `index.html` ergänzen:

```html
<script src="route66MustStops.js"></script>
```

### 2. Daten mergen
Im bestehenden App-Code:

```javascript
const ALL_PLACES = [
  ...window.RAW_PLACES,
  ...window.route66MustStops
];
```

### 3. Neue Highlight-Badges
Empfohlene Labels:
- 🔥 MUST SEE
- 🌃 Best at Night
- 🍔 Food Legend
- 📸 Photospot
- 🤠 Weird Americana

## Enthaltene Highlights
- Cadillac Ranch
- Blue Whale of Catoosa
- Wigwam Motel
- Roy's Motel
- Pops 66
- Gemini Giant
- Santa Monica End Sign

Perfekt für:
- Mobile Route-66 Apps
- Google Maps Integration
- GitHub Pages Deployment
- PWA Roadtrip Apps