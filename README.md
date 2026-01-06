# Parkinson’s Disease Detection Using Voice Data

## Overview

This project focuses on detecting Parkinson’s Disease using voice-based biomedical features and machine learning techniques. Multiple classification models were trained and evaluated to identify the most accurate and interpretable model. The final model was deployed using a Flask web application for real-time predictions.

### Dataset Features
- `name`: Identifier for each record (not used in training)
- `status`: Target variable (1 indicates Parkinson's disease, 0 indicates no Parkinson's disease)
- Various features representing vocal attributes

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `scikit-learn`: For machine learning algorithms and evaluation metrics.

## Technologies Used

Python
Pandas, NumPy
Scikit-learn
Jupyter Notebook
Flask
HTML (for web interface)

##Methodology
Data preprocessing and feature scaling
Trained and evaluated 6 machine learning models
Compared models using Accuracy, Precision, Recall, and F1-score
Selected Random Forest as the best-performing model
Saved the trained model and deployed it using Flask

## Model Implementation

1. **Data Loading**: The dataset is loaded using `pandas`.
2. **Data Preparation**: 
   - Non-numeric columns are removed, and the target variable is separated.
   - The target variable is converted to an integer type.
3. **Data Splitting**: The dataset is split into training and testing sets with a ratio of 80% for training and 20% for testing.
4. **Data Normalization**: The features are standardized using `StandardScaler` to improve model performance.
5. **Random Forest Classifier**: The Random Forest model is trained on the scaled training data, and predictions are made on the testing data.

## Result
Random Forest Accuracy: ~89%
Demonstrated strong performance across precision and recall metrics
Enabled real-time prediction through a web interface

## Conclusion

The Flask-based web app allows users to input voice parameters and receive Parkinson’s Disease predictions instantly.






