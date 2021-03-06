# Deep-Reinforcement-Learning
Deep Reinforcement Learning Algorithms and Code - Explanations of research papers and their implementations (*All algorithm implementations are done in Pytorch*)

1. `REINFORCE`: [Vanilla Policy Gradient](https://spinningup.openai.com/en/latest/algorithms/vpg.html)
2. `DQN`: [Deep Q-Learning, Mnih et al, 2013](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)
3. `A3C/A2C`: [Asynchronous methods for Deep RL,Mnih et al, 2016  ](https://arxiv.org/abs/1602.01783)
4. `PPO`: [Proximal Policy Optimization,Schulman et al, 2017](https://arxiv.org/abs/1707.06347)
5. `DDPG`: [Deep Deterministic Policy Gradient,Lillicrap et al, 2015](https://arxiv.org/abs/1509.02971)

(Folder `General`: General tips on Deep reinforcement Learning)


**From Open AI ["Spinning Up as a Deep RL Researcher (or Practitioner)"](https://spinningup.openai.com/en/latest/spinningup/spinningup.html).**: How to start in Deep RL assuming you've got a solid background in Mathematics([1](http://wiki.fast.ai/index.php/Calculus_for_Deep_Learning),[2](https://www.quantstart.com/articles/matrix-algebra-linear-algebra-for-deep-learning-part-2)), a general knowledge of Deep Learning and are familiar with at least one Deep Learning Library (Like [PyTorch](https://pytorch.org/)  or [TensorFlow](https://www.tensorflow.org/)):

![OPEN AI](https://spinningup.openai.com/en/latest/_static/spinning-up-logo2.png)

>**Which algorithms?** *You should probably start with vanilla policy gradient (also called REINFORCE), DQN, A2C (the synchronous version of A3C), PPO (the variant with the clipped objective), and DDPG, approximately in that order. The simplest versions of all of these can be written in just a few hundred lines of code (ballpark 250-300), and some of them even less (for example, a no-frills version of VPG can be written in about 80 lines). Write single-threaded code before you try writing parallelized versions of these algorithms. (Do try to parallelize at least one.)*



Further Algorithms to study (Suggested at Open AI Hackathon):

* `TRPO`: [Schulman et al, 2015](https://arxiv.org/abs/1502.05477)
* `C51`: [Bellemare et al, 2017](https://arxiv.org/abs/1707.06887)
* `QR-DQN`: [Dabney et al, 2017](https://arxiv.org/abs/1710.10044)
* `SVG`: [Heess et al, 2015](https://arxiv.org/abs/1510.09142)
* `I2A`: [Weber et al, 2017](https://arxiv.org/abs/1707.06203)
* `MBMF`: [Nagabandi et al, 2017](https://sites.google.com/view/mbmf)
* `AlphaZero`: [Silver et al, 2017](https://arxiv.org/abs/1712.01815)

## How to study the RL Algorithms

Start with the most simple algorithm (REINFORCE). First read the paper carefully. Then read the implementation and try to rewrite the code from scratch. Take care not to overfit on implementation details or on paper details. 

## Notes
My framework of choice is [Pytorch](https://pytorch.org/) which is covered by a free licence ([ Modified BSD license](https://en.wikipedia.org/wiki/Modified_BSD_License)).

The implementations were taken from various sources with a focus on simplicity and ease of understanding (including Udacity's [repository for the Deep Reinforcement Learning Nanodegree](https://github.com/udacity/deep-reinforcement-learning)). There are numerous implementations available including very good modular ones but my purpose is mastering the RL theory and algorithms. Creating modular code is a secondary goal.

There are minor corrections on the implementations with the aim of making them easier to understand and consistent.

## Sources
* [Udacity](https://github.com/udacity/deep-reinforcement-learning)
* [OpenAI](https://spinningup.openai.com/en/latest/spinningup/spinningup.html)
* [ShangtongZhang/DeepRL](https://github.com/ShangtongZhang/DeepRL)
* [higgsfield/RL-Adventure-2](https://github.com/higgsfield/RL-Adventure-2)
* [nikhilbarhate99/PPO-PyTorch](https://github.com/nikhilbarhate99/PPO-PyTorch)
