# Udacity_DRLND_Collaboration_and_Competition

### Environment detail

The project uses unity Tennis environment, the state space for one player is a vector whose length is 24, 
whereas Each action is a vector with two numbers, corresponding to movement toward net or away from net, and jumping.
The environment is considered solved when agents get an average score of +0.5 
(over 100 consecutive episodes, after taking the maximum over both agents)


### dependencies

For this project, you'll need to install the following packages whether using pip or conda.

- pytorch(>=0.4)
- numpy(>=1.11)
- matplotlib 

You also need to download Udacity environment for banana collector game, the links are in below. This project has two version, one is to solve one agent environment, two is to solve 20 agents environment, I choose to solve version two.

- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

download the environment you need and unzip in the same folder as the notebook.

### How to use the notebook

For this project, there are 3 python scripts called ddpg_agents.py, model.py and log_control.py, and all the training code is in the Report.ipynb.

To train your agent or see the performance of the pre-trained agent, open Report.ipynb, modify ddpg_agents.py to try different hyperparameters, 
modify model.py to try different architecture. log_control.py is to help you stop the training anytime you want and doesn't lose any progress
