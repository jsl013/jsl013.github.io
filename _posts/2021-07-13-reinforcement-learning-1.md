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
- S: set of states
- A: set of actions
- P_{ss'}^a: (s_t, a_t) -> s_{t+1}: possibility of being s_{t+1} when action a_t is done at the state of s_t
- R_t: reward when action a_t is done at the state of s_t (reward at s_{t+1})
- gamma: discount factor
- G_t: return, R_t + gamma * R_t+1 + gamma^2 * R_t+2 + ...
- Value function: V(s) = E[G_t|s_t], expected return of current state
- Policy: pi(a|s) = P[a_t=a|s_t=s], prob. of doing certain action at certain state
- Action-value function: Q(s,a) = E[G_t|s_t, a_t], expected return of current action at current state

### Bellman Equation
- two equations representing V(s_t)
  - V(s_t) = E_a[Q(s_t,a_t)|s_t] = sigma_a(Q(s_t,a)*P(a|s_t))
  - ** V(s_t) = E[G_t|s_t] = E[R_t + gamma * V(s_t+1)|s_t]
- two equations representing Q(s_t,a_t)

### Optimal Policy

## Mante Carlo

## Temporal Difference

### SARSA

### Q-learning

## DQN

### Double DQN
