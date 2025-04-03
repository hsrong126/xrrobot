#rikirobot

rikirobot is an robotic project that aims to provide students, developers, and researchers a low-cost platform in creating new exciting applications on top of ROS.

# How to install
1. Create a workspace (if not exist)
```
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws
$ catkin_make
```

2. Add dependies
```
$ sudo apt-get install ros-noetic-rosserial-python

$ cd ~/catkin_ws/src
$ git clone https://github.com/ykevin/riki_msgs.git 
```

3. Clone the package
```
$ cd ~/catkin_ws/src
$ git clone https://github.com/hsrong126/xrrobot.git
```

4. Compile
```
$ cd ~/catkin_ws
$ catkin_make
```

5. Run the robot
```
$ source ~/catkin_ws/devel/setup.sh
$ roslaunch xrrobot bringup.launch
```