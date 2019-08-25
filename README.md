# Project Overview
![image1](banana.gif)
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

# Installation Requirerments
For this project, you will not need to install Unity - this is because we have already built the environment for you, and you can download it from one of the links below. You need only select the environment that matches your operating system:

    Linux: click here
    Mac OSX: click here
    Windows (32-bit): click here
    Windows (64-bit): click here

# Code Description

The main code is reported in the Navigation.ypynb file, which includes information about the requirments and at the beginning runs some code examples to get envirorment informations.

The code used to train Agent is a simple value based training algorithm knows as Deep Q-Network.
The package contains two additional files with (model.py, and dqn_agent.py) which contains the code for the model and the agent used for the training.

# Future Developments 
The vanilla DQN used for training the Agent work pretty fine, but there is still room for improvements such as implementing:
a double DQN, a dueling DQN, and/or prioritized experience replay!
