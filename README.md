# imu-orientation-monitor

A real-time, browser-based IMU visualization and motion monitoring system for embedded device development, sensor testing, and smart interaction prototyping.


---

##  Live Demo
(https://miklayback.github.io/imu-orientation-monitor/)

---


##  Functional Modules & Their Purpose

| Module | Description | Real-World Usage |
|--------|-------------|------------------|
|  **3D Orientation Visualization** | Real-time device pose rendered with `Three.js` using Alpha (Yaw), Beta (Pitch), Gamma (Roll) | Sensor calibration, intuitive orientation feedback |
|  **Angle Smoothing** | Moving average applied to raw IMU data for stable readings | Algorithm preprocessing (e.g. low-pass filtering) |
|  **Live Angle History Chart** | Plots IMU angles over time with `Chart.js` | Motion trend analysis, event segmentation |
|  **Shake Detection** | Detects abrupt angular velocity spikes, with cooldown logic | Motion pattern detection, gesture input trigger |
|  **Flip Counting** | Detects full inversion cycles (normal → upside-down → normal) | Behavior recognition, physical device status change |
|  **Posture Classification** | Categorizes device into flat / tilted / dynamic states | User state detection, real-time feedback |
|  **CSV Data Export** | Allows exporting angle data for external analysis | Offline review, ML training dataset generation |


This project simulates core tasks in **IMU algorithm development** and **perceptual interaction systems**, including:

- Orientation state estimation
- Motion anomaly detection
- Sensor-based event classification
- Interactive UI feedback loop

It can be adapted for:

-  Embedded system debugging tools
-  Fitness / rehab motion monitoring
-  Gesture-based UI prototyping
-  Dead reckoning simulation

##  Tech Stack

| Component     | Tech Used          |
|---------------|--------------------|
| Visualization | `Three.js`         |
| Charting      | `Chart.js`         |
| Sensor Input  | `DeviceOrientation` API |
| Deployment    | `GitHub Pages + Actions` |

---


