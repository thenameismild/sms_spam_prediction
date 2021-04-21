# SMS Spam Predicition

In this project I will be looking at a data set which contains spam and non spam text data to predict which SMS is a spam.

# The Data

We have 5572 SMS with two columns of text and identifier if its an SMS or a legitimate text.

# Data Preprocessing

The data was cleaned by identifying url links, phone numbers, text numbers and non letter words first. Then split the sentence into individual words then they were classified and remove the stopwords and lematized them. Finally they are joined back into a string of words.

# The Model

In this project the models were used: Logistic Regression, KNN and Naive Bayes and Decision Tree

# Evaluation

The best model found was Logistic Regression with CountVectorizer and all the default function, it showed that:

- The model predict 98% of the observations
- Among the SMS the model predict 95% correctly as spam SMS
- Among the spam SMS the model correctly classified 94% of the data
- Among the ham SMS the model correctl classified it with 99%
