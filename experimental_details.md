## Experimental Details

### Sequential Recommenders Experiments
For the sequential recommendation experiments, we used the implementations provided by the **RecBole** library. All tested models in RecBole are implemented in **PyTorch**, ensuring consistency across experiments and avoiding confounding factors caused by differences in implementation frameworks.

### Reinforcement Learning Agents on Atari
We conducted reinforcement learning experiments using several Atari 2600 environments from the **Arcade Learning Environment (ALE)**. The environments used were:

- *SpaceInvaders*  
- *Centipede*  
- *Pong*  
- *Atlantis*  
- *Boxing*  
- *Alien*  
- *Asteroids*  
- *Adventure*  
- *Enduro*  
- *VideoPinball*  
- *Tennis*

All environments correspond to the **NoFrameskip-v4** versions to maintain consistency with standard RL benchmarks.

For the agents, we employed the implementations of **DQN**, **PPO**, and **A2C** from the **RL Baselines3 Zoo**, a training framework built on top of **Stable-Baselines3**.
