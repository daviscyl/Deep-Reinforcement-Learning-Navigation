[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Udacity Deep Reinforcement Learning Nanodegree - Project 1: Navigation

### Introduction

For this Udacity project, I used a Deep Q-Network to solve a Unity environment which requires the agent to collect yellow bananas and avoid blue bananas.  

![Trained Agent][image1]

In this environment, a reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.

Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.M
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started

Codes were written using Python3.6.2, run this to install necessary packages:

`pip install -r requirements.txt`

The Unity environment only runs on Macs, for Windows users, download the Windows 32-bit version [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip).

Please follow the instruction in the [Udacity DRLND Instructions](https://github.com/udacity/deep-reinforcement-learning#dependencies) on setting up the environment.


### Instructions

- Run all the block cells `Report.ipynb` to initiate the environment and go through the trainings.
- `model.py` defines the Deep Q-Network's architecture.
- `den_agent.py` defines the DQN agent class.
- `checkpoint.pth` is the saved Deep Q-Network weights after training.
