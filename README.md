💳 Credit Card Fraud Detection 🕵️‍♀️

Welcome to my first machine learning project! This is a simple yet powerful model that detects fraudulent credit card transactions using Logistic Regression.

🔍 About the Project

In this notebook, I explored a popular credit card transactions dataset and built a fraud detection model. Fraudulent transactions are rare and hidden, so the goal was to detect them based on patterns in the data.


⚙️ Workflow

Credit card data ➡️ Data Preprocessing ➡️ Data Analysis ➡️ Train-Test Split ➡️ Logistic Regression ➡️ Evaluation



📁 Dataset

Source: Kaggle Credit Card Fraud Detection dataset
link- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Note: Due to confidentiality, the features are anonymized (V1, V2, ..., V28), with Time, Amount, and Class (0 = legit, 1 = fraud).



🧠 Model Used
Logistic Regression — a basic but effective model for binary classification tasks like fraud detection.



📊 Evaluation

Used Accuracy Score to check model performance.

Class imbalance was a key challenge (very few frauds compared to legit transactions).



📌 What I Learned
Handling imbalanced data

Building a Logistic Regression model with scikit-learn

Reading and analyzing large CSV datasets

Importance of model evaluation
