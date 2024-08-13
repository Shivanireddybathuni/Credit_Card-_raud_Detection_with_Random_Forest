Hi Folks! I’m Shivani, currently pursuing my BCA from Nalanda Institute. I have a deep passion for data science and a strong grasp of machine learning algorithms. This project is a part of my continuous journey to explore and implement advanced data science techniques. Here, I've developed a model to detect fraudulent credit card transactions using the Random Forest algorithm.

Overview
This project involves building a machine learning model to detect fraudulent credit card transactions. The model is built using the Random Forest algorithm, and the dataset used for this project was sourced from Kaggle.

Dataset
The dataset used in this project is the Credit Card Fraud Detection dataset from Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly imbalanced, with only 0.172% of transactions being fraudulent.

Features
Time: The time between this transaction and the first transaction in the dataset.
V1 to V28: The result of a PCA transformation to protect the confidentiality of the original features.
Amount: The transaction amount.
Class: The target variable, where 1 indicates a fraudulent transaction and 0 indicates a legitimate one.
Preprocessing
The Time feature was removed as it was not relevant for the classification task.
The remaining features (V1 to V28 and Amount) were used as independent variables, while the Class feature was used as the dependent variable.
Model
The model used is a Random Forest Classifier with 100 estimators. The dataset was split into 80% training and 20% testing sets, maintaining the balance of the classes.

Training and Evaluation
Training: The model was trained on the 80% training set.
Testing: The model was evaluated on the 20% testing set.
Metrics
The model was evaluated using the following metrics:

Accuracy: Overall accuracy of the model.
Precision, Recall, F1-Score: Detailed classification report.
Confusion Matrix: Visual representation of the model's performance.
Results
The Random Forest model performed well, achieving high accuracy on the testing set.
A confusion matrix was plotted to show the distribution of true positives, true negatives, false positives, and false negatives.
Feature Importance
The importance of each feature was calculated and plotted to understand which features contributed most to the model's predictions.
