# heart-disease-prediction
## Overview
This project provides a pipeline for predicting the likelihood of heart disease using machine learning. It demonstrates data handling, preprocessing, model building, training, and prediction. The workflow is suitable for health analytics, research, and educational demonstration.
## Dataset
Source: [kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- Features:
    - age
    - sex
    - cp
    - trestbps
    - chol
    - fbs
    - restecg
    - thalach
    - exang
    - oldpeak
    - slope
    - ca
    - thal
- Target: target (0:No, 1:Yes).
## Technologies & Libraries Used
- Python 
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost
## Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGB Classifier
## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
## Visualization
- Pairplots show feature distributions and inter-class separations.
- Confusion matrices illustrate per-class prediction accuracy.
## Project Workflow
1. Data Collection:
   - Load the iheart disease prediction dataset

2. Data Preprocessing:
   - data.head()
   - Handle missing values
   - Split into training and testing sets
   - Balance the dataset

3. Feature Scaling:
   - Standardize features for better model performance

4. Model Training:
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - XGB Classifier 

5. Model Evaluation:
   - accuracy
   - precision
   - recall
   - f1-score
   - confusion matrix
  
## Result

              precision    recall  f1-score   support

           0       0.97      1.00      0.99       102
           1       1.00      0.97      0.99       103

    accuracy                           0.99       205
    macro avg      0.99      0.99      0.99       205
    weighted avg   0.99      0.99      0.99       205

## Conclusion
This project illustrates that machine learning algorithms can well predict the risk of heart disease from patient health information. Through meticulous preprocessing of the data, feature engineering, and testing different classifiers—Logistic Regression, Decision Trees, Random Forests, and XGBoost—we obtained good predictive performance with accuracy, precision, recall, and F1-scores all around 0.99 on the test set.
