# BLOCKWORLD

Ein voxelbasiertes Sandbox-Spiel für den Browser – umgesetzt mit HTML, CSS und JavaScript.

## Start
- Repository herunterladen oder klonen.
- `index.html` im aktuellen Desktop-Browser öffnen.
- Für Pointer Lock und zuverlässiges lokales Speichern empfiehlt sich ein lokaler Webserver oder GitHub Pages.

## Enthalten
- 3D-Voxelwelt mit prozeduraler Landschaft und Bäumen
- Blöcke abbauen und platzieren
- Hotbar und Block-Inventar
- Kreativ- und Überlebensmodus-Auswahl
- frei belegbare Tastatursteuerung
- Maus-Empfindlichkeit, Sichtfeld und Grafikoptionen
- lokale Speicherung über IndexedDB (keine Accounts, kein eigener Server)

## Technik
Three.js wird als JavaScript-Bibliothek über jsDelivr geladen. Spielcode, Oberfläche und Logik liegen in `index.html`. Eine Internetverbindung ist beim ersten Laden erforderlich, um Three.js und die Schriftart zu laden.

## Hinweis
BLOCKWORLD ist ein eigenständiges Fan-inspiriertes Sandbox-Projekt und kein offizielles Minecraft-Produkt. Dies ist ein früher spielbarer Prototyp; weitere Systeme wie Crafting, Gegner, Tiere, echte Chunk-Generierung und ausgebaute Survival-Mechaniken können darauf aufbauen.
