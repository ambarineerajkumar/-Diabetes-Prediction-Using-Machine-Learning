# -Diabetes-Prediction-Using-Machine-Learning

# 📘 Objective
The goal of this project is to develop a predictive model to determine whether a patient is likely to be diabetic, based on health parameters. The entire ML pipeline is version-controlled using Git and documented in JupyterLab for reproducibility and collaboration.

# 📊 Dataset Summary
Dataset: diabetes_data.xlsx (based on the PIMA Indians Diabetes dataset)
Source: Public health repository
Rows: 768 | Columns: 9

# 🔬 Methodology
1. Exploratory Data Analysis (EDA)
Analyzed distributions using histograms and boxplots

Identified outliers and missing values (e.g., zero insulin values)

Correlation heatmap to identify feature importance (Glucose, BMI, Age showed strong correlations)

2. Data Preprocessing
Replaced 0s with NaN in invalid fields and applied median imputation

Scaled data using StandardScaler to normalize input features

Split data into 80/20 train-test sets

3. Modeling
Compared multiple classification algorithms:

Logistic Regression

Decision Tree Classifier

Random Forest

K-Nearest Neighbors

Used GridSearchCV for hyperparameter tuning

4. Evaluation Metrics
Accuracy

Precision, Recall, F1-Score

ROC-AUC curve

Model	Accuracy	Precision	Recall	F1-Score

Logistic Regression	78%	0.74	0.68	0.71

Random Forest	83%	0.80	0.76	0.78

KNN	76%	0.70	0.66	0.68



![Diabetes](https://github.com/user-attachments/assets/c4cc8583-8241-4766-9b95-3880f26335f3)

# Conclusion:
This work demonstrates a foundational understanding of both machine learning and collaborative coding. By analyzing the diabetes dataset, you are applying supervised learning techniques, while the Git-based PDF highlights your readiness to manage data science projects efficiently. Together, they showcase a complete ML lifecycle — from data processing and model training to version-controlled deployment and sharing.

