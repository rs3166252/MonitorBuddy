# Installation & First Setup

Monitor Buddy is distributed as a portable Windows application.

## Quick start

1. Download the latest release ZIP.
2. Extract the ZIP to a normal folder.
3. Double-click `MonitorBuddy.exe`.
4. Complete the one-time setup.
5. Allow Monitor Buddy to detect connected monitors.
6. Select a monitor profile and scan its available inputs when needed.
7. Choose the keyboard shortcut for each input.
8. Save and restart when prompted.

After setup, Monitor Buddy runs from the Windows system tray.

## ControlMyMonitor dependency

Monitor Buddy uses ControlMyMonitor for DDC/CI monitor control. Setup attempts to obtain the required dependency automatically.

If automatic setup cannot obtain it, the setup flow provides a manual path:

- Select an existing `ControlMyMonitor.exe` or ZIP if you already downloaded it.
- If you do not have it, open the official NirSoft page, download the appropriate package, and return to Monitor Buddy to select the file.

The dependency is used locally for monitor control.

## Starting Monitor Buddy later

Use the desktop shortcut created during setup, or launch `MonitorBuddy.exe` from the extracted release folder.

Monitor Buddy does not require a traditional Windows installation wizard.