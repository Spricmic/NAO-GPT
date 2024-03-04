# NAO-GPT

Welcome to the NAO-GPT repository, where we enhance the capabilities of the NAO V6 robot, developed by Aldebaran, using a Raspberry Pi 4 as its brain. This setup leverages ROS2 for advanced robot control and automation.

## Setup Instructions

To get started, you'll need to prepare your Raspberry Pi 4 by installing an operating system and setting up the necessary software. Here's how to do it:

### 1. Installing Ubuntu 22.04 on Raspberry Pi

We recommend using Ubuntu 22.04 Jammy Jellyfish for this project, as it ensures compatibility with ROS2 Humble. Follow the steps in this detailed guide to install Ubuntu on your Raspberry Pi without needing a monitor: [Install Ubuntu on Raspberry Pi (Without Monitor)](https://roboticsbackend.com/install-ubuntu-on-raspberry-pi-without-monitor/). Make sure to select the Desktop version of Ubuntu during the installation process, as opposed to the Server version, to match our project requirements and also allow new users access to the Ubuntu platform.

### 2. Installing ROS2 Humble

Once Ubuntu is up and running, the next step is to install ROS2 Humble. This version of ROS2 is chosen for its compatibility and features suitable for our robotics project. Follow this guide to install ROS2 on your Raspberry Pi: [Install ROS2 on Raspberry Pi](https://roboticsbackend.com/install-ros2-on-raspberry-pi/). The tutorial provides step-by-step instructions to ensure a smooth setup process.

### 3. Installing NAOqi Drivers for ROS2

To integrate the NAO V6 robot with ROS2 using the Raspberry Pi, you need to install the NAOqi drivers specifically designed for ROS2. These drivers facilitate communication between the NAO robot and ROS2, enabling advanced control and programming capabilities. Install the drivers from the following GitHub repository: [NAOqi Driver2 for ROS2](https://github.com/ros-naoqi/naoqi_driver2).


