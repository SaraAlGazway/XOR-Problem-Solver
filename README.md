# 🧠 XOR Problem Solver with PyTorch

> This notebook implements a simple neural network to solve the classic XOR problem using PyTorch.

## 🎯 What this notebook covers:

- Defining the XOR dataset
- Building a Simple Neural Network (Hidden Layer + ReLU + Sigmoid)
- Training the model for 1000 epochs
- Printing weights before and after training
- Evaluating final predictions

## 📊 Expected Results:

- ✅ 100% accuracy on XOR after training
- 21 parameters in total

## 🏗️ SimpleModel Architecture

| Layer | Type | Input | Output |
|-------|------|-------|--------|
| 1 | Linear | 2 | 4 |
| 2 | ReLU | 4 | 4 |
| 3 | Linear | 4 | 1 |
| 4 | Sigmoid | 1 | 1 |

**Total Parameters:** 21

## 🚀 How to Run

1. Open `xor-problem-solver-with-pytorch.ipynb`
2. Run all cells
3. Check the final predictions

## 📦 Requirements

```bash
pip install torch
