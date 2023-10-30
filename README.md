# Autonomous vehicle navigation

Welcome to our Autonomous Vehicle project, a remarkable demonstration of modern robotics and computer vision technologies. In this repository, we present an autonomous vehicle capable of navigating a track and effectively detecting traffic signs and traffic lights in real-time. This project leverages the power of the Robot Operating System (ROS) framework, OpenCV, convolutional neural networks, and the YOLOv5 model, all elegantly implemented in Python.

<!-- ## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This project was devolped using ROS melodic on Ubuntu 18.04

Link to ROS melodic instalation: http://wiki.ros.org/melodic/Installation/Ubuntu
```
Give examples
```

### Installing

Install OpenCV

```
sudo apt-get install libopencv-dev
```

Install python dependencies
```
pip install numpy matplotlib
```
Install Yolov5 dependencies
```
git clone https://github.com/ultralytics/yolov5.git
cd yolov5
pip install -U -r requirements.txt
```

## Running the tests


### Initialize ROS workspace

```
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
catkin_init_workspace
cd ~/catkin_ws
catkin_make
source devel/setup.bash
```

### Clone and build repository


```
cd ~/catkin_ws/src
git clone https://github.com/your-username/your-autonomous-vehicle-project.git
cd ~/catkin_ws
source devel/setup.bash
catkin_make
```

### Launch ROS nodes

```
roslaunch puzzlebot_autostart puzzlebot_autostart.launch

roslaunch vehicle_control vehicle_control.launch
``` -->

## Key Features

* Track Navigation: Our autonomous vehicle is equipped with sophisticated algorithms to autonomously follow a designated path, showcasing its agility and precision in real-world scenarios.

* Traffic Sign and Light Detection: It can recognize and respond to traffic signs and lights, a crucial aspect of safe and efficient autonomous driving. This capability is achieved through advanced computer vision techniques and deep learning models.

## Technologies used

* ROS Framework: The project is built on the solid foundation of the Robot Operating System (ROS), providing a robust and flexible environment for controlling the autonomous vehicle.
* OpenCV: OpenCV is employed for image processing and computer vision tasks, ensuring accurate and real-time detection of objects and signs.
* YOLOv5: We utilize the YOLOv5 model, a state-of-the-art deep learning framework, for object detection, making our system highly efficient and capable.
* Python: The entire project is coded in Python, making it accessible and adaptable for a wide range of developers and researchers.

