# Credit-Card-Fraud-Detection

## Overview
This project aims to develop machine learning models for the detection of credit card fraud. The goal is to accurately classify transactions as either fraudulent or legitimate based on various features associated with each transaction.

## Dataset
The dataset used in this project contains anonymized credit card transactions made by European cardholders. It consists of numerical features derived from the principal component analysis (PCA) transformation due to privacy concerns. The target variable indicates whether a transaction is fraudulent (class 1) or legitimate (class 0).

## Models
### RandomForestClassifier
The RandomForestClassifier model was trained using scikit-learn's RandomForestClassifier class. It achieved an accuracy score of approximately 99.92% on the test data, with a precision of 0.91 and recall of 0.71 for detecting fraudulent transactions.

### XGBoost
The XGBoost model was trained using the XGBoost library. It achieved an accuracy score of approximately 99.94% on the test data, with a precision of 0.93 and recall of 0.74 for detecting fraudulent transactions. The XGBoost model outperformed the RandomForestClassifier in terms of precision, recall, and ROC-AUC score.

## Conclusion
Both models demonstrated high accuracy in classifying credit card transactions. However, the XGBoost model exhibited slightly superior performance, particularly in detecting fraudulent transactions. Therefore, the XGBoost model is recommended for fraud detection tasks due to its higher precision, recall, F1-score, and ROC-AUC score.

## Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your_username/credit-card-fraud-detection.git
Install the required dependencies:

Copy code
pip install -r requirements.txt
Run the Jupyter notebook credit_card_fraud_detection.ipynb to train and evaluate the machine learning models.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
The dataset used in this project is sourced from Kaggle: Credit Card Fraud Detection
