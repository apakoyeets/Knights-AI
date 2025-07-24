# 🧠 Q-Learning AI for Knights Game

This project implements a reinforcement learning agent that learns to play **Knights**, a two-player strategy game played on a 4×4 chessboard using knight pieces. The AI is trained using **Q-learning** and learns to optimize its moves by playing thousands of self-play games.

---

## ♟️ Game Overview: Knights

- Two players take turns moving knight pieces on a 4×4 board.
- Each knight moves using traditional chess knight rules (L-shaped jumps).
- A square can only be visited once — it is removed after being stepped on.
- A player loses when they can no longer make a legal move.

The objective: **Trap the opponent** so they have no available moves.

---

## 🧠 AI Overview

The AI uses a **Q-learning algorithm** to learn optimal moves by reinforcement:

- **States**: Encoded board positions and whose turn it is  
- **Actions**: Legal knight moves from the current position  
- **Rewards**:  
  - +1 for a win  
  - -1 for a loss  
  - 0 for intermediate moves  
- **Policy**: Epsilon-greedy (explores random moves with decaying epsilon)

---

## 🔧 Features

- Full game engine for the Knights game  
- Q-table for state-action learning  
- Epsilon decay and learning rate tuning  
- Self-play training for thousands of games  
- Command-line interface to play against the trained bot

---
