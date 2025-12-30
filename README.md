# AwowLab

A 3D combat log visualizer for World of Warcraft. Parse and replay your raid encounters with real-time positioning, damage meters, and spell tracking.

![AwowLab Screenshot](https://img.shields.io/badge/Platform-Windows-blue) ![Version](https://img.shields.io/badge/Version-0.13.0-orange)

## Features

https://youtu.be/eDb4Qo4WY7o?si=Af4eYho4K2DGWcou

- **3D Combat Visualization** - Watch your raid's positioning in real-time 3D
- **DPS/HPS Meters** - Track damage and healing with spell/target/pet breakdowns
- **Raid Frames** - See health/power bars for all raid members
- **Enemy Grid** - Monitor boss and add health
- **Death Log** - Click to jump to any player death in the timeline
- **World Maps** - Dungeon and raid maps rendered on the floor plane
- **Spell Icons** - Optional icon pack for spell history display
- **Timeline Scrubbing** - Navigate through encounters frame-by-frame
- **GCD History** - Track spell casts with customizable filtering
- **Spell Assignments** - Configure which spells appear in each UI panel
- **Wowhead Integration** - Ctrl+click any spell icon to open its Wowhead page
- **PlayAlong Mode (ALPHA)** - Practice movement by following recorded player positions

## Downloads

### Quick Start (Lite Version)
Download **AwowLab-v0.13.0-Lite.zip** from the [Releases](https://github.com/Wobblucy/WoWLogreplayer-Public/releases) page.

This includes everything you need to get started (~39 MB).

### Spell Icons (Optional)
For spell icon support, download one of these icon packs:

**Retail (recommended):**
https://drive.google.com/file/d/1X0eU_QIsGJv7ChgXj_FoACtzm1dVQlys/view?usp=drive_link

Installation:
1. Download and extract the icon pack
2. Replace the `PNG` folder in your AwowLab directory with the one from the ZIP
3. Restart AwowLab - icons will load automatically

**Note:** The PlayAlong feature requires the spell icon pack to function correctly.

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

## What's New in v0.13.0

- **Wowhead Integration** - Ctrl+click on any spell icon to open its Wowhead page in your browser
- **Improved Meters** - Combat meters now show spell, target, and pet breakdowns in tooltips
- **PlayAlong Mode (ALPHA)** - Experimental feature to practice movement by following recorded player positions. Select a player and try to match their movement during the encounter.

## Requirements

- Windows 10/11 (64-bit)
- Vulkan-compatible GPU (NVIDIA GTX 900+, AMD RX 400+, Intel Arc)
- 4GB RAM minimum

## Video Guide
https://www.youtube.com/watch?v=CKY6U37Bn1s

## Bug Reports & Feedback

Please report issues at: https://github.com/Wobblucy/WoWLogreplayer-Public/issues

## License

This software is provided as-is for personal use.

