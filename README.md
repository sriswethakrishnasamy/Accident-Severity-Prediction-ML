🚦** Accident Severity Prediction Using Machine Learning
📌 Project Overview**
Road accidents are a major cause of fatalities and injuries worldwide. Predicting the severity of accidents in advance can help authorities take preventive measures, improve emergency response, and enhance road safety.
This project focuses on building a Machine Learning model to predict accident severity using historical accident data. The model learns patterns from past accidents and classifies the severity level effectively.

🎯 Objective
To analyze accident-related data
To handle imbalanced datasets using advanced techniques
To build and train a machine learning model for accident severity prediction
To evaluate model performance using appropriate metrics

📂 Dataset
The dataset is loaded from a preprocessed CSV file
Contains multiple features related to road accidents
The target variable represents accident severity
Dataset imbalance is handled using SMOTE

🛠️ Tools & Technologies Used
Programming Language: Python
Development Environment: Jupyter Notebook

Libraries Used:
pandas – data manipulation and analysis
scikit-learn – preprocessing, splitting, scaling
StandardScaler – feature scaling
SMOTE – handling class imbalance
CatBoostClassifier – machine learning model
joblib – model saving

⚙️ Methodology / Workflow
Data Loading
Load the preprocessed accident dataset using Pandas
Data Preprocessing
Feature scaling using StandardScaler
Handling missing or inconsistent values
Handling Imbalanced Data
Applied SMOTE (Synthetic Minority Oversampling Technique) to balance severity classes
Train-Test Split
Dataset split into training and testing sets (80% / 20%)
Model Training
Used CatBoost Classifier for better handling of categorical and complex data
Model Saving
Trained model saved using joblib for future predictions

🤖 Machine Learning Model
Algorithm Used: CatBoost Classifier
Reason for Selection:
Handles complex patterns efficiently
Performs well on structured datasets
Reduces overfitting

📊 Evaluation Metrics
The model performance can be evaluated using:
Accuracy
Precision
Recall
F1-score
Confusion Matrix

📈 Results

The trained model successfully predicts accident severity
SMOTE improves model performance by handling class imbalance
CatBoost provides reliable and consistent predictions

The Scores are 
Time taken for Stacking fit: 187.64 seconds
🔥 STACKED ENSEMBLE FINAL ACCURACY: 0.9378
Classification Report (Stacked Ensemble)
              precision    recall  f1-score   support

  Severe (0)       0.99      1.00      0.99      8682
 Serious (1)       0.88      0.95      0.91      8585
  Slight (2)       0.95      0.87      0.91      8801

    accuracy                           0.94     26068
   macro avg       0.94      0.94      0.94     26068
weighted avg       0.94      0.94      0.94     26068
