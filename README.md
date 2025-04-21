# 📰 Personalized News Recommendation System

A **Reinforcement Learning**-based interactive news recommendation system built with **Policy Gradients and DQN**. The app uses **click behavior** to learn and recommend news articles using a Deep Q-Network (DQN), and is deployed via **Gradio** for real-time interaction.

---

## 🚀 Features

- ✅ Personalized recommendations based on user click patterns  
- 🧠 Deep Q-Network (DQN) to learn user preferences  
- 📊 Dynamic state updates with experience replay  
- 🎛️ Interactive UI using [Gradio](https://gradio.app/)  
- 💻 GPU-accelerated training (TensorFlow)  
- 📈 Click-based reward system for improved recommendations  

---

## 📦 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **Gradio**
- **Pandas / NumPy**

---

## 🧠 How it Works

1. The app starts by showing 5 news recommendations.
2. When a user **clicks** on an article, a reward is assigned.
3. This action is recorded in the **Replay Buffer**.
4. The **DQN model** is trained on these actions to improve future recommendations.
5. The next batch of top articles is displayed based on updated Q-values.

---

## 🖥️ Run Locally

### 1. Clone the repository:

```bash
git clone https://github.com/your-username/news-recommendation-rl.git
cd news-recommendation-rl
