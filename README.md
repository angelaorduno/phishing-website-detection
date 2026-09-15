# 💗 Phishing Website Detection

![Python](https://img.shields.io/badge/Python-E92BAA?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-C21884?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Classification](https://img.shields.io/badge/Classification-E92BAA?style=for-the-badge)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-C21884?style=for-the-badge&logo=scikitlearn&logoColor=white)

## 🌸 Project Overview

This project compares machine learning classification algorithms for detecting phishing websites. The goal is to evaluate multiple classification approaches and determine which model provides the strongest performance for distinguishing phishing websites from legitimate websites.

## 💕 Dataset

The project uses the **Phishing Websites dataset** from the UCI Machine Learning Repository. The dataset contains **11,055 observations and 30 features** describing characteristics commonly associated with phishing and legitimate websites.

**Source:** [UCI Machine Learning Repository – Phishing Websites](https://archive.ics.uci.edu/dataset/327/phishing+websites)

## 🌷 Models

Three classification algorithms were evaluated:

- Random Forest
- K-Nearest Neighbors (KNN)
- Logistic Regression

## 💗 Model Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| **Random Forest** | **0.9742** | **0.9696** | **0.9846** | **0.9770** | **0.9977** |
| K-Nearest Neighbors | 0.9484 | 0.9500 | 0.9578 | 0.9539 | 0.9868 |
| Logistic Regression | 0.9285 | 0.9234 | 0.9504 | 0.9367 | 0.9808 |

🌸 **Random Forest achieved the strongest overall performance**, reaching **97.42% accuracy** and a **0.9977 ROC-AUC**.

## 💕 Tools & Technologies

![Pandas](https://img.shields.io/badge/Pandas-E92BAA?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-C21884?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-E92BAA?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-C21884?style=flat-square&logo=scikitlearn&logoColor=white)

## 🌷 Analysis

The analysis includes data exploration, preprocessing, train/test splitting, feature scaling where appropriate, model training, model evaluation, confusion matrices, ROC curves, and comparison of model performance.

📓 **View the complete analysis:**  
[`phishing_website_detection.ipynb`](./phishing_website_detection.ipynb)

---

### 💗 Angela Diaz

**MS Data Science | PhD Student in Data Science**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-E92BAA?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/angela0diaz/)
[![Portfolio](https://img.shields.io/badge/Portfolio-C21884?style=for-the-badge&logo=googlechrome&logoColor=white)](https://angela-diaz.com/)
