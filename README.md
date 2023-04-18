Ubuntu 18.04

Install ROS Melodic.

Install ROS dependencies.

sudo apt install ros-melodic-costmap-2d \
ros-melodic-move-base \
ros-melodic-global-planner \
ros-melodic-amcl

Install Ipopt: Please refer the tutorial in "document/ipopt_install".


# Differential-Wheeled-Mobile-Robot---MPC

里面可以roslaunch mpc_ros nav_gazebo.launch可以实现仿真
同时也有实现轨迹跟踪：roslaunch mpc_ros ref_trajectory_tracking_gazebo.launch
