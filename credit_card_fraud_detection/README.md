# Credit Card Fraud Detection

This project focuses on building a machine learning pipeline to detect fraudulent credit card transactions. The dataset is highly imbalanced, with a small percentage of transactions being fraudulent. To address this, we implemented techniques to handle data imbalance and evaluated multiple machine learning models for their effectiveness.

## Key Highlights
- Addressed data imbalance using advanced techniques to improve model performance.
- Evaluated a range of machine learning models to determine the best-performing approach.
- Achieved **99.7% accuracy** using a Decision Tree Classifier for detecting fraudulent transactions.

## Models Evaluated
The following machine learning models were evaluated during the project:
- Logistic Regression
- Decision Tree Classifier
- Random Forest
- Boosting Methods (Gradient Boosting, AdaBoost)

## Performance
The Random forest Classifier achieved the highest accuracy of **99.7%**, making it the best-performing model for this task. The ensemble methods also demonstrated robust performance, particularly for handling imbalanced data.

## Dataset
The dataset consists of anonymized credit card transaction data, with labels indicating whether a transaction is fraudulent or legitimate.

## Dataset
The dataset used for this project is publicly available on Kaggle:
[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download)  

## Usage
1. Preprocess the data to address imbalance and split it into training and testing sets.
2. Train the models and evaluate them based on key metrics:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
3. Select the best-performing model for deployment.

## Future Improvements
- Experiment with more advanced ensemble methods like XGBoost and LightGBM.
- Explore deep learning approaches for fraud detection.
- Optimize the models for real-time fraud detection systems.


