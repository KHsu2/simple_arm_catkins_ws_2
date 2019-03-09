# simple_arm_catkins_ws_2
This repository is a progress keeper through Udacity's **ROS Essentials Lesson** in the Robotic's Nanodegree, intended as a future reference for setting up a Catkins workspace and ROS system. This project contains a simple robotic arm simulated in Gazebo and is controlled through ROS, allowing the robot arm to move to given joint angles or to automatically move if the attached camera is pointing at a plain background. 

![Simple Arm](/Images/simple_arm_pic.PNG)

## Launch
* Initialize Catkins workspace
``` $ mkdir -p <folder_destination>/catkins_ws/src 
    $ cd <folder_destination>/catkins_ws/src
    $ catkin_init_workspace
    $ cd <folder_destination>/catkins_ws
    $ catkin_make 
```

* Add contents of src (simple_arm, CMakeList) directory to current src folder 
* Launch simple_arm
``` $ cd <folder_destination>/catkins_ws
    $ catkin_make
    $ source devel/setup.bash
    $ roslaunch simple_arm robot_spawn.launch 
```

