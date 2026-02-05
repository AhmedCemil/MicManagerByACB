[English](README.md) | [Türkçe](README.tr.md)

# MicManagerByACB

A lightweight Windows microphone mute toggle utility with system tray integration.

## Features

- **Global Hotkey**: Toggle microphone mute with a customizable hotkey (default: Menu key)
- **System Tray**: Easy access via system tray icon with visual mute state indication
- **Multiple Microphone Support**: Select and switch between available microphones
- **Monitor Selection**: Choose which monitor displays notifications (multi-monitor support)
- **On-Screen Notifications**: Visual feedback when mute state changes (always visible)
- **External Change Detection**: Detects mute changes made by other applications
- **Localization**: English and Turkish language support (auto-detects system language)
- **Run at Startup**: Option to launch automatically with Windows
- **Passive Mode**: Monitor-only mode without capturing the hotkey
- **Block Hotkey Action**: Optionally block the hotkey's original function

## Installation

1. Download the latest release from the [Releases](https://github.com/AhmedCemil/MicManagerByACB/releases) page
2. Run `MicManagerByACB.exe`
3. The application will appear in your system tray

## Usage

- **Double-click** the tray icon to toggle mute
- **Right-click** the tray icon for the context menu:
  - Mute/Unmute Microphone
  - Select microphone from available devices
  - Select monitor for notifications
  - Change hotkey
  - Toggle notifications
  - Enable/disable hotkey blocking
  - Enable/disable passive mode
  - Run at startup
  - Change language (English/Turkish)

## Building from Source

### Requirements
- MinGW-w64 (g++ compiler)
- Windows SDK

### Build
```batch
build.bat
```

The executable will be created in the `build/` folder.

## Configuration

Settings are stored in `%USERPROFILE%\.micmanager\config.json`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Developed by Ahmed Cemil Bilgin

- GitHub: [AhmedCemil](https://github.com/AhmedCemil)
