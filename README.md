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

🧹 Data Preprocessing

- Duplicate records were checked and handled
- Missing values were analyzed
- Dataset was split into features (X) and target (y)
- Train-test split was performed for model evaluation
- Feature scaling was applied using StandardScaler to normalize data


🤖 Machine Learning Models Used

The following models were trained and compared:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)


📈 Model Evaluation

The models were evaluated using multiple performance metrics to ensure reliable comparison:

- Accuracy Score: Measures overall correctness of predictions
- Confusion Matrix: Shows correct vs incorrect classifications
- Precision: Measures correctness of positive predictions
- Recall: Measures ability to detect actual positive cases

This multi-metric evaluation ensures that the model is not only accurate but also reliable for medical prediction scenarios where false negatives are critical.

📊 Results Summary

All models were compared based on accuracy:

- Logistic Regression: Baseline performance
- Decision Tree: Good but prone to overfitting
- KNN: Moderate performance
- Random Forest: Best performing model

Final selected model: Random Forest Classifier

🏆 Best Model

After comparing all models, the Random Forest Classifier was selected as the final model due to its superior performance and stability.

Reasons for selection:
- Higher accuracy compared to other models
- Better handling of non-linear relationships
- Reduced overfitting due to ensemble learning
- More robust predictions on unseen data

This makes it suitable for real-world medical prediction tasks where reliability is crucial.

Saved Model:

model/random_forest_model.pkl

📁 Project Structure

```
Heart-Disease-Prediction/
│
├── data/
│   └── heart.csv
│
├── notebook/
│   └── Heart_Disease_Prediction.ipynb
│
├── model/
│   └── random_forest_model.pkl
│
├── results/
│   ├── age_distribution.png
│   ├── confusion_matrix.png
│   ├── correlation_heatmap.png
│   ├── heart_disease_distribution.png
│   └── model_accuracy_comparison.png
│
└── README.md
```

🚀 How to Run Project

1. Clone the repository
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn

3. Open Jupyter Notebook:
   notebook/Heart_Disease_Prediction.ipynb

4. Run all cells sequentially

5. View results in the results/ folder


 🎤 Conclusion

This project successfully demonstrates the application of machine learning techniques for predicting heart disease based on patient medical data.

Key takeaways:
- Data preprocessing significantly improves model performance
- Exploratory Data Analysis helps in understanding hidden patterns in data
- Ensemble models like Random Forest perform better for classification tasks
- Proper evaluation metrics are necessary for reliable medical predictions

The final model can assist in early detection of heart disease, which may help in timely medical intervention.

🚀 Future Improvements

Hyperparameter tuning for better accuracy
Deployment using Flask or Streamlit
Real-time patient input interface
Integration with hospital systems

📚 References

UCI Machine Learning Repository
Scikit-learn Documentation
Kaggle Datasets

👨‍💻 Author

This project was developed as part of Minor Project submission.

Submitted by: SHUBHI SHARMA (CSE-AI 1st year)
