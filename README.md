# pathplanning_simulation

# Installing prerequisites

### 1. Install ROS Kinetic

```bash
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
```
```bash
sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 421C365BD9FF1F717815A3895523BAEEB01FA116
```
```bash
sudo apt-get update
```
```bash
sudo apt-get install ros-kinetic-desktop-full
```



# Prerequisites

Antlr

```bash
sudo apt install python-antlr
```

TODO: Complete

# Compile

```bash
cd {path_to_your_catkin_workspace}/src
git clone https://github.com/avbokovoy/pathplanning_simulation.git
cd ..
catkin_make
```

# Run

1) Generate world file 

```bash
rosrun pathplanning_generator world_generator.py
```

2) Run simulation 

```bash
roslaunch pathplanning_gazebo turtlebot_world.launch
```

3) Run pathplanning_mover2 (work in progress)

```bash
rosrun pathplanning_mover2 ...
```
