RoboND-SLAM-Project
Udacity's Robotics Nanodegree 'Map My World Robot' Project



For mapping the Kitchen dining scene use the following commands:

First terminal:
$cd /home/workspace/catkin_ws/
$catkin_make
$source devel/setup.bash
$roslaunch slam_project world.launch world_name:=kitchen_dining.world

Second terminal:
$cd /home/workspace/catkin_ws/
$catkin_make
$source devel/setup.bash
$roslaunch slam_project teleop.launch

Third terminal:
$cd /home/workspace/catkin_ws/
$catkin_make
$source devel/setup.bash
$roslaunch slam_project rviz.launch

Last terminal:
$cd /home/workspace/catkin_ws/
$catkin_make
$source devel/setup.bash
$roslaunch slam_project mapping.launch




For mappy the My World scene use the following commands:

First terminal:
$cd /home/workspace/catkin_ws/
$catkin_make
$source devel/setup.bash
$roslaunch slam_project world.launch world_name:=my_world_last.world

Second terminal:
$cd /home/workspace/catkin_ws/
$catkin_make
$source devel/setup.bash
$roslaunch slam_project teleop.launch

Third terminal:
$cd /home/workspace/catkin_ws/
$catkin_make
$source devel/setup.bash
$roslaunch slam_project rviz.launch

Last terminal:
$cd /home/workspace/catkin_ws/
$catkin_make
$source devel/setup.bash
$roslaunch slam_project mapping_myworld.launch



For using the rtabmap database viewer, the mapping launch file has to be closed and the following command must be written in a new terminal: 
$rtabmap-databaseViewer ~/.ros/rtabmap.db
