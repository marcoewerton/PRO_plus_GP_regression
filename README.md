# PRO_plus_GP_regression
Code related to paper "Reinforcement Learning of Trajectory Distributions: Applications in Assisted Teleoperation and Motion Planning", IROS 2019

This repository has already a pre-trained agent. One can see the behavior of this agent by running the script main_test.py
This is a code to make the robot avoid pedestrians and reach a target position with respect to the pedestrian. It uses the same principle as the Pringles experiment described in the paper but here the start position of the ProMP is always where the robot is right now. In the Pringles experiment, there was a certain start position, which was always the same.

In order to train the agent again, one needs to run main_training. But the training takes several hours. I believe that it is possible to make it much more efficient by avoiding certain for loops and making the code more vectorized.
