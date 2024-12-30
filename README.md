# Credit-Card-Fraud-Detection
Task Objectives

The objective of this task is to build a machine learning model that detects fraudulent credit card transactions. Using a dataset of transaction details, the model predicts whether a transaction is fraudulent or legitimate. Key elements include handling class imbalance, data preprocessing, and the application of classification algorithms.

Approach

Data Preprocessing:

Loaded the dataset.

Separated features and the target variable (Class).

Addressed class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

Split the data into training and testing sets.

Model Training:

Used a Random Forest Classifier to train the model.

Fine-tuned hyperparameters to achieve optimal performance.

Evaluation:

Evaluated the model's performance using confusion matrix, precision, recall, F1-score, and accuracy metrics.

Challenges Faced

Class Imbalance: The dataset contained a significant imbalance between fraudulent and legitimate transactions. Addressed using SMOTE to oversample the minority class.

Feature Selection: Ensured irrelevant features were removed to optimize model performance.

Results

Confusion Matrix:
Provided insights into true positives, false positives, true negatives, and false negatives.

Classification Report:
Achieved high precision and recall for fraudulent transaction detection.
