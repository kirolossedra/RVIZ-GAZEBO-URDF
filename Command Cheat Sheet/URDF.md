ros2 run robot_state_publisher robot_state_publisher --ros-args -p robot_description:="$(xacro path/to/urdf)"


 ros2 launch urdf_tutorial display.launch.py model:=urdf/filename ## please note by default the launch file looks in the directory urdf_tutorial so I had to put the intermediate folder



 ros2 run joint_state_publisher_gui joint_state_publisher_gui
