# Email Spam Detection Using Machine Learning

## Project Overview

Email spam refers to unwanted or unsolicited emails that are sent to a large number of users. These emails often contain advertisements, scams, phishing links, or malicious content. Detecting spam emails is an important task in cybersecurity and email management.

This project uses Machine Learning and Natural Language Processing (NLP) techniques to classify emails as either **Spam** or **Ham (Not Spam)**.

---

## Objective

The main objective of this project is to build a machine learning model that can automatically detect whether an email is spam or not based on its content.

---

## Problem Statement

Spam emails are one of the most common forms of unwanted communication on the internet. They can be misleading, harmful, and sometimes dangerous. The goal of this project is to develop a spam detection system that can analyze email text and accurately classify it into:

* Spam Email
* Non-Spam (Ham) Email

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

---

## Dataset Information

The dataset contains:

* Label (Spam or Ham)
* Email Message Content

Example:

| Label | Message                                |
| ----- | -------------------------------------- |
| ham   | Hey, are we meeting today?             |
| spam  | Congratulations! You won a free prize. |

---

## Project Workflow

### 1. Data Collection

* Load dataset from CSV or ZIP file.

### 2. Data Preprocessing

* Remove unnecessary columns.
* Handle missing values.
* Rename columns for better readability.

### 3. Label Encoding

* Ham → 0
* Spam → 1

### 4. Text Vectorization

* Convert text messages into numerical features using CountVectorizer.

### 5. Model Training

* Split dataset into training and testing sets.
* Train the model using Multinomial Naive Bayes.

### 6. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report

### 7. Prediction

* Predict whether a custom email message is spam or not.

---

## Machine Learning Algorithm

### Multinomial Naive Bayes

Multinomial Naive Bayes is a popular algorithm for text classification tasks. It is fast, efficient, and performs exceptionally well on spam detection datasets.

---

## Results

The model successfully classifies email messages into spam and non-spam categories with high accuracy.

Key Findings:

* Spam messages often contain promotional words, prizes, offers, and urgent calls to action.
* The model can accurately identify patterns in spam emails.
* Naive Bayes performs well for text classification problems.

---

## Project Structure

KamilGol_Task4/

├── Email_Spam_Detection.ipynb

├── spam.csv

├── README.md

├── requirements.txt

└── screenshots/

---

## Installation

Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

---

## How to Run

1. Open Google Colab or Jupyter Notebook.
2. Upload the project notebook.
3. Upload the dataset file (CSV or ZIP).
4. Run all cells.
5. Enter custom email messages to test the spam detector.

---

## Future Improvements

* TF-IDF Vectorization
* Random Forest Classifier
* Support Vector Machine (SVM)
* Deep Learning Models
* Web Application Deployment using Streamlit

---

## Conclusion

This project demonstrates how Machine Learning can be used to automatically detect spam emails. By applying Natural Language Processing and classification algorithms, the model can efficiently distinguish between spam and legitimate emails, helping improve email security and user experience.

---

## Author

Kamil Gol

Task 4 – Email Spam Detection Using Machine Learning
