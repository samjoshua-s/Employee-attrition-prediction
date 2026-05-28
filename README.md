# 🧠 Employee Attrition Prediction using Machine Learning

> Predicting employee churn using XGBoost, SHAP Explainability, and SMOTE on IBM HR Analytics Dataset.

---

## 📌 Project Overview

Employee attrition (employees leaving a company) is a costly problem for organizations. This project builds a machine learning system that predicts **which employees are likely to leave**, and more importantly, **explains why** — making it useful for HR teams to take preventive action.

---

## 🛠️ Tech Stack

| Category | Tools / Libraries |
|---|---|
| Language | Python |
| ML Model | XGBoost |
| Explainability | SHAP (SHapley Additive exPlanations) |
| Class Imbalance | SMOTE (Synthetic Minority Oversampling Technique) |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook / Google Colab |
| Dataset | IBM HR Analytics Employee Attrition Dataset |

---

## 🎯 Key Features

- **Attrition Prediction** — Classifies employees as likely to stay or leave using XGBoost
- **Class Imbalance Handling** — Applied SMOTE to balance the dataset and improve minority-class recall
- **Explainable AI** — Used SHAP to visualize which factors most influence each prediction
- **Pattern Mining** — Sequential Pattern Mining to identify behavioral trends linked to attrition
- **Feature Engineering** — Processed and transformed HR features to improve model accuracy

---

## 📊 Dataset

- **Source:** IBM HR Analytics Employee Attrition & Performance Dataset
- **Size:** 1,470 employee records
- **Target Variable:** `Attrition` (Yes / No)
- **Key Features:** Age, Job Role, Monthly Income, Work-Life Balance, Years at Company, Overtime, etc.

---

## 🔍 How It Works

```
Raw IBM HR Data
      ↓
Data Preprocessing & Feature Engineering
      ↓
SMOTE — Handle Class Imbalance
      ↓
XGBoost Classifier — Train & Predict
      ↓
SHAP — Explain Why Each Employee is at Risk
      ↓
Output: Attrition Risk + Top Reasons
```

---

## 📈 Results

- Improved minority-class (attrition = Yes) recall using SMOTE
- SHAP identified **Overtime**, **Monthly Income**, and **Years at Company** as top attrition drivers
- Model produces interpretable predictions suitable for HR decision-making

---

## 💡 What I Learned

- How to handle real-world class imbalance problems using SMOTE
- How to use XGBoost for binary classification tasks
- How Explainable AI (SHAP) makes black-box models transparent and business-friendly
- Feature engineering on HR behavioral data

---

## 🚀 How to Run

1. Clone this repository
```bash
git clone https://github.com/yourusername/employee-attrition-prediction.git
```

2. Open the notebook
```bash
jupyter notebook Employee_Attrition_Prediction.ipynb
```
Or open directly in **Google Colab** by uploading the `.ipynb` file.

3. Install required libraries (if needed)
```bash
pip install xgboost shap imbalanced-learn pandas numpy matplotlib seaborn scikit-learn
```

---

## 👤 Author

**Sam Joshua S**
- 📧 samj59703@gmail.com
- 🔗 [GitHub](https://github.com/samjoshua-s)
- 🎓 B.Tech Computer Science & Business Systems | SASTRA Deemed University

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
