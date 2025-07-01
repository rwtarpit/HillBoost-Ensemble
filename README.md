# HillBoost-Ensemble

A GPU-powered ensemble learning algorithm using **hill climbing optimization** to combine models for optimal predictive performance.

> Built for speed. Tuned for performance. Inspired by chaos.

---

## 🚀 What is Hill Boost?

**Hill Boost Ensemble** finds the best-performing model on a dataset, and then **iteratively adds other models** only if they improve the overall performance. Think of it as smart ensembling with a ruthless edge.

Currently supports:

- ✅ XGBoost
- ✅ LightGBM
- ✅ CatBoost
- ✅ Keras-based MLP

> **Note:** GPU is strictly required. This repo is born and raised on the Kaggle GPU runtime.

---

## 🧠 How It Works

1. Train all candidate models on the same dataset
2. Evaluate performance using a custom metric (e.g., AUC, F1, accuracy)
3. Start with the best single model
4. Iteratively test all other models — include only if ensemble improves
5. Final prediction is the weighted sum of selected models

---

## 📦 Setup

Clone the repo:

```bash
git clone https://github.com/rwtarpit/HillBoost-Ensemble.git
cd HillBoost-Ensemble


