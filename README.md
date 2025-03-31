# Stock Price Prediction using GNN and Transformer Architectures

This research project explores the application of advanced deep learning models, specifically Graph Neural Networks (GNNs), Transformers, and hybrid models, to predict stock prices. The goal is to capture both temporal patterns and inter-stock relationships by combining sequential modeling and graph-based learning.

## 📂 Project Structure

| File Name               | Description                                               |
|------------------------|-----------------------------------------------------------|
| `Transformer_only.ipynb` | Implements a pure Transformer-based model for time-series forecasting. |
| `GAT_only.ipynb`         | Uses Graph Attention Networks (GAT) to model stock relationships. |
| `hybrid.ipynb`           | Combines GNN and Transformer to leverage both spatial and temporal dependencies. |
| `LSTM_GCN.ipynb`         | A baseline hybrid model using LSTM for sequence modeling and GCN for relational data. |

## 🔍 Research Objective

To improve stock price prediction accuracy by integrating:

- **GNNs** to model relational information among stocks (e.g., sector connections, correlations).
- **Transformers** for capturing long-range temporal dependencies in stock time series.
- **Hybrid Architectures** to combine the strengths of both.

## 📊 Dataset

> 📌 **Note:** You must provide the stock data for these notebooks to function. The notebooks expect historical price data formatted as follows:

```text
Date | Stock_ID | Open | High | Low | Close | Volume
