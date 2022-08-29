# Example VPG implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_vpg_example/blob/master/vpg_example.ipynb) of vanilla policy gradient (VPG) with ReLAx.

VPG actor was trained on LunarLander-v2 Gym environment for 4m env-steps. 

The graph of average return vs training step is shown below (`batch_size=40000`):

![vpg_training](https://github.com/nslyubaykin/relax_vpg_example/blob/master/vpg_training.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187155163-679e0191-e5e8-4a7c-8e48-0cdc57d1a19e.mp4
