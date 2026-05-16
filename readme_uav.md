# XI35 UAV 启动
# 飞控(MAV-ROS)
``` bash
# terminal 1
roscd mavros
roslaunch ./launch/px4.launch
```

# FAST-LIVO2
``` bash
# terminal 2
cd src/FAST-Calib/launch_sensors
roslaunch ./rviz_MID360_rer.launch

# terminal 3
roslaunch fast_livo mapping_mid360-rer.launch
```
