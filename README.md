# "arm_urdf" is a ROS package
sw2ros exports ROS packages for urdf files. this ROS package can be directly used in a ros_ws as a package
but this package is not supported in ROS2 and can not be used in a ros2_ws.

# "arm_urdf_ROS2_pack" is a ROS2 package
This is a ROS2 package of the urdf file. this can be directly used in ros2_ws as a package.
rename "arm_urdf_ROS2_pack" to "arm_urdf" before use it in a ros2_ws.
arm_urdf --->> CONVERTER --->> arm_urdf_ROS2_pack
CONVERTER=[sw2urdf_ros2](https://github.com/xiaoming-sun6/sw2urdf_ros2)
