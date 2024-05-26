# Flappy Bird

The goal of this assignment is to apply reinforcement learning methods to a simple game called Text Flappy Bird (TFB). The game is a variation to the well know Flappy Bird in which the player is made with a simple unit-element character as can be seen below.

<p align="center">
  <img src="https://github.com/apoupon/grad-CAM/blob/main/flappy_bird_screen.png?raw=true" alt="Flappy Bird screen"/>
</p>
There are two distinct versions of the environment available, one that returns as an observation the complete screen render of the game (TextFlappyBird-screen-v0) and another one that returns the distance of the player from the center of the closest upcoming pipe gap (TextFlappyBirdv0) along the two axes (x, y).
This work focuses on solving the second environment TextFlappyBirdv0. Two agents are implemented to solve it: a Monte-Carlo based agent and a Sarsa($\lambda$) agent. The report, spanning three pages, details the experimental setup, discusses the limitations inherent to both environments, and examines the performances demonstrated by each agent.




