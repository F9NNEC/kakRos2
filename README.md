# kakRos2

**`buat package'**
~/ros2_ws/src/robot_controller/robot_controller$ ros2 pkg create robot_controller --build-type ament_python --dependencies rclpy

**`buat package agar executeable'**
~/ros2_ws/src/robot_controller/robot_controller$ chmod +x node1.py

**`setiap edit file, run'**
~/ros2_ws$ source ~/.bashrc

**`biar ga build manual'**
~/ros2_ws$ colcon build --symlink-install

**`run fungsi package dari ros2'**
~/ros2_ws$ ros2 run robot_controller node1