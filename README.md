# Bag-of-Words-Meets-Bags-of-Popcorn-Abhishek

#### Data Set:

The labeled data set consists of 50,000 IMDB movie reviews, specially selected for sentiment analysis. The sentiment of reviews is binary, meaning the IMDB rating < 5 results in a sentiment score of 0, and rating >=7 have a sentiment score of 1. No individual movie has more than 30 reviews. The 25,000 review labeled training set does not include any of the same movies as the 25,000 review test set. In addition, there are another 50,000 IMDB reviews provided without any rating labels.

#### File descriptions:

labeledTrainData - The labeled training set. The file is tab-delimited and has a header row followed by 25,000 rows containing an id, sentiment, and text for each review.

#### Data fields:

id - Unique ID of each review
sentiment - Sentiment of the review; 1 for positive reviews and 0 for negative reviews
review - Text of the review

##### Prediction of sentiment of movie reviews
- Used BeautifulSoup and Regular Expressions in Python to remove HTML tags, numbers, punctuation to predict sentiment of movie reviews

#### Used NLTK package to remove stop words and created Bag of Words of the clean review dataset using CountVectorizer from scikit-learn

Applied Random Forest Classifier with 150 trees to predict the sentiment of 25,000 movie reviews with an accuracy of 59% on test dataset

Used TF-IDF vectorization method and Bi-gram Vectorization methods on Logistic and RF models and Naive Bayes Theorems
