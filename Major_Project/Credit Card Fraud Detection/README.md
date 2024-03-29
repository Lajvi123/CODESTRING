# Credit Card Fraud Detection 
## Overview 
This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset contains information about credit card transactions, including various features such as time, amount, and V1-V28 (anonymized features). The goal is to build a model that can effectively classify transactions as either legitimate or fraudulent based on these features.

## Dataset
The dataset used in this project can be found [here.](https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/input) It contains a total of 5974 transactions, with 30 input features and 1 target variable (Class).

## Methodology 

1. Data Preprocessing : The dataset is preprocessed to handle missing values, scale the features, and split it into training and testing sets.

2. Model Selection : Several classification algorithms are considered, such as Random Forest, Logistic Regression, and Decision Trees.

3. Model Training : The selected model is trained on the training set.

4. Model Evaluation : The model is evaluated on the test set using metrics like accuracy, precision, recall, and F1-score.

## Results 

* Detailed classification report is shown below:

<img width="449" alt="Screenshot 2024-02-27 at 4 55 39 PM" src="https://github.com/Lajvi123/CODESTRING/assets/142981262/627d871d-f9fd-4a1e-b4da-dcd7b456b77e">

* As we can see, Random Forest classifier provides the maximum accuracy for the fraud detection task.
  
<img width="408" alt="Screenshot 2024-03-14 at 2 26 49 PM" src="https://github.com/Lajvi123/CODESTRING/assets/142981262/4999dbb8-6979-437f-a561-01bdb724e34b">



