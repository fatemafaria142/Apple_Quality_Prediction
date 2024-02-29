# Apple Quality Prediction

Predicting the quality of apples using Long Short-Term Memory (LSTM), Bidirectional LSTM (Bi-LSTM), Gated Recurrent Unit (GRU), and Bidirectional GRU (Bi-GRU).

## Overview

This project focuses on building and comparing different recurrent neural network (RNN) architectures to predict the quality of apples based on various features such as Size, Weight, Sweetness, Crunchiness, Juiciness, Ripeness, and Acidity. The models used include LSTM, Bi-LSTM, GRU, and Bi-GRU.

## Table of Contents

- [Requirements](#requirements)
- [Results](#results)

## Requirements

- Python version: 3.10.12 
- TensorFlow version: 2.15.0
- Matplotlib version: 3.7.1
- Seaborn version: 0.13.1
- NumPy version: 1.25.2
- Pandas version: 1.5.3
- scikit-learn version: 1.2.2

## Results

| Model                              | Accuracy | Precision | Recall | F1 Score | Log Loss |
| ---------------------------------- | -------- | --------- | ------ | -------- | ---------|
| Bi-GRU                             | 0.7978   | 0.7548    | 0.8828 | 0.8138   | 0.4327   |
| Bi-LSTM                            | 0.7853   | 0.7573    | 0.8404 | 0.7967   | 0.4367   |
| GRU                                | 0.7740   | 0.7723    | 0.7781 | 0.7752   | 0.4615   |
| LSTM                               | 0.8177   | 0.7815    | 0.8828 | 0.8290   | 0.3630   |






