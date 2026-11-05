# 🧊 3D Object Classification using PointNet & PointNet++

This project implements and compares **PointNet** and **PointNet++** architectures for 3D point cloud classification using the ModelNet10 dataset.

The goal is to directly process raw point cloud data while handling permutation invariance and capturing both global and local geometric features.

---

## 🚀 Features

- 📦 Direct 3D Point Cloud Processing (No voxelization)
- 🧠 Implementation of **PointNet** and **PointNet++**
- 📊 Performance comparison using Accuracy, Precision, Recall & F1-score
- 🌐 Gradio-based Web Interface for real-time `.off` file classification
- ⚡ GPU-accelerated training using PyTorch

---

## 📂 Dataset

**ModelNet10**
- 3,991 training samples  
- 908 validation samples  
- 10 furniture object categories  
- 1,024 sampled points per object  

---

## 🏗 Tech Stack

- Python  
- PyTorch  
- NumPy  
- Trimesh  
- Scikit-learn  
- Matplotlib  
- Gradio  

---

## 📈 Results

| Model        | Validation Accuracy |
|--------------|--------------------|
| PointNet     | 80.36%             |
| PointNet++   | **86.38%**         |

PointNet++ outperformed PointNet due to its hierarchical feature learning, capturing local geometric structures more effectively.
