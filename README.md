# AwowLab - WoW Combat Log Visualizer

Visualize your World of Warcraft raid encounters in stunning 3D. Watch combat positioning, track spell casts, and analyze your gameplay like never before.

![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Downloads](https://img.shields.io/github/downloads/Wobblucy/WoWLogreplayer-Public/total)
![License](https://img.shields.io/badge/license-Proprietary-red)

## Features

- **3D Encounter Replay** - Watch boss fights from an RTS-style camera
- **GCD History** - See what spells players are casting with spell icons
- **Timeline Controls** - Scrub through combat, adjust playback speed
- **Player Focus** - Follow individual players through the fight
- **2D Minimap** - Top-down view of positioning
- **Encounter Switching** - Quickly swap between different boss pulls

## Download

**[Download Latest Release](https://github.com/Wobblucy/WoWLogreplayer-Public/releases/latest)**

### Two Download Options

#### Lightweight Build (~3.5MB) - Recommended
- Core application with all features
- Spell icons show as gray placeholders
- Fast download and install

#### Spell Icon Pack (~218MB) - Optional
- Adds spell icon images for visual clarity
- Extract to same folder as AwowLab.exe
- Automatically detected on startup

### System Requirements

- **Windows 10/11** (64-bit)
- **Vulkan-compatible GPU** (NVIDIA GTX 900+ / AMD RX 400+ / Intel Arc)
- **4GB RAM** minimum
- **5MB** disk space (+ 218MB for icon pack if installed)

## Quick Start

1. **Download** the latest `AwowLab-vX.X.X-alpha.zip` from [Releases](https://github.com/Wobblucy/WoWLogreplayer-Public/releases)
2. **Extract** the ZIP file to a folder
3. **Run** `AwowLab.exe`
4. **Select** a combat log file:
   - Default location: `World of Warcraft\_retail_\Logs\`
   - Enable advanced combat logging in-game: `/combatlog`
5. **Choose** an encounter or view the full log
6. **Enjoy** the 3D replay!

### Adding Spell Icons (Optional)

1. **Download** `AwowLab-IconPack-vX.X.X.zip` from the same release
2. **Extract** to the same folder as `AwowLab.exe`
3. **Verify** folder structure:
   ```
   AwowLab.exe
   PNG\
     Spell Icons\
   ```
4. **Restart** AwowLab - icons load automatically

## Controls

### Camera
| Control | Action |
|---------|--------|
| **Right Mouse Drag** | Rotate camera |
| **Left/Middle Drag** | Pan camera |
| **Mouse Wheel** | Zoom in/out |

### Interface
- **File → Change Encounter** - Switch between encounters
- **View Menu** - Show/hide UI panels
- **Timeline Slider** - Jump to any point in combat
- **Playback Speed** - Speed up or slow down replay

## How to Use

### Enabling Combat Logging in WoW

1. Type `/combatlog` in-game to start logging
2. Play through your raid/dungeon
3. Type `/combatlog` again to stop
4. Find your log in `World of Warcraft\_retail_\Logs\`

### Loading an Encounter

1. Launch AwowLab
2. Click **Select File** and browse to your combat log
3. Wait for encounter detection (auto-detects boss fights)
4. Select the encounter you want to visualize
5. Use playback controls to watch the fight

### UI Panels

- **Playback Controls** - Timeline scrubbing, play/pause, speed controls
- **Creatures/Vehicles/Pets** - List of all actors in combat with color coding
- **Filters** - Toggle rendering of specific actor types
- **Player Focus** - Select a player to follow with the camera
- **GCD History** - View recent spell casts for the selected player
- **2D Minimap** - Alternative top-down view

## FAQ

**Q: My GPU doesn't support Vulkan, will this work?**
A: Unfortunately no. AwowLab requires Vulkan 1.3+. Most GPUs from 2015+ support this.

**Q: Does this work with Classic WoW?**
A: Currently only tested with Retail WoW. Classic support may come in the future.

**Q: Can I use this during raids?**
A: AwowLab reads log files **after** the encounter. There is no way to 'refresh' a log without closing and restsrting the .exe. 

**Q: Is this against WoW's Terms of Service?**
A: No. This tool only reads combat log files that Blizzard provides. It does not modify game files or memory.

**Q: Why are some spell icons missing?**
A: Spell icon coverage should be complete with the provided icon pack. If an icon is missing please create a github issue. 

## Known Issues

- No way to 'refresh' the log being parsed.
- No way to filter friendly creatures.
- Terminal used for debug on launch in release build.

## Changelog

See [Releases](https://github.com/Wobblucy/WoWLogreplayer-Public/releases) for version history and changes.

## Links

- **Source Code**: Private repository (contact for access)
- **Issues**: [Report bugs](https://github.com/Wobblucy/WoWLogreplayer-Public/issues)
- **Discussions**: [Ask questions](https://github.com/Wobblucy/WoWLogreplayer-Public/discussions)

## License

Copyright © 2024. All rights reserved.

This software is provided as-is for personal, non-commercial use. Redistribution or modification is prohibited.

## Acknowledgments

Built with:
- **Vulkan** - Graphics rendering
- **ImGui** - User interface
- **GLFW** - Windowing system

---

**Note**: This application analyzes combat log files generated by World of Warcraft. It does not connect to Battle.net or access the game client in any way.

*World of Warcraft © Blizzard Entertainment. This project is not affiliated with or endorsed by Blizzard Entertainment.*
