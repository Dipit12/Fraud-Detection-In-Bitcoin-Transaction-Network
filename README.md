# 🚀 Fraud Detection in Bitcoin Transactions  
### Using Graph Attention Networks (GAT) + Topological Data Analysis (TDA)

This project focuses on detecting fraudulent Bitcoin transactions by combining **Graph Neural Networks (GAT)** with **Topological Data Analysis (TDA)** to capture both local and global structural patterns in transaction graphs.

---

## 📌 Features
- Uses **Elliptic Bitcoin Dataset**
- Graph-based fraud detection using **GAT**
- Extracts **topological features** using persistent homology (TDA)
- Handles **class imbalance**
- Achieves improved performance over baseline models

---

## 🛠️ Tech Stack
- Python
- PyTorch / PyTorch Geometric (if used)
- NumPy, Pandas
- NetworkX
- Scikit-learn
- Jupyter Notebook

---

## 📊 Results
- **Accuracy:** 98%  
- **F1-Score:** 0.84  

The integration of **Topological Data Analysis (TDA)** with **Graph Attention Networks (GAT)** significantly improves the model’s ability to detect fraudulent transactions, especially in highly imbalanced data scenarios.  
Topological features help capture hidden structural patterns such as loops and cycles, which are often indicative of coordinated fraud activity.

---

## 📂 Dataset
[Elliptic Bitcoin Dataset on Kaggle](https://www.kaggle.com/datasets/ellipticco/elliptic-data-set?utm_source=chatgpt.com)