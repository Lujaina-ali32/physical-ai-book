---
id: ros2
title: ROS 2 Fundamentals
---

# ROS 2 Basics

ROS 2 ek **middleware** hai jo robot ke parts ko connect karta hai aur control provide karta hai.

---

## ROS 2 ke core components:

1. **Nodes**  
   - Robot ke programs ke chhote chhote units  
   - Har node ek specific task perform karta hai (jaise camera read karna ya motor control)

2. **Topics**  
   - Nodes ek doosre se **messages** exchange karte hain  
   - Example: Camera node distance ka data send karta hai aur motor node usse use karta hai

3. **Services**  
   - Request-response communication  
   - Example: “Open gripper” request bhejo, robot gripper khol dega

4. **Actions**  
   - Long-running tasks ke liye  
   - Example: “Walk 5 steps forward” action

---

## Python se ROS 2 control karna

- Python package: `rclpy`  
- Python scripts ke zariye nodes bana kar robot ko control karte hain  
- Example: Camera data read karna ya motor control

---

## URDF (Unified Robot Description Format)

- Robot ka digital 3D model define karta hai  
- Gazebo aur Isaac Sim mein load hota hai  
- Robot ke joints, links aur sensors ka structure describe karta hai

---

Next chapter: **Gazebo Simulation**
