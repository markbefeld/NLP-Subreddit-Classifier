# Executive Summary

Reddit is full of information in the form of Subreddits. These Subreddits are spaces for people to post and discuss media centered around certain topics. 
Using machine learning we can classify posts as belonging to certain subreddits. This might be useful for certain applications.
So what model is best suited for Subreddit classification? Well I created and compared two models.
One being a Niave Bayes model that utilized a CountVectorizer transformaer, the other a Logistic Regression model that utilized TfidfVectorizer transformer.
I used data from two Subreddits to train and test my models. The Logistic Regression model faired better in terms of accurately predicting the classification of unseen data. Therefore I would recommend utilizing a Logistic Regression model for further Subreddit classification.