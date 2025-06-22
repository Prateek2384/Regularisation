# 🔒 Regularization in Neural Networks - Sample Demo

This repository contains a sample Jupyter Notebook demonstrating the **use of regularization techniques** (like L1, L2) in neural networks to prevent overfitting on a classification dataset.

---

## 📘 What is Regularization?

Regularization helps improve a model's **generalization ability** by penalizing large weights. This is especially useful in preventing **overfitting** on training data.

Common techniques:
- **L1 Regularization** (Lasso): Adds a penalty equal to the absolute value of weights
- **L2 Regularization** (Ridge): Adds a penalty equal to the square of weights
- **Dropout** (optional): Randomly drops neurons during training to force redundancy

---

## 📁 Files

- `regularization_demo.ipynb` – Jupyter notebook that:
  - Builds a simple neural network on a synthetic dataset
  - Applies L2 regularization using `kernel_regularizer`
  - Visualizes model performance with and without regularization

---

## 🛠️ Technologies Used

- Python 3
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn (for generating data)

