# capo_rviz_launch
Rviz configuration to use on local machine when navigaing mobile robot


Firstly to run Rviz move to work directory and source ROS2.
```
cd ~/dev_ws
source /opt/ros/foxy/setup.bash
. install/local_setup.bash
```

To work with robot visualization and mapping launch:
```
ros2 launch rviz_config urdf.launch.py
```

For navigation purposes launch:
```
ros2 launch rviz_config nav.launch.py
```
