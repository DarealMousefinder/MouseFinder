# MouseFinder

A small Windows tool that centers your mouse cursor on the current monitor when you press **Ctrl+Shift**, with undo/redo via F8.

## Hotkeys
- **Ctrl + Shift** — center mouse on current monitor (saves previous position)
- **F8** — undo last move
- **Shift + F8** — redo
- **Ctrl + Shift + 7** — quit
- **Esc** — emergency quit

## Download
Get the latest `MouseFinder.exe` from the [Releases](../../releases) page.

# 🔒 Security & SmartScreen Notice: 

Because MouseFinder is a free, open-source project built independently without a costly corporate digital certificate, Windows Defender SmartScreen might display a warning when you first run the .exe file. This is completely normal for independent software. The code is fully open-source and visible in this repository for transparency. 

To run the app: Click More info on the Windows warning pop-up. Click Run anyway.

🛠️ Technical Details: This utility is written in Python and uses low-level system hooks to monitor keystrokes globally without lagging your OS.Global Hotkey Listening: Monitored via background event listeners.Coordinate Mapping: Dynamically detects active monitor boundaries to pinpoint the exact screen center. 

State Memory: Caches previous coordinates to allow seamless undo/redo states (F8 / Shift + F8).

