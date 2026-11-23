# NovaChat — Local PC Package

## Quick Start (Fastest)
1. Extract this ZIP folder anywhere on your PC.
2. Double-click **`index.html`** (or **`start-windows.bat`** on Windows) to open NovaChat in your default web browser.

## Optional: Run with a Local Server (Recommended for Voice Input)
Some browsers restrict microphone access on `file://` URLs. To enable voice input on your PC:
- **Python:** Open a terminal in this folder and run:
  ```bash
  python -m http.server 8000
  ```
  Then open `http://localhost:8000` in your browser.
- **Node.js:** Run:
  ```bash
  npx serve .
  ```

## Notes
- Requires an internet connection to load Google Fonts, Tailwind CSS, Lucide icons, and live Wikipedia/Dictionary lookups.
- Math, unit conversions, coding helpers, bookmarks, and saved chats work directly in your browser.
