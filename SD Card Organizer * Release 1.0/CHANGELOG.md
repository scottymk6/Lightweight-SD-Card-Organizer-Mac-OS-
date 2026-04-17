# Changelog

All notable changes to SD Card Organizer will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

### Added
- **SD Card Detection**: Automatic detection when SD card is inserted using FSEvents
- **Refresh Detection**: Manual refresh option to re-detect SD cards and re-prompt for permissions if previously denied
- **File Sorting**: Organizes files into folders by type:
  - JPG - JPEG images (.jpg, .jpeg)
  - TIFF - TIFF/HEIF images (.tiff, .tif, .heic, .heif)
  - RAW - RAW files from all major camera brands
  - VIDEO - Video files (.mov, .mp4, .m4v, .avi, .mkv, .wmv, .flv, .webm)
- **Supported RAW Formats**:
  - Fujifilm: .raf
  - Sony: .arw, .srw, .sr2
  - Canon: .cr2, .cr3
  - Nikon: .nef, .nrw
  - Ricoh/Pentax: .dng, .raw, .pef
  - Olympus/Panasonic: .orf, .rw2
  - Leica: .dng, .rwl
- **Customizable Destination Folder**: Choose where organized files are saved
- **Flexible Folder Naming**: Custom naming patterns with tokens ({date}, {time}, {drive})
- **Progress Tracking**: Real-time progress in menu bar with file count and transfer speed
- **Menu Bar Percentage**: Shows transfer progress percentage on the SD card icon
- **Notifications**: Alert when organization is complete
- **Storage Info**: Shows remaining SD card space after transfer
- **Move vs Copy Option**: Choose to move files (removes from SD) or copy
- **Dynamic Subfolder Creation**: Only creates folders for file types that are found
- **SD Card Eject Prompt**: Option to prompt user to eject SD card after transfer
- **Settings Persistence**: Remembers user preferences across sessions

### Changed
- App runs as a menu bar agent (no dock icon)
- Folders only created for file types that exist on the SD card
- Notification error handling improved (suppresses common "not allowed" errors)
- Variable-length menu bar icon to show full percentage

### Fixed
- SD card detection for cards without volume names (uses "SD_CARD" as default)
- File exists errors when processing duplicate file names
- Permission issues with sandbox disabled for full volume access
- Menu bar icon truncation issue with percentage display

---

## Version History

### v1.0.0 (Current)
- Initial release with core functionality
