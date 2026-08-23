# Compatibility

Monitor Buddy is designed for Windows systems with externally connected monitors that expose the required DDC/CI controls.

## What must be supported

The monitor and connection path need to expose DDC/CI communication and an input-source control through the monitor's DDC/CI interface.

Monitor Buddy discovers monitor information and can scan the values reported for input source control rather than assuming every monitor uses the same numeric values.

## Why compatibility varies

A monitor may support DDC/CI but still behave differently depending on:

- Monitor firmware
- DisplayPort, HDMI, USB-C, dock, adapter, or KVM path
- GPU and display driver behavior
- Monitor vendor implementation of DDC/CI
- Whether input-source control is exposed through the connection

For that reason, Monitor Buddy does not claim universal compatibility with every monitor.

## Recommended test

Before relying on Monitor Buddy for a permanent setup, verify that:

1. The monitor appears during detection.
2. DDC/CI communication is available.
3. Scan Inputs finds the expected input values, when supported.
4. Each configured shortcut changes the monitor input correctly.

If the monitor does not expose input switching through DDC/CI, Monitor Buddy cannot add that capability to the monitor.