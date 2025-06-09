# AI-Agent-Mental-Health-Risk-Detection-Using-Survey-Data
# 🧠 Mental Health Risk Detection AI Agent

This project presents a functional AI Agent that predicts whether an individual is at risk of needing mental health treatment based on survey responses. It uses real-world survey data, applies data analysis techniques, and builds a predictive model using Random Forest Classifier.

---

## 📌 Problem Statement

Mental health issues in tech workplaces are often underreported due to stigma or lack of awareness. This AI Agent aims to analyze individual responses from a mental health survey and predict whether the person is likely to require treatment. It also provides personalized suggestions if needed.

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas** – Data analysis and manipulation  
- **NumPy** – Numerical operations  
- **Scikit-learn** – Machine Learning modeling and evaluation  
- **Joblib** – Model serialization  
- **Google Colab / Jupyter Notebook** – Development Environment  

---

## 📊 Dataset

- File: `survey.csv`  
- Source: Real-world tech workplace mental health survey  
- Contains demographic, work environment, and mental health history data

---

## 🔍 Data Analysis Highlights

- Categorical encoding using `LabelEncoder`
- Standardization of numerical features using `StandardScaler`
- Handling missing values (`Unknown` filled for specific fields)
- Train-test split: 80% training, 20% testing

---

## 🧠 Model Overview

- **Model Used:** `RandomForestClassifier`
- **Accuracy Achieved:** ~83%
- **Evaluation Metrics:**
  - Precision, Recall, F1-score for both treatment and no-treatment classes
  - Confusion matrix and classification report
- **Strength:** Balanced prediction performance across both classes

---

## 🧪 User Interaction

The model takes user input in the form of:
- Age (numeric)
- 22 multiple-choice questions based on workplace, mental health, and support systems

📌 Based on responses, the model:
- Predicts whether the user likely needs treatment
- Provides basic recommendations if treatment is advised


