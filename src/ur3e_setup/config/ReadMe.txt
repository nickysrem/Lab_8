1. Use the calibration file from this folder when starting the ur_driver ROS package. Make sure not to copy the calibration files between computers since each UR3e arm has its own unique calibration.

2. Watch out for these warnings when you are launching the ur_driver package
	- cannot access RT kernel: make sure you launched docker with these paramaters --ulimit rtprio=99 --ulimit rttime=-1 ;
	- calibration file does not match: contact the lab manager to get the correct file.

3. After your Gazebo simulation was approved, launch the ROS package to control the UR3e arm:
