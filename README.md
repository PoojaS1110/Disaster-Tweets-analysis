# Disaster Tweets Sentiment Analysis

## Application of Gaussian Naive Bayes for Sentiment Classification of Disaster-Related Tweets

### Summary

In this project, sentiment analysis was performed on a dataset of tweets related to various disasters. The objective was to classify these tweets as related to disasters or not. The project involved data cleaning, text preprocessing, feature extraction, model training, and evaluation using machine learning techniques.

### Methodology

Data cleaning and preprocessing involved:

- Removing non-alphabetical characters.
- Converting text to lowercase.
- Tokenizing the text into words.
- Applying basic stemming.
- Removing common stopwords.

For feature extraction, a bag-of-words model was created using `CountVectorizer` with a maximum of 1500 features. The dataset was split into training and testing sets. A Gaussian Naive Bayes classifier was trained on the training data and used to predict sentiments on the test data.

### Skills Used

- Data Cleaning and Preprocessing
- Feature Extraction and Vectorization
- Machine Learning Algorithms (Gaussian Naive Bayes)
- Model Evaluation Metrics (Confusion Matrix, Classification Report)
- Data Handling with Pandas

### Results

The project included saving the test data with predictions into a CSV file named `test_with_predictions.csv`. This file contains the original tweet texts along with the predicted sentiment classifications. The results demonstrated the application of text preprocessing and classification techniques in handling disaster-related tweets.

