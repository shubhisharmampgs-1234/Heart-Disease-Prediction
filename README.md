🩺 Heart Disease Prediction System

📌 Project Overview

This project aims to predict the presence of heart disease in a patient using machine learning techniques based on clinical parameters. The goal is to build an accurate, interpretable, and efficient classification model that can assist in early medical diagnosis.


🎯 Problem Statement

To classify whether a patient is likely to have heart disease based on medical attributes such as age, cholesterol level, resting blood pressure, and other diagnostic features.


📂 Dataset Information

Dataset: Heart Disease Dataset
Source: UCI Machine Learning Repository (or Kaggle if applicable)
Features include:
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
ECG results
Maximum Heart Rate
Exercise-induced angina
Target variable (0 = No Disease, 1 = Disease)

🛠 Technologies Used

Python 🐍

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook


📊 Exploratory Data Analysis (EDA)

Performed detailed analysis to understand:

Distribution of heart disease cases
Correlation between features
Age vs disease trends
Heatmap for feature correlation



🤖 Machine Learning Models Used

The following models were trained and compared:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)


📈 Model Evaluation

Models were evaluated using:

Accuracy Score
Confusion Matrix
Precision & Recall
🏆 Best Model

The Random Forest Classifier performed best among all models and was selected as the final model for prediction.

Saved Model:

model/random_forest_model.pkl
📁 Project Structure
Heart-Disease-Prediction/
│
├── data/

│ └── heart.csv
│

├── notebook/

│ └── Heart_Disease_Prediction.ipynb
│

├── model/

│ └── random_forest_model.pkl
│

├── results/

│ ├── age_distribution.png

│ ├── confusion_matrix.png

│ ├── correlation_heatmap.png

│ ├── heart_disease_distribution.png

│ └── model_accuracy_comparison.png
│

└── README.md


🚀 Future Improvements

Hyperparameter tuning for better accuracy
Deployment using Flask or Streamlit
Real-time patient input interface
Integration with hospital systems

📚 References

UCI Machine Learning Repository
Scikit-learn Documentation
Kaggle Datasets
