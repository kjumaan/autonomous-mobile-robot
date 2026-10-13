# Autonomous Mobile Robot with Gesture Recognition, Line Following and Obstacle Avoidance

**Final-Year Mechatronics Engineering Project | Manipal Institute of Technology | May 2026**

## Project Overview

This project focused on developing a low-cost Autonomous Mobile Robot (AMR) using a Freenove 4WD platform and Raspberry Pi 4B. The system integrates vision-based hand gesture recognition, line following, and obstacle avoidance, with development and evaluation across ROS 2 and Gazebo simulation and a physical robot.

The project also investigated the difference between simulated and physical robot performance using Python-based data analysis and Power BI visualizations.

## Objectives

- Develop an AMR model in ROS 2 and Gazebo.
- Implement line following with P, PD and PID controllers.
- Integrate gesture recognition using MediaPipe and OpenCV.
- Implement reactive obstacle avoidance.
- Compare simulated and physical robot performance.
- Analyze performance metrics using Python, Pandas and Power BI.

## Technology Stack

- **Robotics:** ROS 2 Jazzy, Gazebo Harmonic
- **Programming:** Python
- **Computer Vision:** OpenCV, MediaPipe
- **Hardware:** Raspberry Pi 4B, Freenove 4WD platform, USB camera, HC-SR04 ultrasonic sensor
- **Control Systems:** P, PD and PID controllers
- **Data Analysis:** Pandas, Power BI
- **Simulation Model:** SDF, ros_gz_bridge

## System Capabilities

### 1. Gesture Recognition
Recognizes five predefined hand gestures and maps them to robot commands using MediaPipe hand landmarks.

### 2. Line Following
Uses visual line detection and feedback control to correct the robot's direction and follow a defined path.

### 3. Obstacle Avoidance
Uses simulated LiDAR in the simulation environment and ultrasonic sensing on the physical platform for obstacle detection and reactive avoidance.

### 4. Simulation-to-Real Evaluation
Compares reported controller performance, gesture recognition performance and navigation behaviour between simulation and physical deployment.

### 5. Performance Analytics
Uses Python/Pandas for performance data analysis and Power BI for dashboard-based visualization.

## Reported Results

The following results are reported in the project report:

- **97%** line-tracking accuracy in simulation under PID control.
- **94%** line-tracking accuracy on the physical robot under PID control.
- **91%** physical line-tracking accuracy under PD control, with a reported CPU load of 14%.
- **88–95%** gesture recognition success across five gesture classes.
- Gesture command latency below **90 ms**.
- Reported simulation-to-real performance degradation of **2–5%** across the evaluated behaviours.

These figures are reported project results and should be interpreted in the context of the experimental setup described in the report.

## Key Learning Areas

- Integrating perception, control and actuation in a robotics system.
- Working with ROS 2 and Gazebo simulation.
- Understanding feedback control and controller benchmarking.
- Comparing simulated behaviour with physical hardware.
- Analyzing performance metrics and communicating results through dashboards.

## Project Documentation

- [Final Project Report](report/major-project-report.pdf)
- [Final Presentation](presentation/major-project-presentation.pdf)

*The documentation links will work after the corresponding PDF files are added to the repository.*

## Repository Status

This repository currently presents the project documentation and reported outcomes. The original source code and complete experimental datasets are not currently included. Consequently, this repository is intended as a project showcase rather than a fully reproducible implementation.

## Author

**K Jumaan**  
B.Tech. Mechatronics Engineering  
Minor Specialization in Robotics and Automation  
Manipal Institute of Technology, Manipal
