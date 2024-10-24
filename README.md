This repository contains a Jupyter notebook that demonstrates a machine learning approach to detect fraudulent transactions in online payments using logistic regression. The model is trained and evaluated on a dataset of credit card transactions.

Project Overview
In this project, a logistic regression model is used to predict whether a transaction is fraudulent based on various features in the dataset. The dataset is split into training and testing sets, and the model's performance is evaluated on both sets. The goal is to build an accurate and efficient model that can detect fraudulent transactions.

Key Components:

Data Handling:

The dataset (credit_data.csv) is loaded and preprocessed using pandas.
Features are separated from the target variable (Class), where 1 indicates fraud and 0 indicates non-fraud.

Model Training:

A logistic regression model is trained using the scikit-learn library.
The data is split into training (80%) and testing (20%) sets, maintaining the original class distribution (fraud vs non-fraud).

Model Evaluation:

The model's accuracy is evaluated on both the training and test sets to measure its performance.
Results are printed to provide insights into how well the model detects fraudulent transactions.
Libraries Used:
pandas
numpy
scikit-learn



How to Run

1. Clone the repository:
  git clone https://github.com/kunal-masurkar/online-payment-fraud-detection.git

2. Navigate to the project folder and run the Jupyter notebook:
   jupyter notebook Online_Payment_Fraud_Detection.ipynb
   
3. Ensure you have the dataset (credit_data.csv) in the correct location. (The dataset used here is https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Dataset
  The dataset used in this project (credit_data.csv) contains credit card transaction details, with a target column (Class) indicating whether a transaction is fraudulent (1) or non-fraudulent (0).
  
Future Enhancements:
Explore other models such as decision trees or random forests to improve fraud detection accuracy.

Implement additional metrics like precision, recall, and F1-score to assess performance on imbalanced data.
