# Practice For NLP
Data Source:
https://www.kaggle.com/c/word2vec-nlp-tutorial/data
# BagOfWord
Basically, utilize randomforest and bagofwords to do the classification.<br>
##  Important Resources:<br>
https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html <br>
##  The steps for BagofWords :
+ Read Data
+ Remove stop word, non-letter and read from the html font with beautifulsoup and NLTK
+ Utilize CountVectorizer to count the top 5000 most frequent words as the features
+ Create the RandomForest Model with genetic algorithm
+ Preprocessing testing data and predict it
