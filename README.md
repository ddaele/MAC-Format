# MAC Format

A utility to format MAC addresses from clipboard to the standard colon-separated format.

## Description

MAC Format is a simple yet useful tool that converts raw MAC addresses (e.g., `001A2B3C4D5E`) to the standard colon-separated format (e.g., `00:1A:2B:3C:4D:5E`). It reads from your clipboard and automatically formats the address.

## Features

- ✅ Converts raw MAC addresses to colon-separated format
- ✅ Clipboard integration - reads from and writes to clipboard
- ✅ Fast and lightweight
- ✅ Simple one-click operation
- ✅ Supports various MAC address formats

## Usage

1. Copy a MAC address to your clipboard (raw format without colons)
2. Run the MAC Format utility
3. The formatted MAC address is copied back to your clipboard
4. Paste the formatted address wherever needed

## Supported Input Formats

- `001A2B3C4D5E` → `00:1A:2B:3C:4D:5E`
- `00-1A-2B-3C-4D-5E` → `00:1A:2B:3C:4D:5E`
- `001a2b3c4d5e` → `00:1A:2B:3C:4D:5E` (case-insensitive)

## Requirements

- Windows system (if AutoHotkey script)
- AutoHotkey v1.1 or later (depending on implementation)

## Installation

1. Clone or download this repository
2. Run the executable or script
3. Use the clipboard integration to format MAC addresses

## Examples

```
Input:  001A2B3C4D5E
Output: 00:1A:2B:3C:4D:5E

Input:  00-1A-2B-3C-4D-5E
Output: 00:1A:2B:3C:4D:5E

Input:  001a2b3c4d5e
Output: 00:1A:2B:3C:4D:5E
```

## How It Works

The utility:
1. Reads the clipboard content
2. Removes any existing separators (hyphens, spaces, etc.)
3. Validates the MAC address format
4. Converts it to the standard colon-separated format
5. Copies the result back to the clipboard

## Common MAC Address Formats

| Format | Example |
|--------|----------|
| Colon-separated | `00:1A:2B:3C:4D:5E` |
| Hyphen-separated | `00-1A-2B-3C-4D-5E` |
| Dot-separated | `001a.2b3c.4d5e` |
| Raw (no separator) | `001A2B3C4D5E` |

## License

This project is provided as-is for educational and utility purposes.

## Related Projects

- See `AHK_Localizer_README.md` for the AutoHotkey Localizer utility documentation

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## Support

For issues or questions, please open an issue on GitHub.

---

## ⚠️ AI Disclaimer

This README was generated with the assistance of AI. While the documentation has been reviewed and formatted, please verify that all information is accurate and complete for your specific use case. If you notice any inaccuracies or have suggestions for improvement, please feel free to open an issue or submit a pull request.
