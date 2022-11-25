# ZED_UR_handeye_calibrate

cd ~/catkin_ws/
catkin_make
source ./devel/setup.bash
roslaunch zed_ar_track_alvar_example zed_ar_track_alvar.launch
Susbribe the marker information
rostopic echo /zed/ar_pose_marker
