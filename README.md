# AwowLab

A 3D combat log visualizer for World of Warcraft. Parse and replay your raid encounters with real-time positioning, damage meters, and spell tracking.

![AwowLab Screenshot](https://img.shields.io/badge/Platform-Windows-blue) ![Version](https://img.shields.io/badge/Version-0.17.4-green)

## Quick Start

Proceed to the latest release:

https://github.com/Wobblucy/WoWLogreplayer-Public/releases/latest

1. Download `AwowLabUpdater.exe` (200 KB)
2. Put it in a folder where you want AwowLab installed
3. Double-click to run - it downloads everything automatically (~86 MB)
4. AwowLab launches when complete!

## Community

- **Discord:** https://discord.gg/ahvJ3S7XDR - Bug reports, feedback, shared triggers, HQ map textures

## What's New in v0.17.4

- **Auto-Updater Fix** - Fixed path traversal detection false positives that prevented extraction of files with ".." in filenames (e.g., spell icons)

## Recent Updates

**v0.17.0:**
- Improved Cooldown Tracking - Enhanced detection of charge-based spell cooldowns (Fire Blast, Rune of Power, etc.)
- Expanded Modifier Detection - Better tracking of talents and effects that modify spell cooldowns
- Updated Spell Data - Latest spell data and talent modifiers for The War Within Season 1
- PlayAlong Improvements - Friendly players rendered at 30% opacity, audio feedback for positioning errors
- UI Polish - Refined landing page and card rendering

## Features

- **3D Combat Visualization** - Watch your raid's positioning in real-time 3D
- **DPS/HPS Meters** - Track damage and healing with spell/target/pet breakdowns
- **Raid Frames** - See health/power bars for all raid members
- **Enemy Grid** - Monitor boss and add health
- **Death Log** - Click to jump to any player death in the timeline
- **World Maps** - Dungeon and raid maps rendered on the floor plane
- **Spell Icons** - 8,000+ icons included automatically
- **Timeline Scrubbing** - Navigate through encounters frame-by-frame
- **GCD History** - Track spell casts with customizable filtering
- **Cooldown Panel** - Monitor personal and raid-wide cooldowns with charge tracking
- **Spell Assignments** - Configure which spells appear in each UI panel
- **Wowhead Integration** - Ctrl+click any spell icon to open its Wowhead page
- **Auto-Updater** - Click "Check for Updates" to get the latest version
- **PlayAlong Mode (ALPHA)** - Practice movement by following recorded player positions

## Usage

1. Run `AwowLab.exe`
2. Click "Local File" on the landing page
3. Select your WoW combat log file (usually in `World of Warcraft\_retail_\Logs\`)
4. Choose an encounter from the list
5. Use the timeline to scrub through the fight

### Controls
- **Right Mouse Drag** - Rotate camera
- **Left/Middle Drag** - Pan camera
- **Mouse Wheel** - Zoom in/out
- **Space** - Play/Pause timeline
- **F5** - Refresh encounters
- **Ctrl+Click Spell Icon** - Open Wowhead spell page
- **File Menu** - Change encounter or log file


## Requirements

- Windows 10/11 (64-bit)
- Vulkan-compatible GPU (NVIDIA GTX 900+, AMD RX 400+, Intel Arc)

## Bug Reports & Feedback

- **Discord:** https://discord.gg/ahvJ3S7XDR
- **GitHub Issues:** https://github.com/Wobblucy/WoWLogreplayer-Public/issues

## License

This software is provided as-is for personal use.
