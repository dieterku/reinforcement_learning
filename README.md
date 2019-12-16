# Reinforcement learning - an introduction

### Intended audience 

This notebook is for you if you are relatively (or completely) new to reinforcement learning and want to know, how reinforcement learning works on a technical level. It would be quite helpfull, if you already have some experience with: 
* Neural networks
* Pytorch

### Overview
This notebook shows, how to train a neural network to balance a pole on a cart. For this we are using a "prefabricated environment" provided by OpenAI: **The Cart pole environment**.    

![cart_pole_environment.PNG](cart_pole_environment.PNG)
    
Please have a look here: https://gym.openai.com/envs/CartPole-v1/ for more details. 
By using unsupervised reinforcement learning the model learning to balance better and better:    
    
![learning_progress.PNG](learning_progress.PNG) 
       
### Technical preconditions
There are basically two technical preconditions for running this notebook:
* `Pytorch` has to be installed (see https://pytorch.org/  for installation notes)
* `Gym` has to be installed (see https://gym.openai.com/docs/#installation for installation notes)
* Important note: There is no GPU needed for running this code   
 
