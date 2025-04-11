# Comparative Analysis of RNN, LSTM, and GRU

This project presents a comparative analysis of three types of Recurrent Neural Networks (RNNs): **Vanilla RNN**, **Long Short-Term Memory (LSTM)**, and **Gated Recurrent Unit (GRU)**. The analysis is based on a deep learning experiment implemented in Python using TensorFlow and Keras, focusing on performance, accuracy, and training behavior.

## Project Overview

Recurrent Neural Networks (RNNs) are a class of neural networks effective for sequential data, especially in Natural Language Processing and Time Series Forecasting. While traditional RNNs suffer from vanishing gradient issues, LSTM and GRU address this with their gating mechanisms.

<p align="center">
  <img src="![image](https://github.com/user-attachments/assets/48b5c58d-f560-49cf-ad2c-6f0d6ff2a874)
" width="400"/>
</p>

This notebook explores and compares their behavior on a sample dataset, evaluating model accuracy and loss over time.

## Models Compared

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

### Accuracy and Loss Graphs

Below are the training and validation curves:

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/9f258f56-c2b3-45db-b7da-e31708bdce13" width="300"/><br/>
      <sub><b>Before (Early Epoch)</b></sub>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/063af3b5-6ddf-4440-b645-f2885581db6c" width="300"/><br/>
      <sub><b>After (Later Epoch)</b></sub>
    </td>
  </tr>
</table>

# Observation

The graph shows that GRU and LSTM consistently outperform the basic RNN in terms of validation accuracy. While RNN begins with lower accuracy and fluctuates more, LSTM and GRU maintain higher and more stable accuracy across epochs. This demonstrates the superiority of LSTM and GRU in capturing long-term dependencies in sequential data such as text.

<p align="center">
  <img src="https://github.com/user-attachments/assets/45a1692d-7705-48c8-baf0-af399e9dfa09" width="400"/>
</p>

After training and evaluating RNN, LSTM, and GRU models on a sequence prediction task, we observed the following:

**Accuracy:**

- LSTM and GRU achieved higher and more stable accuracy than RNN.

- RNN showed decent performance initially but struggled to retain accuracy over longer sequences due to vanishing gradient issues.

**Convergence Speed:**

- LSTM and GRU converged faster and more smoothly compared to RNN.

- GRU showed the fastest convergence while maintaining good accuracy, owing to its simpler structure.

**Training Time:**

- RNN trained the fastest due to its minimal structure.

- LSTM had the longest training time because of its complex gates and memory cells.

- GRU had balanced training time, faster than LSTM but slower than RNN.

**Stability on Long Sequences:**

- RNN performance degraded on longer sequences.

- Both LSTM and GRU remained stable and retained important context across long inputs.

📘 **View the Notebook**: [RNN LSTM GRU.ipynb](https://github.com/GarimaChaubey/Comparative-Analysis-of-RNN-LSTM-GRU-using-TensorFlow/blob/main/RNN_Assignment.ipynb)

## Refrences
- https://www.mdpi.com/2079-9292/14/4/707#:~:text=The%20proposed%20LSTM%20model%20demonstrated,with%20an%20RMSE%20of%2011.79.
