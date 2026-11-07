# kakRos2

**`Buat package`**<br>
~/ros2_ws/src/robot_controller/robot_controller$ ros2 pkg create robot_controller --build-type ament_python --dependencies rclpy<br>

**`Buat package agar executeable`**<br>
~/ros2_ws/src/robot_controller/robot_controller$ chmod +x node1.py<br>

**`Setiap edit file, run`**<br>
~/ros2_ws$ source ~/.bashrc<br>

**`Biar ga build manual`**<br>
~/ros2_ws$ colcon build --symlink-install<br>

**`Run fungsi package dari ros2`**<br>
~/ros2_ws$ ros2 run robot_controller node1<br>

**`Topek`**<br>
~/ros2_ws$ rqt_graph<br>
~/ros2_ws$ ros2 topic list<br>
~/ros2_ws$ ros2 topic info /<br>

**`Publisher`**<br>
~/ros2_ws$ touch draw_cricle.py<br>
~/ros2_ws$ chmod +x draw_circle.py<br>
~/ros2_ws$ colcon build --symlink-install<br>

**`Subscriber`**<br>
~$ ros2 topic info /turtle1/pose<br>
~$ ros2 interface show turtlesim/msg/Pose<br>
~/ros2_ws$ touch pose_subscriber.py<br>
~/ros2_ws$ chmod +x pose_subscriber.py<br>
~/ros2_ws$ colcon build --symlink-install<br>