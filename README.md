# Ball Survivor — 30 Wellen

Ein Vampire-Survivors-artiges Browser-Spiel: großes Spielfeld, automatischer Aura-Angriff, Gegner spawnen im Takt der Musik, Minibosse alle 5 und Bosse alle 10 Wellen, 17 Fähigkeiten zum Auswählen, Skin-Shop und eingebaute, komplett selbst komponierte Chiptune-Musik.

Läuft komplett im Browser, keine Installation, kein Build-Schritt, keine Abhängigkeiten. Musik-Uploads bleiben lokal im Browser der Person, die spielt — es wird nichts hochgeladen.

## Auf GitHub Pages veröffentlichen

1. Dieses Repo auf GitHub hochladen (alle Dateien im Root-Verzeichnis lassen).
2. **Settings → Pages** öffnen.
3. Unter **Source** den Branch `main` und Ordner `/ (root)` auswählen, speichern.
4. Nach ein bis zwei Minuten ist das Spiel unter `https://<dein-username>.github.io/<repo-name>/` erreichbar.

## Lokal testen

Einfach `index.html` im Browser öffnen, oder z. B. mit:

```
python3 -m http.server 8000
```

und dann `http://localhost:8000` aufrufen.

## Dateien

- `index.html` — das komplette Spiel (HTML, CSS, JavaScript in einer Datei)
- `favicon-16.png`, `favicon-32.png` — Browser-Favicon
- `apple-touch-icon.png` — Icon fürs Homescreen auf iOS/Android
- `icon-512.png` — große Version des Icons

## Hinweise

- Alle Musik-Tracks sind selbst komponiert (Web Audio API, Oszillatoren) — keine Samples, kein Copyright-Risiko.
- Alle Skins/Charaktere sind eigene, originelle Designs.
