# ROS-TurtleBot3-Robot-Simulation
TurtleBot is a low-cost, personal robot kit with open-source software. TurtleBot was created at Willow Garage by MeloneeWise and Tully Foote .With TurtleBot, we’ll be able to build a robot that can drive around a house, see in 3D, and have enough horsepower to create exciting applications.

![86650340-9bf69800-bfb0-11ea-9b14-c3993002c804](https://user-images.githubusercontent.com/67114907/90448255-af3b6e00-e0ed-11ea-9a6f-f8fdd9589e9a.png)

## Downloading the TurtleBot3 simulation files:
Opening new  Terminal (Ctrl+alt+T)

Typing the following commands
```
~$ cd ~/catkin_ws/src/

~$ git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git

~$ cd ~/catkin_ws && catkin_make
```

![11](https://user-images.githubusercontent.com/67114907/90448692-8e274d00-e0ee-11ea-9b91-510a756e8d65.jpg)


## Installing the TurtleBot3 simulation packages:
Installing the independent packages for TurtleBot3 control by Entering the following commands:
```
 ~$ cd ~/catkin_ws/src/

 ~$ git clone https://github.com/ROBOTIS-GIT/turtlebot3_msgs.git

 ~$ git clone https://github.com/ROBOTIS-GIT/turtlebot3.git

 ~$ cd ~/catkin_ws and type catkin_make
```

![22](https://user-images.githubusercontent.com/67114907/90448915-0261f080-e0ef-11ea-8d4f-d29429a3ce06.jpg)
The preparation for TurtleBot3 is done.

## Launching turtlebot simulation:
TurtleBot3 has three models, Burger, Waffle, and Waffle Pi (as on the first picture), 
* specify which model will be used (e.g. Burger)
* choosing which file in gazebo folder to simulate (e.g. empty world)
* opening the file and replacing "TURTLEBOT3_MODEL" with "burger"
* close & save 

Writing the following commands
to  contact my own server without errors
```
~$ export ROS_HOSTNAME=localhost

~$ export ROS_MASTER_URI=http://localhost:11311
```
the following commands to lunch the turtlebot simulation
```
~$ roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch
```
![77](https://user-images.githubusercontent.com/67114907/90450351-2d9a0f00-e0f2-11ea-863b-f319be45ab89.jpg)
Done successfully ))

## Autonomous Navigation and Obstacle Avoidance:
Launching another Turtlebot simulation.

The simulation is to have TurtleBot3 autonomously navigate around a room and avoid crash into objects.
Typing the following commands:
```
~$ export ROS_HOSTNAME=localhost

~$ export ROS_MASTER_URI=http://localhost:11311

~$ roslaunch turtlebot3_gazebo turtlebot3_world.launch
 
```
On new terminal 
```
~$ roslaunch turtlebot3_gazebo turtlebot3_simulation.launch

```
![10](https://user-images.githubusercontent.com/67114907/90452651-5bce1d80-e0f7-11ea-8150-f33b64d56667.jpg)

Done successfully ))

THANK U :)

