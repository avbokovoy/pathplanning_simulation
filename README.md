# pathplanning_simulation

# Prerequisites

TODO: Complete

# Compile

[code language="bash"]
cd {path_to_your_catkin_workspace}/src
git clone https://github.com/avbokovoy/pathplanning_simulation.git
cd ..
catkin_make
[code]

# Run

1) Generate world file (doesn't work atm)

[code language="bash"]
rosrun pathplanning_generator world_generator.py
[code]

2) Run simulation 

[code language="bash"]
roslaunch pathplanning_gazebo turtlebot_world.launch
[code]
