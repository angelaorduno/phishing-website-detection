# Phishing Website Detection

This project compares machine learning classification algorithms for detecting phishing websites. The goal is to evaluate multiple classification approaches and determine which model provides the strongest performance for distinguishing phishing websites from legitimate websites.

## Dataset

The project uses the **Phishing Websites dataset** from the UCI Machine Learning Repository. The dataset contains **11,055 observations and 30 features** describing characteristics commonly associated with phishing and legitimate websites.

**Source:** [UCI Machine Learning Repository – Phishing Websites](https://archive.ics.uci.edu/dataset/327/phishing+websites)

## Models

Three classification algorithms were evaluated:

- Random Forest
- K-Nearest Neighbors (KNN)
- Logistic Regression

## Model Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Random Forest | 0.9742 | 0.9696 | 0.9846 | 0.9770 | 0.9977 |
| K-Nearest Neighbors | 0.9484 | 0.9500 | 0.9578 | 0.9539 | 0.9868 |
| Logistic Regression | 0.9285 | 0.9234 | 0.9504 | 0.9367 | 0.9808 |

Random Forest achieved the strongest overall performance across the evaluated metrics, reaching **97.42% accuracy** and a **0.9977 ROC-AUC**.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- UCI ML Repository

## Analysis

The analysis includes data exploration, preprocessing, train/test splitting, feature scaling where appropriate, model training, model evaluation, confusion matrices, ROC curves, and comparison of model performance.

The complete analysis and code are available in:

[`phishing_website_detection.ipynb`](./phishing_website_detection.ipynb)

## Author

**Angela Diaz**  
MS Data Science | PhD Student in Data Science  
[LinkedIn](https://www.linkedin.com/in/angela0diaz/) | [Portfolio](https://angela-diaz.com/)
