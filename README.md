# Project 1: Navigation

### Introduction

For this project, you will train an agent to navigate and collect bananas in a large, square world.  
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes to be considered solved.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install required package.

```bash
pip install matplotlib
pip install torch
```

## Usage
To run the pre-trained agent, you can use "model.pt", which includes the model weights.
As for training the model, run "Navigation.ipynb"

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
