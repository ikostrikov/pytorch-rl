# pytorch-rl

A list of references to my reimplementations of RL algorithms:

* Asynchronous Methods for Deep Reinforcement Learning (A3C) ([arxiv](https://arxiv.org/abs/1602.01783), [my code](https://github.com/ikostrikov/pytorch-a3c))

* Advantage Actor Critic (A2C) ([my code](https://github.com/ikostrikov/pytorch-a2c-ppo-acktr))

* Proximal Policy Optimization Algorithms (PPO) ([arxiv](https://arxiv.org/abs/1707.06347), [my code](https://github.com/ikostrikov/pytorch-a2c-ppo-acktr))

* Scalable trust-region method for deep reinforcement learning using Kronecker-factored approximation (ACKTR)([arxiv](https://arxiv.org/abs/1707.06347), [my code](https://github.com/ikostrikov/pytorch-a2c-ppo-acktr))

* Trust Region Policy Optimization (TRPO) ([arxiv](https://arxiv.org/pdf/1502.05477.pdf), [my code](https://github.com/ikostrikov/pytorch-trpo))

* Continuous Deep Q-Learning with Model-based Acceleration (NAF) ([arxiv](https://arxiv.org/abs/1603.00748), [my code](https://github.com/ikostrikov/pytorch-naf))

# TODO (volunteers are welcome)

* Move TRPO to a2c-ppo-acktr code, implement it as a hessian free optimizer (as ACKTR is implemented as KFAC)
