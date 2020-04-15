# Report -- Project 2 Continous Control

## About the Architecture

Actor :

Dimensions are : State Space	---	256	---	128	---	Action Space

Activation function :   		Relu	---	Relu	---	Tanh

Critic :

Dimensions are : State Space + Action Space	---	256		---	128		---	1

Activation function :   				Leaky_Relu	---	Leaky_Relu	---	Tanh

## Hyperparameters

BUFFER_SIZE = int(1e6)  # replay buffer size 

BATCH_SIZE = 128         # minibatch size

GAMMA = 0.99            # discount factor

TAU = 1e-3              # for soft update of target parameters

LR_ACTOR = 1e-4         # learning rate of the actor

LR_CRITIC = 1e-4        # learning rate of the critic

WEIGHT_DECAY = 0.0      # L2 weight decay

N_LEARN_UPDATES = 10     # number of learning updates

N_TIME_STEPS = 20       # every n time step do update

MAX TIME STEPS = 1000  # max time steps per episode


## Plot of Rewards


## Result



## Future Work

1. Implementing the latest updates proposed in Twin Delayed DDPG.

2. Exploring PPO, D4PG algorithms
