# RoboND-DeepRL-Project
#RL
The goal of this project is to create a DQN agent and define reward functions to teach a robotic arm to carry out two primary objectives:
1- Have any part of the robot arm touch the object of interest, with at least a 90% accuracy.
2- Have only the gripper base of the robot arm touch the object, with at least an 80% accuracy.
Both of these objectives, have associated tasks that you will complete while working on this project. The upcoming sections will cover these tasks in detail.
This project is implemented in Gazebo environment to simulate Reinforcement Learning with DQN agent using Pytorch library.
In this project robotic arm agent is trained to reach the goal object by defining the reward function and control approaches.
Projects tasks:
- Subscribe to camera and collision topics
- Create the DQN Agent
- Choosing velocity or position-based control of arm joints
- Creating reward function:
    1- Reward for robot gripper hitting the ground
    2-Issue an interim reward based on the distance to the object
    3-Issue a reward based on collision between the arm and the object
- Tuning the hyperparameters
