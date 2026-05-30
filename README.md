📧 Spam Mail Detection using Machine Learning
Overview

This project is a Machine Learning-based Spam Mail Detection System that classifies emails as either Spam or Ham (Legitimate Mail). The model uses Natural Language Processing (NLP) techniques to analyze email text and predict whether a message is spam.

Features
Detects spam and legitimate emails.
Uses text preprocessing and feature extraction techniques.
Implements Logistic Regression for classification.
Achieves high accuracy on test data.
Supports prediction for new email messages.
Technologies Used
Python
NumPy
Pandas
Scikit-learn
TF-IDF Vectorization
Logistic Regression
Dataset

The dataset contains:

Category: Spam or Ham
Message: Email content

Example:

Category	Message
spam	Congratulations! You won a prize.
ham	Meeting scheduled at 10 AM tomorrow.
Project Workflow
1. Data Collection
Load the email dataset using Pandas.
2. Data Preprocessing
Handle missing values.
Convert categorical labels:
Spam → 0
Ham → 1
3. Feature Extraction
Convert text messages into numerical features using TF-IDF Vectorizer.
4. Model Training
Split the dataset into training and testing sets.
Train a Logistic Regression model on the processed data.
5. Model Evaluation
Measure model performance using Accuracy Score.
6. Prediction
Predict whether a new email message is Spam or Ham.
Results
Training Accuracy: High accuracy achieved during model training.
Test Accuracy: Approximately 91.89%.
Example Prediction

Input Email:

Dear Intern, This is a final reminder that the Internship Orientation Session will begin in 15 minutes.

Output:

Ham Mail
