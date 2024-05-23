# Reinforcement Learning project using Gym (OpenAI), Tensorflow, Keras, and Keras-RL. 

## The chosen environment is the Cart-Pole v1 environment : 
This environment corresponds to the version of the cart-pole problem described by Barto, Sutton, and Anderson in “Neuronlike Adaptive Elements That Can Solve Difficult Learning Control Problem”. A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The pendulum is placed upright on the cart and the goal is to balance the pole by applying forces in the left and right direction on the cart. The environment is rendered with PyGame.


## Environment caracteristics
##### Action Space :
The cart can move RIGHT or LEFT
##### Observation Space :
- Cart Position
- Cart Velocity
- Pole Angle
- Pole Angular Velocity
##### Rewards :
Since the goal is to keep the pole upright for as long as possible, a reward of +1 for every step taken. Max score is 500.
##### Episode End :
- Pole Angle > 12°
- Cart reaches the edge of the display
- Episode length = 500 steps



## Included pre-trained models :
- pre-trained-model-20ksteps : this is a pre-trained DQN/BoltzmannQ/Adam=(lr=0.001) model on 20,000 steps (averages a score of about 190-200).
- pre-trained-model-100ksteps : this is a pre-trained DQN/BoltzmannQ/Adam=(lr=0.001) model on 100,000 steps (perfect score every time).


