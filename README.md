# credit-card-fraud-detection
A machine learning project for detecting credit card fraud using KNN, Random Forest, and XGBoost. Based on an anonymized real-world dataset, it addresses class imbalance and evaluates models using metrics like precision, recall, F1-score, and MCC for effective fraud detection.

Dataset
Source: Kaggle - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
Contains transactions made by European cardholders in 2013.
Features are anonymized (V1 to V28) plus Amount, Time, and Class (0 = normal, 1 = fraud).
Highly imbalanced dataset: ~0.17% of transactions are fraud

Project Structure
credit-card-fraud-detection/
│
├── Credit-Card fraud detection.ipynb               
├── README.md                     
└── creditcard.csv       

Models Implemented
1.K-Nearest Neighbors (KNN)
2.Random Forest
3.XGBoost

Evaluation Metrics
1.Accuracy
2.Precision
3.Recall
4.F1-Score
5.Confusion Matrix
6.Matthews Correlation Coefficient (MCC)
