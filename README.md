# RoboCore X1 — Robotics Digital Twin

Engineering-oriented 3D robotics portfolio prototype: an autonomous mobile manipulator presented as an interactive browser-based digital twin.

## Live demo
https://khandetube.github.io/robocore-x1-robotics-demo/

## Capabilities
- Interactive Three.js/WebGL 3D viewer
- 360° orbit, zoom and pan
- Procedural multi-part robot geometry
- Mobile base, wheels, suspension and battery enclosure
- Articulated manipulator and end-effector concept
- LiDAR mast and RGB-D camera concept
- Simulated live telemetry dashboard
- Responsive engineering-style UI
- GitHub Pages deployment workflow

## Engineering scope
This is a portfolio prototype, not a certified production robot. Dimensions, payload, sensing and compute labels are representative engineering assumptions. Telemetry and sensor behavior are simulated.

## Controls
Left drag = orbit; wheel/pinch = zoom; right drag = pan; Reset = camera reset; Auto orbit = continuous inspection; Wireframe = geometry inspection.

## Technology
Three.js, WebGL, JavaScript, HTML/CSS, GitHub Pages.

## Extension path
A production-oriented evolution could replace the simulation loop with ROS/WebSocket state, real joint states, streamed LiDAR point clouds, navigation status and persistent mission telemetry.
