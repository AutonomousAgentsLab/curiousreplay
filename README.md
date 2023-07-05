# Curious Replay for Model-based Adaptation
Implementations of [Curious Replay](https://arxiv.org/abs/2306.15934), a method for prioritizing experience replay that is tailored to model-based reinforcement learning agents.

Experiences are prioritized based on how interesting they are, as measured by a curiosity signal. 
In combination with DreamerV3, this method achieves a new state-of-the-art on the [Crafter](https://github.com/danijar/crafter) benchmark.

![fig_overview-01_small](https://user-images.githubusercontent.com/903830/236350331-b7aacb2c-671a-4137-90c2-b4dd210ebf30.png)

If you find this code useful, please reference in your paper:

```
@article{kauvar2023curious,
  title={Curious Replay for Model-based Adaptation},
  author={Kauvar, Isaac and Doyle, Chris and Zhou, Linqi and Haber, Nick},
  journal={International Conference on Machine Learning},
  year={2023}
}
```

Here we provide links to implementations with different model-based agents. 

## DreamerV3
[github.com/AutonomousAgentsLab/cr-dv3][dv3]

## DreamerV2
[github.com/AutonomousAgentsLab/cr-dv2][dv2]


[dv3]: https://github.com/AutonomousAgentsLab/cr-dv3
[dv2]: https://github.com/AutonomousAgentsLab/cr-dv2

[paper]: 
[website]: 
[tweet]: 
[example]: 
