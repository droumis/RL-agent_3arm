# RL-w

Reinforcement Learning model of a W-shaped spatial alternation maze that rats can learn over a couple hours

![Wtrack image](https://github.com/droumis/RL-w/blob/cf4ff8153b00ecbaefb943195e16401ca58aadcf/Wtrack.png)

- observation space is non-repeating two-well combinations of the 3 wells = 6 states
- action space is the 3 wells
- reward table is the observation space x action space with values reinforcing alternation rule

Approaches:
- Q-Learning with e-greedy
- TD(0) with e-greedy
- TD(lambda) with e-greedy
- TD(lambda) with a memory unit
