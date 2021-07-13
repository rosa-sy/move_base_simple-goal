# move_base_simple-goal
Write a python script that publishes to /move_base_simple/goal topic
---
### First 
open rivs & gazebo

export TURTLEBOT3_MODEL=burger

roslaunch turtlebot3_gazebo turtlebot3_world.launch

export TURTLEBOT3_MODEL=burger

roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

### create a package

cd ~/catkin_ws/src/
catkin_create_pkg navv_pkg geometry_msgs rospy 

in new terminal 

cd ~/catkin_ws

catkin_make

## Make sure that the things to be executed and the libraries are written in a  CMakeLists.txt file

### write python script

pos.py

### change the permission

go to path of pos.py

chmod +x pos.py

### run the node

rosrun navv_pkg pos.py

if dose not run 

in new terminal 

roscore

---
![photo_2021-07-13_14-10-56](https://user-images.githubusercontent.com/85003576/125444651-27daacc5-7c1f-4465-b351-99eb75a930a6.jpg)

![photo_2021-07-13_14-10-43](https://user-images.githubusercontent.com/85003576/125444687-8e71e4a8-250a-4c4c-acd6-57c24a3b8372.jpg)

![photo_2021-07-13_14-11-04](https://user-images.githubusercontent.com/85003576/125444549-f4f15c8a-cbc4-4f21-b41f-937ceef6cfd7.jpg)

![photo_2021-07-13_14-10-51](https://user-images.githubusercontent.com/85003576/125444860-676853e1-ce4b-42b4-a2df-dbaf05dbed36.jpg)


![photo_2021-07-13_14-10-38](https://user-images.githubusercontent.com/85003576/125444774-7d8ddf99-7b30-4199-93f1-13196b7ef670.jpg)

