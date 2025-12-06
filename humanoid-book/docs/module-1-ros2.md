# Module 1: The Robotic Nervous System (ROS 2)

ROS 2 (Robot Operating System 2) is the communication system of a robot. It allows different parts of the robot to talk to each other just like the human nervous system.

## What is a Node?
A node is a small program that performs a single task in a robot.  
Example: One node for camera, one for motors.

## What are Topics?
Topics are communication channels used to send data between nodes.  
Example: Camera image is sent on a topic.

## What are Services?
Services are used when one node requests some data from another node.

## What are Actions?
Actions are used for long tasks such as moving a robot arm.

## Python Control using rclpy
rclpy is the Python library used with ROS 2 to control robots using Python code.

## URDF (Unified Robot Description Format)
URDF is used to describe the physical structure of a robot including joints, links, and sensors.

## Why ROS 2 is Important
- Real-time robot communication  
- Modular design  
- Works with real robots and simulations  
- Industry standard for robotics  
