# Multi-Class Classification with PyTorch

This repository demonstrates **multi-class classification** on a synthetic dataset generated with `sklearn.datasets.make_blobs`.  
The project trains a PyTorch neural network to classify points into one of 5 clusters and visualizes the **decision boundaries**.

---

## 📓 Notebook
Run the notebook directly in Google Colab
---

## 🚀 Features
- Generate synthetic dataset using `make_blobs`:
  - 5 classes (`centers=5`)
  - 2 features (`n_features=2`)
  - 1000 samples total
- Split into train/test sets with `train_test_split`.
- Convert NumPy arrays into PyTorch tensors.
- Build and train a neural network classifier with **CrossEntropyLoss** and **Adam optimizer**.
- Visualize **decision boundaries** for the trained model.

---

## 🛠️ Requirements
Install dependencies with:

```bash
pip install torch scikit-learn matplotlib numpy
