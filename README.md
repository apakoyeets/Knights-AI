🎮 Just taught an AI how to play the game of **Nim** — from scratch! 🤖

Over the past week, I built a reinforcement learning model that uses **Q-learning** to master Nim — a classic strategy game where players remove objects from piles, and the one forced to take the last object loses.

Here’s how it works:

🧠 The AI:
- Represents the game state as pile configurations (like `[1, 3, 5, 7]`)
- Chooses actions using an **epsilon-greedy policy** (explore vs. exploit)
- Updates its strategy using the **Q-learning** algorithm:
  
  `Q(s, a) ← Q(s, a) + α * (reward + max Q(s’, a’) − Q(s, a))`

📈 After training on 10,000 games, the AI becomes nearly unbeatable!

💡 What I learned:
- How to implement Q-learning from scratch
- How to model turn-based strategy games with reinforcement learning
- How to tune hyperparameters like learning rate, exploration rate, etc.

📂 Tech stack: Python, NumPy, object-oriented programming

🕹️ Want to try beating the AI? Check out the project here:
🔗 [GitHub repo link]

#AI #ReinforcementLearning #Qlearning #MachineLearning #Python #OpenSource #GameAI
