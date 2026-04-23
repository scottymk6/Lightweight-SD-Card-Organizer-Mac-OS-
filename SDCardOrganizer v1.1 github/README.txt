SD CARD ORGANIZER
Version 1.1

A macOS menu bar app that automatically organizes photos from SD cards.

INSTALLATION
1. Install XcodeGen: brew install xcodegen
2. Copy the SDCardOrganizer folder to your Mac
3. Open terminal in the SDCardOrganizer folder
4. Run: xcodegen generate
5. Open SDCardOrganizer.xcodeproj in Xcode
6. Build and Run (Cmd+R)

USAGE
The app runs as a menu bar agent (no dock icon). Look for the SD card icon in your menu bar.
- Click the icon to access settings and options
- Insert an SD card to automatically organize photos
- Use "Refresh Card Detection" if cards aren't detected

FEATURES
- Auto-Detection - Automatically detects SD cards when inserted
- File Organization - Sorts photos into JPG, TIFF, RAW, and VIDEO folders
- EXIF Capture Date - Names folders based on photo capture date
- Flexible Naming - Custom folder naming patterns
- Duplicate Handling - Skip duplicate files or overwrite them
- Move or Copy - Choose to move or copy files
- Eject Prompt - Option to eject the card after transfer
- Volume Blacklist - Ignore specific volumes

SUPPORTED FILE FORMATS
JPG/JPEG: .jpg, .jpeg
TIFF/HEIF: .tiff, .tif, .heic, .heif
RAW: .raf (Fujifilm), .arw/.srw/.sr2 (Sony), .cr2/.cr3 (Canon), .nef/.nrw (Nikon), .dng/.raw/.pef (Pentax), .orf (Olympus), .rw2 (Panasonic), .rwl (Leica)
Video: .mov, .mp4, .m4v, .avi, .mkv, .wmv, .flv, .webm

FOLDER NAMING TOKENS
{date} - Date (YYYY-MM-DD)
{time} - Time (HH-mm-ss)
{drive} - Volume name
{date_start} - Earliest EXIF date
{date_end} - Latest EXIF date

SETTINGS
- Destination Folder: Where organized photos go (default: Desktop)
- Folder Naming Pattern: How folders are named
- Photo Capture Date: Use EXIF date for folder naming
- Date Mode: Earliest, latest, or date range
- Read EXIF from: JPG first, RAW first, or either
- Skip Duplicates: Don't overwrite existing files
- Create Subfolders: JPG, TIFF, RAW, VIDEO subfolders
- Move Files: Move instead of copy
- Prompt to Eject: Ask to eject card after transfer
- Ignored Volumes: Volumes to skip

VERSION HISTORY
v1.1 - Added EXIF capture date folder naming, volume blacklist, improved drive detection, duplicate file detection
v1.0 - Initial release

LICENSE
Copyright (c) 2026 Scott Estes. All rights reserved.
This software is provided for free personal use, "as is", without warranty of any kind.