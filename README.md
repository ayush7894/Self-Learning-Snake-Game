# Self-Learning-Snake-Game

Snake has simple rules:

The world is a grid.
The snake can only travel orthogonally along this grid.
This world has a border that kills the snake on contact.
The snake cannot stop moving.
If the snake runs into itself, it dies.
Every time the snake eats, it grows longer.
The goal is to grow as long as possible.
When playing the game, there is a decision to make each time the snake takes a step forward: continue straight, turn left, or turn right.

Our goal is to create an AI to learn how to make this same decision. First assessing the state of the world that the snake lives in, then choosing the move that will keep it alive and continue to grow longer.


![alt text](https://cdn-images-1.medium.com/max/1000/1*mmY1c1s8U_EGcbMCH_vRhA.png)

There are many methods, algorithms, and techniques that could be used to solve Snake. Some of these could fall under the umbrella term of AI.I have developed it using Q-Learning i.e Reinforcement Learning.

This is because I don’t have a dataset of high scoring Snake play throughs to use to train a neural network by example.
