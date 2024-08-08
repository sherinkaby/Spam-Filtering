Spam Detection using Natural Language Processing (NLP)

This project is an implementation of a spam detection model that classifies SMS and email messages as either spam or ham (not spam). The project leverages natural language processing (NLP) techniques and machine learning algorithms to achieve high accuracy in classification.

Table of Contents
Overview
Dataset
Preprocessing
Exploratory Data Analysis (EDA)
Modeling
Evaluation
Installation
Usage
Contributing
License


Overview
The primary goal of this project is to build a robust spam detection system that can identify whether a given SMS or email message is spam or ham. The project involves the following steps:

Data Preprocessing: Cleaning and preparing the data for analysis.
Feature Engineering: Extracting relevant features such as the number of characters, words, and sentences.
Modeling: Using machine learning algorithms like Naive Bayes to train the model.
Evaluation: Assessing the performance of the model using metrics like accuracy, confusion matrix, and classification report.
Dataset
The dataset used in this project is sourced from a publicly available spam classification dataset. It contains columns for the message text and the label (spam or ham).

Key Columns:
sms/email: The content of the message.
Output: The label for the message (ham for non-spam, spam for spam).
num_of_chars: Number of characters in the message.
num_of_words: Number of words in the message.
num_of_sent: Number of sentences in the message.
Preprocessing
The data preprocessing steps include:

Removing duplicate and null values.
Converting text to lowercase.
Tokenizing the text.
Removing stopwords and punctuations.
Applying stemming to reduce words to their root forms.
Exploratory Data Analysis (EDA)
EDA was conducted to understand the distribution of the data. Key insights include:

Distribution of spam vs. ham messages.
Character, word, and sentence counts across spam and ham messages.
Correlation between different features.
Modeling
Three different Naive Bayes models were trained:

Gaussian Naive Bayes
Multinomial Naive Bayes
Bernoulli Naive Bayes
The Multinomial Naive Bayes model was found to perform the best.

Evaluation
The models were evaluated using the following metrics:

Accuracy Score
Confusion Matrix
Classification Report
