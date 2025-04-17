- rmitbot_description:
    - urdf.xacro: added a boolean variable is_sim to select simulation or realrobot
    - ros2_control.xacro: added a condition relative to is_sim to send control to simulation or realrobot
- rmitbot_controller:
    - controller.yaml: use_sim_time removed from parameters
- rmitbot_localization:
    - ekf.yaml: use_sim_time removed from parameters
- rmitbot_firmware:
    - 


