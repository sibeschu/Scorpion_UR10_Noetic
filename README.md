# Scorpion_UR10_Noetic

roslaunch ur_robot_driver ur10_bringup.launch robot_ip:=192.168.1.100 kinematics_config:=path/to/my_robot_calibration.yaml

roslaunch ur10_moveit_config moveit_rviz.launch

roslaunch ur10_moveit_config moveit_planning_execution.launch rviz:=true

roslaunch ur10_moveit_config moveit_rviz.launch
