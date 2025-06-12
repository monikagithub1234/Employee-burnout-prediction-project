# Employee-burnout-prediction-project
This repository focuses on predicting employee burnout using machine learning, offering insights for proactive workplace well-being management

# 🧠 Employee Burnout Prediction

This project uses machine learning to predict employee burnout risk based on HR-related data like working hours, satisfaction level, and more. It was developed as part of APSSDC training.

---

## 📌 Objective

To build a machine learning model that predicts whether an employee is at risk of burnout, helping companies take preventive actions and improve employee well-being.

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📊 Dataset

A sample HR dataset containing the following features:

- Employee satisfaction level
- Last evaluation score
- Number of projects
- Average monthly hours
- Time spent in company
- Work-life balance score
- Overtime (yes/no)

📁 *File:* employee_burnout_data.csv

---

## 🧠 ML Algorithms Used

- Logistic Regression
- Decision Tree
- Random Forest
- Linear Regression (for numerical burnout score prediction)
- Model Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - Confusion Matrix
  - MSE, RMSE, MAE, R² (for regression)

---

## 📈 Output

The model classifies employees into:
- *Burnout Risk = YES / NO*
- Based on prediction thresholds and trained model probabilities.

### 🔍 Linear Regression Model Performance Metrics:
Mean Squared Error (MSE):       0.0031569779113610717
Root Mean Squared Error (RMSE): 0.0561869905882231
Mean Absolute Error (MAE):      0.04595032032644773
R-squared Score (R²):           0.918822674247248

The model achieved high accuracy with *91.88% R² score*, making it suitable for predicting employee burnout based on the input features.
