# 🩺 Cancer Risk Level Prediction using Machine Learning

## 📌 Project Overview

This project predicts a patient's **Cancer Risk Level (Low, Medium, High)** based on demographic, lifestyle, environmental, and medical factors.

The objective is to identify high-risk patients early and assist healthcare professionals in preventive screening and intervention.

The solution includes:

- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Class Imbalance Handling using SMOTE
- Machine Learning Model Development
- Hyperparameter Optimization using Optuna
- Interactive Streamlit Web Application
- Model Deployment

---

## 🚀 Live Demo

🔗 **Streamlit App:**  
https://cancer-risk-detection-g8x63uwr5fuv3kn2wcjjex.streamlit.app/

---

## 📂 Dataset Features

### Patient Information
- Age
- Gender
- BMI

### Lifestyle & Environmental Factors
- Smoking
- Alcohol Use
- Obesity
- Diet Red Meat
- Diet Salted Processed
- Fruit Veg Intake
- Physical Activity
- Air Pollution
- Occupational Hazards
- Calcium Intake

### Medical Factors
- Family History
- BRCA Mutation
- H Pylori Infection

### Target Variable
- Risk Level
  - Low
  - Medium
  - High

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Optuna
- Imbalanced-Learn (SMOTE)
- Joblib
- Streamlit

---

## 🔄 Machine Learning Pipeline

### 1. Data Preprocessing
- Missing value handling
- Label Encoding
- Feature selection

### 2. Exploratory Data Analysis
- Risk distribution analysis
- Correlation analysis
- Feature importance investigation

### 3. Handling Class Imbalance
Implemented:

- SMOTE (Synthetic Minority Oversampling Technique)

to improve recall for High-Risk patients.

### 4. Model Training

Models evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### 5. Hyperparameter Optimization

Used:

- Optuna
- TPE Sampler
- Stratified K-Fold Cross Validation

Optimization Goal:

- Maximize Recall for High-Risk Patients

---

## 🏆 Final Model

### Model
- XGBoost Classifier

### Optimization
- Optuna Tuned Parameters

### Imbalance Handling
- SMOTE Oversampling

### Deployment Model Files

```text
final_xgb_class_weighted.pkl
label_encoder.pkl
feature_names.pkl
```

---

## 📊 Results

The final model achieved strong performance in identifying high-risk patients while maintaining balanced classification across all classes.

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

(Add your actual metrics here)

Example:

| Metric | Score |
|----------|--------|
| Accuracy | 88% |
| Precision | 0.87 |
| Recall | 0.88 |
| F1 Score | 0.87 |

---

## 💻 Streamlit Application

Features:

✅ Manual Patient Risk Prediction

✅ Batch Prediction using CSV Upload

✅ Probability Scores for each Risk Class

✅ Interactive User Interface

---

## 📁 Project Structure

```text
Cancer-Risk-Detection/
│
├── app.py
├── requirements.txt
├── README.md
│
├── data/
│   └── cancer-risk-factors.csv
│
├── notebooks/
│   └── Cancer_Risk_Prediction.ipynb
│
├── models/
│   ├── final_xgb_class_weighted.pkl
│   ├── feature_names.pkl
│   └── label_encoder.pkl
│
├── screenshots/
│
└── .gitignore
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Cancer-Risk-Detection.git
cd Cancer-Risk-Detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## 📈 Future Improvements

- SHAP Explainability
- Feature Importance Dashboard
- PDF Report Generation
- Docker Containerization
- AWS Deployment
- CI/CD Pipeline

---

## 🎯 Key Learnings

This project demonstrates:

- End-to-End Machine Learning Pipeline
- Data Preprocessing
- Class Imbalance Handling
- Hyperparameter Optimization
- Model Deployment
- Interactive Web Application Development

---

## 👨‍💻 Author

**Karan Patel**

LinkedIn: (Add your LinkedIn URL)

GitHub: (Add your GitHub URL)

---

## 📜 License

This project is licensed under the MIT License.