# simple_arm_catkins_ws_2
This repository is a progress keeper through Udacity's **ROS Essentials Lesson** in the Robotic's Nanodegree, intended as a future reference for setting up a Catkins workspace and ROS system.

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

