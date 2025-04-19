# kmeans-clustering-iris
K-Means clustering on the Iris dataset: from-scratch NumPy implementation vs scikit-learn, visualizations, PCA, and evaluation.
# K-Means Clustering on the Iris Dataset: From Scratch vs Scikit-learn

This project implements the **K-Means Clustering algorithm from scratch using NumPy** and applies it to the **Iris dataset**. It compares the custom implementation with Scikit-learn's built-in KMeans, using multiple distance metrics, PCA for visualization, and evaluation via the Silhouette Score.

---

## 🚀 Project Features

- ✅ **K-Means from scratch** (no ML libraries, just NumPy)
- 📊 **Visualization** of clustering results and centroid updates
- 🔁 **K-Means animation** to illustrate the iterative process
- 📉 **Elbow method** for selecting the optimal number of clusters
- 🔬 **PCA** (Principal Component Analysis) for dimensionality reduction and visualization
- 📐 Comparison with **Scikit-learn’s KMeans**
- 📏 Experiments with **Euclidean and Manhattan distance metrics**
- 🏆 Evaluation with **Silhouette Score**

---

## 📚 Dataset

- **Iris Dataset** from Scikit-learn
- Only sepal features are used initially for simplicity.
- Later sections apply K-Means to all four features with PCA.

---

## 📌 Motivation

Clustering is a fundamental unsupervised learning task. Implementing K-Means from scratch deepens understanding of how the algorithm works internally, how convergence happens, and how to optimize performance with the right choice of distance metrics and evaluation methods.

---

## 📈 Results Summary

- Optimal number of clusters **k=3**, aligned with the Iris dataset's natural labels.
- **Silhouette Score**:  
  - Scikit-learn KMeans: **0.4599**  
  - Manhattan KMeans (L1 distance): **0.4596**  
  These scores suggest that both methods produce meaningful but not perfect clusters, showing the complexity of the dataset even with unsupervised learning.

---

## 📦 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/kmeans-clustering-iris.git
   cd kmeans-clustering-iris
