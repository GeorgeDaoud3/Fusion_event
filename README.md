# Fusion_event


## 🔍 Problem

Autonomous vehicles rely on sensors like LiDAR and cameras to perceive their environment. Each sensor has strengths and limitations:

🔹 LiDAR provides accurate 3D data but lacks color information.

🔹 Cameras capture rich visuals but are sensitive to lighting conditions.


Individually, these sensors can be noisy or miss key details due to occlusions from other road agents. However, by fusing data from multiple sensors and vehicles, we can create a more reliable, comprehensive view of the scene, improving safety and awareness.

## 🚦 Scenario

Two self-driving cars are approaching an intersection, each equipped with:


✅ 3D LiDAR

✅ Camera

The environment includes vehicles, pedestrians, and cyclists, some of whom may block each vehicle’s view. By communicating and sharing sensor data, the vehicles can collaborate to overcome occlusions and enhance situational understanding.

![scene](/images/scene.png)

## 🎯 Goal

Process the raw camera and LiDAR data from both vehicles to:


🔹 Generate individual object detection outputs for each car.

🔹 Fuse the data to build a shared perception of the scene.

🔹 Enhance visibility by addressing sensor occlusions and inconsistencies.

🔹 Output a visual representation showing detected agents from both perspectives.
