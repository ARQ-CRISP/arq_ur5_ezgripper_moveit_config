cmake_minimum_required(VERSION 2.8.3)
project(arq_ur5_ezgripper_moveit_config)

find_package(catkin REQUIRED COMPONENTS
  joint_state_publisher
  moveit_kinematics
  moveit_planners_ompl
  moveit_ros_move_group
  moveit_ros_visualization
  robot_state_publisher
  xacro
)

catkin_package()
