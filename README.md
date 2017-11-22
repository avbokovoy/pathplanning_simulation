# pathplanning_simulation

# Prerequisites

TODO: Complete

# Compile

cd {path_to_your_catkin_workspace}/src
git clone https://github.com/avbokovoy/pathplanning_simulation.git
cd ..
catkin_make

# Run

1) Generate world file

rosrun pathplanning_generator world_generator.py

2) Run simulation 

roslaunch pathplanning_gazebo turtlebot_world.launch
