# Twitter Sentiment Analysis using Machine Learning

## Project Overview

This project focuses on analyzing Twitter data using Natural Language Processing (NLP) and Machine Learning techniques. It classifies tweets into two categories: normal tweets and hateful or offensive tweets.

The project compares multiple machine learning algorithms and evaluates their performance using classification metrics.

## Objectives

* Analyze and preprocess Twitter text data.
* Clean tweets using NLP techniques.
* Convert text into numerical features using TF-IDF.
* Train and compare machine learning models.
* Evaluate model performance using precision, recall, F1-score, and confusion matrix.
* Visualize tweet patterns and classification results.

## Technologies Used

* Python
* Pandas and NumPy
* Matplotlib and Seaborn
* Scikit-learn
* NLTK
* TextBlob
* Jupyter Notebook

## Machine Learning Models

* Multinomial Naive Bayes
* Logistic Regression
* Linear Support Vector Machine (SVM)

## Key Features

* Text cleaning and preprocessing
* Stop-word removal and stemming
* TF-IDF feature extraction
* Model comparison and evaluation
* Confusion matrix visualization
* Word cloud analysis
* Error analysis of misclassified tweets
* TextBlob sentiment baseline

## Dataset

The project uses a Twitter sentiment and hate-speech dataset containing 31,962 tweets.

The dataset has two labels:

* 0: Normal tweet
* 1: Racist or sexist tweet

The dataset is imbalanced, so precision, recall, and F1-score are important evaluation metrics.

## Project Structure

```text
Twitter-Sentiment-Analysis-ML/
│
├── Twitter_Sentiment_Analysis.ipynb
├── twitter.csv
└── README.md
```

## Results

The notebook compares Naive Bayes, Logistic Regression, and Linear SVM using accuracy, precision, recall, and F1-score.

In the reference run, Linear SVM achieved an F1-score of 0.690 for the hateful-content class. Results may vary depending on preprocessing and execution environment.

## Applications

* Social media content moderation
* Public opinion analysis
* Brand monitoring
* Customer feedback analysis

## Limitations

The dataset is imbalanced and contains duplicate tweets. The model may also struggle with sarcasm, context, and implicit hateful language.

## Disclaimer

This project is for educational and analytical purposes. Model predictions should not be used as the sole basis for automatically removing content or penalizing users.

## Author

Manoj Kumar Bais
