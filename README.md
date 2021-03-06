# paac-pytorch
We used the repo of the below reference just to see that it works for ourselves. And to verify the scores claimed by the author below. Full credit to the original author. Note(We kept the readme file as it is below)

    @misc{pytorchaaac,
      author = {Ping-Yao Chang},
      title = {Efficient Parallel Methods for Deep Reinforcement Learning},
      year = {2018},
      publisher = {GitHub},
      journal = {GitHub repository},
      howpublished = {\url{https://github.com/pianomania/paac-pytorch}},
    }
    
This is a PyTorch implementation of PAAC from ["Efficient Parallel Methods for Deep Reinforcement Learning"](https://arxiv.org/abs/1705.04862)

![BeamReider](./assets/BeamRider.gif)  ![Breakout](./assets/Breakout.gif)  ![Pong](./assets/Pong.gif)  ![Qbert](./assets/Qbert.gif)

# Environments
- Ubuntu 16.04
- python 3.5.2
- PyTorch 0.2.0
- NumPy 1.13.1
- gym 0.9.2
- matplotlib

# Usage
- You can train the agent by:

```
python main.py --env-name BreakoutDeterministic-v4 --num-workers 4
```

- You can play the game by:
```
python play.py --env-name BreakoutDeterministic-v4
```

# Results
<p float="first 4 envs">
  <img src="./assets/BeamRider.png" width="210" heigh="150">
  <img src="./assets/Breakout.png" width="210" heigh="150">
  <img src="./assets/Pong.png" width="210" heigh="150">
  <img src="./assets/Qbert.png" width="210" heigh="150">
</p>

# Notes



# References

- [origin paper's open source](https://github.com/Alfredvc/paac)
- [openai's universe-starter-agent](https://github.com/openai/universe-starter-agent)
- [pytorch-a3c](https://github.com/ikostrikov/pytorch-a3c)

This test was done by Sulaiman Aljanahi and Naif Alkhunaizi
