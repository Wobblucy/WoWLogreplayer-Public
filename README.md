# AwowLab

A 3D combat log visualizer for World of Warcraft. Parse and replay your raid encounters with real-time positioning, damage meters, and spell tracking.

![AwowLab Screenshot](https://img.shields.io/badge/Platform-Windows-blue) ![Version](https://img.shields.io/badge/Version-0.7.0--alpha-orange)

## Preview

https://github.com/user-attachments/assets/afca0faf-cb98-4675-ab91-565dcdecef63

https://github.com/user-attachments/assets/8197c2d8-3ebb-4143-843c-8b4bff43d357

https://github.com/user-attachments/assets/95a8c0a3-6512-4202-99ee-f4a80251a111

https://github.com/user-attachments/assets/98794ac9-029c-4e0b-af06-c892e64ce4b8

## Features

- **3D Combat Visualization** - Watch your raid's positioning in real-time 3D
- **WarcraftLogs Integration** - Load reports directly from WarcraftLogs URLs
- **DPS/HPS Meters** - Track damage and healing with spell breakdowns
- **Actor Breakdown Panel** - Detailed spell-by-spell analysis with interactive time range selection
- **Raid Frames** - See health/power bars for all raid members
- **Enemy Grid** - Monitor boss and add health
- **Death Log** - Click to jump to any player death in the timeline
- **World Maps** - Dungeon and raid maps rendered on the floor plane
- **Spell Icons** - Optional icon pack for spell history display
- **Timeline Scrubbing** - Navigate through encounters frame-by-frame

![Screenshot 2025-12-19 004159](https://github.com/user-attachments/assets/08f7ad0a-6811-4213-a8f6-ef84502b9435)

## Downloads

### Quick Start (Lite Version)
Download **AwowLab-v0.7.0-Alpha-Lite.zip** from the [Releases](https://github.com/Wobblucy/WoWLogreplayer-Public/releases) page.

This includes everything you need to get started (~16 MB).

### Spell Icons (Optional)
For spell icon support, download the PNG pack from Google Drive:

**[Download PNG Pack (71 MB)](https://drive.google.com/file/d/1ATJqh8SAmv3JDCT79-e5dU1hvi1kNlFb/view?usp=drive_link)**

**[Youtube Guide to Show Icon Pack Installtion](https://www.youtube.com/watch?v=CKY6U37Bn1s)**


Installation:
1. Download and extract the PNG.zip
2. Replace the `PNG` folder in your AwowLab directory with the one from the ZIP
3. Restart AwowLab - icons will load automatically

## Usage

1. Run `AwowLab.exe`
2. Choose your data source:
   - **Local File** - Browse for your WoW combat log (usually in `World of Warcraft\_retail_\Logs\`)
   - **WarcraftLogs** - Paste a WarcraftLogs report URL
3. Select an encounter from the list
4. Use the timeline to scrub through the fight

### Controls
- **Right Mouse Drag** - Rotate camera
- **Left/Middle Drag** - Pan camera
- **Mouse Wheel** - Zoom in/out
- **File Menu** - Change encounter or log file

## Requirements

- Windows 10/11 (64-bit)
- Vulkan-compatible GPU (NVIDIA GTX 900+, AMD RX 400+, Intel Arc)
- 4GB RAM minimum

## Bug Reports & Feedback

Please report issues at: https://github.com/Wobblucy/WoWLogreplayer-Public/issues

## License

This software is provided as-is for personal use.
