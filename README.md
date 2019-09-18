# i2r
To create package:
```
cd ~/catkin_ws/src
catkin_create_pkg urdf_robot rospy
```

Put the folder urdf_robot here.

Then compile it:
```
cd ~/catkin_ws
catkin_make
source devel/setup.bash
```
To launch: 
```
roslaunch urdf_robot urdf.launch
```
