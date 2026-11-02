# BLOCKWORLD

Ein eigenständiges 3D-Voxel-Sandbox-Spiel für den Desktop-Browser. Das Projekt verwendet HTML, CSS und JavaScript; die 3D-Darstellung läuft mit Three.js.

## Spielen

- Am einfachsten über GitHub Pages veröffentlichen oder lokal mit einem kleinen Webserver starten.
- Danach `index.html` im aktuellen Desktop-Browser öffnen.
- Für die 3D-Grafik und Schriftarten ist beim Laden eine Internetverbindung erforderlich (Three.js und Google Fonts werden extern geladen).
- Im Hauptmenü **Welt erstellen / spielen** wählen, einen Weltnamen eingeben und mit der Maus ins Spiel wechseln.

## Spielsysteme

- Prozedural erzeugte, 56 × 56 Blöcke große Landschaft mit unterschiedlichen Landschaftszonen (Wald, Ebene, Wüste und Schneegebiete).
- Über 60 auswählbare Blocktypen, darunter Holzarten, Erze, Baumaterialien, Schnee, Eis, Glas und Dekoration.
- Blöcke mit linker Maustaste abbauen und mit rechter Maustaste platzieren.
- Hotbar mit neun Schnellzugriffsfeldern sowie ein Block-Inventar zum Auswählen.
- Tag-Nacht-Beleuchtung mit wechselnder Helligkeit und Himmelsfarbe.
- First-Person-Steuerung mit Laufen, Sprinten, Springen und Mausblick.
- Individuell belegbare Tastaturaktionen, einstellbare Mausempfindlichkeit und Sichtfeld.
- Lokales Speichern und Laden über IndexedDB; Welt, Position, Hotbar, Einstellungen und Tastenbelegung bleiben auf dem Gerät.

## Standardsteuerung

| Aktion | Taste |
|---|---|
| Bewegen | W, A, S, D |
| Springen | Leertaste |
| Sprinten | Shift |
| Block abbauen | Linke Maustaste |
| Block platzieren | Rechte Maustaste |
| Inventar öffnen | E |
| Hotbar auswählen | 1–9 oder Mausrad |
| Speichern | F5 |
| Pause | Esc |

Die Tastaturbelegung lässt sich im Hauptmenü unter **Steuerung** ändern.

## Lokale Daten

Es gibt kein Benutzerkonto und keinen Spielserver. Die Welt wird im Browser-Speicher des jeweiligen Geräts abgelegt. Browserdaten löschen, privates Surfen oder ein Gerätewechsel können gespeicherte Welten entfernen. Export/Import von Spielständen ist derzeit nicht eingebaut.

## Technik und Grenzen

Der Spielcode und die Oberfläche liegen in `index.html`; Three.js wird über jsDelivr geladen. Das Projekt ist ein spielbarer Sandbox-Prototyp und kein offizielles Minecraft-Produkt. Es enthält noch kein vollständiges Survival-System, Crafting, Tiere/Gegner, Multiplayer oder unendliche Chunk-Welten. Die Welt ist derzeit eine begrenzte, prozedural generierte Karte.
