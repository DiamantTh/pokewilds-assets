# Asset Downloads / Asset-Downloads

## English

### How to Download the Assets

You can download the complete PokeWilds asset collection from the [GitHub Releases page](https://github.com/DiamantTh/pokewilds-assets/releases).

### Available Downloads

We provide three different archive options:

1. **Complete Archive** (`pokewilds-assets-complete-*.zip`) - ~540 MB
   - Contains all assets including documentation and music
   - Best for complete project setup
   
2. **No Music Archive** (`pokewilds-assets-no-music-*.zip`) - ~440 MB
   - Contains all assets except the music folder
   - Useful if you plan to use custom music or want a smaller download
   
3. **Core Assets** (`pokewilds-assets-*.zip`) - ~440 MB
   - Contains only the essential game assets
   - Excludes documentation and music

### What's Included

The asset collection includes:

- **990 Pokémon** - Complete sprites, animations, and data files
  - Front and back battle sprites
  - Overworld sprites (normal and shiny variants)
  - Animation data and stat files
  
- **368 Attack Animations** - Both player and enemy perspectives
  - Move effects and battle animations
  - Status effect animations
  
- **Tile Sets** - Complete world building assets
  - Terrain tiles (grass, water, sand, snow, etc.)
  - Buildings and structures
  - Natural objects (trees, rocks, flowers)
  - Special biome tiles (caves, fairy forest, swamp, etc.)
  
- **UI Elements**
  - Menu systems
  - Battle interfaces
  - Inventory screens
  
- **Audio**
  - 100+ sound effects
  - Background music tracks (in complete archive)
  
- **Player Characters** - 24 playable characters with 6 animations each
  
- **Internationalization** - Support for multiple languages (EN, DE, FR, ES, PT)

### Usage

1. Navigate to the [Releases page](https://github.com/DiamantTh/pokewilds-assets/releases)
2. Download the archive that suits your needs
3. Extract the ZIP file to your desired location
4. Use the assets in your project (please check LICENSE for usage terms)

### Alternative: Clone the Repository

If you prefer to work with git and want version control:

```bash
git clone https://github.com/DiamantTh/pokewilds-assets.git
```

Note: The repository is approximately 539 MB in size.

---

## Deutsch

### Wie man die Assets herunterlädt

Du kannst die komplette PokeWilds-Asset-Sammlung von der [GitHub Releases-Seite](https://github.com/DiamantTh/pokewilds-assets/releases) herunterladen.

### Verfügbare Downloads

Wir bieten drei verschiedene Archiv-Optionen an:

1. **Vollständiges Archiv** (`pokewilds-assets-complete-*.zip`) - ~540 MB
   - Enthält alle Assets inklusive Dokumentation und Musik
   - Am besten für komplettes Projekt-Setup
   
2. **Archiv ohne Musik** (`pokewilds-assets-no-music-*.zip`) - ~440 MB
   - Enthält alle Assets außer dem Musik-Ordner
   - Nützlich wenn du eigene Musik verwenden möchtest oder einen kleineren Download bevorzugst
   
3. **Kern-Assets** (`pokewilds-assets-*.zip`) - ~440 MB
   - Enthält nur die essentiellen Spiel-Assets
   - Ohne Dokumentation und Musik

### Was ist enthalten

Die Asset-Sammlung umfasst:

- **990 Pokémon** - Vollständige Sprites, Animationen und Datendateien
  - Vorder- und Rückansicht für Kämpfe
  - Overworld-Sprites (normale und Shiny-Varianten)
  - Animationsdaten und Stat-Dateien
  
- **368 Attacken-Animationen** - Sowohl Spieler- als auch Gegner-Perspektive
  - Move-Effekte und Kampf-Animationen
  - Statuseffekt-Animationen
  
- **Tile-Sets** - Vollständige Weltenbau-Assets
  - Terrain-Tiles (Gras, Wasser, Sand, Schnee, etc.)
  - Gebäude und Strukturen
  - Natürliche Objekte (Bäume, Steine, Blumen)
  - Spezial-Biom-Tiles (Höhlen, Märchenwald, Sumpf, etc.)
  
- **UI-Elemente**
  - Menü-Systeme
  - Kampf-Interfaces
  - Inventar-Bildschirme
  
- **Audio**
  - 100+ Sound-Effekte
  - Hintergrundmusik-Tracks (im vollständigen Archiv)
  
- **Spieler-Charaktere** - 24 spielbare Charaktere mit je 6 Animationen
  
- **Internationalisierung** - Unterstützung für mehrere Sprachen (EN, DE, FR, ES, PT)

### Verwendung

1. Gehe zur [Releases-Seite](https://github.com/DiamantTh/pokewilds-assets/releases)
2. Lade das Archiv herunter, das deinen Anforderungen entspricht
3. Entpacke die ZIP-Datei an den gewünschten Ort
4. Verwende die Assets in deinem Projekt (bitte prüfe die LICENSE für Nutzungsbedingungen)

### Alternative: Repository klonen

Wenn du lieber mit git arbeiten und Versionskontrolle nutzen möchtest:

```bash
git clone https://github.com/DiamantTh/pokewilds-assets.git
```

Hinweis: Das Repository ist ungefähr 539 MB groß.

---

## Technical Details / Technische Details

### File Structure / Dateistruktur

```
pokewilds-assets/
├── attacks/          # Battle animations / Kampf-Animationen
├── battle/           # Battle backgrounds / Kampf-Hintergründe
├── i18n/             # Translations / Übersetzungen
├── menu/             # UI elements / UI-Elemente
├── music/            # Background music / Hintergrundmusik
├── player/           # Player sprites / Spieler-Sprites
├── pokemon/          # Pokémon data / Pokémon-Daten
├── sounds/           # Sound effects / Sound-Effekte
├── tiles/            # World tiles / Welt-Tiles
└── [root files]      # UI and effect sprites / UI- und Effekt-Sprites
```

### Supported Formats / Unterstützte Formate

- **Images / Bilder:** PNG (with transparency / mit Transparenz)
- **Audio:** OGG (Vorbis)
- **Fonts / Schriftarten:** TTF
- **Data / Daten:** ASM files, Properties files

### Asset Organization / Asset-Organisation

Each Pokémon includes / Jedes Pokémon enthält:
- Sprite files (front, back, overworld)
- Animation data (ASM files)
- Base stats and move data
- Spawn and habitat information

Each attack includes / Jede Attacke enthält:
- Player perspective animation
- Enemy perspective animation
- Frame-by-frame sprite sheets

---

## Support / Unterstützung

For issues with downloads or asset usage, please create an issue on the [GitHub Issues page](https://github.com/DiamantTh/pokewilds-assets/issues).

Bei Problemen mit Downloads oder Asset-Nutzung, erstelle bitte ein Issue auf der [GitHub Issues-Seite](https://github.com/DiamantTh/pokewilds-assets/issues).
