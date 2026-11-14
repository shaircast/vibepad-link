<p align="center">
  <img src="assets/icon.png" alt="Vibepad Link icon" width="140" />
</p>

<h1 align="center">Vibepad Link</h1>

<p align="center">
  Desktop helper for <strong>macOS</strong> and <strong>Windows</strong> that receives Bluetooth input from the Vibepad mobile app and sends it to your computer.
</p>

<p align="center">
  <a href="https://github.com/shaircast/vibepad-link/releases">Download Latest Release</a>
  ·
  <a href="https://vibepadapp.com">Vibepad Website</a>
</p>

> This project was renamed from `VibecodePad Link` to `Vibepad Link`. Some source folders, namespaces, and bundle identifiers still use the older name for compatibility.

## What It Does

Vibepad Link is the desktop-side bridge for Vibepad.

- Connects to the Vibepad app over Bluetooth Low Energy
- Receives keyboard, mouse, and text input events
- Holds keys like a physical keyboard while a shortcut button is pressed, with key repeat and several keys at once (Vibepad 0.8.0+)
- On Mac, streams phone audio into the Vibepad Mic input for a desktop dictation app (Vibepad 0.7.0+); Bluetooth microphone is not yet supported on Windows
- Runs quietly in the menu bar on macOS or the system tray on Windows
- Lets one release page serve both desktop platforms

## Downloads

| Platform | Version | Asset | Notes |
| --- | --- | --- | --- |
| macOS | 0.4.0 | `VibepadLink-macOS.dmg` | Notarized DMG with drag-and-drop install; auto-updates in-app from 0.0.6 |
| Windows | 0.5.1 | `VibepadLink-Windows.exe` | Installs itself for your account on first run, no administrator rights; updates in place from 0.5.0 |

Get both from the [Releases page](https://github.com/shaircast/vibepad-link/releases).

## Install

### macOS

1. Download `VibepadLink-macOS.dmg` from the latest release.
2. Open the DMG and drag `Vibepad Link.app` into `Applications`.
3. Launch the app from `Applications`.
4. If prompted, grant `Accessibility` permission in `System Settings > Privacy & Security > Accessibility`.

For Bluetooth microphone use, install **Vibepad Mic** from Finish Setup or Settings → Microphone (administrator approval required), then select **Vibepad Mic** as the input in your Mac dictation app. In Vibepad 0.7.0+, add a Microphone button or use the Mac Claude Code / Cursor preset. Tap to toggle or hold to talk; keep the phone app open while speaking.

### Windows

1. Download `VibepadLink-Windows.exe` from the latest release.
2. Open it. If Windows SmartScreen appears, choose `More info` and then `Run anyway`.
3. Vibepad Link installs itself for your account, adds a Start menu entry and opens. The downloaded file can be deleted.

Updating from 0.4.0 or earlier works the same way: open the new download and it replaces the running helper, keeping your remembered phone and settings.

To remove it, uninstall **Vibepad Link** from `Settings > Apps > Installed apps`.

## Connect to Vibepad

1. Start `Vibepad Link` on your desktop.
2. Open the Vibepad mobile app on your phone.
3. Connect from the app and start using your pad layout.

## Permissions

- macOS requires `Accessibility` permission to inject keyboard and mouse events.
- Windows does not require administrator privileges. The first time a phone connects, Windows asks to pair it; confirm the same code on the phone and the PC.
