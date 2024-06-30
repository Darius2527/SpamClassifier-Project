# SpamClassifier-Project
This project aims to classify emails into spam and ham emails. We first perform text processing and then use TFIDF vectorizer and bag of words (CountzVectorizer) to convert the text into vectors. Then we pass it to our NaiveBayesClassifier to calculate the accuracy.


***A. Pre-processing***

Removal of Special Characters

Removal of Numbers

Lowercase Conversion

Tokenization

Removal of Stop words

Stemming


***B. Feature Extraction***

Bag of words

Tf-Idf


***C. Classification***

Naive Bayes Algorithm (GaussianNB, MultinomialNB, BinomialNB)
