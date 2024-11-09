<<<<<<< HEAD
# Orangewood-
=======
# About

This ROS Package can be used to control the movement of a bot inside the turtlesim package

# Installation

- Install the `turtlesim` package

    ```bash
    sudo apt-get install ros-noetic-turtlesim
    ```

- Clone this package inside a catkin workspace

    ```bash
    mkdir -p ros_ws/src 
    cd ros_ws/src
    git clone https://github.com/topguns837/ros_session.git
    ```

- Compile the code and source the workspace

    ```bash
    catkin_make
    source devel/setup.bash
    ```

# Instructions to run the code

- In terminal 1

    ```bash
    roscore
    ```

- In terminal 2

    ```bash
    rosrun turtlesim turtlesim_node
    ```

- In terminal 3

    ```bash
    rosrun ros_session move_straight.py
    ```
>>>>>>> Added a basic readme
### Watch the Video
You can watch the video by clicking on the link below:

[Watch Video](https://github.com/codebreaker-pk/Orangewood-/blob/main/roscore%20http___CodePredator_11311_%202024-11-09%2019-04-06%20(2).mp4)

