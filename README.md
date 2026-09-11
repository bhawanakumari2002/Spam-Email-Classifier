# Spam Email Classifier

An AI-based Spam Email Classifier that identifies emails as **Spam** or **Ham (Not Spam)** using Machine Learning.

## Project Overview

This project uses **TF-IDF Vectorization** and **Logistic Regression** to classify email messages into two categories:

* Spam
* Ham (Not Spam)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF
* Logistic Regression
* Jupyter Notebook

## Dataset

The dataset contains email text with corresponding labels for Spam and Ham emails.

## Machine Learning Process

1. Load the dataset
2. Clean the email text
3. Split data into training and testing sets
4. Convert text into numerical features using TF-IDF
5. Train a Logistic Regression model
6. Predict Spam/Ham emails
7. Evaluate the model
8. Save the trained model and TF-IDF vectorizer

## Project Files

```text
Spam-Email-Classifier
├── Spam_Email_Classifier.ipynb
├── spam_email_dataset.csv
├── spam_email_classifier.pkl
└── tfidf_vectorizer.pkl
```

## Model

**Logistic Regression** is used as the classification algorithm.

## Output

The model predicts whether a given email is:

* **Spam**
* **Ham**

## Author

**Bhawana Kumari**
B.Tech Computer Science and Engineering
Gautam Buddha University
