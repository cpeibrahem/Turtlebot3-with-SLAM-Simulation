### Turtlebot3-with-SLAM-Simulation
## `export TURTLEBOT3_MODEL=burger`


![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/27.PNG)

## `roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/28.PNG)
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/29.PNG)
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/30.PNG)
## `export TURTLEBOT3_MODEL=waffle`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/31.PNG)
## `roslaunch turtlebot3_gazebo turtlebot3_world.launch`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/33.PNG)
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/32.PNG)


## `export TURTLEBOT3_MODEL=waffle_pi`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/33.PNG)

## `roslaunch turtlebot3_gazebo turtlebot3_house.launch`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/34.PNG)
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/35.PNG)
## `roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/36.PNG)

## Lunch the Gazebo environment with waffle robot **`export TURTLEBOT3_MODEL=waffle`** then **`roslaunch turtlebot3_gazebo turtlebot3_world.launch`**

## Open new terminel to Run SLAM Node **`export TURTLEBOT3_MODEL=waffle`** then **`roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping`**
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/37.PNG)


## Open a new terminal to control the waffel robot and scan the area using lidar sensor **`export TURTLEBOT3_MODEL=waffle`** then**` roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch`**. (in the terminal we will control the robot direction using W,A,S,D,X keybored keys).
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/38.PNG)


## ``rosrun map_server map_saver -f ~/map``

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/39.PNG)
