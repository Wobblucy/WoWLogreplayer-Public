# AwowLab

A 3D combat log visualizer for World of Warcraft. Parse and replay your raid encounters with real-time positioning, damage meters, and spell tracking.

![AwowLab Screenshot](https://img.shields.io/badge/Platform-Windows-blue) ![Version](https://img.shields.io/badge/Version-0.10.1--beta-orange)

## Features

https://youtu.be/eDb4Qo4WY7o?si=Af4eYho4K2DGWcou

- **3D Combat Visualization** - Watch your raid's positioning in real-time 3D
- **DPS/HPS Meters** - Track damage and healing with spell breakdowns
- **Raid Frames** - See health/power bars for all raid members
- **Enemy Grid** - Monitor boss and add health
- **Death Log** - Click to jump to any player death in the timeline
- **World Maps** - Dungeon and raid maps rendered on the floor plane
- **Spell Icons** - Optional icon pack for spell history display
- **Timeline Scrubbing** - Navigate through encounters frame-by-frame
- **GCD History** - Track spell casts with customizable filtering
- **Spell Assignments** - Configure which spells appear in each UI panel

## Downloads

### Quick Start (Lite Version)
Download **AwowLab-v0.10.1-beta-Lite.zip** from the [Releases](https://github.com/Wobblucy/WoWLogreplayer-Public/releases) page.

This includes everything you need to get started (~29 MB).

### Spell Icons (Optional)
For spell icon support, download one of these icon packs:

#### Video Guide
https://www.youtube.com/watch?v=CKY6U37Bn1

**Retail (recommended for most users):**
[Download Retail Icons](https://drive.google.com/file/d/1ATJqh8SAmv3JDCT79-e5dU1hvi1kNlFb/view?usp=drive_link)

**Beta (smaller file, excludes removed abilities like Cloudburst):**
[Download Beta Icons](https://drive.google.com/file/d/1TIeLQ6Dt7QBSMeqBPAqY_Dy5e_q6ABQ0/view?usp=drive_link)

Installation:
1. Download and extract the icon pack
2. Replace the `PNG` folder in your AwowLab directory with the one from the ZIP
3. Restart AwowLab - icons will load automatically

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
- **File Menu** - Change encounter or log file

## Requirements

- Windows 10/11 (64-bit)
- Vulkan-compatible GPU (NVIDIA GTX 900+, AMD RX 400+, Intel Arc)
- 4GB RAM minimum

## Bug Reports & Feedback

Please report issues at: https://github.com/Wobblucy/WoWLogreplayer-Public/issues

## License

This software is provided as-is for personal use.
