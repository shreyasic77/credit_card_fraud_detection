
# Credit Card Fraud Detection

## Overview
This project is focused on detecting fraudulent credit card transactions using various machine learning algorithms. The goal is to identify fraudulent transactions from a highly imbalanced dataset by employing techniques like oversampling and undersampling, followed by the application of multiple machine learning models.

## Dataset
The dataset used for this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) available on Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly unbalanced, with 492 frauds out of 284,807 transactions (about 0.17%).

- **Features**: 28 anonymized features (`V1` to `V28`) resulting from a PCA transformation, along with `Time`, `Amount`, and the `Class` label, where `1` represents fraud and `0` represents normal transactions.

## Models and Techniques

### Data Preprocessing
- **Handling Imbalanced Data**: Given the highly imbalanced nature of the dataset, oversampling (using SMOTE) and undersampling techniques were applied.
- **Feature Scaling**: Standard scaling was applied to normalize the `Amount` and `Time` features.

### Machine Learning Models
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**

The models were evaluated based on accuracy, precision, recall, and F1-score, with Random Forest achieving the best overall performance.

### Model Evaluation
The performance of each model was assessed using metrics such as:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

## Results
The Random Forest classifier provided the best balance between precision and recall, making it the most effective model for detecting fraudulent transactions in this dataset. The model's final F1-Score and AUC values indicate its robustness in handling the imbalanced nature of the data.


