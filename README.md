# Robotic Arm - URDF Modeling (ROS)

This repository contains the initial setup and **URDF model** of a robotic arm developed using **ROS (Robot Operating System)**. It focuses on building and visualizing the robot in **RViz** and **Gazebo**, laying the foundation for further development like control, perception, and simulation.

---

## Current Progress

✅ URDF modeling  

---

## Tools & Technologies

- ROS2 Humble (mention your version)
- URDF (Universal Robot Description Format)
- RViz for 3D visualization
- Gazebo (optional for simulation)
- Xacro for modular URDF 

---

## Robot Description

The robotic arm includes:

- Base link
- Rotational joints (shoulder, elbow, wrist)
- End effector (placeholder or gripper-ready)
- Joint limits and inertial properties

---

## For Running
```bash
# Clone the repo
git clone https://github.com/codeXpawan/Robotic_Arm.git
cd Robotic_Arm/ROS
colcon build
source install/setup.bash

# Launch RViz with the URDF model
ros2 launch robot_description robot_description.launch.py
```
