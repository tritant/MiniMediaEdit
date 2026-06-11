# MiniMediaEdit
<div align="center">

[![Website](https://img.shields.io/badge/Website-minimediaedit.eu-5b8cff?style=for-the-badge)](https://minimediaedit.eu)
[![Donate](https://img.shields.io/badge/Donate-Get_a_license_key-ffae5b?style=for-the-badge)](https://minimediaedit.eu/donate.php)

</div>

**Lightweight, free video editor for Windows — fast cutting, multitrack timeline, transitions and export.**

MiniMediaEdit is a small, no-nonsense video editor for quick edits: assemble clips, trim, mix an audio track, add transitions, export. It's not trying to replace DaVinci Resolve or Premiere — it does simple edits fast, without a multi-gigabyte install.

## Features

- Media bin for videos, images and audio with thumbnails
- Trim player with in/out marks
- Multitrack video timeline + a dedicated audio track
- Video transitions: fades, slides, wipes, curtains, circles, pixelize, zoom and more
- Per-point audio volume automation
- Undo / redo
- Portable projects (a self-contained folder)
- Optional auto-save with crash recovery
- Export to H.264 / H.265 / VP9, with hardware acceleration (NVIDIA / Intel / AMD) when available
- Bilingual interface: English / French
<img width="1741" height="1190" alt="Capture d&#39;écran 2026-06-07 124223" src="https://github.com/user-attachments/assets/6d6b1ddf-9256-4a01-ac67-bfcac8ce571d" />


## Requirements

- Windows 10 or later
- **[FFmpeg](https://ffmpeg.org/download.html) is required** and must be installed separately, accessible in your system `PATH`. MiniMediaEdit will not start without it (it shows a dialog with the install link).

## Download

Get the latest portable bundle from the **[Releases page](https://github.com/tritant/MiniMediaEdit/releases/latest)**.

No installation required — unzip and run.

## Donateware

MiniMediaEdit is **free and fully functional, with no limitations.** A gentle reminder appears at startup inviting a donation.

If you donate, you receive a license key that registers the software in your name (shown in the title bar) and removes the startup reminder.

## Reporting bugs

Open an [issue](https://github.com/tritant/MiniMediaEdit/issues) and attach your log file, found at:

```
%APPDATA%\MiniMediaEdit\minimediaedit.log
```

(The menu **Help → View log file…** opens it directly.)

## Credits

Built with [Python](https://www.python.org), [wxPython](https://www.wxpython.org), [PyAV](https://github.com/PyAV-Org/PyAV), [Pillow](https://python-pillow.org/), [NumPy](https://numpy.org), and [sounddevice](https://python-sounddevice.readthedocs.io). Video encoding relies on [FFmpeg](https://ffmpeg.org), installed separately.

## License

Donateware — see [LICENSE.txt](LICENSE.txt). Free to use and share unmodified; the source is not publicly distributed.
