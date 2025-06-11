# 🐤 Flappy Bird AI using NEAT

This is an AI-powered version of the classic Flappy Bird game built using **Python**, **Pygame**, and the **NEAT (NeuroEvolution of Augmenting Topologies)** algorithm.

The AI learns how to play Flappy Bird entirely by itself — it starts off with no knowledge and gradually improves over generations!

---

## 🚀 How It Works

- Multiple birds are created, each with a tiny neural network brain.
- Birds try to fly through the pipes. The longer they survive, the better their score.
- NEAT uses genetic evolution to improve bird brains across generations.
- After each generation, the best-performing birds are bred into the next generation.

---

## 🧠 Technologies Used

- Python 3
- [Pygame](https://www.pygame.org/) – Game visuals and physics
- [NEAT-Python](https://neat-python.readthedocs.io/) – Neuroevolution algorithm

---

## 📁 Project Structure

flappy-bird-ai/

├── assets/                  # Game images (bird, pipe, base, bg)

├── main.py                  # Game logic + NEAT integration

├── config-feedforward.txt   # NEAT configuration

├── requirements.txt         # Python dependencies

├── README.md                # Project overview

---
