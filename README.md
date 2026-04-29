# 🚢 Titanic Survival Prediction: Advanced ML Pipeline

This repository contains a comprehensive, end-to-end Machine Learning project that predicts the survival probability of Titanic passengers. Going beyond basic modeling, this project implements advanced data preprocessing, statistical hypothesis testing, and interactive model deployment.

## 🌟 Key Features

* **Advanced Feature Engineering:** Dynamic creation of the `FamilySize` feature and robust handling of missing values using Scikit-Learn's `ColumnTransformer` and `Pipeline`.
* **Multi-Model Comparison:** Trains and evaluates 8 different algorithms concurrently:
  * Logistic Regression, KNN, SVC, Decision Tree, Gaussian NB
  * Ensemble Methods: Random Forest & Gradient Boosting
  * Artificial Neural Network (ANN) using Keras/TensorFlow.
* **Rigorous Validation:** Utilizes both Hold-out testing and **10-Fold Stratified Cross-Validation** to ensure model robustness and prevent overfitting.
* **Statistical Significance:** Implements **McNemar's Test** to statistically compare the performance differences between the Random Forest and ANN models.
* **Interactive UI:** Deploys the best-performing model (Gradient Boosting) into a live, interactive web application using **Gradio**.

## 📊 Evaluation Metrics
Models are strictly evaluated using multiple metrics, avoiding reliance on Accuracy alone:
* Accuracy, Precision, Recall, and F1-Score
* Specificity (Calculated via Confusion Matrices)
* ROC Curve and Area Under the Curve (AUC)

## 🛠️ Tech Stack
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`
* **Deep Learning:** `TensorFlow`, `Keras`
* **Visualization:** `matplotlib`, `seaborn`
* **Deployment/UI:** `Gradio`, `joblib`

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/titanic-advanced-ml-pipeline.git](https://github.com/your-username/titanic-advanced-ml-pipeline.git)
