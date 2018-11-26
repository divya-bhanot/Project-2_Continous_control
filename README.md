[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"
[image2]: https://user-images.githubusercontent.com/10624937/43851646-d899bf20-9b00-11e8-858c-29b5c2c94ccc.png "Crawler"


# Project 2: Continuous Control

### Introduction

For this project, I have  worked with the Deep Deterministic Policy gradient approach by using actor-crtic based model

![Trained Agent][image1]

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

### Distributed Training

For this project, I have opted fo solving the first version via a single agent
The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30. 

### Getting Started

1. Using the workspace provided by udacity . Implementation is done using single python notebook by defining all
the required code componenets like replay memory, agent advances like how to select next action, which is next state
and doing a learning update at desired frequency.

Description for code files in git https://github.com/divya-bhanot/Project-2_Continous_control:
Continous-control.ipynb : It includes all the code base along with comments which defines model , agent and training the agent
Continous-control.html: Html version of above jupyter notebook
checkpoint_critic.pth: Saved model weights of the successful critic agent.
checkpoint_actor.pth: Saved model weights of the successful actor agent.
unit-environment.log : log file from unity environment 
README.md: Environment set up instructions as well as code base description
Report.pdf: Final report for project

2. After successfully running the code, create a new git repo, clone the repositery to local and add all the code and required documentation
files. Commit the code and push the branch to remote repo. 

### Instructions

Follow the instructions in the code file  `Continuous_Control.ipynb` to get started with training your own agent! 