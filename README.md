# Project: Neural Operator for the Heat Equation

### Objective: With initial conditions and a material as an input, train a neural operator to predict the distribution of heat throughout a rod at any time, with this equation:
### $\frac{\partial u}{\partial t} = \alpha \frac{\partial^2 u}{\partial x^2} $

### Then use active learning with selective sampling (based on ensemble disagreement) to fine tune, and compare to if training was randomly sampled.
