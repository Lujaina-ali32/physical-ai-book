---
id: gazebo
title: Gazebo Simulation
---

# Gazebo Simulation

Gazebo ek **physics simulation tool** hai jo robots ke liye realistic environment banata hai.  

Isme aap simulate kar sakte ho:  

- Gravity  
- Collisions  
- Robot movement  
- Sensors (LiDAR, Cameras, IMU)

---

## URDF/SDF Robot Models

- Robots ke models **URDF** ya **SDF** format mein hote hain  
- Links, joints aur sensors define karte hain  
- Gazebo mein load karke robot ka behaviour test karte hain  

---

## Sensor Simulation

- LiDAR, Camera aur IMU virtual world mein test hote hain  
- Robot physical world ke jaise environment samajhta hai  
- Real robot ke bina hi testing possible  

---

## Gazebo + ROS 2

- ROS 2 nodes Gazebo ke sath communicate karte hain  
- Sensors aur actuators ko ROS topics aur services ke zariye control karte hain  
- Example: Camera node Gazebo se data le aur motor node usse movement control kare  

---

Next chapter: **Unity 3D Visualization**
