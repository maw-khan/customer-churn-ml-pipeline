# 📉 End-to-End Customer Churn Prediction Pipeline using Scikit-learn

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success?style=for-the-badge)
![Pipeline](https://img.shields.io/badge/ML-Pipeline-purple?style=for-the-badge)
![GridSearchCV](https://img.shields.io/badge/GridSearchCV-HyperparameterTuning-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)

</p>

---

# 📌 Project Overview

This project implements a complete **Machine Learning Pipeline** for predicting customer churn using the **Telco Customer Churn Dataset**.

The project demonstrates a production-oriented workflow including:

- automated preprocessing
- feature engineering
- machine learning pipelines
- hyperparameter tuning
- model evaluation
- reusable model export

The entire workflow is built using the **Scikit-learn Pipeline API**, making the solution scalable, reusable, and deployment-ready.

---

# 🎯 Objectives

The main objectives of this project are:

- Build a reusable end-to-end ML pipeline
- Automate preprocessing using Scikit-learn
- Train multiple classification models
- Optimize performance using GridSearchCV
- Evaluate model performance using classification metrics
- Export the trained pipeline for deployment and reuse

---

# 🧠 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Computation |
| Scikit-learn | Machine Learning |
| Matplotlib | Data Visualization |
| Joblib | Model Export |
| Google Colab | Development Environment |

---

# 📂 Dataset

The project uses the:

## Telco Customer Churn Dataset

The dataset contains customer information including:

- demographics
- account information
- subscription services
- billing details
- churn status

### Target Variable

| Value | Meaning |
|---|---|
| 1 | Customer Churned |
| 0 | Customer Retained |

---

# 🏗️ Project Workflow

```text
Raw Customer Data
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Train-Test Split
        ↓
Preprocessing Pipeline
        ↓
Model Training
        ↓
Hyperparameter Tuning
        ↓
Evaluation
        ↓
Pipeline Export
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/maw-khan/customer-churn-ml-pipeline.git
```

---

# 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🚀 Running the Project

Run the Jupyter Notebook in Google Colab or Jupyter:

```text
customer_churn_pipeline.ipynb
```

---

# 📊 Exploratory Data Analysis

The notebook includes:

✅ Dataset Overview  
✅ Missing Value Analysis  
✅ Target Variable Distribution  
✅ Data Cleaning  
✅ Feature Type Identification  

---

# 🏭 Machine Learning Pipeline

The project uses:

## Scikit-learn Pipeline API

The preprocessing workflow includes:

### Numerical Features
- Median Imputation
- Standard Scaling

### Categorical Features
- Most Frequent Imputation
- One-Hot Encoding

The preprocessing and model training are combined into a single reusable pipeline.

---

# 🤖 Models Used

## 1. Logistic Regression

Used as a baseline classification model.

## 2. Random Forest Classifier

Used for improved nonlinear pattern learning and better predictive performance.

---

# 🔥 Hyperparameter Tuning

GridSearchCV is used to optimize:

- number of estimators
- tree depth
- model performance

This improves generalization and prediction accuracy.

---

# 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy Score
- Classification Report
- Precision
- Recall
- F1-score
- Confusion Matrix

---

# 📊 Expected Performance

| Model | Accuracy |
|---|---|
| Logistic Regression | 81% |
| Random Forest | 78% - 80% |

---

# 💾 Model Export

The trained pipeline is exported using:

```python
joblib.dump()
```

This allows:

- model reuse
- deployment
- production integration
- scalable inference

Exported File:

```text
customer_churn_pipeline.pkl
```

---

# 📁 Project Structure

```text
customer-churn-ml-pipeline/
│
├── customer_churn_pipeline.ipynb
├── requirements.txt
├── README.md
│
├── models/
│   └── customer_churn_pipeline.pkl
│
├── dataset/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── screenshots/
│   ├── churn_distribution.png
│   ├── confusion_matrix.png
│   └── model_results.png
│
└── logs/
```

---

# 🧪 Sample Prediction

Example:

```python
prediction = loaded_pipeline.predict(sample_customer)
```

Output:

```text
Predicted Churn: 1
```

---

# 📚 Key Learning Outcomes

This project provided practical experience in:

- Machine Learning Pipelines
- Automated Preprocessing
- Feature Engineering
- Hyperparameter Tuning
- Classification Modeling
- Production-Oriented ML Design
- Model Export and Deployment
- End-to-End ML Workflows

---

# 🚀 Future Improvements

Potential future enhancements include:

- XGBoost Integration
- LightGBM Models
- SHAP Explainability
- Streamlit Deployment
- Real-Time API Predictions
- Class Imbalance Handling
- Feature Selection Optimization

---

# 🎓 Focus Areas:

- ML Pipelines
- Hyperparameter Optimization
- Predictive Analytics
- Production-Ready ML Systems

---

# 👨‍💻 Author

## Muhammad Ali Waris Khan

AI/ML Engineer | Machine Learning & NLP Enthusiast

---

# 📜 License

This project is developed for educational and internship purposes.

