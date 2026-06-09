This folder contains the core vehicle localization and state estimation components, including an Error-State Extended Kalman Filter (ES-EKF), 
quaternion-based attitude estimation utilities, multi-sensor fusion of IMU, GNSS, and LiDAR data, and evaluation tools for trajectory tracking and pose estimation accuracy. It also has the results of the 
localization workflow in text files.

- **es_ekf.py** implements an Error-State Extended Kalman Filter (ES-EKF) for GNSS/IMU/LiDAR sensor fusion and 3D vehicle state estimation.
- **rotations.py** implements the core 3D rotation mathematics including quaternions, Euler angles, and skew-symmetric transformations.
