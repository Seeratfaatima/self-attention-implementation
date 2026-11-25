# Manual Self-Attention Implementation

## Overview
This project demonstrates a manual implementation of the Self-Attention mechanism using PyTorch.

The objective is to understand how Query, Key, and Value vectors are generated and how attention scores are calculated to produce context vectors.

## Concepts Implemented
- Input tensor creation
- Query, Key, and Value projections
- Dot-product attention scores
- Scaled dot-product attention
- Softmax normalization
- Context vector calculation
- Causal masking
- Attention weight validation
- Attention visualization using Matplotlib and Seaborn

## Technologies Used
- Python
- PyTorch
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
```text
self-attention-implementation/
├── self_attention.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Clone this repository.
2. Install the required dependencies.
3. Open the notebook using Jupyter Notebook or Google Colab.
4. Run the cells sequentially.

## Learning Objective
To understand and implement the mathematical operations behind Self-Attention without using built-in Transformer or Multihead Attention implementations.