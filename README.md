# ENPM809Y Final Project
 In this project, two ROS2 packages using C++ were implemented to direct the Turtlebot to reach the final destination by retrieving the relevant information from an Aruco marker in a simulated environment (Gazebo). 
 The first package (odom_updater) establishes the correct coordinate system transformation between the robot's odom frame and the robot's base footprint frame, which is required for the robot controller to correctly direct the robot to desired locations in the simulated environment. The second package (target_reacher) is responsible for first directing the robot to reach goal #1, where it could scan the Aruco marker to retrieve the location of goal #2, i.e., the final destination. 
 The package is then responsible for directing the robot to reach the final destination.