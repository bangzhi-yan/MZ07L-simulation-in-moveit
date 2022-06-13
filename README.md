# MZ07L-simulation-in-moveit
A kinematic simulation for MZ07L in moveit
run urdf:  
copy mz07l file into src folder under catkin_ws
under ~/catkin_ws
catkin build
source ~/devel/setup.bash
roslaunch mz07l display.launch  

run moveit simulation:  
copy mz07l_moveit_config file into src folder under catkin_ws  
under ~/catkin_ws  
catkin build  
source ~/devel/setup.bash  
roslaunch mz07l_moveit_config demo.launch  