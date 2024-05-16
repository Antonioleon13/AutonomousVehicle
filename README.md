# Autonomous vehicle navigation

Welcome to our Autonomous Vehicle project, a remarkable demonstration of modern robotics and computer vision technologies. In this repository, we present an autonomous vehicle capable of navigating a track and effectively detecting traffic signs and traffic lights in real-time. This project leverages the power of the Robot Operating System (ROS) framework, OpenCV, convolutional neural networks, and the YOLOv5 model, all elegantly implemented in Python.

## Key Features

* Track Navigation: Our autonomous vehicle is equipped with sophisticated algorithms to autonomously follow a designated path, showcasing its agility and precision in real-world scenarios.

* Traffic Sign and Light Detection: It can recognize and respond to traffic signs and lights, a crucial aspect of safe and efficient autonomous driving. This capability is achieved through advanced computer vision techniques and deep learning models.

## Technologies used

* ROS Framework: The project is built on the solid foundation of the Robot Operating System (ROS), providing a robust and flexible environment for controlling the autonomous vehicle.
* OpenCV: OpenCV is employed for image processing and computer vision tasks, ensuring accurate and real-time detection of objects and signs.
* YOLOv5: We utilize the YOLOv5 model, a state-of-the-art deep learning framework, for object detection, making our system highly efficient and capable.
* Python: The entire project is coded in Python, making it accessible and adaptable for a wide range of developers and researchers.


## Packages
This ROS workspace includes the following packages:
1. **puzzlebot_autostart**: Manages the startup sequence for the puzzlebot.
2. **vehicle_control**: Handles control algorithms for the puzzlebot, including line following and response to traffic signs.
3. **yolo_rec**: Contains the YOLOv5 package for traffic sign detection.

## Getting Started
1. Clone this repository into your ROS workspace's `src` directory.
2. Navigate to your ROS workspace and build the packages:
   ```bash
   cd path/to/your/ros/workspace
   catkin_make
   ```
3. Source the setup script:
```bash
source devel/setup.bash
```
4. Launch the puzzlebot startup sequence:
```bash
roslaunch puzzlebot_autostart puzzlebot_autostart.launch
```
5. Launch the vehicle control:
``` bash
roslaunch vehicle_control vehicle_control.launch
```

## Demo
[![Demo del Proyecto](http://img.youtube.com/vi/bmP49zlKMyg/0.jpg)](https://www.youtube.com/watch?v=bmP49zlKMyg)

