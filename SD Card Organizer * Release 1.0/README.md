# SD Card Organizer

A macOS menu bar app that automatically organizes photos and videos from your SD card.

## License

Copyright (c) 2026 Scott Estes. All rights reserved.

This software is provided for free personal use, "as is", without warranty of any kind.

### You May:
- Download and use SD Card Organizer for free
- Share the download link with friends and family

### You May NOT:
- Redistribute, repackage, or resell this software
- Claim this software as your own
- Include this software in commercial products or services

### Donations

If you find SD Card Organizer useful, consider supporting its development!

[Buy me a coffee on Venmo](https://venmo.com/u/Scott-estes-9)

Your support helps keep the app free and updated!


## Features

- **Automatic Detection**: Detects when an SD card is inserted and automatically starts organizing
- **File Sorting**: Organizes files into folders by type:
  - **JPG** - JPEG images
  - **TIFF** - TIFF/HEIF images
  - **RAW** - RAW files from all major camera brands
  - **VIDEO** - MOV, MP4, M4V, AVI, MKV, WMV, FLV, WEB
- **Customizable Destination**: Choose where files are saved (default: Desktop)
- **Flexible Naming**: Customizable folder naming with tokens like `{date}`, `{drive}`, `{time}`
- **Progress Tracking**: See real-time progress with file count and transfer speed
- **Notifications**: Get notified when organization is complete
- **Storage Info**: See remaining SD card space after transfer
- **Refresh Detection**: Manual refresh to re-detect SD cards after permission issues

## Requirements

- macOS 12.0 or later
- SD card or card reader

## Installation

Download Pre-built App

1. Download the `.zip` file
2. Unzip and drag `SD Card Organizer.app` to your Applications folder
3. **First launch**: Right-click the app and select "Open" to bypass Gatekeeper
4. Or go to System Settings → Privacy & Security → scroll down → click "Open Anyway"


## How to Use

### First Time Setup
1. Launch **SD Card Organizer** from Applications
2. The app icon (SD card) appears in your menu bar
3. Click the icon and select **Settings...** to configure:
   - **Destination Folder**: Where organized files go (default: Desktop)
   - **Folder Naming**: How folders are named (e.g., `2024-01-15_SDCARD`)
   - **Create Subfolders**: Enable/disable JPG/RAW/VIDEO subfolders
   - **Move vs Copy**: Choose to move files (removes from SD card) or copy

### Normal Usage
1. Insert your SD card
2. The app automatically detects it
3. Watch the menu bar for progress updates
4. Get a notification when complete
5. Find your organized files in the destination folder

### Menu Bar Options
- **Status**: Shows current activity
- **Last Card**: Name of the last SD card processed
- **Refresh SD Card Detection**: Re-scan for mounted SD cards (Cmd+R)
- **Settings...**: Open settings window
- **Quit**: Exit the app

## Supported RAW Formats

SD Card Organizer supports RAW files from all major camera brands:

| Brand | Formats |
|-------|---------|
| Fujifilm | .raf |
| Sony | .arw, .srw, .sr2 |
| Canon | .cr2, .cr3 |
| Nikon | .nef, .nrw |
| Ricoh/Pentax | .dng, .raw, .pef |
| Olympus/Panasonic | .orf, .rw2 |
| Leica | .dng, .rwl |

## Supported Image Formats

| Format | Extensions |
|--------|------------|
| JPEG | .jpg, .jpeg |
| TIFF | .tiff, .tif |
| HEIF | .heic, .heif |

## Naming Tokens

Available tokens for folder naming:
- `{date}` - Current date (e.g., 2024-01-15)
- `{time}` - Current time (e.g., 14-30-00)
- `{drive}` - SD card volume name

Example: `{date}_{drive}` → `2024-01-15_SDCARD`

## Troubleshooting

### App doesn't detect SD card
- Make sure the app is running (check menu bar)
- Click **Refresh SD Card Detection** in the menu (Cmd+R) to re-scan
- Try unplugging and replugging the SD card
- Check System Settings → Privacy & Security for Full Disk Access if needed

### Files not being copied
- Ensure you have permission to read the SD card
- Check if destination folder is writable
- Verify SD card is not write-protected

### App won't open
- Right-click the app and select "Open"
- Go to System Settings → Privacy & Security → click "Open Anyway"

## Privacy

- SD Card Organizer only accesses removable drives when you insert one
- No data is sent to any server
- All processing happens locally on your Mac

## Support

For issues or feature requests, ask Scott 
