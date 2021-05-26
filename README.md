
# Creating a simple Robotic Model using ROS (Robot Operating Systems)

## Pre-requisites

This project was done using [ROS Noetic on Ubuntu](http://wiki.ros.org/noetic/Installation/Ubuntu). 

## The Robot model

<p align="center" width="100%">
    <img width="33%" src="https://user-images.githubusercontent.com/59824729/119690418-4ac0f280-be67-11eb-913f-bb8e95fc9adf.png"> 
</p>

## How to run?

Clone the repository inside the src folder of your catkin_ws (source folder of your catkin workspace).

The repo can be cloned using the following commands in the terminal. 

```
cd ~/catkin_ws/src
git clone https://github.com/DeepthiSudharsan/waiterbot.git
```
You can also download the zip file and extract it in the source folder.

Then, we do catkin_make

```
cd ~/catkin_ws
catkin_make
```
To run the robot model, run the commands given below

```
. devel/setup.bash
roslaunch waiterbot display.launch
```
Voila, you get the waiterbot in your rviz window along with a pop-up gui for controlling the robot movement!

<p align="center" width="100%">
<img src="https://user-images.githubusercontent.com/59824729/119692235-e0a94d00-be68-11eb-86bd-cb3e04cd7c77.gif" width="430" height="576" />
</p>

## References

1. http://wiki.ros.org/urdf/Tutorials/Building%20a%20Visual%20Robot%20Model%20with%20URDF%20from%20Scratch
