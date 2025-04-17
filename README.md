Folders and files explanation
.vscode, build, install, log:  autocreated, do nothing
src:      contains pkg
- rmitbot_description:
    - launch/gazebo.launch.py:  added gz_ros2_bridge for gazebo sim_time to ros2 and imu message
    - urdf: 
        - rmitbot.urdf.xacro:   imu_link, imu_joint added
        - rmitbot_gazebo.xacro: imu_pluggins added
- rmitbot_controller:  
    - config/rmitbot_controller.yaml    : odom_frame_id added, base_frame_id chaned from base_footprint to base_footpring_raw, because rmitbot_localization is now broadcasting the tf odom --> base_footprint
- rmitbot_localization:  
    - config/ekf.yaml: configuration of the ekf
    - launch/local_localization.launch.py: launch file for the ekf

