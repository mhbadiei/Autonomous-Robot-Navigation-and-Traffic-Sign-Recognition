# Autonomous Robot Navigation and Traffic Sign Recognition 

## Project Overview

This project aims to develop an autonomous robot capable of navigation, obstacle avoidance, and traffic sign recognition. The system uses the Robot Operating System (ROS) along with algorithms such as Histogram Field Vector (VFH) for path planning and YOLO for object detection.

### Scenarios
 
1. **Obstacle Avoidance and Path Planning**:
   - **Objective**: Navigate from `(0,0)` to `(-7,13)` while avoiding obstacles.
   - **Method**: Utilizes the VFH algorithm, with input from `LaserScan` sensors to detect obstacles and determine the robot's path.

2. **Lane and Traffic Sign Detection**:
   - **Objective**: Follow roads and respond to traffic signs.
   - **Method**: Uses the `detection_lane` package for lane following and integrates traffic sign recognition.

3. **Enhanced Traffic Sign Recognition using YOLO**:
   - **Objective**: Improve sign detection accuracy and recognize additional traffic signs, including stop, intersection, and parking signs.
   - **Method**: Employs the YOLO algorithm for real-time object detection.

## Getting Started

### Prerequisites

- **ROS** (Robot Operating System) installed on your system
- **Python** and required packages
- **OpenCV 4.5.1.18**
- **YOLO** and other dependencies

### Videos
Explore our project in action by watching the full version video:


[Watch the Project Video](https://github.com/mhbadiei/Autonomous-Robot-Navigation-and-Traffic-Sign-Recognition/blob/main/Traffic-Sign-Recognition.mp4) 

