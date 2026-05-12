# Medical Insurance Cost Prediction System with MLflow

An end-to-end Machine Learning pipeline for predicting medical insurance charges using regression models, feature engineering, preprocessing pipelines, and MLflow-based experiment tracking. The project demonstrates production-style ML workflow implementation, model comparison, hyperparameter tuning, and model registry management.

---

# Project Overview

This project was developed to predict individual medical insurance charges based on demographic and health-related attributes such as age, BMI, smoking habits, region, and number of children.

The system follows a complete industry-level Machine Learning workflow including:

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Model training and evaluation  
- Pipeline automation  
- Hyperparameter tuning  
- MLflow experiment tracking and model registry  

The final Random Forest model achieved approximately **88% R² accuracy** on test data.

---

# Key Features

- End-to-end Machine Learning pipeline  
- Automated preprocessing using Scikit-learn Pipelines  
- Outlier handling using Winsorization  
- Numerical scaling and categorical encoding  
- Baseline and advanced model comparison  
- Random Forest regression modeling  
- Feature importance analysis  
- MLflow experiment tracking  
- Hyperparameter tuning with GridSearchCV  
- Model versioning and registry using MLflow  
- Production-ready modular workflow  

---

# Tech Stack

## Languages

- Python  
- SQL  

## Libraries & Frameworks

- Pandas  
- NumPy  
- Scikit-learn  
- Feature-engine  
- Matplotlib  
- Joblib  

## Machine Learning

- Regression Modeling  
- Random Forest Regression  
- Linear Regression  
- Feature Engineering  
- Feature Importance Analysis  
- Model Evaluation  

## MLOps & Experiment Tracking

- MLflow  
- GridSearchCV  
- Model Registry  
- Experiment Tracking  
- Dataset Tracking  

---

# Dataset Information

The dataset contains medical insurance-related records with the following features:

- Age  
- Gender  
- BMI  
- Number of Children  
- Smoking Status  
- Region  
- Medical Charges (Target Variable)  

---

# Machine Learning Workflow

## 1. Data Cleaning

Implemented industry-standard data cleaning pipeline:

- Removed duplicates  
- Standardized column names  
- Cleaned categorical values  
- Corrected data types  
- Structured preprocessing workflow  

---

## 2. Exploratory Data Analysis (EDA)

Performed comprehensive data analysis including:

- Distribution analysis  
- Correlation analysis  
- Outlier detection  
- Feature relationship analysis  
- Categorical feature analysis  
- Residual analysis  

---

## 3. Preprocessing Pipeline

Built modular preprocessing pipelines using Scikit-learn:

### Numerical Pipeline

- Outlier capping using Winsorizer  
- Missing value imputation  
- Feature scaling using StandardScaler  

### Categorical Pipeline

- Missing value handling  
- One-Hot Encoding  
- Unknown category handling  

---

## 4. Model Training

Implemented and compared multiple regression models:

### Baseline Model

- Linear Regression  

### Improved Model

- Random Forest Regressor  

---

# Model Performance

## Linear Regression

- MAE: 4183  
- RMSE: 5956  
- R² Score: 80.6%  

## Random Forest Regressor

- MAE: 2628  
- RMSE: 4726  
- R² Score: 87.8%  

The Random Forest model significantly outperformed the baseline Linear Regression model.

---

# Feature Importance Analysis

Analyzed feature importance using Random Forest model.

Top contributing features:

- Smoking status  
- BMI  
- Age  
- Number of children  

---

# MLflow Integration

Implemented MLflow for complete experiment management:

- Experiment tracking  
- Hyperparameter logging  
- Metric logging  
- Dataset tracking  
- Model signature logging  
- Model artifact storage  
- Model versioning  
- Registered model management  

---

# Hyperparameter Tuning

Used GridSearchCV with MLflow autologging for automated tuning.

Tuned parameters:

- Number of estimators  
- Maximum depth  

Best-performing models were automatically registered in MLflow Model Registry.

---

# Project Outcomes

- Built a complete production-style ML pipeline  
- Achieved ~88% prediction accuracy using Random Forest  
- Automated preprocessing and model workflow  
- Implemented experiment tracking using MLflow  
- Enabled reproducible ML experimentation  
- Demonstrated end-to-end MLOps workflow  

---

# Future Enhancements

- Docker containerization  
- AWS deployment  
- CI/CD integration  
- Real-time prediction API  
- Advanced ensemble models  
- SHAP explainability integration  
- Streamlit prediction dashboard  

---

# Installation

```bash
git clone <your_repo_url>

cd project_folder

pip install -r requirements.txt
```

---

# Run the MLflow Tracking Server

```bash
mlflow server --host 127.0.0.1 --port 5000
```

---

# Run the Project

```bash
python train.py
```

---

# MLflow UI

```bash
http://127.0.0.1:5000
```

---

# Project Structure

```bash
project_folder/
│
├── data/
├── notebooks/
├── models/
├── artifacts/
├── train.py
├── requirements.txt
├── README.md
```

---

# Author

**Sanket Padir**  
Data Scientist | ML Engineer | Generative AI Developer
