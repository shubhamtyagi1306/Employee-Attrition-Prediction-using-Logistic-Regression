# Employee Attrition Prediction using Logistic Regression

This project aims to predict whether an employee is likely to leave the organization using Logistic Regression with L1/L2 regularization and hyperparameter tuning techniques. It uses the IBM HR Analytics dataset to identify key drivers of attrition.

---

## Project Objective

- Build a Logistic Regression model to predict employee attrition.
- Improve performance using L1 and L2 regularization.
- Optimize hyperparameters using GridSearchCV and RandomizedSearchCV.
- Evaluate model using accuracy, precision, recall, F1-score, and confusion matrix.

---

## Dataset

- **Source**: [IBM HR Analytics Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Target Variable**: `Attrition` (Yes/No → converted to binary)

---

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## Workflow

1. **Data Preprocessing**
   - Drop irrelevant columns
   - Encode categorical features
   - Feature scaling

2. **Model Training**
   - Logistic Regression with `penalty='l1'` and `penalty='l2'`
   - Solver: `liblinear` (supports both L1 & L2)

3. **Hyperparameter Tuning**
   - GridSearchCV and RandomizedSearchCV on `C`, `penalty`, `solver`

4. **Model Evaluation**
   - Accuracy
   - Confusion Matrix
   - Precision, Recall, F1-score

5. **Feature Importance**
   - Analyze model coefficients to identify top attrition drivers

---

## Results

- Achieved high accuracy using tuned Logistic Regression model
- Identified key features influencing attrition such as OverTime, JobSatisfaction, and WorkLifeBalance

---
