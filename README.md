# Vörstetten ↔ Freiburg ÖPNV & P+R – PWA

## Dateien
```
voerstetten-pwa/
├── index.html       ← Haupt-App
├── manifest.json    ← PWA-Manifest
├── sw.js            ← Service Worker (Offline-Cache)
└── icons/
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png   ← iOS Home Screen
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```

## Deployment auf GitHub Pages (5 Minuten)

1. Neues Repo auf github.com anlegen, z.B. `voerstetten-transit`
2. Alle Dateien hochladen (inkl. icons/-Ordner)
3. Settings → Pages → Branch: main → Save
4. URL: `https://fsb22.github.io/voerstetten-transit/`

## iPhone Installation

1. URL in **Safari** öffnen (nicht Chrome!)
2. Unten auf das **Teilen-Symbol** tippen (Rechteck mit Pfeil)
3. **„Zum Home-Bildschirm"** wählen
4. Name bestätigen → „Hinzufügen"

→ App erscheint mit eigenem Icon, startet vollbild ohne Browser-Leiste.

## Hinweise
- Verbindungszeiten sind KI-basiert (kein Echtzeit-Feed)
- Offline: App-Shell funktioniert, API-Abfragen benötigen Internet
- API-Key wird automatisch von Claude.ai injiziert (nur auf claude.ai nutzbar)
  → Für eigenständigen Betrieb: Anthropic API Key in index.html eintragen
