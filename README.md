# BotBrains_Battle_Round-2
Overview

This project implements the software for an autonomous parcel delivery robot using Robot Operating System (ROS) and Python. The robot navigates in a simulated environment, performs path planning, obstacle avoidance, and communicates its progress.

Features
- Localization: Uses odometry and laser scan data for localization and mapping.
- Path Planning: Implements A* algorithm for optimal path planning from start to goal.
- Motion Control: Utilizes PID control for smooth velocity control.
- Obstacle Avoidance: Implements potential fields approach for dynamic obstacle avoidance.
- Communication: Publishes robot status and receives navigation goals via ROS topics.
  
Requirements
Ubuntu 18.04 (recommended) or higher
ROS Melodic (or later) installed and configured
Python 2.7 or 3.x with rospy and necessary dependencies

Usage
1) Launch Simulation:
Launch the simulated environment (e.g., Gazebo).
2) Start Node:
Run the main node to start the robot's autonomy.
3) Interact:
Send navigation goals to the robot via ROS topics (/goal_position).
4) Monitor:
Monitor robot status and visualize sensor data using ROS tools (RViz).

Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

Acknowledgments
Inspiration and guidance from robotics textbooks and research papers.
Support from the ROS community and open-source contributors.
