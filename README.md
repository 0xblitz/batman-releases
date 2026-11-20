# Batman

Ein schneller Launcher für macOS: Apps, Dateien und Einstellungen suchen, im Web suchen, rechnen, Clipboard-Verlauf, Snippets und Fragen an eine KI, alles über ein Tastenkürzel.

## Download

**[Batman für Mac herunterladen](https://github.com/0xblitz/batman-releases/releases/latest/download/Batman.dmg)**

Der Link lädt immer die neueste veröffentlichte DMG. Die enthaltene App ist mit Apple Developer ID signiert und von Apple notarisiert.

Voraussetzung: macOS 14 oder neuer. Unterstützt werden Macs mit Apple Silicon und Intel-Prozessor.

## Installation

1. `Batman.dmg` per Doppelklick öffnen.
2. **Batman** auf **Programme** ziehen.
3. Die App aus **Programme** starten. Batman hat kein Fenster im Dock; in der Menüleiste erscheint eine Fledermaus.

Falls macOS meldet, dass nur Apps aus dem App Store erlaubt sind: **Systemeinstellungen → Datenschutz & Sicherheit → Apps erlauben von → App Store & bekannte Entwickler**. Bei einer anderen Warnung hilft [Apples Erklärung zu den verschiedenen Meldungen](https://support.apple.com/de-de/102445).

## Einrichten

- **Kürzel:** Batman öffnet sich mit ⌘Leertaste. Das Kürzel gehört zunächst Spotlight. Entweder Spotlight umstellen (**Systemeinstellungen → Tastatur → Tastaturkurzbefehle → Spotlight**) oder in Batman ein anderes wählen (Fledermaus in der Menüleiste → **Einstellungen … → Allgemein**).
- **Beim Anmelden starten:** in denselben Einstellungen einschalten.
- **Bedienungshilfen:** Beim ersten Einfügen aus dem Clipboard-Verlauf fragt macOS nach der Freigabe. Sie ist nötig, damit Batman in andere Apps einfügen kann.
- **Festplattenvollzugriff** (optional): für Chrome-Lesezeichen und die Dateisuche in Dokumente und Schreibtisch.
- **KI** (optional): einen eigenen API-Schlüssel von Anthropic oder OpenAI unter **Einstellungen … → KI** eintragen.

## Bedienung in Kürze

| Eingabe | Ergebnis |
|---|---|
| Text | Apps und Systemeinstellungen |
| Leertaste vorweg | Dateien und Ordner |
| `<` vorweg | Chrome-Lesezeichen |
| `g wetter` | Google-Suche |
| `5+5*2` | Rechner |
| ⌥Leertaste | Clipboard-Verlauf |
| ⌥⇧Leertaste | Snippets |
| `ai`, dann die Frage | Antwort der KI |
| `coffee`, `coffee 30` | Mac wach halten |
| `clean` | Tastatur und Maus eine Minute sperren, zum Reinigen |

## Automatische Updates

Batman prüft täglich auf neue Versionen, lädt sie im Hintergrund und spielt sie ein; die App startet dabei kurz neu. Über die Fledermaus in der Menüleiste → **Nach Updates suchen …** lässt sich die Prüfung auch von Hand starten.

Die ZIP-Datei und `appcast.xml` in den Release-Dateien dienen dem automatischen Updater.

GitHub liefert nur Installationsdateien und Update-Informationen. Einstellungen, Clipboard-Verlauf und API-Schlüssel bleiben auf dem Mac.
