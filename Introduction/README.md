## Introduction

### Learning Goals

- Understand the Reinforcement Learning problem and how it differs from Supervised Learning


### Summary

- Reinforcement Learning (RL) is concerned with goal-directed learning and decision-making. RL selects actions to maximize future rewards. 
- In RL an agent learns from experiences it gains by interacting with the environment. In Supervised Learning we cannot affect the environment.
- In RL rewards are often delayed in time and the agent tries to maximize a long-term goal. For example, one may need to make seemingly suboptimal moves to reach a winning position in a game.
- An agent interacts with the environment via states, actions and rewards.
- **Fully observable environment** means that agent directly observes environment state (O<sub>t</sub> = S<sup>a</sup><sub>t</sub> = S<sup>e</sup><sub>t</sub>). This is a Markov decision process (MDP). On the other hand, partial observability means that the agent indirectly observes environment. (e.g., A robot with camera vision isn't told its abslute location.) Now S<sup>a</sup><sub>t</sub> != S<sup>e</sup><sub>t</sub>. This is a **partially observable Markov decision process** (POMDP). 


### Lectures & Readings

**Required:**

- [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/bookdraft2018jan1.pdf) - Chapter 1: The Reinforcement Learning Problem
- David Silver's RL Course Lecture 1 - Introduction to Reinforcement Learning ([video](https://www.youtube.com/watch?v=2pWv7GOvuf0), [slides](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/intro_RL.pdf))
- [OpenAI Gym Tutorial](https://gym.openai.com/docs)

**Optional:**

N/A


### Exercises

- [Work through the OpenAI Gym Tutorial](https://gym.openai.com/docs)
