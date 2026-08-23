# Troubleshooting

## Monitor Buddy starts but no input changes

Check that:

- DDC/CI is enabled in the monitor menu, if the monitor provides such a setting.
- The monitor is connected directly to the PC where possible.
- The selected monitor profile matches the monitor you want to control.
- Scan Inputs finds the input values exposed by the monitor.
- The configured keyboard shortcuts are unique.

## The monitor is not detected

Try **Refresh** in Settings. Some docks, adapters, KVMs, and unusual connection paths can interfere with DDC/CI communication.

## Setup cannot obtain ControlMyMonitor

Use the manual dependency option in Setup. You can select an existing ControlMyMonitor executable or ZIP. If you do not already have it, use the official NirSoft download page and then select the downloaded package in Monitor Buddy.

## Shortcuts do not respond

Make sure Monitor Buddy is running in the system tray and that the intended monitor profile is active. Only the active profile registers its configured shortcuts.

## Still having trouble?

When reporting a problem, include:

- Windows version
- Monitor model
- Connection type (DisplayPort, HDMI, USB-C, etc.)
- Whether DDC/CI is enabled
- What appears after Refresh and Scan Inputs
- Whether manual input switching from the monitor itself works

Do not post personal configuration files or private information.