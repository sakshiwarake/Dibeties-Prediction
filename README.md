🩺 Diabetes Prediction Using Machine Learning
This project predicts diabetes using various machine learning models, focusing on recall to minimize false negatives and ensure at-risk patients are identified accurately.

📊 Dataset
Source: Kaggle - Pima Indian Diabetes Dataset
Features: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age
Target: Outcome (0 = Non-Diabetic, 1 = Diabetic)
🚀 Key Steps
Data Preparation:

Handled class imbalance using SMOTE.
Applied feature engineering (Glucose and BMI categories) but did not improve accuracy.
Model Training:

Algorithms: Decision Tree, Random Forest, Logistic Regression, SVM, KNN, XGBoost.
Best Accuracy: 83% (XGBoost).
Best Recall: 86% (Random Forest with tuning).
Optimization:

Used GridSearchCV for hyperparameter tuning.
Focused on recall to reduce false negatives.
Results:

Prioritizing recall ensured effective identification of diabetic patients.
Stacking classifiers didn’t significantly improve results.
🛠 Tools Used
Python, NumPy, pandas, scikit-learn, XGBoost, imbalanced-learn, matplotlib, seaborn
📈 Key Insight
Focusing on recall is crucial for healthcare applications to minimize the risk of missing positive cases.
