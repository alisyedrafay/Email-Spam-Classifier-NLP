# Email Spam Classifier

This project is an **Email Spam Classifier** that predicts whether an email is spam or not.  
It is built using **Python** and **scikit-learn**, and demonstrates how **Natural Language Processing (NLP)** and **machine learning** can be applied to real-world problems like email filtering.  

The classifier leverages **Naive Bayes algorithms** — **Multinomial, Bernoulli, and Gaussian Naive Bayes** — allowing comparison of different model performances on textual data.  
It supports both **CountVectorizer** and **TF‑IDF** for feature extraction, capturing word frequency and importance effectively.

## Features

- Implements **Multinomial, Bernoulli, and Gaussian Naive Bayes** models.
- Supports **CountVectorizer** and **TF‑IDF** for text vectorization.
- Performs standard text preprocessing:
  - Lowercasing all text
  - Removing punctuation
  - Tokenization of words
  - Optional stopwords removal
- Includes training, testing, and evaluation functionalities.
- Provides **accuracy score, precision, recall, F1-score**, and **confusion matrix** for detailed performance analysis.
- Easy to extend for other datasets or advanced feature extraction methods.

## Extended Description

Emails today are one of the most common communication methods, but spam emails can be disruptive and sometimes dangerous.  
This project demonstrates how machine learning can automatically detect spam emails using textual content.

The preprocessing pipeline ensures that the input text is cleaned and transformed into numerical features that the Naive Bayes classifiers can understand.  
By using both **CountVectorizer** and **TF‑IDF**, the models can capture both the frequency of words and their relative importance, which improves classification performance.

The inclusion of three types of Naive Bayes models allows users to explore and compare their effectiveness:
- **Multinomial Naive Bayes:** Suitable for discrete word counts.
- **Bernoulli Naive Bayes:** Works with binary/boolean features.
- **Gaussian Naive Bayes:** Assumes continuous data, used here for demonstration.

This project is ideal for beginners in **machine learning and NLP**, students, and developers who want to understand **text classification**, experiment with different models, and build a foundation for real-world email filtering systems.

## Installation

```bash
# Clone the repository
git clone https://github.com/username/Email-Spam-Classifier.git

# Navigate to the project folder
cd Email-Spam-Classifier

# Install dependencies
pip install -r requirements.txt
