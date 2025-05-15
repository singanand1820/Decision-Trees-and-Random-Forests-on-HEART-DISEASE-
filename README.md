# Decision-Trees-and-Random-Forests-on-HEART-DISEASE-

❤️ Heart Disease Prediction using Decision Trees & Random Forests

📌 Overview

This project uses machine learning models to predict whether a patient has heart disease based on clinical features. We employ Decision Tree and Random Forest classifiers to build interpretable and accurate models, providing visual insights into the data and model behavior.

📂 Dataset

Source: Heart Disease Dataset (from Kaggle)

Features:

Age, Sex, Chest Pain Type (cp), Cholesterol (chol), Resting Blood Pressure (trestbps),
Fasting Blood Sugar (fbs), Rest ECG (restecg), Maximum Heart Rate (thalach),
Exercise-induced Angina (exang), Oldpeak, Slope, CA, Thal, and Target.

Target:

1: Presence of Heart Disease

0: No Heart Disease

🔍 Exploratory Data Analysis (EDA)

Target class is nearly balanced: 526 (disease) vs 499 (no disease)

Visuals:

Bar chart & pie chart to visualize target distribution

Feature-level inspection for top correlated attributes

🧠 Machine Learning Models

🌳 Decision Tree

Trained with max_depth=4 to control overfitting

Visualized using plot_tree

Accuracy: 0.80

Classification Report Highlights:

Precision: 0.88 (No Disease), 0.75 (Disease)

F1 Score: 0.80

🌲 Random Forest

Trained with 100 estimators

Accuracy: 0.985

Cross-Validation Accuracy: 0.997

Top Features:

cp, ca, thalach, oldpeak, thal

📊 Feature Importance

cp: 0.1351  
ca: 0.1273  
thalach: 0.1222  
oldpeak: 0.1219  
thal: 0.1105  
These features contribute most to predicting heart disease.

🛠 Tools Used

Python (Pandas, NumPy)

Scikit-learn

Matplotlib, Seaborn

📈 Outcome

Random Forest outperforms Decision Tree in both accuracy and generalization. The model identifies key medical indicators of heart disease and demonstrates the value of ensemble methods in healthcare prediction.

