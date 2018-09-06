# Machine Learning Engineer Nanodegree
# Reinforcement Learning
## Project: Train a Smartcab How to Drive
### Summary:

In this project, I have implemented a smartcab simulator agent with Reinforcement learning techniques. Initial simulations are done without any policy and it is found that smartcab is making lot of bad decision and it is not safe to drive. Next, i used a default Q-learning policy where there are less number of bad decisions. Next, I did a simulation using a optimized Q-learning algorithm, where after around 600 simulations the safety rating has improved significantly.

### Install

This project requires **Python 2.7** with the [pygame](https://www.pygame.org/wiki/GettingStarted
) library installed


### Run

In a terminal or command window, navigate to the top-level project directory `smartcab/` (that contains this README) and run one of the following commands:

```python smartcab/agent.py```  
```python -m smartcab.agent```

This will run the `agent.py` file and execute your agent code.

For running notebook, use the command below from the same direcotry:


```jupyter notebook smartcab.ipynb```  