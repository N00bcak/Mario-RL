# Mario-RL
## Summary
This README documents my attempts at learning Double Deep Q Networks with the OpenAI Gymnasium Mario environment. (Extending upon [this PyTorch tutorial by Feng et al.](https://pytorch.org/tutorials/intermediate/mario_rl_tutorial.html))

## Significant Differences
- The observations are **zero-centred** to take advantage of Kaiming initialization.
- Mario's Policy network has increased complexity (extra `nn.Linear` layer) and `nn.Dropout` which should help him rely less on specific memories.
- Batch sizes dramatically increased to improve gradient quality.

## Any results yet?
Unfortunately no, because the training requires a lot of time :(. But I'm working on it!

