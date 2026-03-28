# RecStudio

A fast, lightweight screen recording and screenshot tool built for minimal resource usage.

## Features

- **Area Screenshot** — Select any region of your screen and capture it instantly. Saved to `~/Pictures/Screenshots` and copied to clipboard.
- **Screen Recording** — Record your full screen as `.mp4` at a configurable FPS. Saved to `~/Videos/Recordings`.
- **Minimal Footprint** — Runs quietly in the background with a tiny floating toolbar. No bloated UI, no unnecessary processes.
- **Global Hotkey** — Toggle the toolbar visibility with `Ctrl+K`.

## Usage

```
python client.py
```

A small toolbar appears at the bottom-right of your screen:

| Button | Action |
|--------|--------|
| 🔴 Red dot | Click to start recording. Click again to stop and save. |
| 📷 Camera | Click to select a screen area for a screenshot. |

- **Right-click drag** the toolbar to reposition it.
- **Ctrl+K** to show/hide the toolbar.

## Requirements

Dependencies are installed automatically on first run:

- `Pillow`
- `opencv-python`
- `numpy`

## Save Locations

| Type | Path |
|------|------|
| Screenshots | `~/Pictures/Screenshots/capture_YYYYMMDD_HHMMSS.png` |
| Recordings | `~/Videos/Recordings/recording_YYYYMMDD_HHMMSS.mp4` |

## License

MIT
