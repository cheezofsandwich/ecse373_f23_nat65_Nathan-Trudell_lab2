### ECSE 473 Laboratory 2 Submission

##### Nathan Trudell


#### Description

This laboratory incorporates the use of rviz and creates a basic robot with 2 wheels to view as various commands are tested out.


#### Dependencies
ROS
rviz
liburdfdom
catkin
velodyne_description
gazebo_plugins
map_server

#### Installing

Downloading the package directly from github should provide all necessary components.


#### Executing Program

Execute the program by invoking the launch file:

roslaunch navvis_description display.launch

Params:

	use_sim_time default set to false, whether or not to use clock while running map simulation

	use_xacro default set to true, whether or not to use xacro or urdf file for robot model

	use_joint_state_publisher_gui default set to true, whether or not to use joint state gui

	use_robot_state_publisher set totrue, whether or not to use robot state publisher
	
	file 				name of file to use (set to robot.urdf or robot.xacro)
	
	filename 			full path of file to use
	
Purpose of launch file: Creates base configuration for robot and can be used by laboratory 3 via "include" to bring in the model for simulation.


#### Authors
Nathan Trudell using information created by Dr. Greg Lee for ECSE 373/473 laboratory 2
