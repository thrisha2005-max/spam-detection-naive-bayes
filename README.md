**SMS Spam Classifier using NLP**

This project implements an SMS spam detection system using Natural Language Processing (NLP) and Machine Learning techniques. The model classifies messages as Spam or Ham (Not Spam) using TF-IDF vectorization and a Multinomial Naive Bayes classifier.

** Features**

Text preprocessing (lowercasing, punctuation removal, stopword removal, stemming)

TF-IDF feature extraction

Spam vs Ham visualization using WordClouds

Supervised learning with Naive Bayes

Model evaluation using accuracy, precision, and confusion matrix

Custom message prediction

** Dataset**

Source: SMS Spam Collection Dataset

Format: Tab-separated values (sms.tsv)

Classes:

0 → Ham

1 → Spam

**Technologies Used**

Python

Pandas

NLTK

Scikit-learn

WordCloud

Matplotlib

**Installation**

Install the required dependencies:

pip install nltk wordcloud scikit-learn pandas matplotlib


Download NLTK stopwords:

import nltk
nltk.download('stopwords')

** How It Works**

Load Dataset

Clean Text

Lowercase

Remove punctuation & numbers

Remove stopwords

Apply stemming

Visualize Data

Word clouds for spam and ham messages

Feature Extraction

TF-IDF Vectorizer

Model Training

Multinomial Naive Bayes

Evaluation

Accuracy

Precision

Confusion Matrix

Prediction

Classify new messages

**Model Performance (Example)**

Accuracy: ~97%

Precision: High precision for spam detection

Confusion Matrix: Evaluates false positives and negatives

**Sample Predictions**
"Congratulations! You have won a $1000 gift card." → Spam
"Hi John, can we reschedule our meeting?" → Ham

 **Project Structure**
├── spam_classifier.py
├── README.md
└── requirements.txt

** Future Improvements**

Use lemmatization instead of stemming

Try other models (Logistic Regression, SVM)

Deploy as a web app using Flask or Streamlit

Add cross-validation

** Author**

Thrisha SM

