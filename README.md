# Udacity-DRLND-3-Collaboration-and-Competition

**OUNoise's sigma=0.1 was the key!**

In this project, we train a double-jointed arm to reach target locations.

The simulation environment is based on Unity Environment. The code is available [here](https://github.com/udacity/deep-reinforcement-learning/tree/master/python/unityagents)

<img src=".gif" width=480>

### Rewards


### States
There are  states in this environment. Those consist of .

### Actions
Each action is a vector with . Every entry in the action vector is clipped between -1 and 1.

### Criteria
If the average score of the latest 100 episodes exceeds +0.5, it is considered solved.

## Getting started

### Python environment
Follow the instruction by Udacity [here](https://github.com/udacity/deep-reinforcement-learning#dependencies) to set up the Python environment. 

### Unity environment
1. Download the environment from one of the links below. For faster training, choose the "No visualization" environment.

    **No visualization:**
    - Linux: [click here]()

    **With visualization:**
    - Linux: [click here]()
    - Mac OSX: [click here]()
    - Windows (32-bit): [click here]()
    - Windows (64-bit): [click here]()

2. Move the downloaded file in the same folder as in this Readme, then unzip it.

3. Load `Tennis.ipynb` in Jupyter notebook, then follow the instruction.

For more information, please refer to the [Udacity's instruction](https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control).

## Report
The report can be found [here](Report.md)
