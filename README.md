# Polytechnique INF639 2024

Copyright (c) 2019-2024 Jérémie Decock

<img src="https://github.com/jeremiedecock/polytechnique-inf639-2024-students/blob/master/logo.jpg?raw=true" width="250">

- GitHub repository for students: https://github.com/jeremiedecock/polytechnique-inf639-2024-students
- Moodle: https://moodle.polytechnique.fr/course/view.php?id=TODO


## Lab sessions

### Lab session 1: Deep Value-based Reinforcement Learning

- Open in Google Colab (short link): http://www.jdhp.org/inf639/lab1
- Open in Google Colab: https://colab.research.google.com/github/jeremiedecock/polytechnique-inf639-2024-students/blob/master/lab1_deep_value-based_reinforcement_learning.ipynb
- Open in MyBinder: https://mybinder.org/v2/gh/jeremiedecock/polytechnique-inf639-2024-students/master?filepath=lab1_deep_value-based_reinforcement_learning.ipynb
- Open in NbViewer: https://nbviewer.jupyter.org/github/jeremiedecock/polytechnique-inf639-2024-students/blob/master/lab1_deep_value-based_reinforcement_learning.ipynb
- Download the notebook file: https://github.com/jeremiedecock/polytechnique-inf639-2024-students/raw/master/lab1_deep_value-based_reinforcement_learning.ipynb

#### Description

The aim of this lab is to provide an in-depth exploration of the most renowned value-based reinforcement learning techniques, specifically Deep Q-Networks and its enhancements.

In this Python notebook, you will implement and evaluate Deep Q-Networks (DQN) and its various adaptations.

#### Overview

- Deep value-based reinforcement learning
- Part 1: Hands on **Cart Pole** environment
  - Exercise 1: Hands on Cart Pole
- Part 2: A **naive deep value-based agent**
  - Exercise 2: Implement the naive value-based deep reinforcement learning algorithm
- Why It Doesn't Work: The Complexity of Deep Reinforcement Learning
- Part 3: Deep Q-Networks v1 (DQN version 2013)
  - **Experience replay**
  - DQN v2013 Algorithm
  - Exercise 3: Implement DQN with experience replay
- Part 4: Deep Q-Networks v2 (DQN version 2015)
  - **Infrequent weight updates**
  - DQN v2015 Algorithm
  - Exercise 4: Implement DQN v2015 with infrequent weight updates
- Part 5: **Double Deep Q-Network (DDQN)**
  - DDQN Algorithm
  - Exercise 5: Implement DDQN
- Part 6: **Prioritized Experience Replay (PEX or PER)**
  - DQN with PER algorithm
  - Exercise 6: Implement DQN with PER
- Bonus: **Gradient clipping**
- Bonus: Putting everything together (the ***Rainbow paper***)
- Bonus: Test and train a DQN agent to play **Atari games**
- Further readings
  - **Dueling DDQN (DDDQN)** : Advantage function
  - **Distributional methods**
  - **NoisyNets DQN**


### Lab session 2: Deep Policy-based Reinforcement Learning

- Open in Google Colab (short link): http://www.jdhp.org/inf639/lab2
- Open in Google Colab: https://colab.research.google.com/github/jeremiedecock/polytechnique-inf639-2024-students/blob/master/lab2_deep_policy-based_reinforcement_learning.ipynb
- Open in MyBinder: https://mybinder.org/v2/gh/jeremiedecock/polytechnique-inf639-2024-students/master?filepath=lab2_deep_policy-based_reinforcement_learning.ipynb
- Open in NbViewer: https://nbviewer.jupyter.org/github/jeremiedecock/polytechnique-inf639-2024-students/blob/master/lab2_deep_policy-based_reinforcement_learning.ipynb
- Download the notebook file: https://github.com/jeremiedecock/polytechnique-inf639-2024-students/raw/master/lab2_deep_policy-based_reinforcement_learning.ipynb

#### Description

The aim of this lab is to provide an in-depth exploration of policy-based reinforcement learning techniques, with a particular focus on the *Monte Carlo Policy Gradient (REINFORCE)* and *Actor Critic* methods.

In this Python notebook, you'll have the opportunity to implement and assess several renowned Policy Gradient techniques.

#### Overview

- Part 1: Monte Carlo Policy Gradient (**REINFORCE**)
  - The Policy Gradient theorem
  - Monte Carlo policy gradient (REINFORCE)
  - Exercise 1: REINFORCE for discrete action spaces (Cartpole)
  - Exercise 2: **REINFORCE with Baseline**
  - Bonus Exercise: Implementing **REINFORCE for Continuous Action Spaces** (**Lunar Lander**)
- Part 2: **Actor Critic**
  - **Actor Critic with bootstrapping**


### Lab session 3: Model-based Reinforcement Learning

- Open in Google Colab (short link): http://www.jdhp.org/inf639/lab3
- Open in Google Colab: https://colab.research.google.com/github/jeremiedecock/polytechnique-inf639-2024-students/blob/master/lab3_mcts.ipynb
- Open in MyBinder: https://mybinder.org/v2/gh/jeremiedecock/polytechnique-inf639-2024-students/master?filepath=lab3_mcts.ipynb
- Open in NbViewer: https://nbviewer.jupyter.org/github/jeremiedecock/polytechnique-inf639-2024-students/blob/master/lab3_mcts.ipynb
- Download the notebook file: https://github.com/jeremiedecock/polytechnique-inf639-2024-students/raw/master/lab3_mcts.ipynb

#### Description

In our preceding labs, we've delved into model-free approaches, encompassing both value-based and policy-based methods.

Model-free reinforcement learning methods learn directly from episodes of experience. They are called "model-free" because they do not need to know or learn the model of the environment (i.e., the reward and transition probability functions). Examples include Q-learning and policy gradients.

On the other hand, model-based reinforcement learning methods attempt to first learn a model of the environment (i.e., the reward and transition probability functions), and then use this model to make decisions. They can plan ahead by simulating future states in the model, which can lead to more efficient learning than model-free methods.

The aim of this lab is to provide an in-depth exploration of one of the most famous model-based reinforcement learning method: *Monte Carlo Tree Search (MCTS)*.

In this Python notebook, you will implement and assess this algorithm on the Naughts and Crosses board game.

#### Overview

- Part 1: **Monte Carlo Tree Search** for **Naughts and Crosses (Tic-Tac-Toe)**
  - The MCTS algorithm
  - Exercise 1: Playout policy and simulate
  - Exercise 2: the "expand" step
  - Exercise 3: the "backpropogate" step
  - Exercise 4: The "tree policy" and the UCB
  - Exercise 5: Putting all together in the search function
  - Exercise 6 (bonus): **Use another rollout policy**
  - Exercise 7 (bonus): **Progressive widening** for large spaces
- Bibliography


### Lab session 4: INF639 Lab4: Inverse Reinforcement Learning

- Open in Google Colab (short link): http://www.jdhp.org/inf639/lab4
- Open in Google Colab: https://colab.research.google.com/github/jeremiedecock/polytechnique-inf639-2024-students/blob/master/lab4_irl.ipynb
- Open in MyBinder: https://mybinder.org/v2/gh/jeremiedecock/polytechnique-inf639-2024-students/master?filepath=lab4_irl.ipynb
- Open in NbViewer: https://nbviewer.jupyter.org/github/jeremiedecock/polytechnique-inf639-2024-students/blob/master/lab4_irl.ipynb
- Download the notebook file: https://github.com/jeremiedecock/polytechnique-inf639-2024-students/raw/master/lab4_irl.ipynb

#### Description

The purpose of this lab is to introduce some classic algorithms of Imitation learning and Inverse Reinforcement Learning. We will see how they work, their caveats and benefits.

#### Overview

- Define utility functions
- Part 1: **Behavioral Cloning**
  - Cartpole
  - Lunar Lander
  - Lunar Lander stochastic
- Part 2: **DAgger**
- Part 3: **MaxEnt IRL** (bonus)
- Further readings
  - **GAIL**
  - **Guided Cost Learning**
