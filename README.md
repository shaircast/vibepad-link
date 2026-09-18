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
- Runs quietly in the menu bar on macOS or the system tray on Windows
- Lets one release page serve both desktop platforms

## Downloads

| Platform | Version | Asset | Notes |
| --- | --- | --- | --- |
| macOS | 0.2.1 | `VibepadLink-macOS.dmg` | Notarized DMG with drag-and-drop install; auto-updates in-app from 0.0.6 |
| Windows | 0.2.1 | `VibepadLink-Windows.exe` | Portable executable |

Get both from the [Releases page](https://github.com/shaircast/vibepad-link/releases).

## Install

### macOS

1. Download `VibepadLink-macOS.dmg` from the latest release.
2. Open the DMG and drag `Vibepad Link.app` into `Applications`.
3. Launch the app from `Applications`.
4. If prompted, grant `Accessibility` permission in `System Settings > Privacy & Security > Accessibility`.

### Windows

1. Download `VibepadLink-Windows.exe` from the latest release.
2. Run the executable.
3. If Windows SmartScreen appears, choose `More info` and then `Run anyway`.

## Connect to Vibepad

1. Start `Vibepad Link` on your desktop.
2. Open the Vibepad mobile app on your phone.
3. Connect from the app and start using your pad layout.

## Permissions

- macOS requires `Accessibility` permission to inject keyboard and mouse events.
- Windows does not require administrator privileges for normal use.
