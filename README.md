# Collaboration and Competition Deep Reinforcement Learning project.

## Description
![Environment](Figures/env.png)

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
This yields a single score for each episode.
The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

## Installation
### Install deep reinforcement learning repository
1. Clone [deep reinforcement learning repository](https://github.com/udacity/deep-reinforcement-learning)
2. Follow the instructions to install necessary [dependencies](https://github.com/udacity/deep-reinforcement-learning#dependencies)
### Download the Unity Environment
1. Download environment for your system into this repository root

* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)

* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)

* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)

* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

* Headless: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux_NoVis.zip)

2. Unzip (or decompress) the archive

3. Make sure of installing all requirements (find them on requirements.txt)

### How to train
1. Start the jupyter server
2. Open the ipynb notebook
3. Run all the cells. When loading the Unity environment, select the unzipped folder from previous section

## Results
![Results](https://github.com/thenickben/drlnd-p3-collab-compet/blob/master/Figures/Tenis.png)
