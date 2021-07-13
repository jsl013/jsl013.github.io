---
layout: post
title:  "Reinforcement Learning"
date:   2021-05-17 10:53:36
categories: RL 
---
## Goal of Reinforcement Learning
- Find the policy that will make maximum expected return
  - Trial and error
  - Delayed reward : discount factor

## Markov Decision Process (MDP)
- main property: `memoryless` = only current state and action  

### Glossary of terms
- $S$: set of states
- $A$: set of actions
- $P_{ss'}^a: (s_t, a_t) -> s_{t+1}$: possibility of being $s_{t+1}$ when action $a_t$ is done at the state of $s_t$
- $R_t$: reward when action $a_t$ is done at the state of $s_t$ (reward at $s_{t+1}$)
- $G_t$: return 
