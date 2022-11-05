# p2_continuous-control Project

This repository contains the solution for the second project of the Udacity Deep Reinforcement Learning Nanodegree.

# Environment

The environment for this project is the Reacher environment.

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

For this project, two separate versions of the Unity environment were provided:

The first version contains a single agent.
The second version contains 20 identical agents, each with its own copy of the environment.
The second version is useful for algorithms like PPO, A3C, and D4PG that use multiple (non-interacting, parallel) copies of the same agent to distribute the task of gathering experience.

I solved the environment using the first version with just a single agent. According to project requirements, the agent must get an average score of +30 over 100 consecutive episodes to be considered solved.

# Instruction

Run Continuous_Control which is the notebook that contains the solution of the environment with single agent.
