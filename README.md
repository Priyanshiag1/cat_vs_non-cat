# 🧠 Cat vs Non-Cat Image Classifier (Built from Scratch)

This project implements and compares **Logistic Regression**, a **2-layer Neural Network**, and a **Deep L-layer Neural Network** from scratch using only **NumPy** — no TensorFlow, no Keras.

## 🔍 Objective

To classify 64x64 RGB images as either a **cat** or **non-cat**, while learning how neural networks work under the hood — from forward/backward propagation to cost computation and weight updates.

---

## 🚀 Models Implemented

| Model                  | Train Accuracy | Test Accuracy |
|-----------------------|----------------|---------------|
| Logistic Regression   | ~99%           | 70%           |
| 2-Layer Neural Net    | 100%           | 72%           |
| L-Layer Deep Network  | 100%           | 80%           |

---

## 🧱 Architecture

- **Logistic Regression**: Linear classification  
- **2-Layer NN**: 1 hidden layer with ReLU → sigmoid output  
- **L-Layer NN**: [12288, 20, 7, 5, 1] with He initialization

---

## 📈 Learning Curves

Cost plotted over iterations for each model to visualize training performance.

---
