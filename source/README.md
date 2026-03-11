# Source Code (MATLAB App Designer)

This folder contains the main control application developed for the LEGO EV3 robot.

## Key Components:
* **Computer Vision Module:** Uses HSV color filtering to detect the robot (LED), the track boundaries, and the mission bases (Blue, Green, Red).
* **Kinematics Engine:** Implements the Differential Drive Inverse Kinematics model to translate target coordinates into motor RPMs.
* **Control Logic:** Features a "Drive-to-Point" controller with velocity ramps and angular dead-zones to ensure smooth movement.
* **Traffic Sign Recognition:** A rule-based classifier that detects "STOP" and "Directional" signs through real-time image analysis.

### Prerequisites:
* MATLAB (R2021a or newer)
* MATLAB Support Package for LEGO MINDSTORMS EV3 Hardware
* Image Processing Toolbox
