# 5 DOF Robot Arm - Onshape Design

This project is a 3D model of a robotic arm with 5 Degrees of Freedom (DOF), designed using Onshape. It is intended for educational, prototyping, or simulation purposes.

##The project link
(https://cad.onshape.com/documents/ea1968bf1f93a7b7128dfc4e/w/ed606135b0eac99c5626c661/e/9ea1401845a2349fb8ab942e)

## Overview

The robotic arm consists of 5 independent joints, allowing motion in five axes. The structure includes a fixed base and multiple links connected via rotational joints (revolute mates in Onshape).

### Degrees of Freedom:

1. **Base Rotation (Yaw)** – Allows rotation of the entire arm around the vertical axis.
2. **Shoulder Joint (Pitch)** – Lifts the first arm segment up and down.
3. **Elbow Joint (Pitch)** – Moves the second arm segment forward and backward.
4. **Wrist Joint 1 (Pitch)** – Controls up/down movement of the wrist.
5. **Wrist Joint 2 (Roll)** – Enables wrist rotation for tool or gripper alignment.

## Structure

The robotic arm is composed of:

- **Base**: Circular fixed part mounted on the ground or a platform.
- **Link 1 (Shoulder Arm)**: The first main moving arm.
- **Link 2 (Elbow Arm)**: The second moving arm.
- **Wrist Joints (1 & 2)**: Small rotating parts for wrist articulation.
- **Gripper (optional)**: Not included in this version, but can be added easily.

## Onshape Setup

1. Open the [shared Onshape document](https://cad.onshape.com/documents/e4f74b5f6df5bb65a1d8d61a/w/20dbfa7fef9c6c9fa2b1d5c7/e/b220b44d8f504ec5e259fa95).
2. Duplicate it to your workspace to make modifications.
3. Use the `Assembly` tab to simulate movement via `Revolute Mates`.
4. Each part is fully parametric and can be resized or customized.

## Use Cases

- Simulation and testing in robotics projects.
- Mechanical engineering and design practice.
- Educational demonstrations for DOF and kinematics.
- Basis for adding servo motors and microcontroller-based control (Arduino, Raspberry Pi, etc).

## Export

You can export parts as STL files for 3D printing or import them into simulation tools like Gazebo or ROS.

## Notes

- Designed with millimeter units.
- Compatible with standard modeling and simulation pipelines.
- No electronics are included in the model; mechanical only.

## License

Free to use and modify for non-commercial or educational purposes.

