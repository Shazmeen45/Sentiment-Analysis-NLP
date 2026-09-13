# Sentiment Analysis Using NLP

This project is about classifying movie reviews into two categories: positive and negative.

I used the IMDb dataset for this project. First, I cleaned the review text by removing unnecessary characters, stopwords, and applying lemmatization.

After preprocessing, I used TF-IDF to convert the reviews into numerical features. Then I trained a Logistic Regression model to predict the sentiment of the reviews.

## Dataset

The IMDb movie review dataset was used for training and testing the model.

- Training samples: 25,000
- Testing samples: 25,000
- Classes: Positive and Negative

## Tools and Libraries

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TF-IDF
- Logistic Regression
- Matplotlib
- Seaborn

## Steps Used

1. Loaded the IMDb dataset
2. Explored the dataset
3. Cleaned the review text
4. Removed stopwords
5. Applied lemmatization
6. Converted text into TF-IDF features
7. Trained a Logistic Regression model
8. Made predictions on test data
9. Evaluated the model
10. Created a confusion matrix

## Model Results

The model achieved the following results:

- Accuracy: 87.92%
- Precision: 87.73%
- Recall: 88.17%
- F1-Score: 87.95%

## Conclusion

The model was able to classify most of the movie reviews correctly. This project helped me understand the basic process of NLP, including text preprocessing, feature extraction, model training, and evaluation.
