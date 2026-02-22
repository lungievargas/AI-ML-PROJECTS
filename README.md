# 🧠 AI / Machine Learning Research Portfolio

![Python](https://img.shields.io/badge/Python-3.x-blue)
![ML](https://img.shields.io/badge/Machine-Learning-green)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 Overview

This repository contains research-oriented Artificial Intelligence and Machine Learning projects focused on:

- Anomaly Detection  
- Unsupervised Learning  
- Statistical Modeling  
- Deep Learning  
- Feature Engineering  
- Model Evaluation & Benchmarking  
- Data Visualization & Interpretability  

The primary objective is to explore algorithmic foundations, implement reproducible ML pipelines, and benchmark model performance using rigorous evaluation methodologies aligned with research and Kaggle competition standards.

---

# 🔬 Core Research Domains

## 1️⃣ Anomaly Detection – Isolation Forest

Implementation and analysis of the anomaly detection algorithm introduced in:

Liu, F. T., Ting, K. M., & Zhou, Z. H. (2008). Isolation Forest.

### 🎯 Objective
Detect rare and abnormal observations in structured and high-dimensional datasets using path-length-based isolation.

### ⚙️ Methodology
- Data preprocessing & normalization  
- Random partitioning trees  
- Expected path length computation  
- Anomaly score derivation  
- Threshold-based classification  

### 📊 Evaluation Metrics
- ROC-AUC  
- Precision-Recall Curve  
- F1 Score  
- Confusion Matrix  

### 🔎 Comparative Analysis
- Isolation Forest vs Local Outlier Factor (LOF)  
- Sensitivity analysis on contamination parameter  
- Performance under varying feature distributions  

---

## 2️⃣ Density-Based & Distance-Based Models

Exploration of alternative anomaly detection approaches:

- Local Outlier Factor (LOF)  
- DBSCAN clustering  
- k-Nearest Neighbors anomaly scoring  

### Research Focus
- Density estimation behavior in high-dimensional space  
- Cluster separability  
- Hyperparameter sensitivity analysis  
- Robustness to feature scaling  

---

## 3️⃣ Deep Learning for Anomaly Detection

Reconstruction-based anomaly detection using:

- Autoencoders  
- Variational Autoencoders (VAE)  

### Approach
- Encoder-decoder neural architectures  
- Latent space representation analysis  
- Reconstruction error thresholding  

### Evaluation
- Reconstruction loss distribution  
- AUC comparison with tree-based models  
- Latent embedding visualization  

---

# 🧪 Experimental Design & Reproducibility

All projects follow a structured ML workflow:

1. Data Cleaning & Preprocessing  
2. Feature Engineering  
3. Train-Test Split (stratified where applicable)  
4. Cross-Validation  
5. Hyperparameter Optimization  
6. Model Benchmarking  
7. Statistical Performance Comparison  

Reproducibility ensured through:

- Fixed random seeds  
- Modular preprocessing pipelines  
- Clear separation of notebooks and source code  
- Documented experimental configurations  

---

# 📈 Visualization & Interpretability

Visualization is treated as a research instrument rather than aesthetic output.

Techniques include:

- PCA / t-SNE / UMAP projections  
- Anomaly score distribution analysis  
- Feature importance ranking  
- SHAP-based interpretability  
- Decision boundary visualization in reduced dimensions  

---

# 🛠 Technology Stack

- Python 3.x  
- NumPy  
- Pandas  
- Scikit-learn  
- TensorFlow / PyTorch  
- Matplotlib  
- Seaborn  
- Plotly  
- Google Colab
- Jupyter Notebook 


