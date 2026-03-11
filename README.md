# 🤖 Autonomous Robot Navigation & Computer Vision
**Mobile Robotics | MATLAB App Designer | Image Processing | EV3**

## 📖 Overview
This project features an autonomous mobile robot (LEGO EV3) capable of navigating a complex environment. The system uses a global vision approach (overhead camera) to map the arena, identify prohibited zones, and calculate optimal paths to target bases.



## 🎯 Project Goals
The main objective was to develop a robust control system for an EV3 robot to autonomously visit a sequence of targets while:
1. **Avoiding** forbidden zones (Obstacles).
2. **Obeying** traffic signs (STOP, Left, Right).
3. **Correcting** odometry errors using a global vision system.



## ⚙️ Hardware & Software
* **Robot:** LEGO Mindstorms EV3 (Differential Drive).
* **Sensors:** Overhead Camera (Global Vision).
* **Control:** MATLAB App Designer & Hardware Support Package for EV3.
* **Communication:** USB/Bluetooth/Wifi.


## 🛠️ Technical Features
* **Computer Vision:** * Real-time mapping using HSV color space segmentation.
    * Traffic sign recognition (STOP, Turn Left, Turn Right) using rule-based classification.
    * Visual relocation strategy to correct odometry drift.
* **Control & Kinematics:** * Implementation of **Inverse Kinematics** for differential drive.
    * **Drive-to-Point** controller with velocity ramps and angular dead-zones for stability.
* **Path Planning:** * Occupancy grid mapping (Binary maps).
    * Cost-field-based trajectory planning to avoid forbidden zones.
* **Interface:** Custom-built GUI using **MATLAB App Designer** for real-time monitoring and teleoperation.



## 🚀 How it Works
1. **Mapping:** The system captures an overhead image and converts pixels to real-world coordinates.
2. **Path Generation:** The user defines the target sequence; the algorithm generates a valid path avoiding obstacles.
3. **Execution:** The robot follows the trajectory while the vision system recognizes traffic signs to adjust behavior (e.g., stopping at a STOP sign).

## 📺 Video Demonstration
[Watch the Autonomous Navigation in Action](https://www.youtube.com/watch?v=b_EHnqg5K34)

## 👥 Author
* Tiago Oliveira
