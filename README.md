# Elegant FinRL

  This project borrows ideas from [ElegantRL](https://github.com/Yonv1943/ElegantRL) and [FinRL](https://github.com/AI4Finance-LLC/FinRL-Library)
  
  We maintain an **elegant (lightweight, efficient and stable)** FinRL lib, allowing researchers and quant traders to develop algorithimc strategies easily.
  
  + **Lightweight**: The core codes have less than 800 code lines, using PyTorch, OpenAI Gym, and NumPy.
  
  + **Efficient**: Its performance is comparable with Ray RLlib.
  
  + **Stable**: It is stable as Stable Baseline 3.
  

# Design Principles

  + **Be Pythonic**: Quant traders, data scientists and machine learning engineers are familiar with the open source Python ecosystem: its programming model, and its tools, e.g., NumPy.
  
  + **Put researchers and algorithmic traders first**: Based on PyThorch, we support researchers to mannually control the execution of the codes, empowering them to improve the performance over automatical libraries.
  
  + **Lean development of algorithimc strategies**: It is better to have an elegant (may be slightly incomplete) solution than a comprehensive but complex and hard to follow design, e.g., RLlib. It allows fast code iteration.
  
  
# DRL Algorithms

  + **DDPG --> SAC, A2C, PPO(GAE), TD3, InterAC, InterSAC**:
  
  + **DQN --> DoubleDQN, DuelingDQN, D3QN, GAE**
  
# Code Structure

