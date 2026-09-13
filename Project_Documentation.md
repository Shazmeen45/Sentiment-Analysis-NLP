# Project Documentation

## Project Overview

This project is based on sentiment analysis using Natural Language Processing (NLP).

The purpose of the project is to classify movie reviews as positive or negative.

## Dataset

For this project, I used the IMDb movie review dataset.

The dataset contains:

- 25,000 training reviews
- 25,000 testing reviews
- Two sentiment classes: Positive and Negative

## Data Preprocessing

Before training the model, I cleaned the review text.

The preprocessing steps included:

- Converting text to lowercase
- Removing HTML tags
- Removing unnecessary characters
- Removing stopwords
- Applying lemmatization

This helped prepare the text for the next step.

## Feature Extraction

I used TF-IDF to convert the cleaned text into numerical features.

The model cannot directly work with normal text, so TF-IDF was used to represent the reviews as numbers.

## Model

For classification, I used Logistic Regression.

The model was trained using the TF-IDF features from the training data and then tested on the test data.

## Evaluation

The model was evaluated using four metrics:

- Accuracy
- Precision
- Recall
- F1-Score

The final results were:

Accuracy: 87.92%

Precision: 87.73%

Recall: 88.17%

F1-Score: 87.95%

## Confusion Matrix

The confusion matrix showed that:

- 10,959 negative reviews were correctly classified.
- 11,021 positive reviews were correctly classified.
- 1,541 negative reviews were predicted as positive.
- 1,479 positive reviews were predicted as negative.

## Applications

Sentiment analysis can be useful for:

- Customer feedback
- Product reviews
- Marketing
- Customer support
- Social media analysis

## Possible Improvements

The project can be improved by trying other machine learning models and comparing their results.

More advanced NLP techniques such as word embeddings and transformer models can also be explored in the future.

## Conclusion

This project helped me understand the basic NLP workflow. I learned how to clean text, convert text into numerical features, train a classification model, and evaluate its performance.
