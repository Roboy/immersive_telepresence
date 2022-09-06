# Rollbody's Software Stack

## Animus Server

[[GitHub](https://github.com/Roboy/animus_server/tree/rollbody_ros2)]

The connection to the animus cloud on robot side. Also contains the ROS 2 nodes for height control and the head animation.

## Rollbody VR App (Animus Client in Unity)

[[GitHub](https://github.com/Roboy/RollbodyApp)]

Unity app that runs on the operators's VR headset (tested with Oculus Quest). Connects to the vision, audition, proprioception and motor command streams and processes them.

## Animus Python Debug Client

[[GitHub](https://github.com/Roboy/animus_debug_client)]

Can connect to the vision, proprioception and motor commands streams of Animus server for debugging purposes.

## Rollbody's Head Animation (Unity)

[[GitHub](https://github.com/Roboy/RollbodyUnityFace)]

The animated head/face that runs on an Android tablet. Connects to a ROS 2 node in `animus_server` (has a TCP server) via TCP to set the head angles of the animates head according to the operator's head rotation.

## Java-ROS2 Node to drive the Segway Loomo ("Loomo Controller")

[[GitHub](https://github.com/Roboy/ros2-loomo-controller)]

Implements a ROS 2 node in Java using a ROS2-Android-bridge. Controls the Segway Loomo with the Loomo SDK.

## ROS2-Android Bridge

[[GitHub](https://github.com/Roboy/ros2-android-build)]

## Overview

![SW Architecture](static/images/software_architecture.jpg)

