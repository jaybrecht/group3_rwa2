## To run the package follow these steps 
	--> Unpack the zip file "group3_rwa2.zip" into "group3_rwa2" folder.
	--> Open two terminals.
	--> In terminal-1: (This is used to launch the environment)
		cd ~/group3_rwa2
		catkin_make
		source /opt/ros/melodic/setup.bash
		source ~/group3_rwa2/devel/setup.bash (Hoping the folder is in home directory)
		roslaunch group3_rwa2 group3_rwa2.launch

	--> In terminal-2: (This is to run the node which ouputs the sensor data)

		source /opt/ros/melodic/setup.bash
		source ~/group3_rwa2/devel/setup.bash 
		rosrun group3_rwa2 ariac_example_node
