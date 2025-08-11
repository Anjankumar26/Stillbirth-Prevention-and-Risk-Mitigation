# Stillbirth Risk Prediction with Machine Learning

This project focuses on leveraging machine learning to predict fetal health status from Cardiotocography (CTG) data. The primary goal is to build a highly accurate and interpretable model to classify fetal well-being into **Normal**, **Suspect**, or **Pathologic** states, thereby aiding medical professionals in the early detection of fetal distress and helping to mitigate the risk of stillbirth.

## 🚀 Key Features & Performance

This repository contains an end-to-end data science workflow that includes:

* **Data Preprocessing:** Cleaning the raw CTG dataset and handling missing values.
* **Feature Engineering:** Analyzing feature correlations and selecting the most impactful variables for modeling.
* **Model Comparison:** Training and evaluating multiple classifiers, including Decision Tree, Random Forest, and XGBoost.
* **Hyperparameter Tuning:** Optimizing the best-performing model (XGBoost) using Bayesian Optimization (`BayesSearchCV`) to maximize performance.
* **Model Interpretation:** Using SHAP (SHapley Additive exPlanations) to understand the model's predictions and ensure its decisions are based on clinically relevant factors.

### Performance Highlight

The final, tuned **XGBoost model** achieved an outstanding **F1-Score of 99.2%**, demonstrating high reliability in classifying fetal health status.

## 🛠️ Technologies Used

* **Data Handling:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`, `xgboost`
* **ML Optimization:** `scikit-optimize`
* **Model Explainability:** `shap`
* **Visualization:** `matplotlib`
* **File Handling:** `openpyxl`

