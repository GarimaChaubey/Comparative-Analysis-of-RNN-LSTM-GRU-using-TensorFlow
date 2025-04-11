# Comparative Analysis of RNN, LSTM, and GRU

This project presents a comparative analysis of three types of Recurrent Neural Networks (RNNs): **Vanilla RNN**, **Long Short-Term Memory (LSTM)**, and **Gated Recurrent Unit (GRU)**. The analysis is based on a deep learning experiment implemented in Python using TensorFlow and Keras, focusing on performance, accuracy, and training behavior.

## 📊 Project Overview

Recurrent Neural Networks (RNNs) are a class of neural networks effective for sequential data, especially in Natural Language Processing and Time Series Forecasting. While traditional RNNs suffer from vanishing gradient issues, LSTM and GRU address this with their gating mechanisms.

This notebook explores and compares their behavior on a sample dataset, evaluating model accuracy and loss over time.

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn

## 🧠 Models Compared

| Model     | Description |
|-----------|-------------|
| **RNN**   | Basic recurrent unit, suffers from vanishing gradients. |
| **LSTM**  | Adds memory cells and gates to control information flow. |
| **GRU**   | Similar to LSTM but with fewer gates, faster to train. |

## 📈 Visual Results

The models were trained on the same dataset and compared based on:

- **Training Accuracy**
- **Validation Accuracy**
- **Training Loss**
- **Validation Loss**

### 🔍 Accuracy and Loss Graphs

Below are the training and validation curves:

> *(Add these screenshots in the GitHub repo as PNG and use the markdown below to embed them)*

```markdown
![RNN Accuracy](images/rnn_accuracy.png)
![LSTM Accuracy](images/lstm_accuracy.png)
![GRU Accuracy](images/gru_accuracy.png)

![RNN Loss](images/rnn_loss.png)
![LSTM Loss](images/lstm_loss.png)
![GRU Loss](images/gru_loss.png)

