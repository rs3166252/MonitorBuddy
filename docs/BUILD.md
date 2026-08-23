# Technical Build Information

The public repository does not contain Monitor Buddy's implementation source code.

## Release model

Monitor Buddy is developed and tested privately, then packaged into a portable Windows release. The public repository is used for release distribution, documentation, compatibility information, and project history.

## Build environment

The Windows release is compiled from the private development tree using PowerShell and PS2EXE. The packaged application includes the runtime files required by the tested portable release structure.

## Runtime dependency

Monitor Buddy uses ControlMyMonitor for DDC/CI monitor control. Setup can obtain the dependency automatically or accept a user-selected official EXE/ZIP package when automatic setup is unavailable.

## Release verification

A release is considered stable only after testing the extracted release as a new user would:

1. Launch the main EXE.
2. Complete setup.
3. Detect connected monitors.
4. Configure inputs and shortcuts.
5. Verify tray operation.
6. Close and relaunch the application.
7. Verify Settings and profile switching.
8. Verify input switching on the target monitor.

The public release package is kept separate from the private development/build environment.