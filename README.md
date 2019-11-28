# ARQ_ur5_ezgripper_moveit_config
Moveit configuration package for the UR5 + EZGripper robot that we have at Advanced Robotic @ Queen Mary University of London.

This package contains everything that is required to run the UR5 and Ezgripper in simulation using Moveit! linked with Gazebo. Since the EZGripper does not come with any ROS control interface, it is not possible to control the gripper when running on real hardware (but we can still control the robot arm).

**/!\ Please change ```controllers.yaml``` in the config folder according to how you launch the robot (simulation or not) /!\\**
