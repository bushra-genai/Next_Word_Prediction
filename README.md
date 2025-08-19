# 🧠 Next Word Prediction using GRU

This repository contains a **Next Word Prediction** project implemented using a custom **GRU (Gated Recurrent Unit)** model in Python.  
The project demonstrates how GRUs can learn sequential dependencies in natural language and predict the next word from input text.

---

## 📌 Features
- Custom GRU cell implementation (forward + backward pass)
- Training on toy sentences for demonstration
- Predicts the **next word** given an input sequence
- Visualizes **GRU hidden state activations**
- Written in pure Python + NumPy (no high-level deep learning libraries)

---

## 📂 Project Structure

gru-next-word-prediction/
│── next_word_gru.ipynb # Jupyter Notebook (training + prediction + visualization)
│── requirements.txt # Dependencies
│── README.md # Project documentation

Results

Trains a GRU model on simple toy sentences.
Predicts the next word given a sequence.
Plots hidden state activations across timesteps.
