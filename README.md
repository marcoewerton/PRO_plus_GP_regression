# PRO_plus_GP_regression
Code related to the papers "Learning Trajectory Distributions for Assisted Teleoperation and Path Planning", Frontiers in Robotics and AI, 2019 and "Reinforcement Learning of Trajectory Distributions: Applications in Assisted Teleoperation and Motion Planning", IROS 2019.

This repository has already a pre-trained agent. One can see the behavior of this agent by running the script main_test.py
This is a code to make the robot (green) avoid the pedestrian (red) and reach a target position (X) with respect to the pedestrian. It uses the same principle as the Pringles experiment described in the paper but here the start position of the ProMP is always where the robot is right now. In the Pringles experiment, there was a certain start position, which was always the same.

One can control the pedestrian by moving the mouse and left-clicking anywhere on the image. One can also move the mouse while holding the left mouse button.

In order to train the agent again, one needs to run main_training. But the training takes several hours. It may be possible to make it much more efficient by avoiding certain for loops and making the code more vectorized.
