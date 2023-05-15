
<p align="center">
    <div style="display: inline-block; float: left; width: 50%;" align="center">
        <img src="Render/demo.gif" width="600">
        <p align="center">Before</p>
    </div>
    <div style="display: inline-block; float: left; width: 50%;"  align="center">
        <img src="Render/eval.gif" width="600">
         <p align="center">After</p>
    </div>
</p>


**Project Descriptions**

Cartpole is a classic control problem in the field of Reinforcement Learning (RL) where the goal is to balance a pole on top of a cart moving on a frictionless track. It is a simple yet challenging task that requires the agent to make continuous decisions based on the current state of the environment to keep the pole upright while the cart moves left or right.

In the Cartpole environment, the state consists of four continuous variables representing the position and velocity of the cart and pole, respectively. The agent can take two discrete actions - move the cart either left or right. The agent receives a positive reward for every time step that the pole remains upright, and the game continues until the pole falls beyond a certain angle or the cart moves out of the track's boundaries.

On my Github project, I have implemented a solution for the Cartpole problem using Deep Q-Networks (DQN) - a popular RL algorithm that combines deep learning with Q-learning. The agent learns to make decisions by interacting with the environment, collecting experience, and updating its Q-value estimates. The implementation includes the creation of the Cartpole environment, defining the agent's neural network, training the agent using DQN, and evaluating the agent's performance.
