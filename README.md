

#### Launch Files:

First, setup the environment:
```
cd catkin_ws
source devel/setup.bash
export ROS_PACKAGE_PATH=$ROS_PACKAGE_PATH:$(pwd)/src
```

To create your own map, run:
```
roslaunch mybot_sim gazebo1.launch
```

To navigate through your map use:
```
roslaunch mybot_sim navigation.launch
```

