# System Architecture

Browser UI
→ Telemetry state
→ Three.js scene graph
→ Robot subsystem geometry
→ Simulation loop

## Subsystems
1. Mobility — four-wheel base, hubs and suspension.
2. Energy — enclosed battery volume and simulated state-of-charge.
3. Manipulation — shoulder, elbow, wrist and gripper geometry.
4. Perception — LiDAR mast and RGB-D camera.
5. Telemetry — animated operating-state visualization.

## Digital-twin boundary
No physical actuator, safety PLC, ROS node or sensor is connected. The current telemetry layer is simulation-only.

## Extension path
Replace the state generator with a ROS/WebSocket bridge, add real joint-state topics, stream LiDAR data, connect navigation state and persist telemetry.
