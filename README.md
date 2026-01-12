# AwowLab

A 3D combat log visualizer for World of Warcraft. Parse and replay your raid encounters with real-time positioning, damage meters, and spell tracking.

![AwowLab Screenshot](https://img.shields.io/badge/Platform-Windows-blue) ![Version](https://img.shields.io/badge/Version-0.19.1-green)

## Quick Start

Proceed to the latest release:

https://github.com/Wobblucy/WoWLogreplayer-Public/releases/latest

1. Download `AwowLabUpdater.exe` (200 KB)
2. Put it in a folder where you want AwowLab installed
3. Double-click to run - it downloads everything automatically (~73 MB)
4. AwowLab launches when complete!

## Community

- **Discord:** https://discord.gg/ahvJ3S7XDR - Bug reports, feedback, shared triggers, HQ map textures

## What's New in v0.19.1

- **File Associations** - Double-click `.awsnap` files to open them directly in AwowLab
- **Single Instance** - Opening multiple files reuses existing AwowLab window instead of launching duplicates
- **Snapshot System** - Save and load encounter snapshots with `.awsnap` format for faster loading and sharing
- **Custom Model Support** - Load custom 3D models (.obj) for actors with full rotation/scale/offset controls
- **Settings Hub** - Unified settings panel for easier configuration of all UI components
- **UI Improvements** - Enhanced meter panels with better layout and performance

## Recent Updates

**v0.17.4:**
- **Auto-Updater Fix** - Fixed path traversal detection false positives that prevented extraction of files with ".." in filenames

**v0.17.0:**
- Improved Cooldown Tracking - Enhanced detection of charge-based spell cooldowns (Fire Blast, Rune of Power, etc.)
- Expanded Modifier Detection - Better tracking of talents and effects that modify spell cooldowns
- Updated Spell Data - Latest spell data and talent modifiers for The War Within Season 1
- PlayAlong Improvements - Friendly players rendered at 30% opacity, audio feedback for positioning errors

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
- **Custom Models** - Import .obj files for custom actor appearances
- **Snapshot Files** - Save/load encounters quickly without re-parsing logs

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
