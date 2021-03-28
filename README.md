# rtabmap_simulation
to run the simulation use the following commands

## first terminal
$ roscore

## second terminal inside the workspace
$ catkin_make  
$ source devel/setup.bash  
$ roslaunch turtlebot3_gazebo turtlebot3_world.launch  

## third terminal inside the workspace  
$ source devel/setup.bash  
$ roslaunch my_rtabmap mapping_turtlebot3.launch  
