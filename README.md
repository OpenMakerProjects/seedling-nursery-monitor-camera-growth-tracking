# Seedling Nursery Monitor Camera Growth Tracking

Build a smart agriculture prototype that uses capacitive soil sensor, water pump, pH sensor to capture repeatable crop-growth images. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 120 |
| Category | Smart Agriculture |
| Platform | Arduino Mega |
| Difficulty | Beginner |
| Estimated build time | 16 hours |
| Connectivity | Local only |
| Core components | capacitive soil sensor, water pump, pH sensor |
| Control mode | edge classification |

## Repository layout

- `firmware/seedling-nursery-monitor-camera-growth-tracking/seedling-nursery-monitor-camera-growth-tracking.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/seedling-nursery-monitor-camera-growth-tracking/seedling-nursery-monitor-camera-growth-tracking.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **Arduino Mega**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Camera Growth Tracking demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
