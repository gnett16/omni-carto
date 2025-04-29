Cài đặt: `sudo apt-get install ros-noetic-teleop-twist-keyboard`

Thứ tự chạy:
1. `source ~/catkin_ws/install_isolated/setup.bash`
2. `roslaunch omni gazebo.launch`
3. `roslaunch omni cartographer.launch`
4. `rosrun teleop_twist_keyboard teleop_twist_keyboard.py`
