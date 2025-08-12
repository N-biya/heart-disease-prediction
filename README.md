# heart-disease-prediction
Heart Disease Prediction
Task Objective
The goal of this project is to build a machine learning model that predicts whether an individual is at risk of heart disease based on their health data. The project also includes a simplified input method so non-technical users can provide basic health information and receive predictions.

Dataset Used
The dataset used is the Heart Disease UCI Dataset, available on Kaggle. It contains various health-related attributes such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and other medical indicators. The target variable indicates the presence (1) or absence (0) of heart disease.

Models Applied
Logistic Regression: Chosen for its simplicity, interpretability, and suitability for binary classification tasks.

Data preprocessing steps included:

Encoding categorical features

Feature scaling

Train-test splitting

Evaluation metrics used: Accuracy, ROC-AUC, and confusion matrix.

Key Results and Findings
Logistic Regression achieved over 80% accuracy on the test set.

The ROC-AUC score indicated strong model performance in distinguishing between positive and negative cases.

Key features influencing predictions included chest pain type, maximum heart rate achieved, and ST depression induced by exercise.

A user-friendly question-based input method was implemented to make the model accessible for general users.
