# RL Fitness Recommendation System

This repository contains a single Jupyter Notebook implementing a **Q-learning Reinforcement Learning model** for generating personalized fitness recommendations. The notebook trains an RL agent to choose suitable actions for users based on their fitness characteristics.

---

## 📄 Project Contents
This project includes:

- **RL_Fitness_Recommender.ipynb**  
  The complete notebook containing:
  - State encoding  
  - Reward function  
  - Q-learning implementation  
  - Training loop  
  - Plotting reward history  
  - Recommendation generation  
  - Saving/loading Q-tables  
  - Optional CLI-style user interaction  

There are no additional files or modules used outside the notebook.

---

## 🔍 What the Notebook Does

### 1️⃣ **State Representation**
Each user is described by:
- Fitness level  
- Adherence level  
- Fitness goal  

These values are encoded into a unique state index.

### 2️⃣ **Action Space**
A predefined list of fitness-related actions (workouts, routines, habits) the agent can choose from.

### 3️⃣ **Reward Function**
A custom reward function evaluates how suitable an action is for the given user profile based on:
- Goal relevance  
- Fitness-level compatibility  
- Adherence match  

### 4️⃣ **Q-Learning Algorithm**
The notebook includes:
- Initialization of Q-table  
- Epsilon-greedy action selection  
- Q-value update  
- Training over many episodes  

### 5️⃣ **Model Outputs**
After training, the notebook can:
- Recommend **top-K actions** for any user  
- Plot total rewards across episodes  
- Save and load the learned Q-table  

---

## ▶️ How to Run the Notebook

### Install dependencies:
