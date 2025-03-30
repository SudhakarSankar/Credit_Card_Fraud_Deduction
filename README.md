## Credit Card Fraud Transaction

Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning. The dataset used is sourced from Kaggle and contains transaction details, including fraudulent and non-fraudulent transactions. The goal is to build a predictive model that can effectively classify fraudulent transactions.

Dataset

The dataset used in this project is the Credit Card Fraud Transaction Dataset available on Kaggle. It consists of anonymized transaction records with labeled fraud cases.

Project Workflow

The following steps were followed to develop the fraud detection model:

Exploratory Data Analysis (EDA)

Conducted an initial analysis of the dataset to understand data distribution and characteristics.

Data Visualization

Plotted data distribution based on different cities to observe variations in fraud occurrences.

Statistical Analysis

Performed statistical tests to identify key patterns in fraudulent and non-fraudulent transactions.

Hypothesis Testing

Conducted hypothesis testing to validate assumptions regarding fraudulent transactions.

Outlier Handling

Identified and treated outliers in the dataset to improve model performance.

Data Visualization (Plot View)

Generated visualizations to check the impact of different features on fraud detection.

Feature Importance Analysis

Identified the most relevant features contributing to fraud detection using feature selection techniques.

Model Building: RandomForestClassifier

Built a classification model using RandomForestClassifier to detect fraudulent transactions.

Model Saving

Trained model was saved for future predictions and deployment.

Technologies Used

Python

Pandas

NumPy

Matplotlib & Seaborn (for visualization)

Scikit-learn (for machine learning)

Jupyter Notebook / VS Code

How to Use

Clone this repository.

Install the required dependencies.

Run the Jupyter Notebook or Python script for analysis and model training.

Use the trained model for fraud detection on new transactions.

Conclusion

This project successfully identifies fraudulent credit card transactions using machine learning techniques. The RandomForestClassifier model provides a reliable approach to detecting fraud and can be further improved with additional feature engineering and deep learning models.
