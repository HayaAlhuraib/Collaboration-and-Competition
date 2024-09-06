
# Deep Reinforcement Learning Nanodegree Project: Collaboration and Competition

1. Project Overview

The goal of this project is to solve the Tennis environment, where two agents control rackets to bounce a ball over a net. The agents receive rewards based on their actions: +0.1 for hitting the ball over the net and -0.01 for letting the ball hit the ground or hitting it out of bounds. The objective is to keep the ball in play.
2. Environment Details

The observation space consists of 8 variables, including the position and velocity of the ball and racket. Each agent receives its own local observation. Two continuous actions are available: movement toward or away from the net, and jumping. The task is episodic, and the environment is considered solved when the average score over 100 consecutive episodes is at least +0.5.

4. Getting Started

To begin, follow these steps:

- Clone the repository: Clone this repository and install the dependencies specified in the official DRLND-repository.

- Download the environment: Choose the appropriate link for your operating system:

Linux: Tennis_Linux.zip
Mac OSX: Tennis.app.zip

Windows (32-bit): Tennis_Windows_x86.zip
Windows (64-bit): Tennis_Windows_x86_64.zip (For Windows users, check this link to determine your operating system's bit version.)
Place and unzip the file: Place the downloaded file in this GitHub repository and unzip (or decompress) the file. Then, rename the folder to Tennis. (Now Tennis/Tennis.exe should exist.)


Instructions

To train the agent, simply execute the cells in training.ipynb. For a demonstration of the trained agent, execute demonstration.ipynb.