# DQN-NES-Pong
This is a repository for project in MO810 course-1s2018 IC-UNICAMP. The project is about implement DQN, NES and policy gradients for Pong and Catch game.
<br />

## Requirements

Python 3.5, PyTorch >= 0.2.0, numpy, gym, universe, cv2.
<br />


## Deep Q-learning (DQN):

* `dqn_pong.ipynb` : This is a DQN implementation for Pong game (gym environment) and was trained in google colab (aprox 5 hours). Achieved **reward = 18**.

* `kerasdqn_catch.ipynb`: For learn more about DQN, I decided to implement a shallow neural network for catch enviroment. See the results in file.
<br />

## Evolution Strategies (Natural):

* `main.py` : Train ES on Pong and achieved **reward = 5**. Functions from `train.py`, `envs.py` , `model.py`

```
python3 main.py --env-name PongDeterministic-v4 --n 10 --lr 0.01 --useAdam
```

* `catch_ES.ipynb`: NES implementation for catch game! See results in flie. 
<br />



