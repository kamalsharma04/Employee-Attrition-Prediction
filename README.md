![Python](https://img.shields.io/badge/Python-3.13-blue)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)

# 🧠 Employee Attrition Prediction Project

This project predicts whether an employee is likely to leave (Attrition = Yes) or stay (Attrition = No) based on HR data such as job role, age, salary, work-life balance, etc.

---

## 📘 Overview

Employee attrition prediction helps HR departments identify employees at risk of leaving the organization.  
By predicting attrition early, companies can take proactive measures to improve retention.

---

## ⚙️ Technologies Used
- Python 🐍  
- NumPy & Pandas (Data Handling)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (Machine Learning)
- SMOTE (Handling class imbalance)
- Random Forest Classifier (Model)

---

## 🧩 Steps Involved
1. **Data Cleaning & Preprocessing**
   - Removed duplicates and irrelevant columns
   - Encoded categorical features with `LabelEncoder`
   - Balanced dataset using `SMOTE`

2. **Feature Scaling**
   - Standardized numerical features using `StandardScaler`

3. **Model Training**
   - Used `RandomForestClassifier` with tuned hyperparameters  
   - Stratified train-test split (80-20)

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix Visualization  
   - Feature Importance Plot

---

## 📊 Model Performance

| Metric | Score |
|--------|--------|
| **Accuracy** | **80.27%** |
| **Precision (Class 0)** | 0.87 |
| **Precision (Class 1)** | 0.37 |
| **Recall (Class 0)** | 0.89 |
| **Recall (Class 1)** | 0.32 |

---

## 📈 Insights
- Model performs strongly in detecting **non-attrition** cases.
- Improvement area: capturing **attrition (Yes)** cases better using advanced balancing or ensemble techniques.
- Feature importance helps HR identify key reasons for attrition.

---

## 🚀 Future Improvements
- Try XGBoost or CatBoost for better recall.
- Hyperparameter tuning with GridSearchCV.
- Add SHAP or LIME for interpretability.

---

## 👨‍💻 Author
**Kamal Sharma**  
📍 BCA Student | Data Science Enthusiast  
📬 GitHub: [kamalsharma04](https://github.com/kamalsharma04)