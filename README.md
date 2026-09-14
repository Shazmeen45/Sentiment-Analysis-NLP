# Sentiment Analysis Using NLP

## About the Project

This is my Week 02 AI/ML internship project. In this project, I worked on sentiment analysis using NLP.

The purpose of the project is to classify IMDb movie reviews into two categories: positive and negative.

I started by loading the dataset and checking the reviews. After that, I cleaned the text and prepared it for the model. I used TF-IDF to convert the text into numbers and then used Logistic Regression for classification.

## Dataset

I used the IMDb movie review dataset for this project.

The dataset has 25,000 training reviews and 25,000 testing reviews.

The labels are:

- 0 = Negative
- 1 = Positive

I used the training data to train the model and the test data to check its performance.

## What I Did in This Project

The main steps I followed were:

1. Loaded the IMDb dataset
2. Checked the dataset and sample reviews
3. Cleaned the review text
4. Removed HTML tags and unnecessary characters
5. Removed stopwords
6. Applied lemmatization
7. Used TF-IDF for feature extraction
8. Trained a Logistic Regression model
9. Made predictions on the test data
10. Evaluated the model results

## Text Preprocessing

Before training the model, I cleaned the review text.

I converted all text into lowercase, removed HTML tags and unnecessary characters, removed common English stopwords, and applied lemmatization.

This helped me prepare the reviews before using them for model training.

## Feature Extraction

I used TF-IDF to convert the cleaned review text into numerical features.

For this project, I used a maximum of 5,000 features.

The TF-IDF vectorizer was fitted on the training data and then applied to the test data.

## Model

For classification, I used Logistic Regression.

The model was trained using the TF-IDF features and the sentiment labels from the training dataset.

After training, I used the model to predict the sentiment of the test reviews.

## Results

The model gave the following results on the test dataset:

- Accuracy: 87.92%
- Precision: 87.73%
- Recall: 88.17%
- F1-Score: 87.95%

The results were good overall, and the model performed fairly similarly on both positive and negative reviews.

## Confusion Matrix

The confusion matrix from the model was:

[[10959  1541]
 [ 1479 11021]]

This shows that most of the reviews were classified correctly, although some reviews were also predicted incorrectly.

## Tools and Libraries

I used the following tools and libraries:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Hugging Face Datasets

## Project Files

The repository contains the following files:

- `Sentiment_Analysis_NLP.ipynb` – Main project notebook
- `Project_Documentation.pdf` – Project documentation
- `Model_Evaluation_Report.pdf` – Model evaluation report
- `requirements.txt` – Required Python libraries
- `README.md` – Project information

## Future Improvements

There are different things I can try to improve this project in the future.

I can compare Logistic Regression with other machine learning models, try different TF-IDF settings, use word embeddings, or use advanced NLP models such as BERT.

## Conclusion

This project helped me understand the basic process of sentiment analysis.

I learned how to work with text data, clean reviews, use TF-IDF for feature extraction, train a machine learning model, and evaluate its results.

The Logistic Regression model achieved 87.92% accuracy on the IMDb test dataset, which was a good result for this project.
