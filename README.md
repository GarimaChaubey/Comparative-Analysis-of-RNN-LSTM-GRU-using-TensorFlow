# 🤖 Comparative Analysis of RNN, LSTM, and GRU using TensorFlow

This project provides a **beginner-friendly, side-by-side comparison** of three popular recurrent neural network architectures:  
**Simple RNN**, **LSTM**, and **GRU** for sequence prediction tasks.

The models are implemented using **TensorFlow/Keras**, and compared on the basis of training time, accuracy, convergence, and stability over longer sequences.

---

## 📁 Files Included

- `RNN_Assignment.ipynb` — Full implementation of RNN, LSTM, and GRU models
- `README.md` — Project documentation and insights

---

## 🎯 Objective

To understand and compare the performance of different types of recurrent neural networks:

- ✅ How quickly they train
- 📉 How fast they converge
- 🎯 How accurate they are on unseen data
- 🔁 How well they handle long sequences

---

## 🧠 Dataset

This project uses a **simple sequence prediction dataset** (you can replace it with IMDB, weather data, or phoneme datasets).

### Preprocessing steps include:
- Tokenization of sequences
- Padding to handle varying lengths
- One-hot encoding for labels
- Train-test split

---

## 🏗 Model Architectures

Each model contains:
- 📥 Input Layer (Embedding)
- 🔁 One Recurrent Layer:
  - RNN / LSTM / GRU
- 🎯 Dense Output Layer with `sigmoid` activation

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/Comparative-Analysis-of-RNN-LSTM-GRU.git
cd Comparative-Analysis-of-RNN-LSTM-GRU
