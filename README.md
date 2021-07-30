# Robot-Navigation-Using-SLAM-ROS
Use Turtlebot3 with SLAM 
add these commands:

-sudo apt update
-sudo apt upgrade
-wget https://raw.githubusercontent.com/ROBOTIS-GIT/robotis_tools/master/install_ros_melodic.sh
-chmod 755 ./install_ros_melodic.sh
-bash ./install_ros_melodic.sh
-sudo apt-get install ros-melodic-joy ros-melodic-teleop-twist-joy \ ros-melodic-teleop-twist-keyboard ros-melodic-laser-proc \ ros-melodic-rgbd-launch ros-melodic-depthimage-to-laserscan \ ros-melodic-rosserial-arduino ros-melodic-rosserial-python \ ros-melodic-rosserial-server ros-melodic-rosserial-client \ ros-melodic-rosserial-msgs ros-melodic-amcl ros-melodic-map-server \ ros-melodic-move-base ros-melodic-urdf ros-melodic-xacro \ ros-melodic-compressed-image-transport ros-melodic-rqt* \ ros-melodic-gmapping ros-melodic-navigation ros-melodic-interactive-markers
-sudo apt-get install ros-melodic-dynamixel-sdk
-sudo apt-get install ros-melodic-turtlebot3-msgs
-sudo apt-get install ros-melodic-turtlebot3
-cd ~/catkin_ws/src/
-git clone -b melodic-devel https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git
-cd ~/catkin_ws && catkin_make
-Then write cd or open new terminal and write source ~/catkin_ws/devel/setup.bash or use echo "source ~/catkin_ws/devel/setup.bash" >> ~/.bashrc
"Empty world with a robot called "burger":
-export TURTLEBOT3_MODEL=burgert
-roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch

![Screenshot from 2021-07-16 19-22-43](https://user-images.githubusercontent.com/87448729/126088335-4686cd84-9b14-4253-8ea0-5513d947b21d.png)
