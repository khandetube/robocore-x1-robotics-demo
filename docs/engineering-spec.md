# Engineering Concept Specification

## Platform
RoboCore X1 is modeled as a compact autonomous mobile manipulator for supervised industrial inspection, material handling and manipulation scenarios.

## Representative targets
- Footprint: 780 × 610 mm
- Payload concept: 20 kg
- Manipulator reach: 1.15 m
- Perception: LiDAR + RGB-D
- Drive: four-wheel mobile base
- Control: browser simulation / future ROS bridge

## Mechanical concept
The base uses a rigid enclosure, internal battery volume, four wheel modules and visible suspension elements. The upper deck carries perception and manipulation hardware.

## Perception concept
The mast contains a rotating LiDAR representation and a forward RGB-D camera housing. The scan visualization is illustrative.

## Manipulator concept
The arm is represented as an articulated chain with shoulder, elbow, wrist and gripper geometry. This version is visualization-focused and does not implement certified inverse kinematics or safety control.

## Limitations
This is a portfolio prototype, not a validated mechanical design, safety-rated robot or substitute for real-world testing and risk assessment.
