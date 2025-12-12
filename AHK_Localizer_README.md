# AHK Localizer

Utility script to find the correct location of buttons in Clarify application.

## Features
- Captures mouse coordinates in real-time
- Logs coordinates to a text file for reference
- Only active when Clarify.exe window is focused

## Usage
1. Run the script
2. Open Clarify application
3. Press Ctrl to capture mouse position
4. Coordinates are logged to `location.txt`

## Requirements
- AutoHotkey v1.1 or later
- Clarify application installed

## Output
Coordinates are saved to `location.txt` in the script directory in the following format:
```
De x-coordinaat is: XXX De y coördinaat is: YYY
```

## How It Works
The script monitors for the active window to be Clarify.exe. When you press the Ctrl key, it captures the current mouse position and appends it to a text file. This is useful for documenting button locations for UI automation or testing purposes.

## Notes
- The location.txt file is created/appended to in the same directory as the script
- Press Ctrl multiple times to capture multiple coordinates
- All coordinates are logged with timestamps in the format shown above
