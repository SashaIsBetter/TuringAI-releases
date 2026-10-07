# Turing AI

A private AI for your Mac. Turing 1.0 chats, reasons, searches the web, and writes and runs code for you, entirely on your Mac. Nothing you type is sent anywhere except the web searches it makes for you.

## Download

1. Download **Turing-AI.zip** from the [latest release](https://github.com/SashaIsBetter/TuringAI-releases/releases/latest).
2. Double-click the zip, then drag **Turing AI** into your **Applications** folder.
3. Open it. The first time, macOS says it can't verify the developer (the app isn't notarized by Apple):
   - Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to Turing AI.
   - Or, in Terminal: `xattr -dr com.apple.quarantine "/Applications/Turing AI.app"`
4. Turing downloads its brain once (about 6 GB). After that it works offline.

## Requirements

- A Mac with Apple Silicon (M1 or newer), 16 GB of memory recommended
- macOS 15 or later
- About 8 GB of free disk space

## Updates

Turing updates itself. It checks this page every few hours, downloads new versions in the background, and installs them when you click **Update ready · Restart** in the sidebar, or the next time you quit it. Keep it in your Applications folder so it can update.
