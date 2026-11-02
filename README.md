# BLOCKWORLD

Ein voxelbasiertes 3D-Sandbox-Spiel für den Desktop-Browser. Das Projekt verwendet HTML, CSS und JavaScript mit Three.js für die 3D-Darstellung.

## Starten

- Repository über GitHub Pages veröffentlichen oder lokal mit einem Webserver starten.
- `index.html` im aktuellen Desktop-Browser öffnen.
- Für Three.js und die Schriftarten wird beim Laden eine Internetverbindung benötigt.
- Über **Welt erstellen / spielen** eine Welt anlegen. Die Modusauswahl erscheint anschließend.

## Spielmodi

### Kreativmodus
- Alle Blocktypen stehen unbegrenzt zur Verfügung.
- Bauen und Abbauen ohne Ressourcenverbrauch.

### Survivalmodus
- Blöcke abbauen, um Ressourcen zu sammeln.
- Platzierte Blöcke werden aus dem Vorrat abgezogen.
- Hunger sinkt mit der Zeit; bei leerem Hunger sinkt auch die Lebensenergie.
- Bei ausreichend gefülltem Hunger regeneriert sich die Lebensenergie langsam.
- Beerensträucher liefern Äpfel. Mit **F** kann ein Apfel gegessen werden.
- Über **C** öffnet sich die Werkbank mit Rezepten für Bretter, Stöcke, Glas, Ziegel, Steinziegel, Moosstein, Bücherregale, Laternen und Leuchtsteine.

## Welt und Animationen

- Prozedural erzeugte Karte mit 56 × 56 Blöcken und Wald-, Ebenen-, Wüsten- und Schneegebieten.
- 64+ Blocktypen, darunter verschiedene Holzarten, Erze, Baumaterialien, Schnee, Eis, Glas und Dekoration.
- Neun Schnellzugriffsfelder und Block-Inventar.
- Animierte Schafe, Kühe und Schweine mit beweglichen Beinen, Köpfen und eigenständigem Umherlaufen.
- Animierter First-Person-Arm mit Laufbewegung, Armschwung beim Bauen und Abbauen sowie Schrittbewegung der Kamera.
- Platzierte Blöcke wachsen mit einer kurzen Einblendanimation in die Welt.
- Beim Abbauen entstehen passende Partikeleffekte.
- Dynamischer Tag-Nacht-Zyklus mit veränderter Himmelsfarbe und Beleuchtung.

## Standardsteuerung

| Aktion | Taste |
|---|---|
| Bewegen | W, A, S, D |
| Springen | Leertaste |
| Sprinten | Shift |
| Block abbauen | Linke Maustaste |
| Block platzieren | Rechte Maustaste |
| Inventar | E |
| Werkbank im Survivalmodus | C |
| Apfel essen | F |
| Hotbar | 1–9 oder Mausrad |
| Speichern | F5 |
| Pause | Esc |

Tastaturaktionen lassen sich im Hauptmenü unter **Steuerung** neu belegen.

## Speichern und Datenschutz

Die Welt, Position, Hotbar, Ressourcen, Lebens-/Hungerwerte, Einstellungen und Tastenbelegung werden lokal über IndexedDB gespeichert. Es gibt kein Benutzerkonto und keinen Spielserver. Browserdaten löschen, privates Surfen oder ein Gerätewechsel können Spielstände entfernen. Ein Export/Import ist derzeit nicht vorhanden.

## Aktueller Entwicklungsstand

BLOCKWORLD ist ein spielbarer Browser-Prototyp und kein offizielles Minecraft-Produkt. Noch nicht enthalten sind unter anderem Multiplayer, unendliche Chunk-Welten, komplexe Werkzeuge mit Haltbarkeit, vollständige Gegner-KI, Höhlen-/Dungeon-Systeme und ein ausgebautes Quest-/Fortschrittssystem. Die Tiere sind derzeit friedliche, wandernde Kreaturen.