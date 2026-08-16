# AutonomousRobotics

A personal robotics learning repository focused on **ROS 2, simulation, control, perception, and AI for autonomous robotics**.

## Current Work

* ROS 2 workspace development
* ArduinoBot simulation and control
* Robot description and URDF
* Launch files and ROS 2 packages

## Setup

```bash
git clone https://github.com/Utkarsh1601/AutonomousRobotics.git
cd AutonomousRobotics

rosdep install --from-paths src --ignore-src -r -y
colcon build
source install/setup.bash
```

Generated directories such as `build/`, `install/`, `log/`, and `.vscode/` are excluded from version control.

## Status

🚧 **Work in progress** — continuously adding robotics, perception, navigation, and AI capabilities.
