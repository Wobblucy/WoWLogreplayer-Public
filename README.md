# AwowLab

A 3D combat log visualizer for World of Warcraft. Parse and replay your raid encounters with real-time positioning, damage meters, and spell tracking.

![AwowLab Screenshot](https://img.shields.io/badge/Platform-Windows-blue) ![Version](https://img.shields.io/badge/Version-0.14.0-orange)

## Community

- **YouTube:** https://www.youtube.com/@AWowlab - Tutorials and feature demos
- **Discord:** https://discord.gg/ahvJ3S7XDR - Bug reports, feedback, shared triggers, HQ map textures

## Features

- **3D Combat Visualization** - Watch your raid's positioning in real-time 3D
- **DPS/HPS Meters** - Track damage and healing with spell/target/pet breakdowns
- **Raid Frames** - See health/power bars for all raid members
- **Enemy Grid** - Monitor boss and add health
- **Death Log** - Click to jump to any player death in the timeline
- **World Maps** - Dungeon and raid maps rendered on the floor plane
- **Spell Icons** - 8,000+ icons included, optional full pack available
- **Timeline Scrubbing** - Navigate through encounters frame-by-frame
- **GCD History** - Track spell casts with customizable filtering
- **Spell Assignments** - Configure which spells appear in each UI panel
- **Wowhead Integration** - Ctrl+click any spell icon to open its Wowhead page
- **PlayAlong Mode (ALPHA)** - Practice movement by following recorded player positions

## Downloads

### Latest Release
Download **AwowLab-v0.14.0.zip** from the [Releases](https://github.com/Wobblucy/WoWLogreplayer-Public/releases) page.

This release includes **8,000+ spell icons** covering all class abilities, current season content, and recent spells (~59 MB).

**Note:** This release targets patch 12.0 spell data. Some icons from 11.2 or earlier may be missing.

### Full Icon Pack (Optional)
If you encounter missing icons or need coverage for older content:

https://drive.google.com/file/d/1X0eU_QIsGJv7ChgXj_FoACtzm1dVQlys/view?usp=drive_link

Installation:
1. Download and extract the icon pack
2. Replace the `PNG` folder in your AwowLab directory
3. Restart AwowLab

[Video guide](https://www.youtube.com/watch?v=CKY6U37Bn1s)

**Note:** The PlayAlong feature requires spell icons to function correctly.

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

## What's New in v0.14.0

- **Bundled Spell Icons** - 8,000+ icons included directly in the release
- **Smaller Download** - Curated icon pack reduces size from 150MB to 59MB
- **12.0 Spell Data** - Updated for current patch content

## Requirements

- Windows 10/11 (64-bit)
- Vulkan-compatible GPU (NVIDIA GTX 900+, AMD RX 400+, Intel Arc)
- 4GB RAM minimum

## Bug Reports & Feedback

- **Discord:** https://discord.gg/ahvJ3S7XDR
- **GitHub Issues:** https://github.com/Wobblucy/WoWLogreplayer-Public/issues

## License

This software is provided as-is for personal use.
