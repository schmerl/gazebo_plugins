# gazebo_plugins

Contains a local copy of the gazebo plugins, some of which are changed for BRASS.

In particular, the Kinect now has the ability to be turned on and off by sending a string "on" or "off" to the topic /sensor/kinect/onoff

## To build
The repository is a catkin project. So, copy the directory into catkin_ws/src and then do catkin_make

To install properly, ensure that the required .so file that will beiin catkin_ws/devel/lib to ~/customlibs
