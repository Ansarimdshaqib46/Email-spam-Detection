# Email Spam Detection using Naive Bayes

Welcome to the Email Spam Detection project! This project aims to classify emails as either "spam" or "ham" (non-spam) using the Naive Bayes algorithm, a simple yet powerful probabilistic classifier based on Bayes' theorem.


## Introduction

Email spam detection is a critical task in the field of cybersecurity and information filtering. This project employs a Naive Bayes classifier, which is particularly well-suited for text classification problems, to distinguish between spam and legitimate emails.

## Features

- **Efficient Classification**: Quickly categorize emails with high accuracy.
- **Scalable**: Can handle large datasets and email volumes.
- **Customizable**: Easily adjust preprocessing and model parameters.

## Installation

To run this project locally, you will need Python and the following libraries:

- NumPy
- Pandas
- Scikit-learn

## Model
The Naive Bayes classifier implemented in this project utilizes the following steps:
Preprocessing: Tokenizes and cleans email text, removing stop words and performing stemming.
Feature Extraction: Converts the email text into a feature vector using techniques like TF-IDF.
Training: Uses the feature vectors to train the Naive Bayes model.
